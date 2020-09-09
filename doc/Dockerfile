FROM sphinxdoc/sphinx

WORKDIR /docs
ADD .sphinx/requirements.txt /docs
RUN apt-get update && apt-get install git -y
RUN pip3 install -r requirements.txt