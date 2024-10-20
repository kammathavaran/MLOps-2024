# get python alpine image and build with it as a base  
FROM python:3.13.0-alpine3.19

# setting workdir 
WORKDIR /app

# copy all the folder contents to the app folder 
COPY . /app

# run start.py using python
CMD ["python", "hello.py"] 
