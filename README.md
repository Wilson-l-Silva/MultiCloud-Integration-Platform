# MultiCloud-Integration-Platform
criar uma plataforma de integração que recebe requisições HTTP, publica eventos, processa mensagens de forma assíncrona e armazena arquivos em serviços de nuvem.
<img width="1200" height="800" alt="image" src="https://github.com/user-attachments/assets/d2781840-2089-45e6-b644-309eb08bc12f" />

Objetivo: criar uma plataforma de integração que recebe requisições HTTP, publica eventos, processa mensagens de forma assíncrona e armazena arquivos em serviços de nuvem.

O projeto terá dois ambientes cloud:
- AWS: SQS, SNS e S3.
- Azure: Service Bus e Blob Storage.
Para desenvolvimento local, utilizaremos RabbitMQ e MinIO, evitando depender de contas pagas na nuvem durante os primeiros testes.
