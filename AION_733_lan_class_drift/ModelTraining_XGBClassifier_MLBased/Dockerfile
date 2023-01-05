FROM python:3.8-slim-buster
LABEL "usecase"="AION_733_lan_class_drift"
LABEL "usecase_test"="AION_733_lan_class_drift_test"
COPY  requirements.txt requirements.txt
COPY  config.json config.json
COPY  code.py code.py
COPY  utility.py utility.py
RUN pip install --no-cache-dir -r requirements.txt