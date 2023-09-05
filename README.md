# CodeContainer
CodeContainer website repository

Como criar um contêiner para o site:

1. Copie o repositório em um novo arquivo criado no computador.
2. No prompt de comando, vá até o diretório criado usando o comando 'cd local_do_diretorio'
3. Abra o Docker Desktop e tenha certeza de que esteja ligado e funcionando
4. No prompt, insira os seguintes comandos:
   - 'docker build -t codecontainer .'
   - 'docker run -d -p 8081:80'
5. Abra o Docker Desktop e você verá o Contêiner rodando com o nome "codecontainer"
6. Abra o contêiner no browser e ele estará funcionando!
