# Projeto Arte com Pixels

Boas-vindas ao repositório do projeto Arte com Pixels.

Para realizar o projeto, atente-se a cada passo descrito.

Aqui você vai encontrar os detalhes de como estruturar o desenvolvimento do seu projeto a partir desse repositório, utilizando uma branch específica e um _Pull Request_ para colocar seus códigos.

## 🧑‍💻 O que deverá ser desenvolvido

Neste projeto, você vai implementar um editor de arte com pixels em que a pessoa usuária poderá escolher uma cor em uma paleta de cores e poderá pintar o que quiser em um quadro branco 🎨 🧑‍🎨

💡 Veja o exemplo a seguir de como o projeto pode se parecer depois de pronto.

![exemplo de arte com pixels](./art-with-pixels.gif)

Você pode ~~e deve~~ ir além para deixar o projeto com a sua cara e impressionar todas as pessoas, mas não deixe de cumprir os requisitos!

</details>

## Como Desenvolver

<details>
<summary><strong>🤷🏽‍♀️ Como corrigir automaticamente?</strong></summary>

Para corrigir o seu desenvolvimento através do avaliador automático, você deverá criar um _Pull Request_ neste repositório.

</details>

<details>
  <summary><strong>‼️ Antes de começar a desenvolver</strong></summary><br />

1. Clone o repositório e entre nele

2. Instale as dependências

* `npm install`

3. Crie uma branch a partir da branch `main`

* Verifique que você está na branch `main`
  * Exemplo: `git branch`
* Se não estiver, mude para a branch `main`
  * Exemplo: `git checkout main`
* Agora crie uma branch à qual você vai submeter os `commits` de seu projeto
  * Você deve criar uma branch no seguinte formato: `nome-sobrenome-nome-do-projeto`
  * Exemplo: `git checkout -b mariazinha-project-pixels-art`

4. Adicione as mudanças ao _stage_ do Git e faça um `commit`

* Verifique que as mudanças ainda não estão no _stage_
  * Exemplo: `git status` (devem aparecer listados os novos arquivos em vermelho)
* Adicione o novo arquivo ao _stage_ do Git
  * Exemplo:
    * `git add .` (adicionando todas as mudanças - _que estavam em vermelho_ - ao stage do Git)
    * `git status` (devem aparecer listados os arquivos em verde)
* Faça o `commit` inicial
  * Exemplo:
    * `git commit -m 'iniciando o projeto pixels art'` (fazendo o primeiro commit)
    * `git status` (deve aparecer uma mensagem tipo _nothing to commit_ )

5. Adicione a sua branch com o novo `commit` ao repositório remoto

* Usando o exemplo anterior: `git push -u origin mariazinha-project-pixels-art`

6. Crie um novo `Pull Request` _(PR)_

