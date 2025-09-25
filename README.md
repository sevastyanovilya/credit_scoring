# Сервис скоринга

<img width="923" height="702" alt="image" src="https://github.com/user-attachments/assets/6d3791c6-8ab0-45a5-b0c4-a0ab2dec1956" />


## Подготовка
Поставьте нужные пакеты:
```python
pip3 install -r requirements.txt
```

## Сервис скоринга
Запустите сервис скоринга командой:
```python
uvicorn service:app
```

## Форма заявки
Сначала убедитесь, что сервис скоринга работает. Затем в отдельном терминале выполните:
```python
streamlit run app.py
```

Окно приложения запустится само. При закрытии откройте его снова по ссылке в логах или по [адресу](http://localhost:8501/).
