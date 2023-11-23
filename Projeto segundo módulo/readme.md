<h1> Sistema de busca em dados do Twitter </h1>

O objetivo como desenvolvedor, é Sistema de busca de tweets por determinado padrão (por data, termo no tweet, ou por assunto). Esse sistema deverá conter os seguintes requisitos:

<h2>Menu Principal</h2> 

Ao iniciar o programa, o seguinte menu deve ser apresentado ao usuário:

```
Boas vindas ao nosso sistema:

1 - Buscar tweets por data
2 - Buscar tweets por termo
3 - Buscar tweets por assunto
4 - Salvar resultado da busca
5 - Sair
```

<div align="justify";>
<p>O sistema conta com uma base de dados coletada diretamente do Twitter.</p>

<p>Esta base dados está armazenada em um arquivo com extensão CSV que está aqui no repositório, e o sistema deverá ser capaz de manipulá-la em tempo de execução de suas funcionalidades.</p>

<p>A base de dados é composta por cerca de 4 mil tweets separados por 4 assuntos distintos: <b>covid-19</b>; <b>ciência de dados</b>; <b>copa do mundo</b> e; <b>eleições</b>.</p>

<p>Além disso, é possível observar na base, campos contendo a data, a URL, o conteúdo, os nomes de usuários, e o assunto de cada tweet coletado.</p>

<p>Você pode baixar a base de dados <a href="https://drive.google.com/file/d/103GvlCjiVVBl03_sjPvUCCrR7Zb3uXwN/view?usp=sharing">AQUI</a></p>

<h3>Salvar resultado da busca</h3> 

<div align="justify">
<p>Permita que o usuário salve em arquivo cada busca que ele fizer, independente da forma: data, termo ou assunto.</p>

<p>O arquivo é salvo em formato JSON (extensão .json) em que contm a <b>data</b>, <b>conteúdo</b> e <b>assunto</b> de cada tweet retornado na busca feita pelo usuário</p>
</div>
