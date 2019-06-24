FROM python:3.7

COPY shared shared

COPY www www

RUN pip install shared/ www/

CMD ["python", "www/tnd_pyramid/views.py"]