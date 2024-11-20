# Create-Venv
Repositório com as instruções para usar o venv.


### 1- CRIAR O AMBIENTE VIRTUAL
```bash
python -m venv venv

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

