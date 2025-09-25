# Сервис скоринга

<img width="1520" height="893" alt="image" src="https://github.com/user-attachments/assets/848e8e9f-45f9-48f3-abda-c98b7d84bc3e" />

## Подготовка
Поставьте нужные пакеты:
```python
pip3 install -r requirements.txt

## Сервис скоринга
Запустите сервис скоринга командой:
```python
uvicorn service:app

## Форма заявки
Сначала убедитесь, что сервис скоринга работает. Затем в отдельном терминале выполните:
```python
streamlit run app.py

Окно приложения запустится само. При закрытии откройте его снова по ссылке в логах или по [адресу](http://localhost:8501/).
