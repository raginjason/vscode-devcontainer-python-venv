# Use the official Python image from the Docker Hub
ARG VARIANT="3"
FROM mcr.microsoft.com/vscode/devcontainers/python:0-${VARIANT}

# RUN su vscode -c "umask 0002 && pip3 install poetry==${POETRY_VERSION}"; fi

# RUN whoami | tee /tmp/whoami.txt
# COPY requirements.txt /tmp/pip-tmp/requirements.txt
# # RUN python -m venv /workspaces/.venv \
#     && chown -R vscode:vscode /workspaces/.venv \
#     && su -l vscode -c "source /workspaces/.venv/bin/activate && pip --disable-pip-version-check --no-cache-dir install -r /tmp/pip-tmp/requirements.txt"
# RUN su -l vscode -c "python -m venv /workspaces/.venv && source /workspaces/.venv/bin/activate && pip --disable-pip-version-check --no-cache-dir install -r /tmp/pip-tmp/requirements.txt"
#  && rm -rf /tmp/pip-tmp

# # Copy the requirements file into the container

# RUN su vscode -c "umask 0002 && pip3 install poetry==${POETRY_VERSION}"; fi



# # Install the dependencies
# RUN pip install --no-cache-dir -r requirements.txt
