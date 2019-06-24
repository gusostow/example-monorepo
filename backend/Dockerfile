FROM python:3.7

COPY shared shared

RUN pip install shared/

COPY backend .

CMD ["python", "db_scripts/extract_stubhub_listings.py"]