---
layout: post
author: Vitor "Pliavi" Silvério
title:  "Google e suas belezas... Material Design!"
date:   2016-10-30 22:50:25 -0300
categories: educake
resume: > #
  E esses lindos usuários do GitHub que criaram JComponents com esse estilo!
---
Entre o mês passado e hoje tivemos um crescimento do projeto a passos curtos, mas mesmo que parecendo pouca coisa, foram grandes as mudanças:
### Projeto Reestruturado
  Agora MVC está bem implementado e correndo como nos conformes. 👍
![structure]  
### Oracle 11g Funcionando!
  O que antes era só uma tentativa agora é realidade, banco Oracle rodando sem problema  junto com a utilização do Hibernate, tabelas estão sendo geradas, atualizadas e triggers engatilhando nas horas certas.
### Material Design com Swing-Material
  Cá entre nós, os componentes do Swing do Java não são dos mais bonitos e os Look&Feels existentes não melhoram tanto sua aparência. Então, na busca por uma forma de embelezar nossos formulários, encontramos no GitHub um repositório chamado [leMaik/Swing-Material][Swing-Material], que recriava os componentes do Material Design da Google para JComponents, e já colocamos para utilização no projeto:  
![form]  
  Como esses componentes não tem beans para utilização no Netbeans todas as janelas terão de ser feitas via código, então foi criada uma classe geradora que simplifica muito a criação de qualquer janela de nosso sistema:  
![generator]  
  Além disso, durante as atualizações do projeto, houve a a oportunidade dada pelo próprio [Maik Marschner][leMaik] (Criador do Repositório) de ampliar o [Swing-Material] e já estamos com um pullrequest aceito para adição do componente MaterialFormattedTextField.  
![pullrequest]  
Por hora é só! E sigamos printando!

[LeMaik]: https://github.com/leMaik
[Swing-Material]: https://github.com/leMaik/swing-material

[structure]:   /img/2016-10-14/structure.jpeg
{: width="100%"}
[form]:        /img/2016-10-14/form.jpeg
{: width="100%"}
[generator]:   /img/2016-10-14/generator.jpeg
{: width="100%"}
[pullrequest]: /img/2016-10-14/pullrequest.jpeg
{: width="100%"}
