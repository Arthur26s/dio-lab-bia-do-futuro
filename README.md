----

# 💰 Aufi | Auxiliar de Finanças Pessoais

O **Aufi** é um agente de finanças pessoais desenvolvido para transformar a maneira como você lida com seu dinheiro. Utilizando Inteligência Artificial local, o Aufi analisa seus dados financeiros para ensinar conceitos de economia de forma didática, amigável e totalmente personalizada.

## 🚀 Diferenciais da Solução

Diferente de assistentes genéricos, o Aufi:

  * **IA Local:** Roda através do **Ollama**, garantindo maior privacidade para seus dados financeiros.
  * **Contexto Real:** Utiliza seus arquivos JSON e CSV para criar exemplos práticos baseados na sua realidade.
  * **Foco Educativo:** Não apenas mostra números, mas explica conceitos financeiros como um amigo.
  * **Segurança:** Configurado com *system prompts* que impedem a recomendação direta de investimentos, focando em educação e gestão.

## 🛠️ Tecnologias Utilizadas

  * **Python:** Linguagem base do projeto.
  * **Streamlit:** Interface de chat interativa e moderna.
  * **Ollama (LLM):** Motor de inteligência artificial (Modelo: `gpt-oss:20b-cloud`).
  * **Pandas & JSON:** Manipulação eficiente de bases de dados de transações e perfis.

## 📁 Estrutura de Dados

Para funcionar, o Aufi consome quatro fontes principais de informação:

1.  `perfil_investidor.json`: Metas, patrimônio e tolerância a risco.
2.  `transacoes.csv`: Registro de entradas e saídas recentes.
3.  `historico_atendimento.csv`: Memória de conversas e dúvidas anteriores.
4.  `produtos.json`: Catálogo de conceitos e opções para exemplificação.

## ⚙️ Como Executar

1.  **Certifique-se de ter o Ollama instalado** e o modelo configurado.
2.  **Instale as dependências:**
    ```bash
    pip install streamlit pandas requests
    ```
3.  **Rode a aplicação:**
    ```bash
    streamlit run seu_arquivo.py
    ```

## 🧠 Lógica do Agente (System Prompt)

O Aufi opera sob diretrizes rígidas de segurança e didática:

  * **NUNCA** recomenda investimentos específicos.
  * **SEMPRE** utiliza dados reais do usuário para ilustrar explicações.
  * **ADMITE** quando não possui uma informação específica, oferecendo-se para explicar o conceito teórico por trás.

-----

**Desenvolvido por [Arthur26s](https://www.google.com/search?q=https://github.com/Arthur26s) | Lab DIO - Bia do Futuro**
