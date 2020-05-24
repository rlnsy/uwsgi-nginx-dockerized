FROM python:3.7
ADD ./uwsgi-app.py /test/uwsgi-app.py
ADD ./requirements.txt /test/requirements.txt
ADD  ./uwsgi.ini /test/uwsgi.ini
WORKDIR /test
RUN pip install -r requirements.txt
CMD ["uwsgi", "--ini", "./uwsgi.ini"]