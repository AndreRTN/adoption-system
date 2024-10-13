# adoption-spring-boot
Projeto de gestão de adoção de animais

---

> ### Forma mais fácil de executar o projeto: em uma pasta vazia, execute os seguintes comandos: 
  - `git clone --recurse-submodules https://github.com/AndreRTN/adoption-system`
  - `docker-compose up --build`

> Backend do sistema de gestão de adoção de animais

> - Java 21
> - Banco de dados H2
> - Spring JPA
> - Swagger

> ### Observações: 
- > Para utilizar o swagger, executar o projeto e entrar na url: http://localhost:8080/swagger-ui.html

- >### Executando diretamente (Necessário Java 21 na máquina)
  > - Abrindo o projeto em alguma IDE (IntelliJ) e clicando em run project 
          
- > ### Docker compose (default) (necessário docker na máquina)
  > - Rodar o comando: docker-compose up --build (apenas na primeira vez, após isso subirá um container)
  > - Qualquer alteração feita no projeto será atualizada no container, basta parar a aplicação e rodar novamente


  > Frontend do sistema de gestão de adoção de animais

> - React
> - Typescript


- >### Executando diretamente (Necessário Node na máquina)
  > - Abrindo o projeto no VSCode e digitando npm install -> npm start
          
- > ### Docker compose (default) (necessário docker na máquina)
  > - Rodar o comando: docker-compose up --build (apenas na primeira vez, após isso subirá um container)
  > - Qualquer alteração feita no projeto será atualizada no container, basta parar a aplicação e rodar novamente