# Por onde começar

Você deve criar um servidor web simples, onde a simplicidade é a palavra chave, o importante é ter como base e criar um ambiente que se encaixe o máximo possível às [12 factor app](https://12factor.net/ "12factor app").

O código produzido deve estar versionado em algum repositório público (Github, Bitbucket etc.).

Quando estiver tudo pronto, você deve mandar um e-mail para codesubmissions@vagas.com.br com o assunto Infraestrutura Linux -  VAGAS.com - <%SEU_NOME%> e o link para o seu repositório.

## Entregável

Ter uma aplicação web provisionada via [user-data](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/user-data.html) da AWS.

**Especificações ou requisitos referente a linguagem, framework ou arquitetura.**

- A aplicação deve rodar na AWS.
- Utilizar o user-data para executar os scripts após a inicialização da instância.
- O [CHEF](https://www.chef.io/chef/) como configuration management.
- O NGINX como webserver.
- Utilizar o Ubuntu na versão 16.04.
- Uma página web estática como frontend, temos um exemplo "index.html" caso queira utilizar.
  
**Caso queira utilizar o [Terraform](https://www.terraform.io) fique a vontade!**

----

## Tempo de entrega

O tempo para entrega dos testes será acordado junto ao seu contato na VAGAS, entendemos que é difícil encontrar tempo principalmente quando está trabalhando, portanto tente se organizar e combinar o tempo correto com a VAGAS.

----

## O que iremos avaliar

Queremos simplicidade. No entando alguns pontos serão importantes para avaliação:

- Como você cria documentações.
- Uso de controle de versão.
- Uso das melhores práticas de desenvolvimento (Unit/Integrations) testes.
- Estilo de código.
- Execução dos código sem erros.

Caso não consiga entregar todo o teste, não se preocupe, nos envie mesmo assim!

### Em caso de Dúvidas

Se tiver alguma dúvida, converse com seu contato na VAGAS!

Boa sorte! :))