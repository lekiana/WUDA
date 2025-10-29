# ADD YOUR OWN DOCKERFILE
# ustawienie środowiska dla obrazu 
FROM python:3.10

# ustawienie katalogu roboczego
WORKDIR /backend

# kopiowanie plików z repo
COPY . .

# instalowanie pip i zależności
RUN pip install --upgrade pip && pip install -r requirements.txt

# ustawiamy port dla backendu
EXPOSE 5000

# uruchomienie aplikacji backend
CMD ["python3", "app.py"]
