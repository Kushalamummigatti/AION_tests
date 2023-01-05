FROM python:3.8-slim-buster
LABEL "usecase"="AION_733_lan_class_drift"
LABEL "usecase_test"="AION_733_lan_class_drift_test"

COPY  utility.py utility.py
COPY  __init__.py __init__.py
COPY  dataProfiler.py dataProfiler.py
COPY  code.py code.py
COPY  requirements.txt requirements.txt
COPY  config.json config.json
RUN  pip install --no-cache-dir -r requirements.txt
