# set the base image 
FROM python-3.6
ADD . /my-django-app
WORKDIR /my-django-app
ENV STATIC_URL /ecommerce
ENV STATIC_PATH /home/administrator/demosite/ecommerce
COPY ./requirements.txt /home/administrator/demosite/ecommerce/requirements.txt
RUN pip install -r /home/administrator/demosite/ecommerce/requirements.txt
RUN pip install -r requirements.txt

CMD [ "python", "./manage.py runserver 0.0.0.0:8000" ]
