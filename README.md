# Desafio Estágio Data Engineering
A sua tarefa é escrever um ETL usando esses arquivos de input e gerando dois outputs.

### Quickstart
Para visualizar os códigos e análises, abra o arquivo [DESAFIO ESTÁGIO DATA ENGINEERING](notebooks/challege-data-enginner-intern.ipynb)


### Requirements
- Python 3.7 ou superior
```sh
sudo apt-get install python3.7
```

- Git
```sh
sudo apt-get install git
```

- pip
```sh
sudo apt-get install python-pip
```

- Python Virtual Environment
```sh
pip3 install --user virtualenv==16.6.0
```


### Running ETL
1. Abra o terminal e clone o repositório 
```bash
git clone https://github.com/brunocampos01/challenge_indicium/
cd challenge_indicium/
```

2. Escolha em qual ambiente quer executa
 - [local](src/environment/README.md)
 - [virtual environment](src/environment/README.md)
 - [container](src/environment/README.md)

3. Execute o notebook: [DESAFIO ESTÁGIO DATA ENGINEERING](notebooks/challege-data-enginner-intern.ipynb)


### Output 1
- São 3 imagens:
  - Valor Total Vendido por Contato.jpg
  - valor_total_vendido_por_mês-2017.jpg
  - valor_total_vendido_por_mês-2018.jpg
 
OBS: as imagens já constam salvas no diretório. Elas são geradas a partir da execução do script_etl.py

### Output 2
- É a lista dos setores de empresa, ordenado por quanto esse setor representa no total vendido pela empresa no mês  **a partir de cada ano.**
- Arquivo: [output.csv](data/cleansing/)

---

#### Author
<a href="mailto:brunocampos01@gmail.com" target="_blank"><img class="" src="https://github.com/brunocampos01/devops/blob/master/images/gmail.png" width="28"></a>
<a href="https://github.com/brunocampos01" target="_blank"><img class="ai-subscribed-social-icon" src="https://github.com/brunocampos01/devops/blob/master/images/github.png" width="30"></a>
<a href="https://www.linkedin.com/in/brunocampos01/" target="_blank"><img class="ai-subscribed-social-icon" src="https://github.com/brunocampos01/devops/blob/master/images/linkedin.png" width="30"></a>
Bruno Aurélio Rôzza de Moura Campos 

---

#### Copyright
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br/>
