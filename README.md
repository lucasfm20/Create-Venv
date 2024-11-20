# Create-Venv
Repositório com as instruções para usar o venv.


###1- CRIAR O AMBIENTE VIRTUAL
python -m venv venv

###2- ATIVAR O AMBIENTE VIRTUAL
venv\Scripts\activate

#3- CRIAR O ARQUIVO Requirements.txt
pip freeze > requirements.txt

#4- INSTALAR PACOTES NECESSÁRIOS
pip install nome_pacote

#5- ATUALIZAR PACOTE INSTALADO
pip freeze > requirements.txt

#- INSTALAR DEPENDÊNCIAS DE UM REQUIRIMENT
pip install -r requirements.txt


