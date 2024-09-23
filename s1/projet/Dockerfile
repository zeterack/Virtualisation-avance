FROM python:3.9-slim

WORKDIR /

COPY app.py .
RUN apt-get update && apt-get install -y 

RUN pip install streamlit

EXPOSE 8501

ENTRYPOINT ["streamlit", "run", "app.py", "--server.port=8501", "--server.address=0.0.0.0"]