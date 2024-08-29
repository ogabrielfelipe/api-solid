# App

Gympass style app.

## RFs (Requisitos funcionais)
O que o usuário pode realizar na aplicação

- [x] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível obter o perfil de um usuário logado;
- [ ] Deve ser possível obter o número de check-ins realizados pelo usuário logado;
- [ ] Deve ser possível o usuário obter seu histórico de check-ins;
- [ ] Deve ser possível o usuário buscar academias próximas;
- [ ] Deve ser possível o usuário buscar academias pelo nome;
- [ ] Deve ser possível o usuário realizar check-in em uma academia;
- [ ] Deve ser possível validar o check-in de um usuário;
- [ ] Deve ser possível cadastrar uma academia;

## RNs (Regras de negócio)
Caminhos que cada requisito pode tomar.

- [ ] O usuário não deve poder se cadastrar com um e-mail duplicado;
- [ ] O usuário não pode fazer 2 check-ins no mesmo dia;
- [ ] O usuário não pode fazer check-in se não estiver perto (100m) da academia;
- [ ] O check-in só pode ser validado até 20 minutos após criado;
- [ ] O check-in só pode ser validado por administradores;
- [ ] A academia só pode ser cadastrada por administradores;

## RNFs (Requisitos não-funcionais)
São requisitos que não partem dos clientes, são requisitos técnicos (Banco de dados, etc)

- [ ] A senha do usuário precisa estar criptografada;
- [ ] Os dados da aplicação precisa estar persistidos em um banco PostgreSQL;
- [ ] Todas as litas de dados precisam estar paginadas com até 20 itens por páginas;
- [ ] O usuário deve ser identificado por um JWT (JSON Web Token);