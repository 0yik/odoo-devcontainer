# Find the Dockerfile at this URL
FROM odoo:17.0

USER root

RUN apt-get update \
    && apt-get install -y git \
    && apt-get clean

RUN pip install --upgrade pip

RUN pip install pylint-odoo

USER odoo
