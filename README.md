# Google ADK Project 🤖⚡

> Projeto para desenvolvimento, experimentação e implantação de agentes de IA autônomos e sistemas multiagentes utilizando o **Google Agent Development Kit (ADK)** e os modelos Gemini.

---

## 📋 Sobre o Projeto

Este repositório contém a implementação de agentes de inteligência artificial construídos com o **Google ADK**. A proposta do projeto é explorar arquiteturas baseadas em agentes para:

* **Orquestração Multiagente:** Criação de agentes especializados que colaboram de forma autônoma ou hierárquica.
* **Uso de Ferramentas (Tool Use & Function Calling):** Integração de agentes com APIs externas, bancos de dados e serviços do ecossistema Google.
* **Gerenciamento de Memória e Estado:** Persistência de contexto e memória de longo/curto prazo entre interações.
* **Integração com Gemini:** Utilização dos modelos da família Gemini como motor de raciocínio para os agentes.

---

## 🛠️ Tecnologias e SDKs

* **[Google ADK (Agent Development Kit)](https://github.com/google/adk):** Framework principal para orquestração de agentes.
* **Google GenAI SDK / Gemini API:** Modelos de linguagem e raciocínio.
* **Python / TypeScript:** (Altere para a linguagem principal utilizada no seu projeto).
* **Google Cloud Platform (GCP):** Infraestrutura e serviços de suporte (opcional).

---

## ⚙️ Pré-requisitos

Antes de iniciar, certifique-se de possuir:

* **Python 3.10+** ou **Node.js 18+** instalado.
* Uma conta no **Google AI Studio** ou **Google Cloud Platform** com acesso à **Gemini API**.
* Uma chave de API configurada (`GEMINI_API_KEY`).

---

## 🚀 Como Executar Localmente

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/martinezrafael/google-adk-project.git](https://github.com/martinezrafael/google-adk-project.git)
   cd google-adk-project

```

2. **Crie e ative um ambiente virtual (se usar Python):**
```bash
python -m venv .venv
source .venv/bin/activate  # No Windows: .venv\Scripts\activate

```


3. **Instale as dependências:**
```bash
pip install -r requirements.txt
# Ou se for Node.js:
# npm install

```


4. **Configure as Variáveis de Ambiente:**
Crie um arquivo `.env` na raiz do projeto contendo:
```env
GEMINI_API_KEY=sua_chave_api_aqui

```


5. **Execute o agente principal:**
```bash
python main.py

```



---

## 📂 Estrutura do Projeto

```text
google-adk-project/
├── agents/             # Definição e lógica dos agentes ADK
├── tools/              # Ferramentas e integrações (APIs, scripts, etc.)
├── memory/             # Gerenciamento de contexto e memória
├── .env.example        # Modelo de variáveis de ambiente
├── requirements.txt    # Dependências do projeto
└── main.py             # Ponto de entrada / execução dos agentes

```

---

## 🤝 Contribuições

Sinta-se à vontade para abrir *Issues* ou enviar *Pull Requests* com melhorias para este projeto!

---

## 📝 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo `LICENSE` para mais detalhes.

---

*Desenvolvido por [Rafael Molina Martinez*](https://github.com/martinezrafael)

```

```
