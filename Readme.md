Bom dia, bom dia!
No sir!
Yes sir!

Neste arquivo eu irei ensinar como usar o Git. Por ser a minha primeira vez ensinando algo 
relacionado com programação e coding, minha didática será bem ruim, presumo eu.

PRIMEIROS PASSOS:
Antes de mais nada, será necessário ter uma pasta com os arquivos que você deseja enviar ao Git ou GitHub.
Uma ordem simples e resumida dos passos seria a seguinte:

    1° Git Bash Here
        Esse comando é efetuado na pasta citada anteriormente e ele inicia o terminal 
        do Git.

    2° git init
        Cria um repositório na pasta qual você fez o Git Bash Here.

    3° git config --global user.name [...]
        Comando que configura o Git no seu computador. Este comando será efetuado 
        apenas uma vez, assim como o próximo.

    4° git config --global user.email [...]
        Comando semelhante ao de acima. Enquanto o "user.name" diz ao Git qual o seu nome,
        "user.email" diz ao Git qual o seu email.

    5° git add [nome do arquivo.sua extensão]
        Após criar um arquivo e/ou efetuar mudanças neles, utilize este comando para deixá-lo staged. 
        Caso faça "git add .", todos os arquivos com mudanças na pasta serão adicionados ao stage.
        
    6° git commit -m "[...]"
        Este comando pede ao git para dar commit a tudo que foi adicionado recentemente ao stage.
        O que está entre as aspas é a mensagem que será commitada junto às mudanças.

    7° git remote add origin https://[...].git
        Este comando adiciona o seu repositório do Git ao GitHub desejado. Usando como exemplo o
        meu GitHub ficaria assim: git remote add origin https://github.com/PedroPicole/SobreGit.git

    8° git push -u origin main
        Este comando envia todos os commits já feitos ao reporitório no GitHub.

Estes são os passos básicos.
Esta linha é apenas um teste de branchs no Git.


    git push origin main
        Comando parecido com o 8° e tem a mesma função. Não contém o "-u" pois não é a primeira vez
        que o comando "push" é dado.

    git remote set-url origin [url...]
        Comando útil para quando se quer mudar a url do repositório origin/main.
