FROM python:slim

WORKDIR /app

COPY Requirementfile.txt .

RUN pip install -r Requirementfile.txt
RUN pip  install pandas 

COPY demo.py .

CMD ["python", "demo.py"]

# INSTALL jAva 21
RUN apt-get update && apt-get install -y