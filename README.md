# my-langchain-app

## Installation

1. Clone this repository

```bash
git clone https://github.com/ryo-kihara/my-langchain-app.git
```

2. Change directory to `my-langchain-app`

```bash
cd my-langchain-app
```

3. Build and run docker containers

```bash
docker compose up -d --build
```

4. Start streamlit server
```bash
docker compose exec streamlit streamlit run main.py
```

5. Access to `http://localhost:8501`

## Usage

### Start streamlit server

```bash
docker compose exec streamlit streamlit run main.py
```

### Install Library

1. write `requirements.txt`
2. Install library

```bash
docker compose exec streamlit pip install -r requirements.txt
```
