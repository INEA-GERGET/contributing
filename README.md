# Contibuindo com o GERGET

Contribuições de todos são bem-vindas ao nossos códigos open source. Quando for contribuir, por favor, siga nosso [Código de Conduta](https://github.com/INEA-GERGET/contributing/blob/main/CODE_OF_CONDUCT.md) e, se existir, leia o CONTRIBUTING.md do repositório de interesse.

## Issues

Sinta-se livre para submeter issues e solicitações de aprimoramento.

## Contribuindo

Por favor, consulte o estilo e as diretrizes de contribuição de cada projeto para enviar patches e adições. Em geral, seguimos o fluxo de trabalho Git "fork-and-pull":
1. Faça um fork do repositório no GitHub
2. Clone o projeto para sua própria máquina
3. Crie seu próprio branch `usurario-patch-1`
4. Faça commit das alterações no seu branch
5. Envie seu trabalho de volta para o seu fork
6. Envie uma Pull request para que possamos revisar suas alterações

> [!NOTE]
> **Não faça um merge sem a revisão de um owner ou moderador.**

## Boas práticas

Toda colaboração deve ser feita respeitando o [Código de Conduta do INEA - GERGET](https://github.com/INEA-GERGET/contributing/blob/main/CODE_OF_CONDUCT.md).

### Nomeclatura
Por padrão, usaremos o *kebab case* (todas as letras minúsculas, palavras separadas por hífens, como `meu-nome-de-usuario`).

### Commits

Faça commits pequenos. Uma tarefa grande demais pode ser quebrada em pequenas issues, onde cada uma delas será resolvida em um commit.
Cada commit deverá ser responsável por uma única alteração no software: uma nova funcionalidade, uma correção, etc. Cada commit possui poucas alterações com um único propósito, alterando ou adicionando poucos arquivos.

Coloque uma mensagem clara no commit. Tente também manter sua mensagem entre 40 e 72 caracteres.
> "Bug no gráfico de barras corrigido"
> 
> "Corrigido tema escuro da página inicial"
>
> "ReadMe adicionado no repositório"

### Branches

Sempre faça as alterações e o pull request na sua branch. Caso seja um commit de uma tarefa grande, que ainda não será finalizada, o merge será feito em uma branch secundária **develop**, onde estará as últimas adições feitas pelos colaboradores.
A branch criada por um usuário deve serguir o padrão de nomeclatura `usurario-patch-1`, como descrito no ítem [Contribuindo](#Contribuindo).

### Gitgnore

Não envie arquivos de build, temporários ou de sua IDE para o repositório remoto. Para isso, adicione as devidas pastas e tipos de arquivo no arquivo ".gitignore". Uma boa versão inicial deste arquivo pode ser encontrada [clicando aqui](https://github.com/github/gitignore).











