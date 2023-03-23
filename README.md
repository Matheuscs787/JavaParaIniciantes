# JavaParaIniciantes

Esse repositório tem como objetivo servir de espaço para anotações enquanto leio o livro Java para iniciantes 6° edição.
Além de ler o livro e praticar o que estou aprendendo, vou escrever materias sobre os tópicos que julgar importantes, com o foco inicial de ajudar os iniciantes.

Esse livro é baseado no Java SE 8 (JDK8) e seu autor é **Herbert Schildt**

![This is an image](https://imgv2-2-f.scribdassets.com/img/document/439748451/original/d8e41a4cff/1677012396?v=1)

O primeiro capítulo do livro trata sobre os **fundamentos da linguagem**, porém o primeiro material que escolhi para escrever e postar será uma breve introdução sobre a linguagem.

# Introdução
## Resumo das versões até o Java SE 8
&nbsp;&nbsp;&nbsp;&nbsp;O impacto gerado pelo lançamento do Java 1.0 feito pela Sun Microsystems, Inc em 1995 foi tão grande que não é um absurdo falar que isso causou uma revolução na programação. É interessante saber que foi definido um novo padrão no design de linguagens de computador após o lançamento da primeira versão do Java.
<br>&nbsp;&nbsp;&nbsp;&nbsp;Após o seu lançamento, os anos foram passando e o Java continuou crescendo e evoluindo, recebia atualizações frequentemente, algumas pequenas e outras mais significativas.
<br>&nbsp;&nbsp;&nbsp;&nbsp;A primeira grande atualização de Java foi a versão 1.1, sendo que os recursos adicionados foram mais significativos do que se esperaria de uma versão ".1". Um exemplo, é que foram adicionados elementos de biblioteca, a maneira que os eventos são tratados foi redefinida e vários recursos da versão 1.0 foram reconfigurados.
<br>&nbsp;&nbsp;&nbsp;&nbsp;A versão 1.2 do Java foi tão significativa que ela passou ser chamada de Java 2, nessa versão a Sun criou um novo pacote para o produto Java, chamando de J2SE (Java 2 Platform Standar Edition), e os números de versão começaram a ser aplicados a esse produto.
<br>&nbsp;&nbsp;&nbsp;&nbsp;A próxima atualização do Java foi J2SE 1.3, essa foi a primeira grande atualização de Java 2 original. Com isso, aumentou a funcionalidade existente e "integrou melhor" o ambiente de desenvolvimento.
<br>&nbsp;&nbsp;&nbsp;&nbsp;Com a versão J2SE 1.4 melhorou ainda mais a linguagem, com novos recursos importantes, como exceções encadeadas, I/O baseada em canais e a palavra chave **assert**.
<br>&nbsp;&nbsp;&nbsp;&nbsp;Com o J2SE 5 foi uma nova revolução na linguagem, as atualizações anteriores ofereceram melhorias que apesar de importantes, foram apenas incrementais, já o J2SE 5 basicamente expandiu o escopo, o poder e o alcance da linguagem. Como exemplo dos recursos lançados nessa versão, segue uma pequena lista:
> * Tipos Genéricos
> * AutoBoxing/unboxing
> * Enumerações
> * O laço **for** foi melhorado para o estilo "for-each"
> * Argumentos em tamanho variável (varargs)
> * Importação estática
> * Anotações

&nbsp;&nbsp;&nbsp;&nbsp;Isso não é uma lista de pequenos ajustes, cada item representa um grande impacto positivo à linguagem Java. Alguns introduziram novos elementos de sintaxe, outros alteraram a semântica da linguagem e as anotações adicionaram uma dimensão inteiramente nova à programação. A importância foi tão grande que o número da versão que naturalmente seria 1.5, não foi chamada assim pois não parecia expressar a magnitude da mudança. A Sun resolveu chamar a versão de Java 5, para deixar claro que era um evento maior que estava ocorrendo, sendo assim, ela foi nomeada de J2SE 5 e o kit de desenvolvedor foi chamado de JDK 5.
<br>&nbsp;&nbsp;&nbsp;&nbsp;A próxima versão do Java foi chamada de Java SE 6, novamente a Sun resolveu mudar o nome da plataforma. Dentre as alterações, o "2" foi removido e a plataforma passou a ter o nome Java SE (Standard Edition). Dentre as alterações, tiveram aperfeiçoamento das bibliotecas de APIs, novos pacotes, melhores no tempo de execução. O Java SE 6 serviu para solidificar ainda mais os avanços feitos pelo J2SE 5.
<br>&nbsp;&nbsp;&nbsp;&nbsp;A próxima versão, que foi chamada de Java SE 7 e o JDK 7 foi a primeira grande versão pós aquisição da Sun Microsystems pela Oracle. Nessa versão foram incluidos muitos recursos novos, inclusive acréscimos significativos à linguagem e às bibliotecas de API.
Parte dos recursos mais importantes, foram desenvolvidos pelo Project Coin, que tinha como objetivo de identificar várias pequenas alterações feitas na linguagem que seriam incorporadas ao JDK 7, como exemplo:
> * Objeto **String** pode controlar uma instrução **switch**.
> * Literais inteiros binários.
> * Sublinhados em literais numéricos.
> * Instrução **try** expandida, chamada try-with-resources, que dá suporte ao gerenciamento automático de recursos.
> * Inferência de tipos (via operador losango <>) na construção de uma instância genérica.
> * Tratamento de exceções melhorado, em que duas ou mais exceções podem ser capturadas pela mesma instrução catch (multicatch), e melhor verificação de tipos para exceções que são relançadas.

&nbsp;&nbsp;&nbsp;&nbsp;Apesar de ter sido consideradas pequenas alterações na linguagem, seus benefícios foram grandes, principalmente o try-with-resources afeta a maneira como uma grande quantidade de códigos é escrita.