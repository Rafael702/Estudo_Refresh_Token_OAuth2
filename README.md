#Estudos sobre Refresh Token

>Neste repositório consta os meus estudos sobre o refresh token com o oauth2.
> 

Dependencia:

```maven
<dependency>
<groupId>org.springframework.security.oauth</groupId>
<artifactId>spring-security-oauth2</artifactId>
<version>6.21.2</version>
</dependency>
```

Para quê serve o Refresh Token?

>Uma vez que o token JWT estiver expirado o cliente terá que realizar uma nova requisição para a rota de autenticação enviando as credenciais do usuário, porém isso não traz uma boa usabilidade para o nosso projeto, convenhamos que ninguém gosta de ficar informando seu usuário e senha a todo momento enquanto está utilizando algum sistema.
> 
>Então, para evitar que o cliente tenha que novamente realizar uma nova autenticação sempre que o token estiver expirado podemos utilizar o refresh token.
>
> Link: https://www.treinaweb.com.br/blog/fluxo-de-autenticacao-baseado-em-jwt


Obs: Este Projeto Foi desenvolvido com base no curso da AlgaWorks e outras pesquisas.
Recomendo o curso: Especialista Spring Rest (ESR)