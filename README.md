##Calculadora API com FastAPI
Projeto avaliativo desenvolvido para a disciplina Programação de Sistemas Distribuídos da Universidade dos Grandes Lagos – UNILAGO, sob supervisão do Professor Gleydes Oliveira.

##Como rodar o projeto
Para executar o projeto, primeiro é necessário clonar o repositório e entrar na pasta correspondente. Em seguida, crie um ambiente virtual com o comando python -m venv venv. Depois, ative o ambiente: no Windows utilize venv\Scripts\activate e no Linux ou Mac utilize source venv/bin/activate. Com o ambiente ativo, instale as dependências com pip install -r requirements.txt. Finalmente, inicie o servidor com uvicorn main:app --reload. O servidor ficará disponível em http://127.0.0.1:8000/.

##Endpoints disponíveis
A aplicação possui os seguintes endpoints:

GET / : retorna uma mensagem de boas-vindas.

POST /somar : realiza a soma de dois números.

POST /subtrair : realiza a subtração de dois números.

POST /multiplicar : realiza a multiplicação de dois números.

POST /dividir : realiza a divisão de dois números, com tratamento para divisão por zero.

POST /raiz : calcula a raiz n-ésima de um número.

POST /potencia : calcula a potência de um número.

GET /calcular : recebe parâmetros pela URL e executa a operação escolhida. Exemplo: http://127.0.0.1:8000/calcular?numero1=10&numero2=5&operacao=soma.

##Documentação
O FastAPI gera automaticamente documentação interativa para os endpoints. Ela pode ser acessada em http://127.0.0.1:8000/docs (Swagger UI) ou em http://127.0.0.1:8000/redoc (Redoc).

##Testes
Todas as operações foram testadas utilizando o Insomnia. As requisições retornam respostas em formato JSON e status 200 OK quando executadas corretamente. O vídeo demonstrativo dos testes foi publicado no YouTube conforme solicitado na atividade.
