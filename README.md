# Docker Microservices App
Projeto baseado em Docker e microsserviços, aprimorado a partir de um projeto original.

# Docker Microservices App

Este repositório é um projeto baseado em Docker e microsserviços, aprimorado a partir do projeto original de [Denilson Bonatti](https://github.com/denilsonbonatti/toshiro-shibakita). O objetivo é demonstrar boas práticas na arquitetura de microsserviços utilizando contêineres.

## Melhorias Implementadas
- Documentação mais completa.
- Otimização do `Dockerfile` para reduzir tamanho da imagem.
- Aprimoramentos no `nginx.conf` para maior segurança e eficiência.
- Melhor separação da lógica de negócio no `index.php`.
- Melhor tratamento de erros e sanitização de entrada.

## Como Executar o Projeto

1. **Clone este repositório:**
    ```bash
    git clone https://github.com/newtonfalbo/docker-microservices-app.git
    cd docker-microservices-app
    ```

2. **Suba os containers com Docker Compose:**
    ```bash
    docker-compose up -d
    ```

3. **Acesse a aplicação:**
    - Abra o navegador e acesse `http://localhost`

4. **Parar os containers:**
    ```bash
    docker-compose down
    ```

## Estrutura do Projeto
```
/docker-microservices-app
│── /app               # Código-fonte principal
│── /db                # Scripts de banco de dados
│── docker-compose.yml # Orquestração dos containers
│── Dockerfile         # Configuração da imagem Docker
│── nginx.conf         # Configuração do Nginx
│── README.md          # Documentação do projeto
```

## Tecnologias Utilizadas
- Docker
- Docker Compose
- PHP
- MySQL
- Nginx

## Contribuição
Fique à vontade para contribuir com melhorias, sugerindo alterações ou abrindo issues!

## Licença
Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
