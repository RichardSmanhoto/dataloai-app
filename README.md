# 🧠 DataloAI

**DataloAI** é uma plataforma inteligente de análise de dados que transforma informações brutas em gráficos interativos, relatórios e insights com apoio de inteligência artificial. Conecte sua base de dados (como Shopify, VTex ou arquivos CSV), e deixe que a IA gere visualizações e análises automaticamente para você.

---

## 🚀 Funcionalidades

- 📊 Geração automática de gráficos a partir de dados conectados  
- 💬 Interação via linguagem natural: "Mostre as vendas por produto"  
- 🛒 Suporte a dados de e-commerce (vendas, produtos, clientes)  
- 🌐 Interface web simples com Streamlit  
- 🤖 IA integrada com OpenAI para gerar análises  

---

## 📁 Estrutura do Projeto

```text
dataloai/
├── src/               # Código-fonte principal
├── data/              # Dados simulados (CSV, JSON etc.)
├── notebooks/         # Prototipações e testes
├── requirements.txt   # Bibliotecas necessárias
└── README.md          # Este arquivo
```

---

## ⚙️ Como rodar localmente

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/dataloai.git
cd dataloai
```

2. Crie um ambiente virtual:

```bash
python -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate no Windows
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Execute a aplicação:

```bash
streamlit run src/app.py
```

---

## 🔐 API Key da OpenAI

Crie um arquivo `.env` com sua chave da OpenAI:

```env
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxx
```
