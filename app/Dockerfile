# Imagem
FROM python:3.11-slim

# Diretório
WORKDIR /app

# Copiar arquivos
COPY . /app

# Instalar dependências
RUN pip install -r requirements.txt

# Porta
EXPOSE 5000

# Comando para iniciar
CMD ["python", "app.py"]