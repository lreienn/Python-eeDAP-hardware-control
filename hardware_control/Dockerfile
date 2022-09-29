FROM python:3

# ADD ./app.py ./proscan.py ./base_stage.py ./check_ports.py /

COPY ./requirements.txt /app/requirements.txt

WORKDIR /app

RUN pip install -r requirements.txt

COPY . /app

CMD [ "python", "./move_stage_tester.py" ]