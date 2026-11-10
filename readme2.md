para ativar o .venv use: 
```
.\.venv\Scripts\Activate.ps1
```

para rodar o front use:
```
streamlit run frontend/streamlit_app.py
```

para rodar o back(api) use:
```
uvicorn app.main:app --reload
```

para rodar os testes use: 
```
pytest -v
```

instalar os requirements:
```
python -m pip install -r requirements.txt
```

e os requirements do front: 
```
python -m pip install -r frontend/requirements.txt
```