<h1>Olá, seja BEM-VINDO!</h1>

<div align="left">
  
  <h2>Objetivo</h2>
  <p>Construir um modelo de Machine Learning capaz de prever a cotação de criptomoedas.</p>
  
  <h2>O que é Criptomoeda e Bitcoin?</h2>
    <p>Bitcoin é a criptomoeda mais antiga e conhecida, lançada pela primeira vez como código aberto em 2009 pelo anônimo Satoshi Nakamoto. </p>
    <p>O Bitcoin serve como um meio descentralizado de troca digital, com transações verificadas e registradas em um livro público distribuído (a Blockchain) sem a           necessidade de uma autoridade de manutenção de registros ou intermediário central. </p>
    <p>Os blocos de transação contêm um hash criptográfico SHA-256 de blocos de transação anteriores e, portanto, são "encadeados" juntos, servindo como um registro         imutável de todas as transações que já ocorreram. </p>
    <p>Neste Mini-Projeto foram utilizados dados históricos de cotação do Bitcoin de 2011 a 2021. Como o ano de 2022 foi bem atípico para o Bitcoin, optamos por não usar dados deste ano.</p>
  
  <h2>O que é Apache Spark?</h2>
  <p>O Apache Spark é uma ferramenta de análise de Big Data, escalável e eficiente. Apache Spark é um framework open-source para processamento de Big Data construído para ser veloz, fácil de usar e para análises sofisticadas. O Spark é desenvolvido na linguagem Scala e executa em uma máquina virtual Java. Atualmente, suporta como    linguagens para o desenvolvimento de aplicativos, as linguagens: Scala, Java, Python e R.</p>
  <p>O Apache Spark é um sistema de análise de dados distribuído e altamente escalável que permite processamento em memória. É atualmente um dos principais projetos da Apache Foundation. O Spark estende as funcionalidades do MapReduce, suportando tarefas mais eficientes de computação como queries iterativas e processamento de streams de dados. Velocidade é importante quando processamos grandes conjuntos de dados (Big Data) e uma das principais características do Spark é exatamente sua velocidade, permitindo o processamento de dados em memória e ainda é bastante eficiente quando precisa processar dados em disco.</p>
  <p>O Apache Spark pode ser usado sempre que os requerimentos abaixo fizerem parte de um projeto de Ciência de Dados:</p>
    <ul>
      <li> Integração de dados e ETL </li>
      <li> Análises interativas e manipulação de grandes massas de dados</li>
      <li> Computação em batch de alta performance</li>
      <li> Análises avançadas e Machine Learning</li>
      <li> Processamento de dados em tempo real</li>
    </ul>
  
  <h2>O que é PySpark?</h2>
  <p>Segundo a própria documentação do projeto, Pyspark é uma interface, escrita em Python, para o Apache Spark.</p>
  <p>Permite escrever aplicações Spark utilizando APIs Python que interagem com o core do Spark. Em resumo: é uma forma fácil de se comunicar com o Spark utilizando Python!</p>
  
  <h2>O que é RDD?</h2>
  <p>RDD é uma coleção de objetos, distribuída e imutável. Cada conjunto de dados no RDD é dividido em partições lógicas, que podem ser computados em diferentes nodes do cluster.</p>
  <p>Os RDDs são imutáveis. Ainda que aparentemente seja possível modificar um RDD com uma transformação, na verdade o resultado dessa transformação é um novo RDD, sendo que o original permanece intocável.</p>
  <p>Formalmente, um RDD é uma coleção de objetos read-only, ou seja, uma vez criado um RDD ele é apenas para leitura. RDDs podem ser criados a partir de arquivos locais, HDFS, bancos de dados relacionais ou não relacionais ou mesmo a partir de outros RDDs. RDD é um conjunto de elementos tolerante a falhas e que pode ser operado em paralelo.</p>
  <p>As RDD’s são a essência do funcionamento do Spark. Com o conceito de RDD, o Spark armazena os resultados intermediários em memória, permitindo que operações iterativas que precisam acessar os dados diversas vezes, possam recorrer a memória do computador e não ao disco. Os dados serão gravados em disco apenas ao fim do processo ou se durante o processo, não houver memória disponível. Lembre que estamos falando aqui de cluster de compuatdores, com Terabytes de memória RAM quando se combina a memória de cada node do cluster.</p>
  <p>O RDD suporta dois tipos de operações: Transformação e Ação.</p>
  <p><b><i>Transformações</i></b> são “operações preguiçosas” (lazy operations) executadas sobre os RDD’s e que criam um ou mais RDD’s.</p>
  <p>Dizemos que as transformações são operações lazy, porque elas não são executadas imediatamente, mas sim no momento em que as operações de ação são executadas.</p>
  <p><b><i>Ações</i></b> são operações executadas sobre os RDD’s que geram um resultado. Ações são operações síncronas mas podemos usar a função AsyncRDDActions() para tornar as operações assíncronas.</p>
  <p>Podemos pensar nas ações como válvulas. Os dados estão prontos para serem processados e operações de transformação já foram definidas, mas somente quando abrirmos as válvulas, ou seja, executarmos as ações, o processamento será realmente iniciado.</p>
  
</div>
