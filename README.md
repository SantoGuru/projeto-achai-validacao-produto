# Análise de Validação de Produto: Projeto AchAí

## 1. Contexto do Projeto

Este projeto de análise de dados foi desenvolvido como parte da disciplina de Projetos Intercursos e serve como validação para a solução "AchAí". O "AchAí" é um sistema de achados e perdidos proposto para a comunidade da Universidade de Fortaleza (Unifor) criado a partir da disciplina de Intercurso do Curso de Análise e Desenvolvimento de Sistemas (ADS), que utiliza QR Codes e formulários online para agilizar o processo de devolução de itens. O público-alvo inclui alunos, professores e funcionários.

## 2. Objetivo da Análise

O objetivo deste notebook é realizar uma Análise Exploratória de Dados (EDA) em cima dos dados coletados de uma pesquisa de validação com 48 membros da comunidade acadêmica. A análise visa responder a duas perguntas centrais:
1.  **Validação do Problema:** Existe uma necessidade real e percebida de melhoria no serviço de achados e perdidos atual?
2.  **Validação da Solução:** A solução digital proposta ("AchAí") seria bem recebida e utilizada pela comunidade?

## 3. Ferramentas e Metodologia

* **Linguagem:** Python
* **Bibliotecas Principais:** Pandas (para manipulação de dados), Matplotlib e Seaborn (para visualização).
* **Metodologia:** O notebook segue um fluxo de trabalho padrão de EDA, incluindo limpeza e pré-processamento de dados, análise de perfil demográfico, análise descritiva e cruzamento de variáveis para extração de insights aprofundados.

## 4. Principais Insights Encontrados

A análise dos dados forneceu evidências quantitativas que validam fortemente o projeto:

* ✅ **Problema Validado:** **65%** (`31 de 48`) dos respondentes já perderam algum item na universidade. A principal dificuldade apontada com o serviço atual é a **"Falta de informação"**.

* 👍 **Forte Aceitação da Solução:** A solução "AchAí" foi muito bem recebida, com uma nota média de **4.6 de 5** para utilidade e **4.3 de 5** para a probabilidade de uso.

* ⭐ **Funcionalidades Mais Desejadas:** As funcionalidades mais importantes para os futuros usuários são: **Upload de foto do item**, **Notificação quando um item semelhante for encontrado** e uma **Consulta pública dos itens cadastrados**.

* 📍 **Direcionamento Estratégico:** Os melhores locais para a implantação dos QR Codes, segundo os próprios usuários, são os **Blocos acadêmicos (Salas de Aula)**, o **Centro de Convivência (CC)** e a **Biblioteca**.

## 5. Como Executar o Projeto

1.  Clone este repositório.
2.  Certifique-se de ter o Python e as bibliotecas listadas acima instaladas.
3.  O arquivo de dados utilizado é o `dados.csv`.
4.  Abra o notebook `pesquisa_de_validacao.ipynb` em um ambiente como Jupyter Notebook ou Google Colab e execute as células.