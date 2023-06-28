FROM python:3.8-slim
WORKDIR /app
COPY . .
RUN pip install -r requirements.txt 
CMD ["streamlit", "run", "app.py"]   

# steps 1 to 4 is for building the image

#docker build -t pred_service .  -t is the tage and . is from current working directory there is any docker file use that docker file to create an image
# look into docker docs 
# docker run -p 8501:8501 pred_service, here -p 8501:8501 means maps the docer container port of 8501 to local 8501, first port 8501 is for local(i.e., windows)
# we can run docker in interactive mode