FROM {{ cookiecutter.base_docker_image  }}
ADD requirements.txt /build/requirements.txt
WORKDIR /build/
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
RUN jupyter labextension install jupyterlab-plotly@4.14.3
WORKDIR /mnt/
