# contador_flutter

# Comandos git usados

Criar pasta no diretorio local 
SEMPRE EM LETRAS MINUSCULAS E SEM TRAVESSÃO

Entrar na pasta 
Clonar repositorio 

git clone https://github.com/Latamila/contador_flutter.git

ls /checar os arquivos

entrar na pasta do contador_flutter

observar se tem os arquivos README e .gitignore

flutter create -t app --org com.camilaveloso.app -a kotlin -i swift .

ls /para ver os arquivos do app na pasta 

git add . 

git commit -m "commit inicial"

git push origin main

Possível problema para este último comando:

Certifique-se de que o repositório remoto (origin) já esteja configurado com git remote add origin <url>.

Confirme se o branch principal realmente se chama main (pode ser master em repositórios antigos).

Se for o primeiro push para um repositório remoto vazio, pode precisar do parâmetro -u:

git push -u origin main
