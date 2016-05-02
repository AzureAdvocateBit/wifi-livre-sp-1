# #AzureSolutionlet - Dados Abertos

##Wifi Livre em São Paulo
Encontre redes wifi com acesso gratuito na cidade de São Paulo.

> Este web app foi desenvolvido com dados abertos e hospedado na plataforma [Microsoft Azure](https://azure.microsoft.com/pt-br/) e faz parte da série #AzureSolutionlets, onde resolve-se problemas específicos através de rápidos deploys utilizando o Microsoft Azure. Os dados abertos utilizados nesta aplicação, estão disponíveis no portal [Praças Wifi Livre SP](http://wifilivre.sp.gov.br/). 

Através deste Hands-on-lab você aprenderá a criar e configurar de um web app com integração contínua. Os recursos utilizados para deploy deste web app são extremamente úteis em projetos de diversos portes e é interessante que você faça o setup de uma conta trial no Azure a fim de obter o máximo desempenho e poder utilizar os recursos da plataforma.

### Passo 0: Criar conta trial do Microsoft Azure
Acesse https://azure.microsoft.com/pt-br/pricing/free-trial/ e clique no botão **Teste agora**:

![](https://raw.githubusercontent.com/allantargino/AzureSolutionlets/master/01-Prevendo-valores-no-Excel/images/p0-img01.png)

Logue-se com uma conta Microsoft (hotmail, live, etc). Em seguida, preencha seus dados. É necessário um telefone celular para verificar sua identidade, bem como um cartão de crédito válido. Após ler os termos e, caso concorde com eles, cheque *Eu concordo..."* seguido do clique em **Inscrever-se**:

![](https://raw.githubusercontent.com/allantargino/AzureSolutionlets/master/01-Prevendo-valores-no-Excel/images/p0-img02.png)

Você será uma levado a uma página onde deve aguardar alguns instantes até que sua subscrição esteja pronto para uso. Uma vez pronta, clique no botão verde para continuar e ser levado à tela inicial do Microsoft Azure:

![](https://raw.githubusercontent.com/allantargino/AzureSolutionlets/master/01-Prevendo-valores-no-Excel/images/p0-img03.png)

### Passo 1: Executando o projeto
Clone este projeto em sua máquina e instale as dependências via command line:
```
npm install
```
O gerenciamento de tasks do app é feito com [gulp](http://gulpjs.com/). Após a instalação das dependências, execute o comando a seguir:
```
gulp
```
Seu projeto estará acessível em: 127.0.0.1:4000.
