## Criação de um projeto utilizando o django e o venv.

Primeiro abra a prompt de comandos e coloque

mkdir django_aulas

(Django_aulas é exemplo mas pode colocar qualquer outro nome)

mkdir: (make directory)

E depois

cd django_aulas

cd:(change directory)

'cd' para abrir o arquivo que foi criado anteriormente junto com o nome dele

python -m venv venv

Para cirar um ambiente dentro da pasta django_aulas

venv/Scripts/activate

Para ativar o ambiente 

(se der certo vai aparecer um "venv" antes das informações na linha de comandos)
EX: (venv)C:\django_aulas


django-admin --version

Ele te exibe a versão atual do django

pip install django

Para instalar o django caso o comando anterior não funcione

django-admin startproject meu_projeto

Cria uma pasta com o nome meu_projeto (pode ser outro nome tambem)

cd meu_projeto
Para entrar na pasta meu_projeto criada anteriormente

use o comando 'code .' Para entrar no vscode
