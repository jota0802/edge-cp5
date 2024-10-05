
# **Challenge Mahindra Edge-Computing**

Este projeto exemplifica uma solução de Edge Computing, onde um **ESP32** simulado no **Wokwi** coleta informações de **temperatura** e **umidade** e envia esses dados para uma plataforma **IoT** integrada ao **FIWARE**. As variáveis são gerenciadas pelo **Postman**, enquanto o projeto é hospedado em uma **VM no Azure**. Além disso, utilizamos **Docker** para facilitar o gerenciamento de ambientes e **MQTT** como protocolo de comunicação para os dados.

## Índice
- [Visão Geral](#visão-geral)
- [Arquitetura do Projeto](#arquitetura-do-projeto)
- [Funcionalidades](#funcionalidades)
- [Instalação](#instalação)
- [Como Usar](#como-usar)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Demonstração em Vídeo](#demonstração-em-vídeo)
- [Desenvolvedores](#desenvolvedores)

## Visão Geral

O projeto tem como foco ilustrar a aplicação de Edge Computing em um ambiente simulado de IoT. Um **ESP32**, simulado no **Wokwi**, coleta dados de temperatura e umidade. Esses dados são enviados via **MQTT** para uma plataforma IoT integrada ao **FIWARE**, onde são gerenciados e monitorados. Para a criação e manipulação de variáveis, utilizamos o **Postman**. O projeto é totalmente containerizado com **Docker** e está hospedado em uma **VM no Azure**.

## Arquitetura do Projeto

1. **ESP32 (Wokwi)**: O dispositivo simula a coleta de dados de sensores de temperatura e umidade.
2. **MQTT**: Protocolo de comunicação usado para enviar os dados coletados para o FIWARE.
3. **FIWARE**: Plataforma IoT que recebe, processa e gerencia os dados.
4. **Postman**: Utilizado para criação e manipulação de variáveis que controlam o fluxo de dados.
5. **VM no Azure**: Ambiente de hospedagem do projeto.
6. **Docker**: Facilita a gestão do ambiente, garantindo que todas as dependências estejam contidas em um ambiente isolado.

### Fluxo de Dados
1. O **ESP32** no Wokwi coleta os dados de temperatura e umidade.
2. Os dados são enviados via **MQTT** para o **FIWARE**.
3. O **FIWARE** recebe os dados e os processa.
4. Utilizamos o **Postman** para criar e testar as variáveis que gerenciam o fluxo de dados dentro da plataforma.
5. Finalmente, os dados são apresentados na interface do Postman.

## Funcionalidades

- Coleta de dados de temperatura e umidade.
- Envio de dados via **MQTT** para o **FIWARE**.
- Hospedagem e gerenciamento do projeto via **Docker** e **VM no Azure**.
- Manipulação de variáveis e teste de rotas com **Postman**.
- Simulação completa de Edge Computing e IoT.

## Instalação

### Pré-requisitos

- Docker
- Virtual Machine no azure
- Wokwi
- Postman

### Passos de Instalação

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/PCD-CodeX/Edge-Computing/blob/main/FIWARE%20Descomplicado.postman_collection.json
   ```

2. **Configurar o Docker**:
   Certifique-se de que o Docker esteja instalado e rodando em sua máquina. Para instalar as dependências necessárias, rode:
   ```bash
   docker-compose up
   ```

3. **Configurar a VM no Azure**:
   Siga as instruções da documentação do Azure para configurar uma VM com FIWARE, e em seguida busque como baixar o docker na VM. e clone o repositorio do Fiware descompilado para o postman.

4. **Configurar o Wokwi**:
   Acesse o [Wokwi](https://wokwi.com/projects/410502656857220097) e configure o ESP32 para simular os sensores de temperatura e umidade.

5. **Configurar o Postman**:
   Importe o Fiware descompilado no Postman e configure as variáveis de ambiente.

## Como Usar

1. Inicie a simulação no **Wokwi** para coletar dados de temperatura e umidade.
2. O **ESP32** enviará os dados via **MQTT** para o **FIWARE**.
3. Abra o **Postman** para visualizar e manipular os dados recebidos.
4. Ligue a VM configurada no **Azure**, e todos os componentes podem ser gerenciados pelo **Docker**.

## Tecnologias Utilizadas

- **ESP32 (Wokwi)**: Simulação de hardware.
- **FIWARE**: Plataforma para IoT e Smart Solutions.
- **MQTT**: Protocolo de transporte leve para dispositivos IoT.
- **Postman**: Ferramenta para API Testing.
- **Azure**: Plataforma de cloud computing para hospedar a VM.
- **Docker**: Containerização e gestão de ambientes.
- **JavaScript**: Lógica de backend.
- **Node.js**: Execução de JavaScript no servidor.

## Demonstração em Vídeo

Para uma explicação visual do projeto e seu funcionamento, assista ao vídeo abaixo:

[![Demonstração do Projeto](https://img.youtube.com/vi/MWhlSmGXl88/0.jpg)](https://youtu.be/MWhlSmGXl88)

## Desenvolvedores

# <h1 align="center">Desenvolvedores</h1>

-------

| Dev | Avatar | RM |
| ------------- | ------ | ----- |
| ![](https://img.shields.io/badge/DEV-João-47797a?style=for-the-badge&logo=github) | <a href="https://github.com/jota0802"><img src="https://avatars.githubusercontent.com/u/161319025?v=4" height="50" style="border-radius:30px;"></a> | RM556790 |
| ![](https://img.shields.io/badge/DEV-Yuri-70b2b4?style=for-the-badge&logo=github) | <a href="https://github.com/yurisilpess"><img src="https://avatars.githubusercontent.com/u/99032447?v=4" height="50" style="border-radius:30px;"></a> | RM557475 |
| ![](https://img.shields.io/badge/DEV-Igor-7ca787?style=for-the-badge&logo=github) | <a href="https://github.com/igor-soos"><img src="https://avatars.githubusercontent.com/u/164360059?v=4" height="50" style="border-radius:30px;"></a> | RM556010 |
| ![](https://img.shields.io/badge/DEV-Pietro-537064?style=for-the-badge&logo=github) | <a href="https://github.com/Pic0777"><img src="https://avatars.githubusercontent.com/u/162361580?v=4" height="50" style="border-radius:30px;"></a> | RM557283 |
| ![](https://img.shields.io/badge/DEV-Gustavo-516b58?style=for-the-badge&logo=github) | <a href="https://github.com/gus7a2005"><img src="https://avatars.githubusercontent.com/u/161319479?v=4" height="50" style="border-radius:30px;"></a> | RM556289 |
