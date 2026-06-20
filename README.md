# Projeto Artistas

Este projeto foi desenvolvido como desafio no curso de Java da Alura, com o objetivo de registrar artistas e suas músicas em um banco de dados relacional e fornecer esses dados ao usuário por meio de uma interface amigável via terminal.

---

## Objetivos

- Criar uma aplicação interativa via terminal para cadastro e consulta de artistas e músicas
- Implementar relacionamentos entre tabelas (Um para Muitos) utilizando Spring Data JPA
- Persistir as informações de forma definitiva em um banco de dados relacional (PostgreSQL) local
- Filtrar e buscar dados específicos do banco de dados, como listar as músicas de maior duração

---

## Tecnologias Utilizadas

- **Java 17**
- **Spring Boot 4.0.6**
- **Spring Data JPA** (Gerenciamento e persistência de dados com o banco)
- **PostgreSQL** (Banco de dados relacional para armazenamento dos dados)
- **Maven** (Gerenciador de dependências)
- **pgAdmin** (Interface gráfica para gerenciar o banco de dados)

---

## Como Executar

1. Certifique-se de ter o **Java 17+** e o **PostgreSQL** instalados
2. Clone o repositório
3. Configure as credenciais do seu banco de dados no arquivo `src/main/resources/application.properties`
4. Execute a aplicação através da sua IDE de preferência ou utilizando o comando:
```bash
   mvn spring-boot:run
```

---

## Imagens da Execução do Programa

### 1. Registrando um novo artista

   <img width="533" height="454" alt="image" src="https://github.com/user-attachments/assets/496e6e08-7c8e-41c5-b3ab-654ce7a66855" />
   
   Visualização no pgAdmin:
   
   <img width="468" height="128" alt="image" src="https://github.com/user-attachments/assets/b9bf447f-bb20-431d-97b9-b89ba7e5a28f" />
   
### 2. Registrando uma música para um artista

   <img width="499" height="408" alt="image" src="https://github.com/user-attachments/assets/92abce75-07fc-4544-9eb7-0d740b7d028d" />

   Visualização no pgAdmin:

   <img width="453" height="119" alt="image" src="https://github.com/user-attachments/assets/95664618-cb49-4b6a-afe7-b1548b924a02" />

### 3. Pesquisando um artista

<img width="518" height="383" alt="image" src="https://github.com/user-attachments/assets/a5ed745b-d224-4285-8791-b6523fbc0b56" />

### 4. Pesquisando as músicas de um artista

<img width="529" height="335" alt="image" src="https://github.com/user-attachments/assets/034cfd48-0141-4f96-93ae-b1b6351182b2" />

### 5. Analisando as músicas com maior duração de tempo

<img width="534" height="395" alt="image" src="https://github.com/user-attachments/assets/5c8616c8-1b2f-4a2a-aaac-f264f1110f05" />

### 0. Saindo

<img width="1535" height="384" alt="image" src="https://github.com/user-attachments/assets/63f0e9f3-7d52-41cd-a471-95cfb04a802c" />



   

