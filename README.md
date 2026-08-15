# Inteligencia-Artificial---UMC
Repositorio para entregas de atividades do professor Fabiano Bezerra Menegidio na materia de Inteligencia Artificial do 6° Periodo da faculdade UMC(Universidade de Mogi das Cruzes)

---

## 📁 Estrutura do Repositório

```text
.
├── README.md
├── Exercícios_Python_AntonioSaurin_6D.ipynb   # Notebook com lista prática de nivelamento / algoritmos
```
---

## 📚 Conteúdo Programático & Arquivos

### 1. `Exercícios_Python_AntonioSaurin_6D.ipynb`
Notebook desenvolvido no Google Colab contendo a resolução comentada de 50 exercícios de lógica de programação, algoritmos clássicos, estruturas de dados e manipulação numérica em Python.

#### Tópicos abordados no notebook:
- **Sintaxe Básica, Entrada/Saída & Tipos Primitivos:** Operações aritméticas, manipulação de inteiros (`int`), ponto flutuante (`float`) e formatação com `f-strings` (Exercícios 1 ao 5, 43, 49).
- **Estruturas Condicionais & Lógica Booleana:** Validação de par/ímpar, números primos, classificação de valores e validação formal de CPF com dígitos verificadores (Exercícios 6, 7, 18, 24, 25, 42, 45).
- **Estruturas de Repetição & Séries Numéricas:** Laços `for` e `while`, cálculo de Fatorial (iterativo e recursivo), Sequência de Fibonacci e FizzBuzz (Exercícios 5, 6, 9, 10, 29, 35, 37, 44).
- **Manipulação de Coleções (Listas, Tuplas, Dicionários, Sets):** Ordenação, busca, remoção de duplicatas com conjuntos, cálculo de estatísticas e frequências de ocorrência (Exercícios 11, 13, 14, 15, 17, 40, 41, 47, 48, 50).
- **Manipulação de Strings & Criptografia:** Inversão de texto, detecção de palíndromos e anagramas, contagem de caracteres/vogais/palavras e implementação de cifragem/decifragem com a **Cifra de César** (Exercícios 8, 12, 16, 22, 23, 27, 33, 34, 38, 50).
- **Algoritmos Clássicos e Jogos:** Implementação de busca binária, ordenação por bolha (*Bubble Sort*), ordenação por inserção (*Insertion Sort*), jogo de adivinhação, jogo de dados, jogo da forca e jogo da velha completo (Exercícios 19, 21, 30, 31, 32, 39).
- **Matrizes, Estatística & Visualização de Dados:** Operações com matrizes transpostas utilizando `numpy`, estatística descritiva (média e desvio padrão populacional) com `statistics` e geração de gráficos com `matplotlib` (Exercícios 20, 28, 46).

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **Linguagem:** [Python 3.x](https://www.python.org/)
- **Ambiente de Desenvolvimento:** [Google Colaboratory](https://colab.research.google.com/) / Jupyter Notebook
- **Bibliotecas Padrão:** `math`, `random`, `string`, `statistics`, `os`
- **Bibliotecas Externas:**
  - `numpy` (Manipulação e álgebra linear básica com arrays multidimensionais)
  - `matplotlib` (Geração de gráficos e visualização de dados)

---

## 🚀 Como Executar os Notebooks

### Opção 1: Diretamente no Google Colab
1. Abra o [Google Colab](https://colab.research.google.com/).
2. Vá em **Arquivo** > **Abrir notebook** > selecione a aba **GitHub**.
3. Insira o link deste repositório e selecione o arquivo `.ipynb` desejado.

### Opção 2: Localmente (via Jupyter Notebook / VS Code)
1. Clone o repositório:
   ```bash
   git clone https://github.com/<seu-usuario>/<nome-do-repositorio>.git
   cd <nome-do-repositorio>
   ```
2. Crie e ative um ambiente virtual (recomendado):
   ```bash
   python -m venv venv
   # No Linux/macOS:
   source venv/bin/activate
   # No Windows:
   venv\Scripts\activate
   ```
3. Instale as dependências necessárias:
   ```bash
   pip install numpy matplotlib jupyter
   ```
4. Inicie o Jupyter:
   ```bash
   jupyter notebook
   ```
