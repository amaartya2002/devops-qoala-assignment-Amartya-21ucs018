FROM python:3.9

# Typo Fixed - changed /appp to /app
WORKDIR /app              

# Typo Fixed - changed appy.py/app to app.py
COPY app.py /app          

# Typo Fixed - changed netiface to netifaces
RUN pip install flask netifaces

# Typo Fixed - changed "eight thousand" to 8000
EXPOSE 8000                    

# Typo Fixed - changed "pythn" to python
CMD ["python", "app.py"]     
