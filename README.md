# UFCD0816_JAVA_2023

# Exercício: Desenvolver uma Aplicação Spring Boot de Gestão de Tarefas

## Objetivo

Este exercício tem como objetivo permitir que os alunos apliquem conceitos basicos do Spring Boot, incluindo a configuração de projetos, a criação de classes de modelo, a implementação de controladores, a persistência de dados e a criação de uma API RESTful. Além disso, terão a oportunidade de integrar uma página web (HTML, CSS e JavaScript) para interagir com a lista de tarefas.

## Passos

1. **Configuração do Projeto:** Configure um novo projeto Spring Boot no seu ambiente de desenvolvimento. Pode utilizar o [Spring Initializer](https://start.spring.io/) para criar um projeto com as dependências necessárias, como o Spring Web, o Spring Data JPA e o Thymeleaf para a renderização de páginas web.

2. **Classe de Modelo:** Crie uma classe `Tarefa` para representar uma tarefa. A classe `Tarefa` pode conter campos como `id`, `título`, `descrição`, `data de vencimento` e `concluída`.

3. **Persistência de Dados:** Crie um repositório (interface) para a classe `Tarefa` e configure-o para comunicar com uma base de dados H2 (ou outra base de dados à sua escolha) para a persistência dos dados.

4. **Controlador Spring MVC:** Implemente um controlador Spring MVC para criar, listar, atualizar e excluir tarefas. Os métodos do controlador devem ser anotados com `@RequestMapping`, `@GetMapping`, `@PostMapping`, `@PutMapping` e `@DeleteMapping` conforme necessário.

5. **Interface de Utilizador Web:** Crie uma página web (HTML, CSS e JavaScript) que permita aos utilizadores visualizar a lista de tarefas, adicionar novas tarefas, marcar tarefas como concluídas e excluir tarefas.

6. **Lógica de Negócios:** Implemente um serviço que trate da lógica de negócios para as tarefas, como adicionar, listar, atualizar e excluir tarefas.

7. **API RESTful:** Configure um endpoint RESTful para fornecer a funcionalidade de API REST para a sua aplicação. Pode utilizar `@RestController` e `@RequestMapping` para definir os endpoints.

8. **Teste e Depuração:** Incentive-se a testar e depurar a sua aplicação à medida que avança. Pode usar as funcionalidades de depuração da sua ferramenta de desenvolvimento (por exemplo, o VS Code).

9. **Controle de Versão:** Certifique-se de efetuar commits regulares no seu repositório Git à medida que trabalha no projeto. Isso ajudará a acompanhar o seu progresso.

10. **Entrega e Revisão:** Quando concluir o exercício, envie o seu projeto para um repositório Git online (por exemplo, o GitHub) e partilhe o link com o seu instrutor ou colegas para revisão.

## Observações

Lembre-se de que este exercício é uma excelente oportunidade para aplicar o que aprendeu e também para integrar uma interface de utilizador utilizando HTML, CSS e JavaScript. Pode utilizar frameworks JavaScript como o Vue.js, React ou Angular, ou mesmo JavaScript puro, para criar a interatividade na página web. Use a sua criatividade para tornar a sua lista de tarefas amigável e funcional.
