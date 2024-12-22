<p align=center> 
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/> 
<img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white"/> 
<img src="https://img.shields.io/badge/pandas-109989?style=for-the-badge&logo=pandas&logoColor=white"/>
</p>

<p align="center">
  <img height="100px" src="../utils/python.png">
</p>


# Roteiro da Aula 1: Introdução ao Python e Visão Geral

## Objetivo da Aula
Apresentar o ambiente de desenvolvimento Python, configurar as ferramentas necessárias, e fornecer uma visão geral do uso de Python na ciência de dados. Ao final, os alunos devem estar com o ambiente pronto e compreender os principais conceitos introdutórios.

---

## Estrutura da Aula (Duração: 1 hora)

### **1. Abertura (5 minutos)**
- Apresentação do instrutor e boas-vindas.
- Objetivo da aula e como o Python será utilizado ao longo do curso.

### **2. Configuração do Ambiente (20 minutos)**
- **Passo 1:** Instalação do Python:  
  - Demonstração no site oficial ([https://www.python.org](https://www.python.org)) para download.
  - Configuração da variável de ambiente (caso necessário).
- **Passo 2:** Instalação e configuração de uma IDE:  
  - Opção principal: VS Code (extensão Python).  
  - Alternativa: Jupyter Notebook via Anaconda.
- **Passo 3:** Teste do ambiente:  
  - Execução de um código simples: `print("Hello, Python!")`.

### **3. Introdução ao Python (20 minutos)**
- Estrutura básica de um programa Python.
  - O que é um interpretador e como funciona.
  - Demonstração de scripts e execução pelo terminal.
- Tipos de dados básicos:  
  - Números (inteiros, floats).  
  - Strings (operações e boas práticas).
  - Booleanos (True, False)


### **4. Encerramento (5 minutos)**
- Recapitulação dos principais pontos abordados.
- Resposta a dúvidas.
- Tarefa de casa:  
  - Instalar as ferramentas configuradas na aula.
  - Escrever e rodar códigos simples para praticar.

---

## Materiais de Apoio
- Documentação oficial do Python: [https://docs.python.org](https://docs.python.org)
- Guia para instalação de IDEs: [https://code.visualstudio.com/docs/python/python-tutorial](https://code.visualstudio.com/docs/python/python-tutorial)
- Links para as bibliotecas:
  - Pandas: [https://pandas.pydata.org](https://pandas.pydata.org)
  - NumPy: [https://numpy.org](https://numpy.org)
  - Matplotlib: [https://matplotlib.org](https://matplotlib.org)

---

**Próxima Aula:** Estrutura básica do Python: Entrada/saída de dados, variáveis e operações matemáticas e lógicas. Introdução ao GitHub.


---


# Questões

1. **Operações Matemáticas**  
   Escreva um programa que:  
   - Declare duas variáveis `a = 50.0` e `b = 25.0`.
   - Calcule a soma, subtração, multiplicação, divisão e exponenciação (elevar `a` ao valor de `b`) e exiba os resultados no console usando a função `print()`.

2. **Formatação de Strings com `f-strings`**  
   Altere o código para criar uma variável `profissao` com o valor `"Engenheiro de Dados"` e use-a para modificar a frase para:  
   `"Olá, meu nome é Oseias Farias e minha profissão é Engenheiro de Dados."`

3. **Concatenação de Strings**  
   Crie um código que concatene três variáveis `nome`, `sobrenome` e `idade` para formar a frase:  
   `"Meu nome é <nome> <sobrenome> e tenho <idade> anos."`  
   Use apenas a concatenação `+`.

4. **Uso de `.format()`**  
   Altere a construção da frase usando o método `.format()` para criar a mensagem:  
   `"Bem-vindo(a), Oseias Farias! Você está na aula de Python."`


5. **Formatando Números em Strings**  
   Use `f-strings` para exibir os números `n1` e `n2` da seguinte forma:  
   `"O primeiro número é 20.0 e o segundo número é 30.0."`  
   Substitua os valores pela soma, subtração, multiplicação e divisão em novas frases.


6.  **Faça o cálculo de uma função**  \
    Faça o falculo da seguinte função
   `funcao = (A + B) / C * D` onde `A = 23; B = 32; C = 23.25, D = 43.75` 
    

---


### **GABARITO DAS QUESTÕES**

1. **Operações Matemáticas**  
   - Soma: 75.0  
   - Subtração: 25.0  
   - Multiplicação: 1250.0  
   - Divisão: 2.0  
   - Exponenciação: \( ~3.355 \times 10^{42} \) (ou aproximadamente esse valor, pois 50 elevado a 25 é muito grande).

2. **Formatação de Strings com `f-strings`**  
   Resultado:  
   `"Olá, meu nome é Oseias Farias e minha profissão é Engenheiro de Dados."`

3. **Concatenação de Strings**  
   Resultado:  
   `"Meu nome é Oseias Farias e tenho 30 anos."`

4. **Uso de `.format()`**  
   Resultado:  
   `"Bem-vindo(a), Oseias Farias! Você está na aula de Python."`

5. **Formatando Números em Strings**  
   Resultados:
   - `"O primeiro número é 20.0 e o segundo número é 30.0."`
   - `"A soma dos números é 50.0."`
   - `"A subtração dos números é -10.0."`
   - `"A multiplicação dos números é 600.0."`
   - `"A divisão dos números é 0.6666666666666666."`

6. **Cálculo da Função**  
   Função:  
   $$
   \text{função} = \frac{(A + B)}{C} \times D
   $$
   Onde:  
   $A = 23 , B = 32 , C = 23.25 , D = 43.75$  

   Resultado:  
   $\text{função} = 103.2258$ (aproximadamente).