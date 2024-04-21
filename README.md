# DockerSpringBoot

## Descrição

O projeto DockerSpringBoot é uma demonstração simples de como executar uma aplicação Spring Boot dentro de um contêiner Docker. Este repositório fornece instruções básicas sobre como construir e executar a aplicação dentro de um ambiente Dockerizado.

## Pré-requisitos

- Docker instalado e configurado no seu sistema. Para instruções de instalação, consulte a [documentação oficial do Docker](https://docs.docker.com/get-docker/).
- Conhecimento básico sobre o Spring Boot.

## Como usar

1. **Construa a imagem Docker:**

    Execute o seguinte comando para construir a imagem Docker:

    ```bash
    docker build -t docker-spring-boot .
    ```

2. **Execute o contêiner Docker:**

    Após a construção da imagem, execute o seguinte comando para iniciar a aplicação dentro de um contêiner Docker:

    ```bash
    docker run -d -p 8080:8080 docker-spring-boot
    ```

3. **Acesse a aplicação:**

    Abra o seu navegador web e acesse `http://localhost:8080` para visualizar a aplicação Spring Boot em execução dentro do contêiner Docker.
