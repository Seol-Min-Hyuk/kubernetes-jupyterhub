FROM jupyterhub/k8s-hub:2.0.0


USER root

WORKDIR ~/

COPY ./jwtauthenticator ./jwtauthenticator


RUN python -m pip install --upgrade pip
RUN pip install --no-cache-dir -e ./jwtauthenticator

