# Super Trunfo de Cidades 🏙️ — Desafio Nível 2

Este projeto é a continuação do desafio anterior e implementa a **lógica de comparação entre duas cartas** do jogo Super Trunfo, usando a linguagem C. Aqui, as cartas representam cidades com seus dados populacionais e econômicos.

## 📌 Funcionalidades

- Cadastro de duas cartas contendo:
  - Estado (A–H)
  - Código da Carta (ex: A01)
  - Nome da Cidade
  - População (int)
  - Área em km² (float)
  - PIB em bilhões de reais (float)
  - Número de Pontos Turísticos (int)

- Cálculo automático de:
  - **Densidade Populacional** = População / Área
  - **PIB per Capita** = (PIB * 1.000.000.000) / População

- Comparação de um atributo fixo (ex: **PIB per Capita**)
  - Para **PIB, população, área, PIB per capita**: maior valor vence
  - Para **densidade populacional**: menor valor vence

- Saída clara com o resultado da comparação e os valores das duas cidades.

---

## 🖥️ Compilação e Execução

### Compilar

```bash
gcc super_trunfo_comparacao.c -o super_trunfo
