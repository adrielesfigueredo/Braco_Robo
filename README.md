
# Projeto: Controle de Braço Robótico com Arduino

Este projeto visa aplicar os fundamentos da programação de microcontroladores na operação de um braço robótico, utilizando a plataforma Arduino. O principal objetivo é desenvolver um sistema capaz de controlar os movimentos do braço para a manipulação e movimentação de pequenos objetos, demonstrando a integração entre hardware e software no contexto da robótica.

## 2. Concepção e Idealização do Projeto

A criação deste projeto teve como propósito principal a aplicação prática dos conhecimentos em programação de microcontroladores. O objetivo é fazer com que um braço robótico consiga mover pequenos objetos.

### Pontos Considerados na Idealização

- **Escolha da Plataforma:** Optamos pelo Arduino por ser uma plataforma eficiente e amplamente utilizada para desenvolver protótipos.
- **Entendimento do Braço Robótico:** Analisamos os servomotores e articulações do braço para entender seu funcionamento.
- **Componentes Adicionais e Interface de Controle:** Integração de dois joysticks como interface de controle manual, permitindo manipulação intuitiva.
- **Planejamento da Programação:** Programar o Arduino para interpretar sinais dos joysticks e mover os motores de forma coordenada e precisa.

## 3. Desenvolvimento do Projeto Físico

### 3.1. Construção Física

A montagem prática do circuito envolveu:

**Componentes Utilizados:**

- **Arduino Uno:** Unidade central de processamento.
- **Servomotores (4):** Responsáveis pelas articulações do braço.
- **Joysticks (2):** Interface de controle manual.
- **Protoboard:** Para organização das conexões temporárias.
- **Cabos Jumper:** Para interconexões entre componentes.
- **Fonte de Alimentação Externa:** Garante energia adequada aos servos.


### 3.2. Simulação Virtual

A simulação foi realizada na plataforma **Wokwi**, proporcionando:

- **Teste do Código:** Execução e depuração do código para Arduino.
- **Prevenção de Danos:** Redução do risco de falhas físicas.
- **Agilidade no Desenvolvimento:** Alterações rápidas no código.

**Aspectos Testados:**

- Inclusão da biblioteca `Servo.h`
- Mapeamento de pinos com `attach()`
- Leitura dos joysticks com `analogRead()`
- Lógica condicional de controle de movimento
- Limitação de ângulos e comandos `write()`
- Uso da saída serial para depuração

**Link da Simulação no Wokwi:** [Simulação Wokwi](https://wokwi.com/projects/377825276048594945)

## 4. Apresentação Visual do Projeto

### 4.1. Vista do Circuito


**Organização:**

- **Placa de Controle (Arduino + Shield):** Conexões simplificadas com os servos.
- **Conexões Diretas para Servos:** Pinos dedicados (S, V, G).
- **Servomotores:** Conectados diretamente com fios:
  - Vermelho (VCC)
  - Preto (GND)
  - Amarelo (PWM)


### 4.2. Vista Esquemática do Circuito


Representação padronizada das conexões elétricas usando símbolos eletrônicos.

## 5. Lista de Componentes Utilizados

- Keyestudio V4.0 Control Board (1)
- Keyestudio Servo Motor Driver Shield (1)
- Placas Acrílicas (1 conjunto)
- Alça Acrílica (1)
- Suporte Cilíndrico MeArm ABS (1)
- Servo Preto 180° (4)
- Módulo BT-24 (1)
- Módulo Joystick Keyestudio (2)
- Capa Joystick PS2 3D (2)
- Chave de Fenda 3\*40MM (1)
- Chave Inglesa Galvanizada (1)
- Parafusos de Cabeça Redonda M3\*6MM (12)
- Parafusos de Cabeça Redonda M3\*10MM (22)
- Parafusos de Cabeça Chata M3\*14MM (2)
- Parafusos de Cabeça Redonda M3\*12MM (12)
- Pilar de Cobre M3\*24+6MM (4)
- Pilar de Cobre M3\*6mm+6mm (10)
- Porcas Sextavadas de Aço Inoxidável M3 (22)
- Porcas Sextavadas M3 (24)
- Parafusos Auto-atarraxantes Phillips M1.2x5MM (8)
- Parafusos Auto-atarraxantes Phillips M2x5MM (10)
- Arruela Plana de Aço Inoxidável 304 M3 (10)
- Parafusos Auto-atarraxantes Phillips M2x8MM (2)
- Parafusos de Cabeça Chata M3\*16MM (2)
- Fio Jumper Macho-Fêmea 10CM (4)
- Fio Jumper Fêmea-Fêmea 50CM (10)
- Abraçadeiras de Cabo Pretas 3\*100MM (7)
- Suporte de Bateria 18650 de 2 Slots (1)

## 6. Simulação do Projeto

### 6.1. Simulação Física ou Virtual

Demonstração prática do funcionamento do circuito em sala de aula.

### 6.2. Análise e Ajustes

- **Resposta dos Servomotores:** Movimentos suaves e precisos.
- **Estabilidade Mecânica:** Boa fixação e ausência de folgas excessivas.

## 7. Conclusão

Este projeto demonstrou com sucesso a aplicação da programação de microcontroladores para controlar um braço robótico, permitindo a movimentação de pequenos objetos.

- Utilizou-se o Arduino como plataforma central.
- Os joysticks permitiram um controle intuitivo.
- A simulação virtual foi crucial para validar o código antes da montagem física.
- A construção física mostrou robustez e funcionalidade.

O projeto consolidou conhecimentos em microcontroladores e robótica, destacando a importância de um desenvolvimento iterativo e bem testado.
