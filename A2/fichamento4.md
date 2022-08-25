# To Type or Not to Type? A Systematic Comparison of the Software Quality of JavaScript and TypeScript Applications on GitHub

J. Bogner and M. Merkel, "To Type or Not to Type? A Systematic Comparison of the Software Quality of JavaScript and TypeScript Applications on GitHub," 2022 IEEE/ACM 19th International Conference on Mining Software Repositories (MSR), 2022, pp. 658-669, doi: 10.1145/3524842.3528454.

## 1. Fichamento de Conteúdo

O artigo apresenta uma comparação entre JavaScript(JS) e TypeScript. JavaScript é uma linguagem muito popular e muito versátil, porém ela carrega com si uma fama de produzir softwares de baixa qualidade. Por outro lado existe o TypeScript que com sua tipagem forte visa cobrir esses “buracos” que são deixados pelo JavaScript na produção de software. Com base nisso, os pesquisadores conduziram uma pesquisa baseada na mineração de repositórios do GitHub em projetos que utilizam JavaScript e TypeScript como linguagem principal. Com esses dados, os pesquisadores analisaram a qualidade do código, a complexidade cognitiva, os _bugs_ concertados e o tempo para consertar cada _bug_.
O objetivo da pesquisa era responder duas principais questões:a) As aplicações que utilizam TypeScript apresentam melhor qualidade do que as que utilizam JavaScript?
b) As aplicações TypeScript que utilizam tipagem de qualquer tipo com menos frequência tem melhor qualidade?. Baseado nessas perguntas os autores utilizaram o _SonarQube_
para: fazer análise de _code smells_ na aplicação e fazer o cálculo da complexidade cognitiva do código. Analisaram a propensão de _bugs_ baseados em uma análise de _commits_ no _GitHub_ e também o tempo que levou para ser resolvido cada um desses _bugs_. Com isso os autores chegaram à conclusão de que aplicações TypeScript apresentam uma qualidade muito maior e apresentam maior facilidade de entendimento da aplicação do que aplicações JavaScript, porém, a aparição de _bugs_ e o tempo de resolução dos mesmos não foi tão diferente entre as linguagens.

## 2. Fichamento Bibliográfico

- _Code Smells_ (fedores de código) partes do código que não são necessariamente bugs ou estão incorretos tecnicamente mas sim uma violação de princípios de design (página 1).
- _Bug proneness_ (tendências de bugs) no texto se refere a suscetibilidade de um código de apresentar um bug (página 4).
- _LoC(lines of code)_ (linhas de código) uma abreviação para linhas de código (página 6).

## 3. Fichamento de Citações

- _"The analysis indicates that TS applications exhibit significantly better code quality and understandability than JS applications."_
- _"Both RQs are well suited for a mining software repository (MSR) study [16, 20], as open-source platforms like GitHub7 provide large quantities of the necessary data for such analyses."_
- _" we could show that TypeScript applications and refraining from using the any type are connected to improved code quality and understandability."_
