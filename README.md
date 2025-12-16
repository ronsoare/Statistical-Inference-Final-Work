# Estudo de Simulação 

## 📖 Sobre o Projeto
Este repositório contém os códigos e recursos desenvolvidos para disciplina de Inferência Estatística I com o fito de realizar um Estudo de Simulção.

O objetivo deste estudo de simulação é investigar como o tamanho da
amostra influencia os intervalos de confiança de 95% para a média populacional.

## 👨‍🏫 Identificação
**Instituição:** Universidade Federal do Amazonas  
**Disciplina:** Inferência Estatística I  
**Professora:** Camila Pinheiro

**Aluno:** Ronaldo Rodrigues Soares  
**Email:** ronaldo.soares@icomp.ufam.edu.br

---

## 🚀 Como Executar o Projeto

Existem duas formas principais de executar os notebooks deste projeto: **localmente** (em sua própria máquina) ou na **nuvem** (usando Google Colab).

### Opção 1: Execução Local (Recomendado)

Para rodar o projeto localmente, utilizaremos o **Conda** para gerenciamento de ambientes virtuais e o **VS Code** como editor.

#### 1. Pré-requisitos
Certifique-se de ter o **Conda** instalado. Se não tiver, faça o download e instale a versão adequada para seu sistema operacional (recomenda-se o Miniconda por ser mais leve, ou o Anaconda):
* [Download do Conda (Miniconda/Anaconda)](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)

#### 2. Criando o Ambiente Virtual
Abra o seu terminal (ou Anaconda Prompt no Windows) e execute o seguinte comando para criar um ambiente isolado. Substitua `nome_do_ambiente` pelo nome que desejar:

```bash
conda create --name nome_do_ambiente python=3.11
```

#### 3. Ativando o Ambiente
Para começar a usar o ambiente criado, ative-o com o comando:

```bash
conda activate nome_do_ambiente
```

#### 4. Instalando as Bibliotecas
Com o ambiente ativado, instale as dependências necessárias. 
```bash
pip install numpy pandas matplotlib scipy
```

#### 5. Executando no VS Code (Jupyter Notebook)
1. Abra a pasta do projeto no **VS Code**.
2. Abra o arquivo `simulation.ipynb` (Jupyter Notebook) que deseja executar.
3. No canto superior direito da tela do editor, clique no botão para **Selecionar Kernel** (geralmente aparece como "Select Kernel" ou a versão do Python atual).
4. Selecione a opção **Python Environments**.
5. Escolha o ambiente que você criou (`nome_do_ambiente`).
6. Agora você pode rodar as células do notebook.

---

### Opção 2: Google Colab (Nuvem)

Se preferir não instalar nada em sua máquina, você pode usar o Google Colab.

1. Acesse o [Google Colab](https://colab.research.google.com/).
2. No menu, vá em **File (Arquivo) > Upload notebook**.
3. Faça o upload do arquivo `simulation.ipynb` deste repositório.