# Regressão para Dados de Contagem com R

**ME904 — Computação Estatística | Universidade Estadual de Campinas (UNICAMP)**

## Sobre o projeto

Trabalho acadêmico de reprodução e análise crítica de modelos de regressão para dados de contagem, desenvolvido no âmbito da disciplina ME904.

A principal referência é o livro *Extending the Linear Model with R*, de Julian J. Faraway (2006), Capítulo 3, Seções 3.1 a 3.3.

O objetivo é reproduzir os procedimentos e resultados apresentados pelo autor, avaliar os pressupostos dos modelos e discutir suas limitações.

## Estudos abordados

| Base de dados | Aplicação | Métodos |
|---|---|---|
| `gala` | Espécies nas Ilhas Galápagos | Regressão de Poisson e análise de dispersão |
| `dicentric` | Alterações cromossômicas e radiação | Regressão de Poisson com offset |
| `solder` | Defeitos em processos de soldagem | Poisson e binomial negativa |

## Objetivos

1. Reproduzir as análises estatísticas das seções indicadas.
2. Comparar as estimativas e os diagnósticos com os resultados publicados.
3. Investigar formalmente a sobredispersão nos três conjuntos de dados.
4. Interpretar os resultados e discutir as limitações dos modelos.
5. Garantir a reprodutibilidade computacional das análises.

## Ferramentas

- Linguagem R
- RStudio
- Pacotes `faraway` e `MASS`

## Reprodutibilidade

As análises serão desenvolvidas em R, utilizando os conjuntos de dados disponibilizados pelo pacote `faraway`.

As instruções de execução e os resultados de referência serão documentados conforme a implementação avançar.

## Referência bibliográfica

FARAWAY, Julian J. *Extending the Linear Model with R: Generalized Linear, Mixed Effects and Nonparametric Regression Models*. Chapman & Hall/CRC, 2006.

## Status

Em desenvolvimento — reprodução computacional dos estudos.
