
## Backend

### Configuração

1. Instale os pacotes necessários:
    ```bash
    pip install -r backend/requirements.txt
    ```

2. Execute o servidor:
    ```bash
    cd backend
    bash run.sh
    ```

### Estrutura do Backend

- `main.py`: Ponto de entrada da aplicação FastAPI.
- `models.py`: Modelos de dados usando Pydantic.
- `agents/`: Contém os módulos para cada agente (secretary, teacher, tutor, grader).
- `db/`: Contém módulos para configuração de diferentes bancos de dados (MongoDB, PostgreSQL, Pinecone, FAISS).

## Frontend

### Configuração

1. Instale os pacotes necessários:
    ```bash
    cd frontend
    npm install
    ```

2. Execute a aplicação:
    ```bash
    npm start
    ```

### Estrutura do Frontend

- `components/`: Contém os componentes React (VideoPlayer, App).

## Tecnologias Utilizadas

- **Frontend**: React, TailwindCSS, styled-components, react-player, react-webcam.
- **Backend**: FastAPI, LangChain, OpenAI, SQLAlchemy, MongoDB, Pinecone, FAISS.
- **Infraestrutura**: AWS, Groq.

## Contribuição

Sinta-se à vontade para contribuir com este projeto enviando pull requests, relatando issues, ou sugerindo melhorias.
