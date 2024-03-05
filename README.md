# Web Aplication 

Reyd_style

# OBJETIVO:

O objetivo dessa aplicação é realizar a criação de um E-commerce de vestuarios interativo e responsivo que possa suprir a demanda do cliente.

# Liguagens de Densenvolvimento Front-End:

- HTML5;
- CSS3;
- JavaScript;

  
## RFs (Requisitos funcionais)

-  [x] Deve ser possível se cadastrar;
-  [x] Deve ser possível se autenticar;
-  [x] Deve ser possível obter o perfil de um usuário logado;
-  [x] Deve ser possível que o usuário obtenha seu histórico de compras;
-  [x] Deve ser possível o usuário buscar o produto desejado;
-  [x] Deve ser possível o usuário buscar o produto pelo nome;
-  [x] Deve ser possível que o usuário realize check-in no carrinho;
-  [x] Deve ser possível validar o meio de pagamento do usuário;
-  [x] Deve ser possível check-out;
-  [x] A senha do usuário precisa ser criptografada;
-  [x] Os dados da aplicação precisam ser persistidos em um banco PostgreSQL;
-  [x] O usuário deve ser identificado por um JWT (JSON Web Token);

## RNFs (Requisitos não funcionais)

-  [x] O login da aplicação deve ser concluído em até 7seg
-  [x] A aplicação deve ser mantida em funcionamento 24h/7d por semana.
-  [x] Todas as listas de dados precisam estar paginadas com 20 itens por página;
-  [x] Ecalabilidade: A aplicação deve se manter em funcionamento mesmo tendo 1000 usuários simultaneamente.
-  [x] Degradação: Um aplicativo deve ser capaz de atender 100° requisições por segundo e ignorar requisições acima de 100° para que não aconteça uma degradação do tempo de resposta.


## RNs (regras de negócios)

-  [x] O usuário não deve poder se cadastrar com um e-mail duplicado;
-  [x] O usuário só pode ser validado até a confirmação do email;
-  [x] O usuário só pode ser validado pelo 2FA;