* Vá até a página de _Pull Requests_ do [repositório no GitHub](https://github.com/tryber/sd-0x-project-pixels-art/pulls)
* Clique no botão verde _"New pull request"_
* Clique na caixa de seleção _"Compare"_ e escolha a sua branch **com atenção**
* Coloque um título para a sua Pull Request
  * Exemplo: "Cria tela de busca"
* Clique no botão verde "Create pull request"
* Adicione uma descrição para o _Pull Request_, e clique no botão verde _"Create pull request"_
* **Não se preocupe em preencher mais nada por enquanto!**
* Volte até a [página de _Pull Requests_ do repositório](https://github.com/tryber/sd-0x-project-pixels-art/pulls) e confira que o seu _Pull Request_ está criado

</details>

<details>
  <summary><strong>⌨️ Durante o desenvolvimento</strong></summary>

* Faça `commits` das alterações que você fizer no código regularmente

* Lembre-se de sempre após um (ou alguns) `commits` atualizar o repositório remoto

* Os comandos que você utilizará com mais frequência são:
  1. `git status` _(para verificar o que está em vermelho - fora do stage - e o que está em verde - no stage)_;
  2. `git add` _(para adicionar arquivos ao stage do Git)_;
  3. `git commit` _(para criar um commit com os arquivos que estão no stage do Git)_;
  4. `git push` _(para enviar o commit para o repositório remoto após o passo anterior)_;
  5. `git push -u origin nome-da-branch` _(para enviar o commit para o repositório remoto na primeira vez que fizer o `push` de uma nova branch)_.

</details>

## Orientações

<details>
  <summary><strong>🏗 Estrutura do projeto</strong></summary>

* Implemente uma paleta de cores usando `javascript`, `css` e `html`;

* Crie os arquivos `index.html`, `style.css` e `script.js`, que conterão seu código HTML, CSS e JavaScript, respectivamente;

:warning: **É importante que seus arquivos tenham exatamente estes nomes!** :warning:

* Você pode adicionar outros arquivos se julgar necessário. Caso tenha alguma dúvida, poste no _Slack_;

 ⚠️ **Recomenda-se que você desenvolva seu projeto com a resolução de tela  de `1366 x 768`, a mesma que será utilizada pelo avaliador. Para facilitar a configuração da resolução, use este [plugin do `Chrome`](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh?hl=en).** ⚠️

* Caso seu projeto contenha imagens, ⚠️ **Atenção**:
  * Não utilize arquivos maiores que _500Kb_;
  * Utilize uma ferramenta como [esta](https://picresize.com/pt) para redimensionar as imagens.

* Você tem liberdade para implementar novos comportamentos ao seu projeto, seja na forma de aperfeiçoamentos em requisitos propostos ou novas funcionalidades, mas atente-se para **não conflitar com os requisitos propostos**.

</details>

<details>
  <summary><strong>⚛️ Dicas</strong></summary>

* Não recomenda-se a utilização de `table`, pois o sentido semântico de construir uma tabela no HTML não tem relação  com a construção de uma grade de pixels para serem coloridos. Nesse caso, fazer uso de `table` representa uma má prática;

**Atenção ⚠️:** É importante que você inicie o projeto utilizando seus conhecimentos em **manipulação de DOM com JavaScript** pois além de ser o **objetivo do projeto**, vai deixar seu código mais limpo, fácil de ajustar e evitar repetições;

* Que tal usar um [_loop_](https://flaviocopes.com/how-to-add-event-listener-multiple-elements-javascript/) para adicionar o mesmo evento em vários elementos? Ou então a técnica de [_event bubbling_](https://gomakethings.com/attaching-multiple-elements-to-a-single-event-listener-in-vanilla-js/) combinada com `classList`?

* Se precisar consultar os valores do _CSS_ de um elemento a partir do _JavaScript_, [dê uma olhada aqui](https://www.w3schools.com/jsref/jsref_getcomputedstyle.asp);

* Para alterar alguma propriedade do _CSS_ de um elemento por meio do _JavaScript_, dê uma olhada no [atributo `style`](https://www.w3schools.com/jsref/prop_style_backgroundcolor.asp) do elemento.
* Caso a avaliação falhe com alguma mensagem de erro do tipo `[409:0326/130838.878602:FATAL:memory.cc(22)] Out of memory. size=4194304` é provável que as imagens que está utilizando são muito grandes. Tente redimensioná-las para um tamanho menor.

* Ao trabalhar com desenvolvimento, você vai se deparar com vários tipos de desafios, por isso é muito importante que os problemas sejam quebrados em partes menores, para que sejam resolvidos aos poucos. Isso vai te ajudar a encontrar uma solução de maneira mais fácil. Dessa forma, um bom jeito de começar a desenvolver um projeto é lembrar que as funções são compostas por pequenos blocos de lógica que têm um objetivo específico.

* Antes de começar a desenvolver, entenda o que está sendo requisitado e planeje como será feito.
</details>

<details>
  <summary><strong>🎛 Linter</strong></summary><br />

Para garantir a qualidade do código, vamos utilizar neste projeto os linters `ESLint` e `StyleLint`.
Desta forma, o código estará alinhado com as boas práticas de desenvolvimento, sendo mais legível e de fácil manutenção!
  Para rodar o `ESLint` e o `StyleLint` localmente no projeto, execute os comandos abaixo:

  1. Para avaliar se os arquivos com a extensão `CSS` estão com o padrão correto

```bash
npm run lint:styles
```

  2. Para avaliar se os arquivos com a extensão `JS` estão com o padrão correto

```bash
npm run lint
```

⚠️ **Atenção** O `ESLint` e o `StyleLint` não serão avaliados neste projeto. Você pode rodar os testes localmente e fazer as correções se desejar. ⚠️

</details>

<details>
  <summary><strong>🛠 Testes e Cypress</strong></summary><br />

O Cypress é uma ferramenta de teste de front-end desenvolvida para a web. Antes de utilizá-lo, certifique-se de ter executado o comando `npm install` dentro do projeto.

Você pode rodar o Cypress localmente para verificar se seus requisitos estão passando, para isso execute um dos seguintes comandos:

1. Para executar os testes apenas no terminal:

```bash
npm test
```

2. Para executar os testes e vê-los rodando em uma janela de navegador:

```bash
npm run cypress:open
```

Após executar o comando acima, uma janela de navegador será aberta e, então, você poderá escolher o arquivo de teste a ser executado ou escolher `Run all specs` para executar todos os arquivos

Assista [este vídeo](https://vimeo.com/539240375/a116a166b9) para ver como rodar o Cypress localmente 😉🎙

* Siga este passo a passo para verificar os **detalhes da execução do avaliador**:

  * Na página do seu _Pull Request_, acima do "botão de merge", procure por _**"Evaluator job"**_ e clique no link _**"Details"**_;

  * Na página que se abrirá, clique na linha _**"Cypress evaluator step"**_ ;

  * Analise os resultados a partir da mensagem _**"(Run Starting)"**_;

  * Caso tenha dúvidas, consulte [este vídeo](https://vimeo.com/420861252).

⚠️ **O avaliador automático não necessariamente avalia seu projeto na ordem em que os requisitos aparecem no readme. Isso acontece para deixar o processo de avaliação mais rápido. Então, não se assuste se isso acontecer, ok?**

* Contudo, tenha em mente que **nada além do que for pedido nos requisitos será avaliado**. _Esta é uma oportunidade de você exercitar sua criatividade e experimentar com os conhecimentos adquiridos._

</details>

<details>
  <summary><strong>🔗 Links auxiliares para o desenvolvimento
do projeto</strong></summary>

* Como pessoa desenvolvedora você deve fazer pesquisas para auxiliar o seu entendimento do assunto. Assim, para solucionar os requisitos do projeto é inevitável e estimulado que pesquisas sejam feitas nas mais variadas fontes (plataforma da Trybe, google, youtube, etc) sempre tomando cuidado para utilizar fontes **confiáveis** nas pesquisas da Internet, como por exemplo:

  * [Javascript.com](http://javascript.com/)

  * [W3Schools](https://www.w3schools.com/js/default.asp)

  * [MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

  * [StackOverflow](https://pt.stackoverflow.com/questions/tagged/javascript)

</details>

# Requisitos

:warning: **Leia todos os requisitos atentamente e siga à risca o que for pedido. Em particular,**atente-se para os nomes de _ids_  e _classes_ que alguns elementos de seu projeto devem possuir**. Não troque `ids` por `classes` ou vice-versa** :warning:

**De olho na dica 👀:** Existem várias formas de realizar os requisitos desse projeto, lembre-se que você pode usar o que já aprendeu até agora sobre HTML e principalmente **manipulação do DOM com JavaScript**.

## 1 - Adicione à página o título "Paleta de Cores" e uma paleta contendo quatro cores distintas

<details>
  <summary>A página deve conter o título "Paleta de Cores" e uma paleta com quatro opções de cores</summary><br />

* O título deverá ficar dentro de uma tag `h1` com o `id` denominado `title`;
* O texto do título deve ser **exatamente** "Paleta de Cores".
* A paleta de cores deve ser um elemento com `id` denominado `color-palette`, e cada cor individual contida na paleta de cores deve possuir a `classe` chamada `color`;
* A cor de fundo de cada elemento da paleta deverá ser a cor que o elemento representa. **A única cor não permitida na paleta é a cor branca**;
* Cada elemento da paleta de cores deverá ter uma borda preta, sólida e com 1 pixel de largura;
* A paleta de cores deverá listar todas as cores disponíveis para utilização lado a lado, e deverá ser posicionada abaixo do título `Paleta de Cores`;
* A paleta de cores não deve conter cores repetidas.

**De olho na dica 👀:** utilize manipulação do DOM para criar os elementos, adicionar identificadores, classes e estilos.

**O que será testado:**

* O título deve possuir a tag `h1`;
* O título deve possuir o `id` `title`;
* O título deve ser `Paleta de Cores`.
* A paleta de cores deve possuir o `id` `color-palette`;
* As cores individuais da paleta devem possuir a `classe` `color`;
* A cor de fundo de cada elemento da paleta é a cor que o elemento representa :warning: **A única cor não permitida na paleta é a cor branca** :warning:;
* Os elementos da paleta de cores devem ter borda preta, sólida e com 1 pixel de largura;
* As cores da paleta devem estar lado a lado;
* A paleta de cores deve estar posicionada abaixo do título `Paleta de Cores`;
* A paleta de cores não pode conter cores repetidas.

</details>

## 2 - Adicione à página um quadro contendo 25 pixels, sendo que cada elemento do quadro de pixels possua 40 pixels de largura, 40 pixels de altura e seja delimitado por uma borda preta de 1 pixel

<details>
  <summary>Sua página deve conter um quadro de pixels 5x5; sendo que dada <code>pixel</code> do quadro deve possuir 40px de largura e 40px de altura e uma borda preta sólida de 1px de espessura</summary>

* O quadro de _pixels_ deve estar visível na tela e ter 5 elementos de largura e 5 elementos de comprimento;
* O quadro de _pixels_ deve possuir o `id` denominado `pixel-board`, e cada _pixel_ individual dentro do quadro deve possuir a `classe` denominada `pixel`;
* A cor inicial dos _pixels_ que compõem o quadro de pixels deve ser branca;
* O quadro de _pixels_ deve aparecer abaixo da paleta de cores.

**De olho na dica 👀:** utilize os _loops_ para evitar trabalhos repetitivos e a manipulação do DOM para criar os elementos, adicionar identificadores, classes e estilos.

**O que será testado:**

* O quadro de _pixels_ deve possuir o `id` `pixel-board` e deve estar renderizado na tela;
* Cada pixel individual dentro do quadro deve possuir a `classe` `pixel`;
* A cor inicial dos _pixels_ dentro do quadro deve ser branca;
* O quadro de _pixels_ deve aparecer abaixo da paleta de cores.
* O quadro de _pixels_ deve possuir altura e comprimento de 5 elementos;
* Os elementos do quadro devem possuir 40 px de altura e 40 px de largura, incluindo o seu conteúdo e excluindo a borda preta;
* Os elementos do quadro devem possuir borda preta sólida de 1px de espessura.

</details>

## 3 - Crie uma função para selecionar uma cor na paleta de cores

<details>
  <summary>A cor clicada deve ser a única selecionada na paleta de cores.</summary>

* A cor clicada deve receber a `classe` `selected` e a cor previamente selecionada deve perder esta `classe`;
* Somente uma das cores da paleta pode ter a classe `selected` de cada vez;
* Os elementos que deverão receber a `classe` `selected` devem ser os mesmos elementos que possuem a classe `color`, como especificado no **requisito 1**.

**O que será testado:**

* Somente uma cor da paleta de cores pode ter a classe `selected` de cada vez;
* Os pixels dentro do quadro não devem ter a classe `selected` quando são clicados.

</details>

## 4 - Crie uma função que permita preencher um pixel do quadro com a cor selecionada na paleta de cores

<details>
  <summary>O <code>pixel</code> do quadro clicado deve ter sua cor alterada para a cor selecionada na paleta de cores</summary><br />

**O que será testado:**

* Após selecionar uma cor na paleta de cores, é possível pintar os pixels do quadro com essa cor;
* Somente o pixel que foi clicado deve ter a cor alterada, sem influenciar na cor dos demais pixels.

</details>

## 5 - Crie um botão que, ao ser clicado, limpa o quadro preenchendo a cor de todos seus pixels com branco

<details>
  <summary>Sua página deve ter um botão que, ao ser clicado, deixe todos os <code>pixels</code> do quadro com a cor branca</summary><br />

**De olho na dica 👀:** use manipulação do DOM com JavaScript para criar os elementos, adicionar identificadores, classes e estilos.

**O que será testado:**

* O botão deve possuir o `id` `clear-board`;
* O botão deve estar posicionado entre a paleta de cores e o quadro de pixels;
* O botão deve possuir o texto `Limpar`;
* O botão ao ser clicado, deve deixar todos os pixels do quadro preenchidos de branco.

</details>

## 6 - Adicione um botão para gerar cores aleatórias para a paleta de cores

<details>
  <summary>As quatro cores devem ser geradas aleatoriamente ao clicar no botão.</summary><br />

**De olho na dica 👀:** use manipulação do DOM com JavaScript para criar os elementos, adicionar identificadores, classes e estilos.

**O que será testado:**

* O botão deve possuir o `id` denominado `button-random-color`;
* O botão deve possuir o texto `Cores aleatórias`;
* As cores geradas na paleta são diferentes a cada click do botão;

</details>

## 7 - Crie uma função para salvar e recuperar o seu desenho atual no localStorage

<details>
  <summary>Ao recarregar a página, o quadro deve permanecer. Para isso, a cada clique em um pixel, salve a cor e a posição no localStorage. Ao recarregar a página o quadro deverá ser recuperado a partir dos dados que foram salvos no localStorage.</summary><br />

**De olho na dica 👀:** Antes de usar o dado do localStorage verifique se ele está lá (existe) ou se é a primeira vez.

**O que será testado:**

* O quadro deve ser preenchido com as mesmas cores utilizadas anteriormente, nas posições corretas ao recarregar a página

</details>

## 8 - Crie um input que permita à pessoa usuária preencher um novo tamanho para o quadro de pixels

<details>
  <summary>A página deve conter um input para que a pessoa usuária possa definir o tamanho do quadro de pixels</summary>

* Crie um input com `id` `board-size` posicionado entre a paleta de cores e o quadro de pixels para receber um valor maior que zero para definir o tamanho do quadro de pixels.
* Crie um botão que deve conter o texto "VQV" e `id` `generate-board`;
* O input e o botão com o texto "VQV" devem ter o mesmo `parent-node`;
* O botão, ao ser clicado, deve alterar o tamanho do quadro para **N** pixels de largura e **N** pixels de altura, em que **N** é o número inserido no input. Ou seja, se o valor passado para o input for igual a 7, ao clicar no botão, será gerado um quadro de 49 pixels (7 pixels de largura x 7 pixels de altura);
* O input só deve aceitar número maiores que zero. Essa restrição **deve** ser feita usando os atributos do elemento `input`;
* Se nenhum valor for colocado no input ao clicar no botão, mostre um `alert` com o texto: "Board inválido!";
* O novo quadro deve ter todos os pixels preenchidos com a cor branca.

**De olho na dica 👀:** use manipulação do DOM com JavaScript para criar os elementos, adicionar identificadores, classes e estilos.

**O que será testado:**

* O input deve possuir o `id` `board-size`;
* O input deve aceitar apenas números maiores que zero. Essa restrição deve ser feita usando os atributos do elemento `input`;
* O input deve estar posicionado entre a paleta de cores e o quadro de pixels;
* O botão deve possuir o `id` `generate-board`;
* O botão deve possuir o texto `VQV`;
* O input e o botão com o texto "VQV" devem ter o mesmo `parent-node`;
* O botão, ao ser clicado, deve mudar o tamanho do board usando o valor do input;
* O botão, ao ser clicado sem valor definido no input, deve emitir um `alert` com o texto: `Board inválido!`;
* O quadro gerado deve ter todos os pixels preenchidos com a cor branca.

</details>

## 9 - Crie uma função que limite o tamanho mínimo e máximo do quadro de pixels

<details>
  <summary>O quadro não pode ser definido com menos de 5 ou mais de 50 <code>pixels</code></summary>

* Caso o valor digitado no input `board-size` esteja fora do intervalo de 5 a 50, faça:

  1. Para um valor de `board-size` menor que 5, considere 5 `pixels` como o valor padrão;

  2. Para um valor de `board-size` maior que 50, considere 50 `pixels` como o valor padrão.

**O que será testado:**

* A altura do board pode ser igual a 50;
* A altura do board é 5 pixels quando um valor menor que 5 é colocado no input;
* A altura do board é 50 pixels quando um valor maior que 50 é colocado no input.

</details>

## 10 - Crie uma função para manter o tamanho novo do board ao recarregar a página

<details>
  <summary>O tamanho do board deve ser mantido ao recarregar a página usando localStorage</summary><br />

**De olho na dica 👀:** Antes de utilizar os dados armazenados no localStorage, verifique se eles existem ou se é a primeira vez que estão sendo criados.

**O que será testado:**

* O quadro deve ter o mesmo tamanho gerado ao recarregar a página.
* O quadro deve ser preenchido com as mesmas cores utilizadas anteriormente, nas posições corretas ao recarregar a página.

</details>
