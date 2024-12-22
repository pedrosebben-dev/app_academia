#App

Gympass Style app.

## RFs (Requisitos funcionais)

- [] Deve ser possivel se cadastrar;
- [] Deve ser possivel se autenticar;
- [] Deve ser possivel obter o perfil de um usuário logado;
- [] Deve ser possivel obter o número de chack-ins realizados pelo usuario logado;
- [] Deve ser possivel o usuario obter seu historico de check-ins;
- [] Deve ser possivel o usuario buscar academias proximas;
- [] Deve ser possivel o usuario buscar academias pelo nome;
- [] Deve ser possivel o usuario realizar check-in em uma academia;
- [] Deve ser possivel validar o check-in de um usuario;
- [] Deve ser possivel cadastrar uma academia;

## RNs (Regras de negócios)

- [] O usuario náo deve poder se cadastrar com um e-mail duplicado;
- [] O usuario nao pode fazer 2 check-in no mesmo dia;
- [] O usuario nao pode fazer check-in se nao estiver perto (100metros) da academia;
- [] O chack-in so pode ser validado ate 20 minutos apos criado;
- [] O check-in so pode ser validado por administradores;
- [] A academia so pode ser cadastrada por administradores;

## RNFs (Requisitos nao-funcionais)

- [] A senha do usuario precisa estar criptografada;
- [] Os dados da aplicacao precisam estar persistidos em um banco postgreSQL;
- [] Todas listas de dados precisam estar paginados com 20 itens por pagina;
- [] O usuario deve ser identificado por um JAT (JSON Web Token)
