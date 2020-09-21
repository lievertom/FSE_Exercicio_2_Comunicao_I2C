# Programa em C

## Proposta

Criar um programa em C, utilizando a biblioteca oficial do fabricante (Bosch) para realizar a medida das 3 grandezas (Temperatura, Umidade e Pressão) a cada 1 segundo e registrar, a cada 10 segundos, a média das amostras em um arquivo em formato CSV registrando data e hora de cada registro.

**Repositório da Bosch:** https://github.com/BoschSensortec/BME280_driver

## Execução

1. Clonar repositório:

```
    $ git clone https://github.com/lievertom/FSE_Exercicio_2_Comunicao_I2C.git
```

2. Entrar no diretório programa_em_c:

```
    $ cd FSE_Exercicio_2_Comunicao_I2C/programa_em_c
```

3. Compilar:

```
    $ make
```

4. Executar:

```
    bin/bin
```

## Resultado Esperado

- é impresso no terminal, a cada segundo, os valores aferidos para temperatura, pressão e humidade;

- é registrado, a cada 10 aferições, no arquivo data.csv a média dos valores, além da data (YYYY-MM-DD) e hora do registro (hh:mm:ss).