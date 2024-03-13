# Hub_IoT
 Visualização em tempo real de dados provenientes de sensores conectados ao Azure Hub IoT
 

## Documentação do Projeto: Visualização de Dados do Azure IoT Hub
Este documento fornece um roteiro de prática para configurar e executar um aplicativo web para visualização de dados provenientes do Azure IoT Hub. Siga os passos abaixo para configurar seu ambiente de desenvolvimento e implantar o aplicativo na nuvem Azure.

Link: https://webfullstackiot.azurewebsites.net/

Execução:
![image](https://github.com/Wfelipetm/Hub_IoT/assets/108297008/bfc1392e-3591-450f-b9ba-47f1038df6ab)
![WhatsApp Image 2024-03-13 at 09 32 17](https://github.com/Wfelipetm/Hub_IoT/assets/108297008/25015091-622d-40f2-a3b8-4fb3dba2d9f9)

## Procedimentos
- Antes Precisa criar hub IOT no azure
- Adicionar um dispositivo
- Usar o Raspberry Pi para enviar Dados ao seu dispositivo criado
## 1. Baixar e Configurar o Código-fonte
- Acesse o repositório do aplicativo web no GitHub: Azure Samples - Web Apps Node IoT Hub Data Visualization.
- Clone ou faça o download do código-fonte.
- Descompacte os arquivos em uma pasta de sua escolha.
- Abra a pasta do aplicativo Web em sua IDE preferida, como o Visual Studio Code.
## 3. Adicionar Grupo de Consumidores ao Hub IoT
- Execute o seguinte comando na CLI do Azure para adicionar um grupo de consumidores ao ponto de extremidade interno do hub IoT: az iot hub consumer-group create --hub-name YOUR_IOT_HUB_NAME --name YOUR_CONSUMER_GROUP_NAME
## Execução:

![WhatsApp Image 2024-03-13 at 09 54 58](https://github.com/Wfelipetm/Hub_IoT/assets/108297008/7f983c75-5a0e-490b-b062-dabc95ab3050)







![WhatsApp Image 2024-03-13 at 09 58 04](https://github.com/Wfelipetm/Hub_IoT/assets/108297008/de1121a6-dcef-4e95-8734-1af3fb771989)

![WhatsApp Image 2024-03-13 at 09 33 48](https://github.com/Wfelipetm/Hub_IoT/assets/108297008/eb4caf48-7fc2-414e-9370-a975b39ff0a6)


