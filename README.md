# Desafio Estágio Data Engineering

### About
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
- Arquivo: [output.csv](https://github.com/brunocampos01/challenge-indicium/blob/master/reports/output.csv)
