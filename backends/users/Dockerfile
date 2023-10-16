FROM python:3.8
LABEL maintainer="elijahobara357gmail.com"

WORKDIR /app

COPY requirements.txt /app
COPY api.py /app

RUN pip install -r requirements.txt

EXPOSE 8002

ENTRYPOINT ["python"]
CMD ["api.py"]