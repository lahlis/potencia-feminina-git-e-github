##<center> Notas do Módulo 1 de:<br> *"Desvendando o GitHub"* <br> curso da primeira turma de *"Programação Web para Iniciantes"* da WoMakers Code.</center>
<br>
####Conceitos Iniciais:
 - Versionamento
        - Controle de versões por numerações de históricos diferentes
        - Tudo que é adicionado no Git, ele recebe um código para cada alteração que significa o estado do projeto. Esse código nunca se repete
        
    - Repositório
        - Pasta onde é armazenado o projeto
        - Dentro do repositório, os projetos podem se dividir em módulos específicos para cada projeto
        - Todo repositório tem um arquivo .gif, indicando que ele é rastreável para o Git
    - Commit
        - Conjunto de alterações no código
        - Toda vez que se desejar salvar as alterações no projeto, as alterações são “comitadas”
        - Um commit tem as alterações e uma mensagem descritiva, além de informações como autor, data e etc
        - Change (Diff): o Git mantém o controle de versão rastreando as alterações e diferenças entre as versões dos arquivos “cadastrados” nele
        - Ações entendidas pelo Git como alterações:
            - Criação, renomeação ou exclusão de arquivos
            - Inserção ou exclusão de uma linha em um arquivo
    - Branch
        - Separação de código (branches = galhos)
        - São etiquetas que apontam para os commits
        - Possibilita que várias atuem em um mesmo projeto de forma independente
        - Branch main: branch inicial de todo projeto
        - Nas empresas, há uma prática de criar branches de acordo com o ambiente que o código do projeto será disponibilizado:
            - Develop: ambiente para uso em tempo de desenvolvimento, onde o código é disponibilizado após ter sido testado na máquina do dev
            - Homolog: após as alterações serem validadas em ambiente de desenvolvimento, o código vai para a branch de homologação, onde as pessoas de negócio podem validar a solução e pessoas da área de qualidade efetuam mais testes para validar a solução
            - Master: branch principal do projeto, possui os códigos que vão para a produção (nome dado ao site disponibilizado para o público)
    - Merge
        - Consiste em unir duas branches
        - Geralmente utilizado para juntar alterações de duas branches em que duas pessoas estavam atuando simultaneamente
    - Clone
        - Possibilita a cópia de um repositório que está no GitHub para a máquina local
        - Fornece o acesso ao repositório localmente, podendo realizar as alterações e enviar para o GitHub
    - Pull
        - Atualiza o repositório local e todas as branches de rastreamento remoto
        - É realizado um merge entre o repositório online (github) com o que se tem localmente
        - Sem ele, a branch local não vai receber nenhum update
    - Push
        - Envia as alterações locais para o repositório remoto
        - Ou seja, atualiza o branch remoto com os commits locais
    - Fork
        - Permite a cópia de um repositório na sua conta no GitHub, porém sem baixar para a máquina
        - Depois de “forkar” o repositório de outra pessoa, é possível contribuir com o conteúdo
        
    - Pull Request
        - Gera uma solicitação para que um projeto de outras pessoas “puxe” (pull) mudanças propostas para si
        - Uma forma de propor alguma alteração no código de um repositório
        - Após “forkar” o repositório de outra pessoa, é possível resolver issues dele e fazer pull requests enviando soluções para erros e adicionando novos conteúdos
        - A pessoa dona do repositório avalia a pull request e, se tudo estiver certo, ela será mergeada no repositório principal


