# Siri, Write the Next Method

F. Wen, E. Aghajani, C. Nagy, M. Lanza and G. Bavota, "Siri, Write the Next Method," 2021 IEEE/ACM 43rd International Conference on Software Engineering (ICSE), 2021, pp. 138-149, doi: [10.1109/ICSE43902.2021.00025](https://doi.org/10.1109/ICSE43902.2021.00025)

## 1. Fichamento de Conteúdo

O artigo apresenta um _"plugin"_ chamado FeaRS, que é um _"plugin"_ para auxiliar o desenvolvedor Android. O FeaRS tem como objetivo gerar de maneira automática código para o autor, não somente um código que complemente como a maioria das IDEs de hoje em dia fazem, mas sim gerar métodos de maneira automática, com o intuito de diminuir o tempo de implementação de novas funcionalidades. Para alcançar sua finalidade de gerar código para o desenvolvedor, os autores mineraram projetos Android open source e buscaram padrões de desenvolvimento comum entre esses desenvolvedores para que assim pudessem gerar padrões de implementação. Nessa mineração os autores observaram commits feitos no GitHub e identificaram métodos que costumam ser implementados de forma conjunta assim podendo estabelecer uma relação entre quais métodos seguem aqueles que já foram implementados. Após análises os autores chegaram à conclusão de que o FeaRS faz sim boas recomendações, porém, ainda possui inconsistência na sua precisão. A ideia de um sistema que gere linhas de código de maneira automática chama bastante a atenção, não só pela facilidade que traria ao desenvolvimento mas também na rapidez que traria pro mesmo. Na minha opinião ainda é difícil ter um sistema com alta eficiência nas recomendações de código, já que, os softwares tendem a se diferenciarem uns dos outros porém considero sim ser possível que o FeaRS ajuda bastante o desenvolvimento. Esse tópico abre portas para pensar em um tópico importante: Um software que se auto-escreve e se automodifica, seria possível atingir tal nível da tecnologia?

## 2. Fichamento Bibliográfico

- _Recommender systems_ (Sistemas de recomendação) são sistemas que auxiliam o desenvolvedor, oferecendo dicas e complementos pra complementar o código (página 138).
- _Cluster of methods_ (conjuntos de métodos) conjuntos de métodos gerados a partir da análise da frequência de implementação dos mesmos (página 140).
- _Method_ (Métodos) no sentido do texto método se dá como uma sub-rotina executada por um objeto (página 141).

## 3. Fichamento de Citações

- _"Code completion is one of the killer features of Integrated Development Environments (IDEs)"_
- _"FeaRS applies association rule discovery [ 1 0 ] on all commits, thus creating the set of implementation patterns it relies on."_
- _"We aim at reaching the next level in supporting developers during the writing of new code."_
