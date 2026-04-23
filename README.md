# 📝 Task Manager API

API RESTful para gerenciamento de tarefas desenvolvida com Python e Flask durante a formação Python da [Rocketseat](https://rocketseat.com.br).

## Tecnologias

- Python 3 + Flask
- pytest

## Como rodar

```bash
pip install -r requirements.txt
python app.py
```

## Endpoints

| Método | Rota | Descrição |
|--------|------|-----------|
| `POST` | `/tasks` | Cria uma nova tarefa |
| `GET` | `/tasks` | Lista todas as tarefas |
| `GET` | `/tasks/<id>` | Busca uma tarefa pelo ID |
| `PUT` | `/tasks/<id>` | Atualiza uma tarefa |
| `DELETE` | `/tasks/<id>` | Remove uma tarefa |

## Testes 🧪

Com o servidor rodando:

```bash
pytest tests.py -v
```