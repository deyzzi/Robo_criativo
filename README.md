![GitHub License](https://img.shields.io/github/license/deyzzi/Robo_criativo)
# Robo_criativo
#  Projeto Robô Autônomo com Arduino UNO

Projeto de robótica com Arduino UNO utilizando uma ponte H L293D, que utiliza sensores ultrassônicos HC-SR04 e motores para **navegar em um labirinto evitando colisões automaticamente**. Ideal para práticas de eletrônica, programação embarcada e lógica de navegação autônoma.


## 📌 Objetivo

Criar um **robô autônomo** capaz de:
- Detectar obstáculos à frente usando um sensor ultrassônico;
- Tomar decisões de movimentação (frente, esquerda, direita);
- Navegar por um labirinto simples **sem colidir com as paredes**.

## 🧩Arquitetura do Projeto

|        Componente      |         Função           |
| ---------------------- | ------------------------ |
|    🧠   Arduino UNO      |Microcontrolador principal que executa o código de navegação|
|  ⚡Ponte H - L293D  |Controle da direção, velocidade e sentido dos motores|
|📡 Sensor Ultrassônico HC-SR04|Medição de distância para evitar obstáculos|
|🔋 Pilhas(6x AA ou 9V) e suporte |Alimenta todo o sistema|
| ⚙️ Mini Protoboard + Cabos Jumpers|	Conexão e organização dos componentes|
| 🛞 Motores + rodas	|  Estrutura física do robô que permite a movimentação |

## 🎨 Imagem do Projeto 
<img width="1536" height="1024" alt="500265191-6154e267-23fe-4704-986c-5294ad3a20e1" src="https://github.com/user-attachments/assets/ccda06a6-3e9e-4598-bdb3-8015a8675db6" />

## 🧠 Conceitos Envolvidos
- Programação em Arduino C++
- Controle de motores via PWM
- Uso de sensor ultrassônico para medição de distância
- Decisões autônomas com base nas leituras do sensor
- Integração entre hardware e software embarcado

# 🧑‍💻 Autores

Este projeto foi desenvolvido por:

|          Nome       |  Contribuição  |
| ---------------------- | ------------------------ |
|  Alexandre Santos   |Montagem mecânica e testes|
|     Deysi Quispe    |Documentação e pesquisa técnica|
|  Gustavo Cardoso    |Programação e integração de hardware|

### Wiki
[acessar wiki](https://github.com/deyzzi/Robo_criativo/wiki)

