FROM python:3.7-slim

# Create app directory
WORKDIR /usr/src/app

# Install app dependencies
COPY ./kill-listener.py ./

CMD [ "python3", "kill-listener.py" ]
