# Docker Manager API

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)


Este projeto é um gerenciador de containers Docker utilizando **Java, Spring Boot, Biblioteca Java Docker Client com 
JUnit e Mockito para testes unitários.** A API permite listar containers em execução ou 
parados, iniciar, parar, excluir containers e criar novos a partir de imagens 
especificas.

Projeto desenvolvido como forma de estudo.


## API Endpoints
A API fornece os seguintes endpoints:

```markdown
API Disponível na porta http://localhost:8080

GET /api/containers?showAll=true - Mostra todos os containers

GET /api/images - Mostra todas as imagens

POST /api/containers/{ID DO CONTAINER}/start - Inicia um container

POST /api/containers/{ID DO CONTAINER}/stop - Para um container

DELETE /api/containers/{ID DO CONTAINER} - Delete um container

```

## Contato

[![](https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/claytonbentes/)
[![](https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white)](mailto:claytonjhony.bentes@gmail.com)
