Perfeito! Aqui está um **README.md** completo, profissional e bem estruturado para o seu repositório:

---

# Metaheurística: Algoritmo Genético aplicado ao Problema da Mochila

Este repositório contém o código, dados, resultados e artigo acadêmico relacionados ao estudo e aplicação de um **Algoritmo Genético (AG)** para resolução do **Problema da Mochila 0-1** com 100 itens.

---

## 📂 Estrutura do Repositório

```
Metaheuristica-artigo/
├── codigo/
│   ├── algoritmo_genetico.py   # Código principal com o AG
│   ├── knapsack-instance.txt   # Arquivo de entrada com os pesos e valores
│   ├── figs/
│   │   ├── boxplot_valores.png        # Gráfico de distribuição das soluções
│   │   ├── evolucao_melhor_fitness.png# Gráfico da evolução média
│   │   ├── tabela_resultados.tex      # Tabela LaTeX com resultados individuais
│   │   └── tabela_metricas.tex        # Tabela LaTeX com métricas finais
│   └── saida_execucoes.txt     # Log completo da execução
├── main.tex                    # Artigo acadêmico em LaTeX
└── README.md                   # Este arquivo
```

---

## 📝 Descrição do Projeto

O projeto consiste em:

✅ Implementação de um **Algoritmo Genético** com operadores clássicos (seleção por torneio, cruzamento por máscara, mutação bit flip, elitismo).
✅ Modelagem do **Problema da Mochila 0-1** com 100 itens e capacidade máxima de 1550 unidades de peso.
✅ Geração automática de:

* Tabelas `.tex` com os resultados das execuções.
* Gráficos `.png` com o boxplot das soluções e a evolução média da aptidão.
  ✅ Artigo acadêmico escrito em **LaTeX**, com apêndice contendo o código e resultados.

---

## ⚙️ Como Executar

### Pré-requisitos

* Python 3.8+
* Bibliotecas:

  * `numpy`
  * `matplotlib`

```bash
pip install numpy matplotlib
```

### Passos

1. Clone o repositório:

```bash
git clone https://github.com/christian-amarildo/Metaheuristica-artigo.git
cd Metaheuristica-artigo/codigo
```

2. Execute o código:

```bash
python algoritmo_genetico.py
```

3. O script irá:

✅ Realizar **20 execuções** do AG, com **100 gerações** cada.
✅ Salvar gráficos e tabelas na pasta `figs/`.
✅ Gerar `saida_execucoes.txt` com o log completo.

4. Compile o artigo em LaTeX:

* Abra `main.tex` no Overleaf ou use `pdflatex`:

```bash
pdflatex main.tex
```

O artigo incluirá automaticamente os gráficos e as tabelas geradas.

---

## 📊 Exemplos de Saídas

### Gráficos gerados:

* **Boxplot:** `figs/boxplot_valores.png`
* **Evolução média:** `figs/evolucao_melhor_fitness.png`

### Tabelas LaTeX geradas:

* `figs/tabela_resultados.tex`
* `figs/tabela_metricas.tex`

### Log de execução:

* `saida_execucoes.txt`

---

## 🧮 Parâmetros do Algoritmo

| Parâmetro            | Valor     |
| -------------------- | --------- |
| Tamanho da Mochila   | 100 itens |
| Capacidade Máxima    | 1550      |
| Tamanho da População | 200       |
| Taxa de Mutação      | 5%        |
| Número de Gerações   | 100       |
| Número de Execuções  | 20        |

---

## 🏆 Resultados Obtidos

Resultados típicos para as execuções incluem:

* **Média** dos valores: \~2000
* **Desvio padrão**: \~10
* **Melhor valor**: \~2078
* **Pior valor**: \~1975

---

## 📚 Artigo

O artigo `main.tex` segue o **template SBC** e contém:

* Introdução ao Problema da Mochila.
* Modelagem matemática.
* Descrição completa da implementação.
* Resultados e análise estatística.
* Conclusão e sugestões para trabalhos futuros.
* Apêndice com o código-fonte.

---

## 🖇️ Recursos e Links

* 📖 [Problema da Mochila](https://en.wikipedia.org/wiki/Knapsack_problem)
* 📚 [Algoritmos Genéticos](https://pt.wikipedia.org/wiki/Algoritmo_genético)
* 🎓 Template da SBC: [https://github.com/sbc-org/sbc-template](https://github.com/sbc-org/sbc-template)

---

## 👥 Autores

* David Galhego
* Christian Amarildo
* Daniel Naiff

Instituto de Ciências Exatas e Naturais — Universidade Federal do Pará (UFPA)

---

## ✅ Licença

Este projeto é de uso acadêmico e educacional.
Sinta-se livre para estudar, modificar e reutilizar com os devidos créditos.

---

## 💡 Sugestões para Trabalhos Futuros

* Comparação com outras metaheurísticas (Simulated Annealing, GRASP, etc.).
* Exploração de diferentes estratégias de seleção e mutação.
* Aplicação do AG a variantes do problema da mochila (multiobjetivo, multidimensional).

---

Se quiser posso também criar o **`Makefile`** ou um **script `run_all.sh`** para automatizar a execução e a compilação do artigo. Quer?
Se sim, me diga qual sistema operacional você usa (Linux/Mac/Windows).
