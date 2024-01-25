# Do Gwyddion ao Python

<p align = "justify"> Este diretório faz parte de um projeto acerca de mecanismos de processamento de imagem realizado pelo <i>Gwdyddion</i> a partir de operações por matrizes em Python. O <i>Gwyddion</i> é um <i>software</i> que apresenta diversas ferramentas padrão para tratar imagens de microscopia de varredura por sonda (SPM, do inglês <i>Scanning Probe Microscopy</i>). A partir disso, explorou-se três funções altamente relevantes do <i>Gwyddion</i>: nivelamento, filtro de mediana e aplicação de cor na imagem. Assim, neste trabalho, objetiva-se compreender os mecanismos de funcionamento dessas funções em operações de matrizes, replicando-os em <i>Python</i>. Este projeto foi realizado por quatro alunos da Ilum da turma de 2023 no ano de 2023. 
  
## <i>Gwyddion</i>

<p align = "justify"> O <i>Gwyddion</i> é um <i>software</i> de código aberto gratuito de análise e visualização de dados de SPM, apresentando diversas ferramentas padrão para o processamento de dados, que consistem em operações com matrizes, dada a representação computacional das imagens. Projetado para oferecer uma ampla gama de ferramentas para a visualização e manipulação de dados tridimensionais, o Gwyddion permite aos pesquisadores explorar informações detalhadas sobre superfícies nanométricas de forma eficiente. Ele suporta a importação de dados de várias fontes, fornecendo recursos avançados para a correção de artefatos, filtragem de ruído e visualização precisa de topografias de superfícies. Dessarte, o Gwyddion tornou-se uma ferramenta valiosa na comunidade científica para estudos envolvendo micro e nanoestruturas a partir de análise e visualização de dados de SPM.

Para mais informações, pode-se consultar o [guia do usuário](http://gwyddion.net/download/user-guide/gwyddion-user-guide-en.pdf) oficial do <i>software</i>, além do [site oficial](http://gwyddion.net/).

## Microscopia de Varredura por Sonda (SPM)

<p align = "justify"> A SPM é uma técnica avançada de imagem que permite a observação e a manipulação de materiais em escalas nanométricas. Dois tipos importantes de SPM são o AFM (Atomic Force Microscopy) e o STM (Scanning Tunneling Microscopy).

<p align = "justify"> O AFM utiliza uma sonda com uma ponta extremamente afiada na extremidade, que é posicionada muito próxima à superfície da amostra. À medida que a ponta percorre a superfície, as forças de interação entre a ponta e a amostra são medidas. Essas forças incluem a força de repulsão atômica quando a ponta se aproxima da amostra e a força de atração devido às interações de van der Waals. Essas informações são então usadas para criar uma imagem tridimensional da topografia da superfície com resolução atômica.

<p align = "justify"> O STM, por sua vez, explora as propriedades de tunelamento quântico entre a ponta e a amostra. Quando a ponta está muito próxima da amostra, os elétrons podem tunelar através da fina barreira de potencial, criando uma corrente. A variação dessa corrente é medida à proporçao que a ponta é movida pela superfície, criando uma imagem da topografia da amostra. O STM é especialmente útil para estudar superfícies condutoras, permitindo uma resolução atômica extraordinária.

<p align = "justify"> Ambas as técnicas, AFM e STM, desempenham um papel crucial em pesquisas nas áreas de física, química, biologia e ciência dos materiais, oferecendo insights valiosos sobre as características e propriedades de materiais em escalas nanométricas.
  
Para mais informações, pode-se consultar o artigo [Microscopia de sondas: uma caixa de ferramentas da nanotecnologia](http://cienciaecultura.bvs.br/scielo.php?pid=S0009-67252013000300013&script=sci_arttext), akém também da página da [Wikipedia](https://en.wikipedia.org/wiki/Scanning_probe_microscopy)

## Organização do Diretório

<p align = "justify"> Neste diretório, há uma pasta nomeada como <i>Entendendo os mecanismos</i>, o qual apresenta um arquivo em <i>ipynb</i> (<i>Jupyter Notebook</i>) com o código documentado que replica tais funções citadas, uma imagem utilizada como demonstração e uma outra para mostrar que o código pode tratar qualquer imagem. Além disso, nesta pasta, encontra-se um documento em PDF que descreve minuciosamente o projeto. </p> 

## Autores

<p align = "justify"> Este projeto foi realizado por quatro alunos da Ilum - Escola de Ciência do Centro Nacional de Pesquisa em Energia e Materiais (CNPEM): José David Alves Sales, Diogo Pereira de Lima Carvalho, Natalia Alcantara de Souza, Kayllany Lara da Silva Oliveira. Esse projeto foi criado sob orientação do professor da Ilum - Escola de Ciência Vinicius Francisco Wasques, havido sido realizado como um projeto da disciplina de "Algébra Linear Computacional".

## License

Este projeto está licenciado sob GNU General Public License v3.0 - consulte o arquivo [LICENSE](https://github.com/joseDavid23038/do_gwyddion_ao_python/blob/main/LICENSE) para obter detalhes
