# Guia Básico NestJS

Este guia fornece uma introdução básica ao framework NestJS e compara sua estrutura e conceitos com o Spring Boot.

## Configuração e Compilação do Projeto NestJS

### Instalação

Certifique-se de ter o Node.js instalado. Em seguida, instale o CLI do NestJS globalmente:

```bash
npm install -g @nestjs/cli
```

### Criação do Projeto
Se você já tem um projeto, ótimo! Caso contrário, crie um novo com:

```sh
nest new project-name
```

### Estrutura de Diretórios
A estrutura de diretórios do NestJS é similar ao Spring Boot, com algumas diferenças:

* **Modules (Módulos)**: Equivalente aos @Component no Spring Boot, são classes anotadas com @Module.
* **Controllers (Controladores)**: Assim como os @RestController no Spring Boot, são anotados com @Controller.
* **Services (Serviços)**: Semelhante aos @Service no Spring Boot, são anotados com @Injectable.
* **Entities (Entidades)**: No NestJS, as entidades são definidas como classes simples em TypeScript, geralmente dentro de uma pasta entities ou models.

### Compilação
Execute o seguinte comando para compilar o projeto NestJS:

```sh
npm run build
```

### Execução
Para rodar o projeto, use:

```sh
npm run start
```