# Projeto Kafka Java

Este projeto tem como objetivo demonstrar a implementação de comunicação assíncrona entre produtores e consumidores utilizando **Apache Kafka** com **Java**.

## 🛠 Tecnologias Utilizadas

- Java 17+
- Apache Kafka
- Spring Boot (opcional)
- Docker (para execução local do Kafka)
- Maven ou Gradle
- Kafka Tool ou Offset Explorer (para visualização dos tópicos)

## 📁 Estrutura do Projeto

```bash
kafka-java-project/
│
├── producer/              # Código do produtor Kafka
│   └── ProducerMain.java
│
├── consumer/              # Código do consumidor Kafka
│   └── ConsumerMain.java
│
├── docker/                # Scripts e arquivos Docker para subir Kafka/Zookeeper
│   └── docker-compose.yml
│
└── README.md              # Documentação do projeto
```
💡 Objetivo
Este projeto foi criado com o intuito de estudar e praticar os conceitos fundamentais do Apache Kafka, incluindo a criação de tópicos, produtores e consumidores simples com Java puro.

📌 Notas
Certifique-se de que o Docker esteja instalado e funcionando.

Os tópicos podem ser criados automaticamente dependendo da configuração (auto.create.topics.enable).

Você pode usar o Kafka Tool (Offset Explorer) para visualizar os tópicos.

