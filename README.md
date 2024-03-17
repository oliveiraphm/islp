# islp
1) Clone o repositório
```bash
git clone https://github.com/oliveiraphm/islp_repo.git
``` 

2) Acesse o repositório 
```bash 
cd islp 
```

3) Instale a versão correta do Python
```bash 
pyenv install 3.12.1
pyenv local 3.12.1
```
4) Configure o Poetry e para a versão do Python 3.12.1 e ative o ambiente virtual
```bash 
poetry env use 3.12.1
poetry shell
```

5) Instale as dependências do projeto
```bash 
poetry install
```