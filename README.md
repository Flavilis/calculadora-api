Calculadora API com FastAPI

Projeto Avaliativo desenvolvido para a disciplina **Programação de Sistemas Distribuídos** da **Universidade dos Grandes Lagos - UNILAGO**, sob supervisão do **Professor [Gleydes Oliveira](https://github.com/gleydes)**.

## 🚀 Como Rodar o Projeto
1. Clone o repositório.
2. Crie o ambiente virtual: `python -m venv venv`.
3. Ative o venv: `venv\Scripts\activate` (Windows) ou `source venv/bin/activate` (Linux/Mac).
4. Instale as dependências: `pip install -r requirements.txt`.
5. Inicie o servidor: `uvicorn main:app --reload`.

## 📌 Endpoints
- `GET /`: Boas-vindas.
- `POST /somar`: Realiza a soma de dois números.
- `GET /docs`: Documentação Swagger interativa.
