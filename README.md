# Battleship

Grupo - TP04-1

Curso - LETI

Tiago Eliseu nº122603

Guilherme Teixeira nº111138

#YAML File
Este projeto utiliza GitHub Actions para garantir a qualidade do código através de um workflow de Integração Contínua ("Java CI with Maven").

O workflow é acionado automaticamente em cada `push` ou `pull_request` para o ramo `main` e realiza as seguintes verificações:
 Configura o ambiente com JDK 17 (Eclipse Temurin).
 Compila o projeto utilizando o Maven.
 Executa automaticamente todos os testes unitários (JUnit) para validar a integridade da build.

Desta forma, garantimos que novas alterações não introduzem erros no código existente.
