# notas-importantes-banco-de-dados

Contexto geral sobre bancos de dados na atualidade:
Os bancos de dados relacionais e não relacionais podem se complementar em algumas situações. E o trabalho do engenheiro de dados é ter a flexibilidade de entender e não se limitar a só uma opção. 

O NoSQL não foi criado para substituir o SQL. O banco não relacional surgiu das diferentes necessidades de acordo com a escalabilidade, de ter que armazenar um volume maior de informações e não estruturada. Com a necessidade de armazenar diferentes arquivos, documentos, fotos e ele vem como um banco que permite-se trabalhar sem ter um esquema de dados rígidos. Ele é um complemento e veio para atender o que não era possível fazer com o banco de dados relacional. O Mongo por exemplo dá a liberdade de ir adicionando os dados e organizando conforme os dados são adicionados. Cada banco tem as suas particularidades e contextos diferentes, sendo adequados para o tipo de uso que se encaixa melhor com quem está fazendo uso. Ele oferece uma escalabilidade horizontal que facilita a consulta de informações, ele reduz a complexidade da consulta. 

Como fazer uma consulta de dado armazenado no NoSQ:
É importante definir as chaves e a forma como se quer consultar esses dados. A aplicação também deve saber com a falta de previsibilidade de um schema, quais informações podem ou não ser desprezadas dentro de uma consulta dentro de um banco não relacional. 

Não é necessário conhecer todas as ferramentas que existem para começar a trabalhar. São muitas ferramentas e muitos tipos. É importante saber o contexto e as particularidades, e os propósitos. Dessa forma, quando for necessário fazer o uso, é possível ter uma curva de aprendizado mais simples para aprender outra tecnologia, já conhecendo esse contexto. 

O data lake recebe muitas informações e é necessário tomar precauções para não ficar com muitas informações de forma que seja possível fazer a gestão necessária. O maior desafio é a manipulação dos dados, seja da gestão, da manipulação, do processamento, preparação de dados para que eles fiquem disponíveis nas camadas de processamento. Tudo envolve essa manipulação, e daí podem ser criadas rotinas, online, diárias, semanais e etc. 

O banco é um componente importante dentro da arquitetura, e a escolha do banco parte por como a informação vai ser manipulada, e o quanto pode-se ter conexão com outras ferramentas. Existe a correlação entre a complexidade dos bancos de dados e da gestão. Dependendo do tipo do banco de dados, ao fazer a escolha do banco e colocar no contexto, é necessário saber que tipo de dados vão ser colocados ali, o tipo de processamento que vai ser aplicado para os dados armazenados, quais são as formas mais comuns para fazer isso, como vão ser realizadas as consultas e etc. 
