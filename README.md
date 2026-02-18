# Projeto Lógico de Banco de Dados: E-commerce 🛒

Este projeto faz parte do desafio final de Modelagem de Dados do curso **Excel e Power BI Dashboards 2026**, realizado na plataforma **[DIO](https://www.dio.me/)** sob o patrocínio e bolsa de estudos da **[Klabin](https://www.klabin.com.br/)**.

**Desenvolvedor:** [Fred Cavalheiro]

**Auxílio Técnico:** Gemini AI (Colaborador de análise e suporte)

---

## 💡 Sobre o Projeto e Desafios de Implementação

Este repositório apresenta a solução completa para um sistema de banco de dados de E-commerce. Diferente da abordagem convencional, este projeto exigiu a superação de diversas barreiras técnicas, detalhadas abaixo:

### 🛠️ Solução Criativa e Adaptação de Hardware
Devido ao fato de estar utilizando um **computador emprestado** que não possui suporte para a instalação de softwares pesados como o **MySQL Workbench**, optei por uma solução inteiramente baseada em nuvem:
* **Ambiente de Desenvolvimento:** [Google Colab](https://colab.research.google.com/)
* **Tecnologia:** Linguagem **SQL** executada via **Python** com as bibliotecas `mysql-connector-python` e `Pandas` (utilizada para o tratamento dos dados e para possibilitar a visualização dos resultados das queries em formato de tabelas organizadas).
* **Proatividade:** Essa escolha garantiu que o desafio fosse entregue dentro dos prazos, validando a lógica e a integridade referencial através de scripts funcionais, mesmo sem a ferramenta visual padrão.

### 📊 Representação Visual (Diagrama ERD)
Para permitir que a professora e outros desenvolvedores visualizem a estrutura das **12 tabelas** criadas, utilizei a ferramenta **[dbdiagram.io](https://dbdiagram.io/)**. 

* **Contorno Técnico:** Como a ferramenta exige login para certas funções e utiliza a linguagem **DBML**, realizei a conversão manual dos scripts SQL para este formato, garantindo a geração correta das tabelas e seus relacionamentos (Primary Keys e Foreign Keys).
* **Entregas Visuais:** Devido às restrições de exportação da plataforma (que exigem conta), o diagrama foi capturado via **print** e o código fonte de backup salvo em arquivo de texto, ambos disponíveis neste repositório.

---

## 🏗️ Estrutura do Banco de Dados

O projeto contempla os seguintes refinamentos de negócio solicitados no desafio:
* **Tipos de Clientes (PF/PJ):** Diferenciação lógica para CPF e CNPJ.
* **Gestão de Pagamentos:** Suporte para múltiplos métodos de pagamento por cliente.
* **Logística de Entrega:** Inclusão de status de entrega e código de rastreamento (tracking).
* **Relacionamentos Complexos:** Tabelas de ligação (N:M) para produtos, fornecedores e estoques.

---

## 📂 Arquivos no Repositório (Acesse os arquivos abaixo)

| Arquivo | Descrição |
| :--- | :--- |
| 📄 [Projeto_Logico_Ecommerce_SQL.ipynb](./Projeto_Logico_Ecommerce_SQL.ipynb) | Notebook principal com o código SQL/Python. |
| 🖼️ [Visualização do Diagrama (Print)](./diagrama_ecommerce.png) | Print da modelagem visual das tabelas. |
| 📝 [Código Fonte DBML (Texto)](./projeto_ecommerce.dbml.txt) | Código fonte DBML usado no diagrama visual. |

---

## 🔗 Ferramentas Utilizadas
* [Google Colab](https://colab.research.google.com/) - Execução do Banco de Dados.
* [MySQL](https://www.mysql.com/) - Sistema de Gerenciamento de Banco de Dados (SGBD).
* [MySQL Connector/Python](https://dev.mysql.com/doc/connector-python/en/) - Driver oficial da Oracle para integração entre Python e MySQL.
* [Pandas](https://pandas.pydata.org/) - Visualização e Manipulação de Dados.
* [dbdiagram.io](https://dbdiagram.io/) - Modelagem Visual.
* [GitHub](https://github.com/) - Hospedagem e Documentação.
* [DIO](https://www.dio.me/) & [Klabin](https://www.klabin.com.br/) - Apoio educacional e patrocínio.

---

> "A falta de uma ferramenta instalada não impediu a execução da lógica. A adaptabilidade é o que torna o desenvolvedor resiliente."
