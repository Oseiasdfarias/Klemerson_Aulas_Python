<p align=center> 
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/> 
<img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white"/> 
<img src="https://img.shields.io/badge/pandas-109989?style=for-the-badge&logo=pandas&logoColor=white"/>
</p>

<p align="center">
  <img height="100px" src="../utils/python.png">
</p>


# Roteiro da Aula 2: Estrutura Básica do Python

## Estrutura básica do Python: Entrada/saída de dados, configurar o python no windows, como instalar bibliotecas no python com pip, usando o jupyter notebook para análise de dados.

**Objetivo da Aula:**  
Proporcionar aos alunos uma introdução prática ao uso do Python, cobrindo desde a configuração inicial até as operações básicas de entrada e saída de dados, além de como utilizar ferramentas importantes como o Jupyter Notebook.  

---

### **1. Abertura (5 min)**  
- Apresentação do instrutor e da proposta da aula.  
- Breve introdução ao Python e sua importância na programação e ciência de dados.  
- Objetivos específicos do encontro:  
  1. Configurar o Python no Windows.  
  2. Usar o pip para instalar bibliotecas.  
  3. Compreender operações básicas de entrada e saída de dados.  
  4. Trabalhar no Jupyter Notebook para análises de dados.  

---

### **2. Configuração do Python no Windows (15 min)**  
**Tópicos abordados:**  
- Baixar o Python no site oficial: [https://www.python.org](https://www.python.org).  
- Explicar a importância de marcar a opção **"Add Python to PATH"** na instalação.  
- Verificar se a instalação foi bem-sucedida:  
  ```bash
  python --version
  pip --version
  ```  
- Configuração do ambiente de desenvolvimento com um editor de texto (VS Code ou outro).  

**Atividade prática:**  
- Os alunos realizam a instalação no próprio computador.  

---

### **3. Instalando bibliotecas com o `pip` (10 min)**  
**Tópicos abordados:**  
- Introdução ao gerenciador de pacotes `pip`.  
- Instalar uma biblioteca simples como exemplo (e.g., `numpy`):  
  ```bash
  pip install numpy
  ```  
- Explicar o comando para verificar bibliotecas instaladas:  
  ```bash
  pip list
  ```  
- Solução de problemas comuns (e.g., atualizações com `pip install --upgrade`).  

**Atividade prática:**  
- Cada aluno instala uma biblioteca como `matplotlib` ou `pandas`.  

---

### **4. Entrada e Saída de Dados no Python (20 min)**  
**Tópicos abordados:**  
- Uso de `input()` para entrada de dados do usuário:  
  ```python
  nome = input("Digite seu nome: ")
  print(f"Olá, {nome}!")
  ```  
- Formas de saída de dados:  
  - `print()`.  
  - Formatação de strings (f-strings, `.format()`).  

**Exemplos práticos:**  
- Criar um pequeno script que solicita ao usuário nome, idade e calcula o ano de nascimento.  

**Atividade prática:**  
- Alunos desenvolvem um programa simples de calculadora que aceita dois números e realiza operações básicas.  

---

### **5. Usando o Jupyter Notebook (20 min)**  
**Tópicos abordados:**  
- O que é o Jupyter Notebook e sua importância para análise de dados.  
- Instalação do Jupyter:  
  ```bash
  pip install notebook
  ```  
- Como iniciar um notebook:  
  ```bash
  jupyter notebook
  ```  
- Explicação básica das células:  
  - Código.  
  - Markdown.  
- Demonstração prática:  
  - Criar um notebook.  
  - Importar bibliotecas (`numpy`, `pandas`).  
  - Fazer uma operação simples (e.g., carregar e exibir um pequeno DataFrame).  

**Atividade prática:**  
- Cada aluno cria um notebook, insere uma célula Markdown com uma breve descrição e uma célula de código para fazer uma operação simples com listas ou arrays.  

---

### **6. Fechamento e Dúvidas (10 min)**  
- Recapitulação dos tópicos abordados.  
- Resumo das atividades realizadas.  
- Responder dúvidas.  
- Indicação de materiais para estudo adicional:  
  - [Documentação oficial do Python](https://docs.python.org/3/).  
  - Tutoriais de Jupyter Notebook no [site oficial](https://jupyter.org/).  

---

### **Carga Horária Total:** 1h20min  

**Observação:** Personalize o ritmo e as atividades conforme o nível de conhecimento da turma. 😊  