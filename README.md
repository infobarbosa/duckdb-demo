# DuckDB (work in progress)
Author: Prof. Barbosa<br>
Contact: infobarbosa@gmail.com<br>
Github: [infobarbosa](https://github.com/infobarbosa)

## Objetivo
Avaliar de forma rudimentar o banco de dados [DuckDB](https://duckdb.org/).

## Ambiente 
Este laborarório pode ser executado em qualquer estação de trabalho.<br>
Recomendo, porém, a execução em Linux.<br>
Caso não tenha uma estação de trabalho Linux à sua disposição, recomendo utilizar o AWS Cloud9. Para isso siga essas [instruções](Cloud9/README.md).

## Setup
Para começar, faça o clone deste repositório:
```
git clone https://github.com/infobarbosa/duckdb-demo
```

### Atenção! 
Os comandos desse tutorial presumem que você está no diretório raiz do projeto.<br>
Após clonar o repositório, navegue no terminal para ele:
```
cd duckdb-demo
```

## Instalação
#### Download do binário
```
```




### Inicialização
```
echo x
```

## A base de dados
## Download da base de dados
```
git clone https://github.com/infobarbosa/datasets-csv-pessoas
git clone https://github.com/infobarbosa/datasets-parquet-pessoas
```

As duas bases são iguais, apenas em formatos diferentes.

### Tabela `pessoas`
```
duckdb :memory: "SELECT * FROM './datasets-parquet-pessoas/pessoas.gz.parquet' LIMIT 1"
```

```
duckdb :memory: "SELECT * FROM './datasets-csv-pessoas/pessoas.csv.gz' LIMIT 1"
```


## Operações em linhas (ou registros)

### 1. Insert
```

```



## Datafiles

```

```


## Parabéns
Neste laboratório nós:
