# Teste Prático Afya RAG 🚀📚 

---

## 💡 Sobre o Projeto

Este projeto foi desenvolvido como parte de um teste prático para a empresa **Afya**, com o objetivo de demonstrar habilidades em técnicas de **RAG (Retrieval-Augmented Generation)** utilizando a biblioteca **LangChain** e o modelo **OpenAI GPT-4o-mini**. O objetivo é realizar a extração de texto de um arquivo PDF e responder perguntas com base nas informações contidas no documento.

---

## 📝 Instruções do Teste

O teste consiste em:  
1. Ler um arquivo PDF com informações sobre heróis da Marvel.  
2. Extrair o texto contido no PDF.  
3. Gerar **embeddings** a partir do texto extraído.  
4. Utilizar a API da **OpenAI** para responder perguntas com base no conteúdo do PDF.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.10+**  
- **LangChain** para criação do pipeline de RAG.  
- **OpenAI API** para geração de respostas.  
- **FAISS** para criação de índices vetoriais.  
- **PyPDF2** para extração de texto do PDF.  
- **CustomTkinter** para a interface gráfica.  
- **dotenv** para carregamento de variáveis de ambiente.  
- **PIL** para manipulação de imagens.

---

## 🗃️ Estrutura do Projeto

📂 teste-pratico/<br>
├── 📂 data/ <br>
│ └── herois_marvel.pdf <br>
├── 📂 venv/ # Ambiente virtual (ignorado pelo Git) <br>
├── .env # Arquivo com as chaves da API (ignorado pelo Git) <br>
├── main.py # Código principal <br>
├── marvel_logo.png # Logo da interface gráfica <br>
├── README.md # Documentação do projeto <br>
├── requirements.txt # Dependências do projeto <br>
└── .gitignore # Ignora arquivos desnecessários<br>

---


---

## 🖥️ Como Rodar o Projeto Localmente

1. Clone o repositório:
```bash
git clone https://github.com/estanislauisa/afya-teste-pratico-rag.git
cd afya-teste-pratico-rag
```

2. Crie e ative um ambiente virtual:
```bash
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

4. Crie o arquivo `.env` com sua chave da OpenAI:
```bash
OPENAI_API_KEY=your_api_key
```

5. Execute o projeto:
```bash
python main.py
```

A interface gráfica será aberta automaticamente.

---

## 💬 Exemplos de Perguntas para o RAG

Aqui estão algumas perguntas que você pode fazer ao assistente:

- Qual é a origem do Homem de Ferro?
- Quem é o vilão principal do Capitão América?
- Qual é a relação de Thor com Loki?
- O que motivou o Homem-Aranha a se tornar um herói?
- Quais poderes o Homem-Aranha possui?
- Como o Capitão América adquiriu seus poderes?
- Quem são os principais vilões enfrentados pelo Homem-Aranha?
- Qual é o lema do Homem-Aranha?
- Quais são as principais características do Thor?
- Quais são os conflitos internos do Tony Stark?

---

## 📝 Notas Importantes

- O projeto utiliza a API da OpenAI para responder perguntas, portanto, é necessário ter uma chave ativa e funcional.  
- A interface gráfica utiliza o CustomTkinter, garantindo uma experiência amigável e fácil de usar.

---


## 💬 Agradecimentos

Agradeço a oportunidade de participar deste desafio! Foi uma experiência enriquecedora e divertida. 😄

Atenciosamente,  
**Isadora Estanislau**
