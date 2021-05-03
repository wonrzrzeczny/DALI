FROM nvcr.io/nvidia/tensorflow:21.04-tf1-py3
WORKDIR yolov4
RUN python -m pip install --upgrade pip 
COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
COPY * ./

CMD python3 src/main.py 
