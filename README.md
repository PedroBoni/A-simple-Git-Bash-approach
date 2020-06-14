# Git Bash

### Git bash é um sistema de controle de versão distribuído e não usa um servidor centralizado.[[1]](#link_1)
****

Inicialmente feito para uso em sistema Unix, o Windows não tinha o Git Bash no começo por não ser baseado em Unix e os comandos eram diferentes tornando a compatibilidade uma barreira.

Foi desenvolvido por Linus Torvalds e Junio Hamano. Torvalds também foi o desenvolvedor do Linux, ele decidiu desenvolver o git porque na época, mais especificamente em 7 de abril de 2005 - dia do lançamento - tinha poucas ferramentas de versionamentos e todas eram ruins segundo Torvalds fala nessa apresentação na Google em 14 de maio de 2007 [Tech Talk: Linus Torvalds on git](https://www.youtube.com/watch?v=4XpnKHJAok8).

Git é um software livre e usa as linguagens C, Shell e Perl.

Recursos e sobre: 'ramificação e fusão', 'pequeno e rápido', 'distribuído', 'garantia de dados', 'área de preparação', 'código aberto e gratuito', 'marca comercial'. [[2]](#link_2)

**Uma curiosidade sobre o nome 'Git': **[[3]](#link_3)

Citando Linus: 

> "Sou um bastardo egoísta e nomeio todos os meus projetos depois de mim. Primeiro 'Linux', agora 'Git'"

'Git' é uma gíria britânica para cabeça dura, pessoas que tem sempre razão,etc. 

"Todos nós somos um pouco git as vezes"

****
**Comandos básicos**

Inicia um repositório git.

`git init`

Adciona o conteúdo ao índice, o '.' diz para enviar todos os arquivos que estão no repositório local. Você pode adicionar  um arquivo apenas trocando o '.' pelo nome do arquivo.

`git add .` 

Registra alterações no repositório, a opção '-m' é usado para enviar uma msg como 'Primeiro commit'

`git commit -m "Primeiro commit"`

Gerenciar conjunto de repositórios rastreados, a opção 'add' é usado para adicionar um controle remoto na 'origin' ramificação e a 'url' do repositório remoto.

`git remote add origin {repositório_remoto_URL}`

Atualiza o repositório remoto enviando arquivos

`git push`

Atualiza o repositório local com recebendo arquivos

`git pull`

****
**Hospedagem de código fonte**

O site mais famoso usado para esse fim é o [GitHub](https://github.com/)

****

**Refencias**

<a id="link_1">[1] </a>- *What is Git?*  <https://git.wiki.kernel.org/index.php/GitFaq#What_is_Git.3F>

<a id="link_2">[2] </a>- *About* <https://git-scm.com/about/branching-and-merging>

<a id="link_3">[3] </a>- *Why the 'Git' name?* <https://git.wiki.kernel.org/index.php/GitFaq#Why_the_.27Git.27_name.3F>

****
### Autoria

Pedro Bonifacio, 1DS3, ETEC ITANHAÉM.

Pesquisa para a matéria de Técnicas de Progamação.

Uma abordagem rápida sobre o Git Bash.

