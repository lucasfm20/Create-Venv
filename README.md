# Create-Venv
Repositório com as instruções para usar o venv.


### 1- CRIAR O AMBIENTE VIRTUAL
No cmd do projeto.
```bash
python -m venv venv
```
### 2- ATIVAR O AMBIENTE VIRTUAL
```bash
venv\Scripts\activate
```
### 3- CRIAR O ARQUIVO Requirements.txt
```bash
pip freeze > requirements.txt
```
### 4- INSTALAR PACOTES NECESSÁRIOS
```bash
pip install nome_pacote
```
### 5- ATUALIZAR PACOTE INSTALADO
```bash
pip freeze > requirements.txt
```
### - INSTALAR DEPENDÊNCIAS DE UM REQUIRIMENT
```bash
pip install -r requirements.txt
```

### - RODAR PROJETO PELO CMD DENTRO DO VENV
```bash
python main.py
```


docker pull dpage/pgadmin4

docker run -p 80:80 \
-e PGADMIN_DEFAULT_EMAIL=admin@admin.com \
-e PGADMIN_DEFAULT_PASSWORD=admin \
--name pgadmin \
-d dpage/pgadmin4


http://localhost
