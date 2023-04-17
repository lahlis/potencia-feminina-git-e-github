##<center> Notas do Módulo 2:<br><br> *"Criando seu primeiro repositório e aprendendo os comandos mais utilizados"* </center>
<br>
####Criando repositórios localmente:
1. No Git Bash, escreve: mkdir nomedapastaquesequercriar Obs.: para mudar o diretório utiliza o comando “cd nomediretorio: “
2. Para abrir o VsCode: code .
3. Dentro do VsCode, abre o terminal e escreve: git config --global user.name “Nome da Pessoa” e git config  --global user.email “emaildapessoa”
4. Confere se as configurações estão ok com git config --list
5. Para inicializar o diretório: git init → assim o git vai entender que o conteúdo é rastreável
6. Para conectar os repositórios remoto e local: cria o repositório no GitHub, depois escreve no terminal do local “`git remote add origin git@github.com:user/nome-do-repositorio-no-github.git`"
<br>
####Comandos mais utilizados:
- git status
    - Verifica o status dos arquivos e pastas dentro do repositório
- git add
    - Adiciona arquivos para a esteira de commit:
        - Para adicionar um arquivo específico: escreve git add caminhodoarquivo
        - Para adicionar todos arquivos do repositório: git add .
- git commit
    - git commit -m “Mensagem sobre o commit”
- git push e pull
    - Antes de fazer o push, é necessário conectar a branch local com a upstream
        - Upstream: origem remota da branch no GitHub
        - Para configurar a branch como a upstream da master, usa o comando fornecido pelo próprio git: git push --set-upstream origin master
    - git pull: “traz” os arquivos que foram criados (ou alterados) no GitHub para a máquina