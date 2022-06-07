## Comandos Windows :computer:

- dir: lista diretórios
- cd/: base do diretório C
- cd .. : volta um nível
- cls: limpar
- mkdir: criar diretório
- del: deletar arquivos
- rmdir: deleta diretórios.

## Objetos internos do Git :robot:

- Blobs: Contém metadados do Git;
- Trees: Armazenam blobs. Pode haver outra tree dentro de uma tree.
- Commit: Aponta para tree, parente, autor, mensagem e timestamp. Possui um SHA1 que quando alterado, altera-se o SHA de toda a estrutura.

SHA1: Encriptação que gera um conjunto identificador de 40 caracteres.

## Git init, git add e git config :pencil:

- git init: Iniciar o Git, cria um repositório dentro da pasta.
- git add: Adiciona no staged as modificações feitas no arquivo.
- git commit: Coloca os arquivos "Staged" em "Unmodified". Compõe o repositório local.

## Colocar os projetos no GitHub :smile_cat:

​		Os arquivos, para serem adicionados no GitHub, precisam ser commitados. Assim passarão a compor o repositório remoto. 

​		Depois de commitados, executa-se os seguintes comandos no Git:

- git remote add origin _https_: para onde os arquivos serão enviados;
- git remote -v: lista os repositórios remotos.
- git push origin master (ou main): "empurrar" para o GitHub.

## Resolvendo conflitos :woman_student:

​		Quando há mais de uma versão para o mesmo arquivo.

- git pull origin master: "puxar" o arquivo do GitHub

​		As alterações desejadas devem ser feitas manualmente, verificando quais linhas foram alteradas em outras versões. Depois repete-se o processo de commitar e adicionar no GitHub.



