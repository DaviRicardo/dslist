# Projeto DSList
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/DaviRicardo/dslist/blob/main/LICENSE) 

# Sobre o projeto

DSList é uma aplicação back-end de coleções de jogos por listas onde os usuários podem reposicionar seus jogos favoritos e criar suas próprias classificações. Isso funciona por meio de uma API Web fornecida pela aplicação com endpoints que vão desde a listagem de todos os jogos até a possibilidade de reposicioná-los a gosto.

O projeto foi desenvolvido no período de uma semana durante a edição de agosto de 2025 do evento **Intensivão Java Spring** organizado pela escola [DevSuperior](https://devsuperior.com.br "Site da DevSuperior").

## Diagrama de Classes
![Diagrama de Classes](https://github.com/DaviRicardo/assets/raw/main/IJS25/diagrama-classes.png)

## Testes de API com Postman

![Postman](https://github.com/DaviRicardo/assets/raw/main/IJS25/postman.png)

## Persistência de dados e homologação com PostgreSQL

![Pgadmin](https://github.com/DaviRicardo/assets/raw/main/IJS25/pgadmin.png)

# Tecnologias utilizadas

- Java LTS 21;
- Spring Boot 3.5.5;
- Spring Data JPA e Hibernate;
- Maven apache 3.1.0;
- Docker Compose

## Banco de dados
- Realização de testes: H2;
- Homologação: PostgreSQL

# Como executar o projeto

## Pré-requisitos 
- Java Development Kit (JDK) 21 ou superior;
- Maven apache 3.1.0 ou superior

## Spring Tool Suite (STS)
```bash
# clonar repositório na pasta de destino
git clone git@github.com:DaviRicardo/dslist.git
```
### No STS siga:
1. File -> Import -> Maven -> Existing Maven Projects;
2. Ao lado de Root Directory pesquise pela pasta do projeto com Browse e selecione-a;
3. Em Boot Dashboard clique com o botão direito no nome do projeto e Re(start) para executá-lo.

## Visual Studio Code (VSCode)

```bash
# clonar repositório
git clone git@github.com:DaviRicardo/dslist.git

# executar o projeto
./mvnw spring-boot:run
```

# Autor

Davi Ricardo Alves da Silva

https://www.linkedin.com/in/davialvessilva