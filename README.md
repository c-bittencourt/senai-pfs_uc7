# senai-pfs_uc7
Arquivos de atividades e execícios da disciplina SENAI PFS-UC7 - Versionamento
Encontro Remoto 1- PFS UC7 - Versionamento

AÇÕES NO REPOSITÓRIO LOCAL
1. Foi criada pasta para versionamento no Windows Explorer ("encontroRemoto1")
2. Nessa pasta, foi iniciado o Git ("Git Bash Here")
3. No prompt do Git, o versionamento do repositório foi iniciado
4. Foi criado um arquivo html nessa pasta ("paginaInicial.html")
5. Para verificação do status completo do repositório, foi rodado o comando "git status"
6. O arquivo html criado foi então transferido para o staging, através do comando "git add."
7. Para verificar as alterações antes de salvar, foi usado novamente o comando "git status"
8. As alterações foram então salvas (git commit -m "Versão corrente da página HTML")
9. Para verificar as alterações confirmadas no repositório, foi executado o comando "git log"
10. Usando o número do commit, foi visualizada a alteração no projeto ("git show <número do commit>.")

AÇÕES NO REPOSITÓRIO REMOTO (Github)
1. Após as configurações no repositório local, foi iniciada a configuração para publicação no repositório online informando a pasta remota ("git remote add origin https://github.com/c-bittencourt/senai-pfs_uc7")
2. Foi visualizado o repositório remoto ("git remote -v"), que retornou o local do Github para a transferência do arquivo html para o repositório remoto
3. Em seguida, o arquivo html foi transferido para o ramo principal (master) do repositório do Github ("git push -u origin master")
4. Por fim, o repositório publicado foi visualizado no navegador

CRIAÇÃO DE BRANCH, MERGE E SINCRONIZAÇÃO
1. Foi criada uma ramificação no repositório local para a modificação do arquivo html ("git checkout -b desenvolvimento")
2. O arquivo "paginaInicial.html" foi editado e salvo. No Git Bash, nessa branch, foi usado o "git add .", o commit (git commit -m "Nova evolução da página html - adicionados dois parágrafos") e o "git push origin desenvolvimento" para enviar a alteração na branch para o repositório remoto
3. Em seguida, o branch foi alterado para o master ("git checkout master")
4. Foi criada uma tag para marcar o ponto atual da versão (git tag -a v1.0 -m "Primeira versão da página")
5. Foi visualizada a tag com o "git tag", e verificadas as informações específicas dessa tag ("git show v1.0")
6. A tag foi postada também no repositório remoto (git push origin --tags)
7. Foi visualizada a tag no navegador (no Github, clicando no link "tags")
8. Por fim, foi feito o merge da alteração na versão master ("git merge desenvolvimento").
9. Foi criado o README.MD no repositório remoto para documentar a atividade.
