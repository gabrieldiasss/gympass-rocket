# App

## Rfs (Requisitos funcionais)

O que vai ser possível o usuário fazer na aplicação (Funcionalidade)

- [] Deve ser possível se cadastrar
- [] Deve ser possível se autenticar
- [] Deve ser possível obter o perfil de um usuário logado
- [] Deve ser possível obter o numéro de check-ins realizados pelo usuário logado
- [] Deve ser possível o usuário obter seu histórico de check-ins
- [] Deve ser possível o usuário buscar academias próximas
- [] Deve ser possível o usuário buscar academias pelo nome
- [] Deve ser possível o usuário realizar check-in na academia
- [] Deve ser possível validar o check-in de um usuário
- [] Deve ser possível cadastrar uma academia

## Rns (Regras de negócio)

Caminhos que cada requisito pode tomar (Determina as condições que são aplicadas)

- [] O usuário não deve poder se cadastrar com um email duplicado
- [] O usuário não pode fazer 2 check-ins no mesmo dia
- [] O usuário não não pode fazer check-in se não estiver a 100 metros da academia
- [] O check-in só pode ser validado até 20 minutos após criado
- [] O check-in só pode ser validado por administradores
- [] A academia só pode ser cadastrada por administradores

Sempre vai está associada ao requisito funcional

-

## RNFs (Requisitos não funcionais)

Requisito técnicos

- [] A senha do usuário precisa estar criptografada
- [] os dados da aplicação precisa estar persistidos em um banco PostgreSQL
- [] Todas as listas de dados precisam estar paginados com 20 itens por página
- [] o usuário deve ser identificado por um JWT
