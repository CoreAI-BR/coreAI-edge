Global Solution 

Descrição do Projeto

Este projeto tem como objetivo simular a comunicação entre um dispositivo IoT e um broker MQTT, representando o envio de dados relacionados à análise de currículos e vagas disponíveis. A proposta está alinhada com os requisitos da Global Solution, utilizando ferramentas acessíveis e funcionais mesmo sem hardware físico.
Tecnologias Utilizadas

    Python 3

    Google Colab

    Biblioteca paho-mqtt

    Broker público HiveMQ

    Aplicativo My MQTT (Android/iOS)

 Funcionalidade

O sistema realiza os seguintes passos:

    Solicita ao usuário:

        Quantidade de vagas disponíveis

        Quantidade de pessoas que já aplicaram

    Calcula uma chance estimada de ser chamado, com base em uma fórmula simples que gera valores entre 0% e 100%.

    Envia a mensagem via protocolo MQTT para o tópico coreAI/curriculo.

    A mensagem pode ser visualizada em tempo real no aplicativo My MQTT, conectado ao broker público HiveMQ.

 Como testar com o app My MQTT

    Baixe o app My MQTT no celular.

    Vá em Configurações e insira:

        Host: broker.hivemq.com

        Porta: 1883

        Client ID: qualquer nome (ex.: CoreAIClient)

    Vá em Subscribe e insira o tópico:
    coreAI/curriculo
Link Do Video (https://youtu.be/4lY24P2x4R8)
eito por:

    Tomomé — RM: 562422

    Leonardo Eiji Kina — RM: 562784

    Nicholas Braga de Souza — RM: 561733
