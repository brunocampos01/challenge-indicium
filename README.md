# DESAFIO ESTÁGIO DATA ENGINEERING

### About
A sua tarefa é escrever um ETL usando esses arquivos de input e gerando dois outputs.

### Quickstart
Para visualizar os códigos e análises, abra o arquivo [DESAFIO ESTÁGIO DATA ENGINEERING.ipynb](https://github.com/brunocampos01/challenge-indicium/blob/master/notebooks/challege-data-enginner-intern.ipynb) 

### Requirements
- Python 3.7 ou superior:<br/>
`sudo apt-get install python3.7`
- Git:<br/>
`sudo apt-get install git`
- pip:<br/>
`sudo apt-get install python-pip`
- Bibliotecas:<br/>
`pip install -r requirements.txt`

### Running ETL
1. Abra o terminal e clone o repositório: <br/>
`git clone https://github.com/brunocampos01/challenge_indicium/`<br/>
`cd challenge_indicium/`
2. Execute o script:<br/>
`python3 script_etl.py`

### Output 1
- São 3 imagens:
  - Valor Total Vendido por Contato.jpg
  - valor_total_vendido_por_mês-2017.jpg
  - valor_total_vendido_por_mês-2018.jpg
 
OBS: as imagens já constam salvas no diretório. Elas são geradas a partir da execução do script_etl.py

### Output 2
- É a lista dos setores de empresa, ordenado por quanto esse setor representa no total vendido pela empresa no mês  **a partir de cada ano.**
- Arquivo: [output.csv](https://github.com/brunocampos01/challenge-indicium/blob/master/reports/output.csv)
