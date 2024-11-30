### Com a biblioteca do langchain é possível carregar uma nova fonte de dados para que possa resumir o conteúdo, traduzir



![RAG](https://miro.medium.com/v2/resize:fit:1400/0*tJ3Oi3pJRr-2wL3O.jpeg)


***


A primeira etapa deste projeto é conseguir carregar os documento. O passo-a-passo para este processo pode ser visto
na pasta [Load docs](./Load-docs)
Existem várias formas de fazer download dos documentos, podendo ele ser em PDF, vídeos do Youtube, URL's, arquivos do
Notion dentre outros formatos. Desta forma é possível trabalhar com vários formatos de arquivos para conseguir 
melhorar a atualização do seu algoritmo.
Após ter feito o load do arquivo é necessário quebrar os arquivos em chunks, [Split docs](./Document-splitting).
Desta forma conseguimos entender a melhor maneira que o arquivo pode ser quebrado para conseguir fazer buscas
mais precisas. Porém é importante ver os retorno de cada uma dessas técnicas para o objetivo proposto.