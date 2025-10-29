# ADD YOUR OWN DOCKERFILE
# ustawienie środowiska dla obrazu 
FROM python:3.10

# ustawienie katalogu roboczego
WORKDIR /frontend

# kopiowanie plików z repo
COPY . .

# instalowanie pip i zależności
RUN pip install --upgrade pip && pip install -r requirements.txt

# ustawiamy port dla frontend
EXPOSE 8000

# uruchomienie aplikacji frontend
CMD ["python3", "app.py"]
