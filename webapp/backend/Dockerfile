FROM python:3.7
ADD . /home/user/webapp
WORKDIR /home/user/webapp
# TODO: Add virtualenvs support here.
RUN pip install -r requirements.txt
# CMD python webapp/manage.py makemigrations && python webapp/manage.py migrate
CMD python webapp/manage.py runserver 0.0.0.0:8000