### Poetry

```Bash
# Создание requirements.txt экспорта зависимостей без хэшей
poetry export --without-hashes -f requirements.txt --output requirements.txt  
```

### download all packages for local install 
```bash
pip download -d vendor -r requirements.txt
```

### Install all packages localhost from folder
```bash
pip install --no-index --find-links /vendor -r requirements.txt
```
- (install wheel package) https://stackoverflow.com/questions/51748058/all-dependencies-are-not-downloaded-with-pip-download


#### Run Application
1) start server main.py
2) send message via - python.exe .\publisher.py
