# ☁️ Gerenciamento de Instâncias EC2 na AWS

![Diagrama de Arquitetura](Diagrama%20sin%20titulo.drawio.png)

## 📋 Descrição do Projeto
Este repositório contém a documentação de uma arquitetura de nuvem AWS desenhada para o desafio prático da **DIO**. O objetivo é demonstrar o fluxo de dados entre serviços de armazenamento, processamento serverless e computação elástica.

## 🏗️ Arquitetura Utilizada
A solução desenhada no **Draw.io** integra os seguintes serviços:
* **Amazon S3**: Bucket para armazenamento de objetos, configurado como gatilho de eventos.
* **AWS Lambda**: Função serverless que processa os dados automaticamente assim que chegam ao S3.
* **Amazon EC2**: Instância de servidor virtual para hospedar a aplicação e gerenciar os recursos finais.

## 🚀 Melhorias Implementadas
* **Documentação Visual**: Inclusão do diagrama diretamente no README para facilitar a visualização.
* **Organização de Fluxo**: Definição clara das responsabilidades de cada serviço na arquitetura.
* **Infraestrutura como Código (Mentalidade)**: Preparação do ambiente para futuras automações.

---
🚀 *Desenvolvido por Roberlande como parte do Roadmap de Cloud AWS.*
