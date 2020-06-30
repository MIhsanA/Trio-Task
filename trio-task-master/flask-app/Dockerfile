#Use Python Image
From python:3.8
# Install apt dependencies
Run apt update
Run apt install python3-pip -y
# Copy contents into image
Copy . .
# run pip dependencies
Run pip3 install flask
Run pip3 install flask_sqlalchemy
Run pip3 install PyMySQL[rsa] 
# Expose correct port
EXPOSE 5000
# Create an entrypoint
ENTRYPOINT [ "/usr/local/bin/python3", "app.py" ]
