# Retificador onda completa

## Esquemático:
![image](https://github.com/user-attachments/assets/ac67897a-e506-43c6-b19e-9f68a608fcb1)

Componentes e suas funções:

**Entrada**: Representa a fonte de tensão alternada de entrada. Pode ser a tensão da rede elétrica (110V ou 220V) ou a saída de um transformador.

**Transformador**: Reduz a tensão alternada de entrada para um nível mais baixo e seguro. Além disso, isola o circuito da rede elétrica, aumentando a segurança.

**Ponte Retificadora**: Converte a tensão alternada reduzida do transformador em uma tensão contínua pulsante.

**Capacitor**: Filtra a tensão contínua pulsante da ponte retificadora, suavizando as ondulações e tornando-a mais contínua.

**Capacitores**: Filtram ruídos de alta frequência na tensão contínua, melhorando a estabilidade da tensão de saída.

**Regulador de Tensão**: Mantém a tensão de saída em um valor constante de 5V, independentemente das variações na tensão de entrada ou na carga.

**Resistor**: Limita a corrente que passa pelo LED, protegendo-o de danos. O valor de 220Ω é adequado para LEDs comuns que operam com baixa corrente.

**LED**: Emite luz vermelha quando a corrente passa por ele, indicando que o circuito está funcionando e fornecendo tensão.


## Prática:
![image](https://github.com/user-attachments/assets/e67626eb-0345-46b6-922f-20f38a4ef90b)

![image](https://github.com/user-attachments/assets/6eed1721-2c3a-4854-8760-c9ec8b70193b)

### Componentes utilizados:
#### Transformador:
Converte a tensão elétrica de um nível para outro. Pode reduzir a tensão da rede elétrica (ex: 220V para 12V) ou aumentá-la, dependendo da aplicação. Funciona por indução eletromagnética.

#### Diodo
Permite a passagem de corrente elétrica em apenas uma direção, funcionando como uma válvula. Muito usado em retificadores para converter corrente alternada (CA) em corrente contínua (CC).

#### Capacitor
Armazena e libera carga elétrica, funcionando como um pequeno reservatório de energia. Pode ser usado para filtragem (suavizar variações de tensão), acoplamento e temporização em circuitos eletrônicos.

#### Regulador de Tensão - LM7805
Mantém uma tensão de saída estável de 5V, independentemente de variações na tensão de entrada ou na corrente consumida. Muito usado em circuitos que precisam de alimentação fixa.

#### Resistor
Limita o fluxo de corrente elétrica em um circuito, ajudando a controlar tensões e correntes. Seu valor é medido em ohms (Ω).

#### LED:
Emissor de luz

#### Conectores Jumper:
São fios ou cabos com terminais específicos para conectar componentes em protoboards ou placas de circuito, permitindo testes e montagens temporárias sem necessidade de solda.

### Medição da voltadgem do regulador de tensão do circuito de retificador de onda completa
![image](https://github.com/user-attachments/assets/69d45d6d-48e4-4e1e-953b-f845e2decb7e)

### Fluxo de Conversão de Tensão  

1. **Transformador**: Reduz a tensão da rede elétrica para 12V CA.  
2. **Ponte de Diodos**: Converte a corrente alternada (CA) em corrente contínua pulsante.  
3. **Capacitor**: Armazena carga e libera energia conforme necessário, reduzindo oscilações e fornecendo um sinal mais estável, próximo de uma corrente contínua pura.  
4. **Regulador de Tensão (LM7805)**: Ajusta a tensão para 5V CC fixos na saída.  

#### Não foi adicionado as outras imagens de medição, porque o transformador nãe era o 7805. Então estava dando o resultado errado.

## PcB:
![image](https://github.com/user-attachments/assets/b099d23e-6e01-4b4d-8c19-561b2034f7a3)

### Trilhas e Conexões:

#### As trilhas azuis conectam os componentes, seguindo o esquema elétrico do circuito.
#### A espessura das trilhas pode variar para acomodar diferentes correntes.
#### Os pads circulares com números indicam os pontos de solda para os pinos dos componentes.


## 3D:

### Representação em 3D da parte superior da placa
![image](https://github.com/user-attachments/assets/6ec56372-d491-4606-b210-12e8b1849709)

### Representação em 3D da parte inferior da placa
![image](https://github.com/user-attachments/assets/e5a3acbe-c877-453e-bcc6-39f4410ae05b)


