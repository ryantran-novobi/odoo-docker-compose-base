FROM odoo:17

USER root

RUN apt-get update && apt-get install -y \
        git

COPY requirements.txt /requirements.txt
RUN pip3 install -r /requirements.txt

USER odoo
