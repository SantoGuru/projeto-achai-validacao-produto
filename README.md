# Análise de Validação de Produto: Projeto AchAí

## 1. Contexto do Projeto

Este projeto de análise de dados foi desenvolvido como parte da disciplina de Projetos Intercursos e serve como validação para a solução "AchAí". O "AchAí" é um sistema de achados e perdidos proposto para a comunidade da Universidade de Fortaleza (Unifor) criado a partir da disciplina de Intercurso do Curso de Análise e Desenvolvimento de Sistemas (ADS), que utiliza QR Codes e formulários online para agilizar o processo de devolução de itens. O público-alvo inclui alunos, professores e funcionários.

## 2. Objetivo da Análise

O objetivo deste notebook é realizar uma Análise Exploratória de Dados (EDA) em cima dos dados coletados de uma pesquisa de validação com 48 membros da comunidade acadêmica. A análise visa responder a duas perguntas centrais:
1.  **Validação do Problema:** Existe uma necessidade real e percebida de melhoria no serviço de achados e perdidos atual?
2.  **Validação da Solução:** A solução digital proposta ("AchAí") seria bem recebida e utilizada pela comunidade?

### 3. Ferramentas e Metodologia

* **Linguagem:** **Python 3**, executado em um ambiente Jupyter Notebook. A escolha se deu pela sua simplicidade, legibilidade e pelo robusto ecossistema de bibliotecas para análise de dados.

* **Bibliotecas Principais:**
    * **Pandas:** Peça central do projeto, utilizada para a importação dos dados do arquivo `.csv`, bem como para toda a etapa de limpeza, transformação e estruturação do DataFrame. Foi fundamental para a manipulação das respostas (como a consolidação de colunas de alunos/colaboradores) e para a preparação dos dados para a visualização.
    * **Matplotlib & Seaborn:** Utilizadas em conjunto para a criação dos gráficos. O **Seaborn** permitiu a criação de visualizações estatísticas complexas (como os `countplot`) com maior rapidez e um visual mais limpo, enquanto o **Matplotlib** foi usado para personalizações finas nos gráficos, como títulos e rótulos.
    * **Collections (Counter):** A classe `Counter` foi empregada de forma estratégica para realizar a contagem de frequência nas respostas de múltipla escolha (dificuldades e funcionalidades).

* **Metodologia:** O notebook segue um fluxo de trabalho padrão de EDA, incluindo limpeza e pré-processamento de dados, análise de perfil, análise descritiva e cruzamento de variáveis para extração de insights aprofundados.

## 4. Principais Insights Encontrados

A análise dos dados forneceu evidências quantitativas que validam fortemente o projeto:

* ✅ **Problema Validado:** **65%** (`31 de 48`) dos respondentes já perderam algum item na universidade. A principal dificuldade apontada com o serviço atual é a **"Falta de informação"**.

<img width=55% height="572" alt="image" src="https://github.com/user-attachments/assets/d4f8fd15-8949-46ac-85bc-72954d560f46" />
<img width=55% height="711" alt="image" src="https://github.com/user-attachments/assets/72cbc0ea-7e90-4c2e-8bfe-ac6d959d741c" />

* 👍 **Forte Aceitação da Solução:** A solução "AchAí" foi muito bem recebida, com uma nota média de **4.6 de 5** para utilidade e **4.3 de 5** para a probabilidade de uso.

* ⭐ **Funcionalidades Mais Desejadas:** As funcionalidades mais importantes para os futuros usuários são: **Upload de foto do item**, **Notificação quando um item semelhante for encontrado** e uma **Consulta pública dos itens cadastrados**.

* 📍 **Direcionamento Estratégico:** Os melhores locais para a implantação dos QR Codes, segundo os próprios usuários, são os **Blocos acadêmicos (Salas de Aula)**, o **Centro de Convivência (CC)** e a **Biblioteca**.



## 5. Como Executar o Projeto

1.  Clone este repositório.
2.  Certifique-se de ter o Python e as bibliotecas listadas acima instaladas.
3.  O arquivo de dados utilizado é o `dados.csv`.
4.  Abra o notebook `pesquisa_de_validacao.ipynb` em um ambiente como Jupyter Notebook ou Google Colab e execute as células.
