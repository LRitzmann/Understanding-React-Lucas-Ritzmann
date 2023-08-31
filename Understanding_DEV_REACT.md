# **Git/GitHub**
O **Git** é uma ferramenta essencial para a organização e o trabalho em equipe num dado projeto uma vez que ele
é responsável pelo **controle de versão**: por meio do Git podemos rastrear e entender o status de um projeto (na forma de um *repositório*) ao longo de todos os possíveis galhos (*branches*) de trabalho, e assim também podemos levar a frente nossa própria contribuição para o projeto de modo organizado, evitando conflitos.

O **GitHub** é uma plataforma online que hospeda repositórios de usuários do mundo todo, públicos ou privados, não só oferecendo diversas ferramentas que ajudam na colaboração como também funcionando como uma espécie de rede social para desenvolvedores. O Git não necessita do GitHub para ser utilizado; é altamente recomendável, no entanto, que um desenvolvedor possua uma conta na plataforma.

O Git é instalado a partir de seu site oficial, e seu acesso e funcionamento ocorre através da linha de comando (*cmd.exe*). Um atalho para que o usuário não precise navegar por meio do *cmd* até o diretório de interesse é simplesmente clicar no caminho da pasta do diretório Git, substituí-lo por "cmd" e apertar *enter*.


## Comandos Git Essenciais
- **`git init`**: Inicializa um novo repositório Git no diretório atual.
- **`git clone [url_do_repositório]`**: Clona um repositório remoto para sua máquina local.
- **`git add [arquivo(s)]`**: Adiciona mudanças para serem commitadas.
- **`git commit -m "[mensagem_do_commit]"`**: Realiza um commit das mudanças adicionadas com uma mensagem descritiva.
- **`git status`**: Mostra o status do seu diretório de trabalho e das mudanças preparadas para commit.
- **`git log`**: Exibe o histórico de commits.
- **`git diff`**: Mostra as diferenças entre o seu diretório de trabalho e o último commit.
- **`git pull`**: Busca e integra mudanças de um repositório remoto para a sua branch atual.
- **`git push`**: Envia seus commits locais para um repositório remoto.
- **`git branch`**: Lista toda as branches no repositório.
- **`git checkout [nome_da_branch]`**: Alterna para uma branch diferente.
- **`git merge [nome_da_branch]`**: Mescla mudanças de uma branch para outro.
- **`git remote -v`**: Lista repositórios remotos associados ao seu repositório local.
- **`git fetch [nome_do_repositório]`**: Busca mudanças de um repositório remoto sem mesclá-las.
- **`git reset [arquivo(s)]`**: Remove mudanças da área de preparação.
- **`git revert [commit]`**: Cria um novo commit que desfaz as mudanças introduzidas por um commit específico.
- **`git stash`**: Salva temporariamente mudanças que ainda não estão prontas para serem commitadas.
- **`git help`**: Obtém ajuda para um comando específico do Git.

<br>

# **Markdown**

## Dicas de Markdown  
O site [Markdown Guide](https://www.markdownguide.org/ "Markdown Guide Site") é um recurso online que explica   basicamente tudo a respeito do Markdown e como utilizá-lo ao máximo.


# **HTML**
O HTML é uma linguagem usada para estruturar e apresentar conteúdo na internet. Ele utiliza "tags" para definir elementos como cabeçalhos, parágrafos, links e imagens em uma página web. Essas tags são interpretadas pelos navegadores para renderizar o conteúdo de maneira adequada aos usuários.

## Tags HTML Essenciais
- **`<html>`**: Define o início do documento HTML.
- **`<head>`**: Contém informações do cabeçalho do documento, como título e metadados.
- **`<title>`**: Define o título da página exibido na guia do navegador.
- **`<meta>`**: Fornece metadados sobre o documento, como descrição e palavras-chave.
- **`<link>`**: Liga o documento a recursos externos, como CSS.
- **`<script>`**: Usado para incorporar scripts de JavaScript na página.
- **`<style>`**: Contém estilos CSS para aplicar ao documento.
- **`<body>`**: Define o conteúdo principal do documento exibido no navegador.
- **`<h1>`**, **`<h2>`**, ..., **`<h6>`**: Cabeçalhos de diferentes níveis, usados para títulos.
- **`<p>`**: Define um parágrafo de texto.
- **`<a>`**: Cria um link para outra página ou recurso.
- **`<img>`**: Insere uma imagem na página.
- **`<ul>`**: Cria uma lista não ordenada.
- **`<ol>`**: Cria uma lista ordenada.
- **`<li>`**: Define um item em uma lista.
- **`<br>`**: Insere uma quebra de linha.
- **`<hr>`**: Insere uma linha horizontal.
- **`<table>`**: Cria uma tabela.
- **`<tr>`**: Define uma linha em uma tabela.
- **`<td>`**: Define uma célula em uma tabela.


## Tags Semânticas
Para que uma página não só apresente maior legibilidade para outros desenvolvedores como também seja melhor posicionada nos mecanismos de busca, é altamente recomendado o uso de **tags semânticas**. As tags semânticas não possuem propriedades inerentes que alterem a página, o emprego desse tipo de tag visa apenas dividir o código e discriminar os elementos de acordo com seu papel na estrutura da página. A seguir, temos uma lista das principais tags semânticas:

- **`<nav>`**: Define a área de navegação da página.
- **`<main>`**: Define o conteúdo principal da página.
- **`<article>`**: Define um conteúdo independente do resto.
- **`<section>`**: Define uma seção genérica em um documento.
- **`<aside>`**: Define conteúdo secundário, como barras laterais.
- **`<footer>`**: Define o rodapé da página ou seção.
- **`<figure>`**: Define um conteúdo multimídia, como imagens.
- **`<figcaption>`**: Define a legenda para elementos em `<figure>`.
- **`<time>`**: Define datas ou horários significativos.
- **`<mark>`**: Destaca texto com fins de referência.
- **`<blockquote>`**: Define uma citação longa em bloco.
- **`<q>`**: Define uma citação curta embutida.
- **`<abbr>`**: Define uma abreviação ou acrônimo.
- **`<cite>`**: Define o título de uma obra citada.
- **`<address>`**: Define informações de contato.