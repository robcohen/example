FROM sphinxdoc/sphinx

WORKDIR /docs
ADD .sphinx/requirements.txt /docs
RUN apt-get update && apt-get install git -y
RUN pip3 install -r requirements.txt
RUN python -m pip install git+https://github.com/input-output-hk/sphinx_rtd_theme.git#egg=sphinx_rtd_theme