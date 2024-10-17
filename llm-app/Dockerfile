FROM python:3.8

WORKDIR /app
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
#RUN pip install -r requirements.txt
COPY . .

CMD ["streamlit", "run", "streamlit/app.py"]