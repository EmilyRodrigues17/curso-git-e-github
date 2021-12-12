## Versionamento
    Processo de controle de versões, definido através de "numerações" de históricos diferentes, permite que alterações no software sejam visualizadas.
    Git controla o histórico das versões de um código, atribuindo "numerações" para o estado do código no momento específico que foi salvo por uma pessoa.

## Repositório
    é a pasta onde é armazenado o projeto, que podem ser divididos em módulos ou divisões específicas para cada tipo de projeto.
    Todo repositório tem um arquivo .git que indica que esse repositório é rastreavel pelo Git.

## Commit
    Conjunto de alterações no código
    Usado para salvar/registrar as alterações feitas no projeto

    ex: git commit -m "adicionando alteração 1"

    ### Change (Diff)
        controle sobre alterações e diferenças entre as versões dos arquivos.

    ### O que o git entende por diferença
        criação, renomeação ou exclusão de arquivos
        inserção ou exclusão de uma linha em um arquivo

## Branch
    Separações de código
    Com isso é possível várias pessoas atuarem no mesmo projeto independentemente.
    Branch `main`: branch principal do projeto, é onde fica os códigos que vão para produção.
    Branch `Develop`: ambiente para uso em tempo de desenvolvimento.
    Branch `Homolog`: onde as pessoas de negócio podem validar a solução proposta, além de mais realizações de testes, após as alterações feitas serem validadas.

## Merge
    Une duas branchs, onde pessoas estavam atuam simultaneamente.

## Pull
    usado para atualizar o repositório local com as recentes alterações feitas.
    assim, realiza um merge entre o local e online (github), evitando possíveis conflitos quando for subir uma alteração.

    ex: git pull origin `nome da branch`

## Push
    usado para enviar as alterações locais para o repositório remoto.

    ex: git push origin `nome da branch`

## Fork
    usado para criar uma cópia de um projeto no seu github, após isso é possível fazer pull requests para contribuir com o projeto principal.

## Pull Request
    alterações de código para resolver uma tarefa, bug e etc.
    se o pull request for aprovado essa alteração será mergeado no repositório principal.