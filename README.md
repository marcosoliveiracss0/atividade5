# Relatorio de Desempenho - Atividade 5 (Programacao Concorrente)

## Identificacao

- Aluno: Marcos de Oliveira Campos
- Professor: Rafael Marconi Ramos
- Turma: ADS04N1
- Curso: Analise e Desenvolvimento de Sistemas

## Resultados de Execucao

### Serial (1 processo)

```
=== RESULTADO FINAL ===
Tempo total MPI: 32.02 segundos
Total de pares avaliados: 12497500
```

### Paralelo com 2 processos

```
=== RESULTADO FINAL ===
Tempo total MPI: 24.32 segundos
Total de pares avaliados: 12497500
```

### Paralelo com 4 processos

```
=== RESULTADO FINAL ===
Tempo total MPI: 16.23 segundos
Total de pares avaliados: 12497500
```

### Paralelo com 8 processos

```
=== RESULTADO FINAL ===
Tempo total MPI: 11.58 segundos
Total de pares avaliados: 12497500
```

### Paralelo com 12 processos

```
=== RESULTADO FINAL ===
Tempo total MPI: 10.32 segundos
Total de pares avaliados: 12497500
```

## Tabela de Desempenho

Formula utilizada:

- Speedup: S(p) = T(1) / T(p)
- Eficiencia: E(p) = S(p) / p

| Processos (threads) | Tempo de execucao (s) | Speedup | Eficiencia |
|---:|---:|---:|---:|
| 1  | 32.02 | 1.00 | 100.00% |
| 2  | 24.32 | 1.32 | 65.83% |
| 4  | 16.23 | 1.97 | 49.34% |
| 8  | 11.58 | 2.77 | 34.56% |
| 12 | 10.32 | 3.10 | 25.86% |

## Arquivos dos Graficos

- Planilha Excel com dados e graficos: [graficos/graficos_desempenho.xlsx](graficos/graficos_desempenho.xlsx)
- Imagem do tempo de execucao: [graficos/tempo_execucao.png](graficos/tempo_execucao.png)
- Imagem do speedup: [graficos/speedup.png](graficos/speedup.png)
- Imagem da eficiencia: [graficos/eficiencia.png](graficos/eficiencia.png)

## Grafico 1 - Tempo de Execucao

![Tempo de Execucao](graficos/tempo_execucao.png)

## Grafico 2 - Speedup

![Speedup](graficos/speedup.png)

## Grafico 3 - Eficiencia

![Eficiencia](graficos/eficiencia.png)

