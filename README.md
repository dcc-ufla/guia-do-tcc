# Guia do TCC <!-- omit in toc --> 

Este guia tem como objetivo disponibilizar em um só lugar as respostas para as principais dúvidas que os alunos do Departamento de Ciência da Computação da Universidade Federal de Lavras (DCC/UFLA) têm ao começarem a escrever seus Trabalhos de Conclusão de Curso (TCC). Não se trata de um guia exaustivo, muito menos dogmático. Ou seja, as respostas aqui apresentadas são apenas sugestões baseadas em experiência própria na orientação de vários alunos de graduação. 

## Sumário <!-- omit in toc --> 
- [1. Quais modalidades de TCC de eu posso realizar?](#1-quais-modalidades-de-tcc-de-eu-posso-realizar)
- [2. Qual formato devo utilizar para escrever meu TCC?](#2-qual-formato-devo-utilizar-para-escrever-meu-tcc)
- [3. Quais são as orientações gerais para a escrita de um TCC?](#3-quais-são-as-orientações-gerais-para-a-escrita-de-um-tcc)
  - [3.1. Prefira frases e parágrafos curtos](#31-prefira-frases-e-parágrafos-curtos)
  - [3.2. Dê destaque para os capítulos](#32-dê-destaque-para-os-capítulos)
  - [3.3. Cuidado com o tempo verbal](#33-cuidado-com-o-tempo-verbal)
  - [3.4. Seja impessoal](#34-seja-impessoal)
  - [3.5. Comente suas figuras, tabelas e trechos de código](#35-comente-suas-figuras-tabelas-e-trechos-de-código)
  - [3.6. Evite plágio! Faça citações sempre que necessário](#36-evite-plágio-faça-citações-sempre-que-necessário)
  - [3.7. Tenha cuidado com suas fontes!](#37-tenha-cuidado-com-suas-fontes)
- [4. Como escrever um convite de participação para os membros da banca de defesa de TCC?](#4-como-escrever-um-convite-de-participação-para-os-membros-da-banca-de-defesa-de-tcc)
- [5. Como posso contribuir com o Guia do TCC?](#5-como-posso-contribuir-com-o-guia-do-tcc)
- [6. Quem são os colaboradores do Guia do TCC?](#6-quem-são-os-colaboradores-do-guia-do-tcc)

## 1. Quais modalidades de TCC de eu posso realizar?

Aqui no DCC/UFLA, as modalidades aceitas para TCC são: **monografia**, **relatório técnico**, **plano de negócios** e **relatório de estágio**. Contudo, isso pode variar de curso para curso; **consulte o coordenador de seu curso** (ou seu orientador) sobre as modalidades disponíveis.

Uma vez escolhida a modalidade do TCC, acesse o *link* correspondente abaixo para obter mais informações sobre ela:

- [Monografia](monografia.md)
- [Relatório de Estágio](relatorio-estagio.md)

## 2. Qual formato devo utilizar para escrever meu TCC?

Todo trabalho acadêmico realizado na UFLA deve (ou pelo menos deveria) estar em conformidade com o **Manual de Normalização de Trabalhos Acadêmicos da UFLA**, o qual pode ser obtido [aqui](http://repositorio.ufla.br/jspui/handle/1/41282). Para saber mais sobre este manual, assista a esta [vídeo-aula](https://www.youtube.com/watch?v=KqeUe-H5yGo).

Quanto ao *template* utilizado para a escrita do TCC, muitos alunos preferem utilizar *Latex*. Contudo, nada impede que você utilize editores de texto tradicionais, tais como MS Word, Google Docs, entre outros. 

Caso pretenda utilizar *Latex*, há um modelo disponível [aqui](http://repositorio.ufla.br/jspui/bitstream/1/41282/5/Template%20para%20Monografias%20da%20UFLA%20%28Uflamon%29.zip). Uma dica importante é: **instale um pacote de verificação ortográfica para o idioma Português**. Isso facilitará muito sua vida (e a de seu orientador) durante o processo de revisão do TCC. Outra dica é utilizar ferramentas *online*, tais como [Overleaf](https://www.overleaf.com/project), para facilitar a escrita bem como compartilhamento do TCC com seus orientadores.

Se for utilizar Google Docs, há um modelo disponível [aqui](https://docs.google.com/document/d/1DkKLDBG4UxdgKHiKxWdOuFusPQNOWOaB6TqeS0C6F80/edit?usp=sharing). 

## 3. Quais são as orientações gerais para a escrita de um TCC?

Abaixo estão algumas orientações gerais, as quais se aplicam a qualquer modalidade de TCC descrita na [Questão 1](#1-quais-modalidades-de-tcc-de-eu-posso-realizar) deste Guia.

### 3.1. Prefira frases e parágrafos curtos

Escreva frases e parágrafos curtos com ideias completas, isto é, contendo *início*, *meio* e *fim*.

### 3.2. Dê destaque para os capítulos

Cada início de capítulo deve ficar em uma página nova. Ou seja, se uma seção terminou no meio de uma página e você pretende iniciar um novo capítulo, então deixe o restante da página em branco e começe uma página nova.

### 3.3. Cuidado com o tempo verbal

Em textos acadêmicos, normalmente nós escrevemos no tempo presente ou passado, mas raramente no futuro, pois se trata de um trabalho já finalizado (uma exceção à regra é a seção *Trabalhos Futuros*). 

Exemplo:

    [EVITE!] A organização deste relatório será feita em capítulos...
    
    [ASSIM FICA MELHOR] Este relatório está organizado em capítulos... 

### 3.4. Seja impessoal

Evite usar pronomes e verbos em primeira pessoa (singular ou plural). 

Exemplo:

    [EVITE!] Nós fizemos a avaliação do aplicativo com 10 usuários... 
    
    [ASSIM FICA MELHOR] A avaliação do aplicativo foi realizada com 10 usuários...

### 3.5. Comente suas figuras, tabelas e trechos de código

Mais importante do que as figuras, tabelas e trechos de código que você apresenta em seu TCC são as explicações que você oferece a respeito deles. Na maioria dos casos, esses elementos não são autoexplicativos, por isso você deve discutir sobre eles no texto. Eis um exemplo:

> O código abaixo apresenta um exemplo de programa escrito na linguagem Go. Na linha 1 é definido o nome do pacote ao qual esse código está 
> embutido, neste caso, o pacote *main*. A linha 3 apresenta a importação de um pacote nativo da linguagem Go, a saber _fmt_, o qual possui 
> funções de I/O análogas às funções *printf* e *scanf* da linguagem C. Entre as linhas 5 e 7 está compreendido o código da função _main_, que
> é o ponto de partida de um programa Go. Por último, a linha 6 usa a função *Println* do pacote *fmt* para imprimir a mensagem *Hello from
> "Guia do TCC"* na tela do usuário.


```go
1. package main
2. 
3. import "fmt"
4. 
5. func main() {
6.     fmt.Println(`Hello from "Guia do TCC"`)
7. }
```

### 3.6. Evite plágio! Faça citações sempre que necessário

Algo bem comum em um trabalho acadêmico (seja Relatório de Estágio, Monografia, Relatório Técnico, etc) é você precisar citar algum documento produzido por outra pessoa, tal como um estudo científico, uma pesquisa de opinião, um *website* de uma ferramenta computacional, entre outros. 

Para fazer isso, siga as instruções do **Manual de Normalização de Trabalhos Acadêmicos da UFLA**, o qual pode ser obtido [aqui](http://repositorio.ufla.br/jspui/handle/1/41282). No vídeo a seguir, eu explico um pouco mais sobre isso (a partir do minuto 8): [fazendo citações de acordo com Manual de Normalização de Trabalhos Acadêmicos da UFLA](https://www.youtube.com/watch?v=KqeUe-H5yGo&t=480s).

### 3.7. Tenha cuidado com suas fontes!

Algumas perguntas que ocorrem como consequência direta da recomendação anterior são: *Que tipo de documento eu posso citar em um TCC? Como posso escolher um estudo que seja confiável para emabasar meu TCC?*

Essas são boas perguntas e indo bem direto ao ponto, do mais confiável para o menos confiável, eu sugiro: 

- **Artigos Científicos**: porque, em geral, são revisados por 3 (três) pesquisadores antes de serem publicado.
- **Livros**: passam por revisão técnica e pelo crivo do editor também. É importante destacar que o conteúdo advindo de livros pode estar "desatualizado", por isso eles não são tão recomendados para embasar problemas de pesquisa. Podem ser úteis para explicar conceitos já consolidados.  
- **Artigos disponibilizados por órgãos governamentais**: passam por revisão interna, mas são propensos a influência por questões políticas mais do que os outros tipos de estudo.
- **TCC, monografia, etc**: apesar de passarem pela revisão de uma banca, muitas vezes, o processo de revisão do texto final fica apenas a cargo do orientador e do orientando.
- **Artigos em blogs**: não costumam passar por revisão, a não ser a do próprio autor. Porém, isso é relativo. Eu considero um *post* do Martin Fowler mais confiável do que alguns artigos científicos que vejo por aí :) 

Outro ponto que eu gostaria de destacar é que a **Wikipédia** sofre muito preconceito, mas é uma boa fonte de consulta. Em geral, para você publicar alguma coisa lá, outros usuários têm que aprovar e você precisará fornecer referências (evidências) para as afirmações que fizer. 

Eu recomendo utilizar a Wikipédia da seguinte forma: (1) leia o conteúdo da página; (2) vá até a(s) referência(s) indicada(s) por ela e confira se está(ão) OK; e (3) caso sim, cite a(s) referência(s) indicada(s). Dessa forma, a **Wikipédia** serve mais como um guia para lhe direcionar às fontes importantes.

Para tornar esse tópico um pouco mais concreto, eis alguns exemplos:

> *Quero colocar uma informação no meu TCC sobre porcentagem de estradas pavimentadas no Brasil*: as melhores fontes, neste caso, são os órgãos do governo, como a ANTT (Agência Nacional de Transporte Terreste), por exemplo. Tais órgãos costumam emitir relatórios anuais com esse tipo de informação.

> *Quero falar sobre Kaban no meu TCC*: procure em livros sobre métodos ágeis. Caso não encontre nada, recorra à Wikipédia, conforme expliquei anteriormente. Caso não encontre nada ainda (pouco provável), procure em postagens de *blogs* cujo autor seja alguém reconhecido pela comunidade (Martin Fowler, Robert Martin, Alistair Cockburn, entre outros).

## 4. Como escrever um convite de participação para os membros da banca de defesa de TCC?

A banca de defesa de um TCC é constituída por indivíduos irão avaliar seu trabalho e deliberar sobre sua aprovação ou não. No caso de trabalhos de graduação, a banca é composta por seu orientador (que assume o papel de presidente da banca) e mais duas pessoas.

Geralmente, quem escolhe a banca é o próprio aluno, juntamente com seu orientador, e um dos primeiros passos após a escolha dos nomes é enviar um convite formal para participação da defesa. Esse é um passo importante, pois é o primeiro contato entre o aluno e, possivelmente, os membros da sua banca de defesa.

Ao redigir um convite, atente-se para que algumas informações estejam presentes, tais como **seu nome**, o **nome do seu orientador** e o **título do seu trabalho**. Se preferir, o convite de participação pode também indicar uma lista de prováveis horários para a defesa. Segue abaixo um *template* para convite a ser enviado aos membros da banca:

> Prezado(a) prof(a). ________ (ou mais informalmente: "Olá, prof(a). ________")
> 
> Meu nome é ________ e sou aluno(a) do curso Bacharelado em ________. Estou para defender meu Trabalho de 
> Conclusão de Curso (TCC), intitulado ________, que foi desenvolvido sob a orientação do(a) prof(a). ________.
> 
> Gostaria de convidá-lo(a) para fazer parte da banca de defesa de meu TCC. Caso aceite o convite, gostaria
> de saber quais são suas disponibilidades de horário para a semana de __ / __ a __ / __. 
> 
> Atenciosamente, ________

Com relação às disponibilidades de horário dos membros da banca, algumas pessoas costumam utilizar ferramentas online, tais como [Doodle](https://doodle.com/pt_BR/marcar-reuniao), para gerenciá-las.


## 5. Como posso contribuir com o Guia do TCC?

Encontrou algum erro gramatical no Guia? Está com alguma dúvida que ainda não foi respondida? Há alguma resposta incompleta ou que não está muito clara para você? Caso sim, então você está convidado(a) a contribuir com o Guia do TCC. 

Para isso, inicialmente, você deve:

- criar uma uma nova *issue* no repositório oficial do Guia do TCC, caso ainda não exista alguma que lhe atenda. Por exemplo, você pode criar uma *issue* para uma pergunta que ainda não foi respondida pelo Guia ou para pedir esclarecimentos sobre uma pergunta já existente. 

Uma vez feito isso, você deve aguardar até que alguém escolha sua *issue* para resolver ou, então, você mesmo(a) pode propor a resolução desta *issue*. 

Para isso, você deve seguir os seguintes passos:

- [ ] fazer um *fork* do repositório oficial do Guia do TCC para sua conta no Github;
- [ ] clonar o repositório de sua conta em sua máquina de trabalho local;
- [ ] realizar as modificações necessárias para solucionar a *issue* em questão;
- [ ] fazer o *push* das mudanças realizadas para uma nova *branch* do seu respositório no Github;
- [ ] criar um PR (*Pull Request*) para o repositório oficial do Guia do TCC (isso pode ser feito pela própria interface do Github).

A partir daí, seu PR será revisado pelos administradores do repositório e algumas interações poderão ser ocorrer, utilizando a própria interface do Github. Caso tudo ocorra bem, será feito um *merge* de sua contribuição para a *branch main* do Guia do TCC e seu nome passará a constar na seção de colaboradores do Guia.


## 6. Quem são os colaboradores do Guia do TCC?

*Todo*