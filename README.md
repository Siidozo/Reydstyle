# Web Aplication 

Reyd_style

# OBJETIVO:

O objetivo dessa aplicação é realizar a criação de um E-commerce de vestuarios interativo e responsivo que possa suprir a demanda do cliente.

# Liguagens de Densenvolvimento Front-End:

- HTML5;
- CSS3;
- JavaScript;
  
## RFs (Requisitos funcionais)

- [x] Deve ser possível se cadastrar;
- [x] Deve ser possível se autenticar;
- [x] Deve ser possível obter o perfil de um usuário logado;
- [x] Deve ser possível o usuário obter o seu histórico de compras;
- [x] Deve ser possível o usuário buscar o produto desejado;
- [x] Deve ser possível o usuário buscar o produto pelo nome;
- [x] Deve ser possível o usuário realizar check-in no carrinho;
- [x] Deve ser possível validar o meio de pagamento do usuário;
- [x] Deve ser possível check-out;
- [x] A senha do usuário precisa estar criptografada;
- [x] Os dados da aplicação precisam estar persistidos em um banco PostgreSQL;
- [x] O usuário deve ser identificado por um JWT (JSON Web Token);

## RNFs (Requisitos não funcionais)

- [x] O login da aplicação deve ser concluido em ate 7seg
- [x] A aplicação deve se mantida em funcionamento 24h/7d por semana. 
- [x] Todas as listas de dados precisam estar paginadas com 20 itens por página;
- [x] Ecalabilidade: A aplicação deve se manter em funcionamento mesmo tendo 1000 usuarios simultaneamente.
- [x] Degradação: A aplicação deve ser capaz de atender 100° requisiçoes por segundo e ignorar a requições acima da 100° para que nao aconteça a degradaçao do tempo de resposta.


## RNs (regras de negócios)

- [x] O usuário não deve poder se cadastrar com um e-mail duplicado;
- [x] O usuario só pode ser validado até confimação do email;
- [x] O usuario só pode ser validado pelos 2FA;
- [x] Uma academia só pode ser cadastrada por administradores;
