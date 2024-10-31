# Typo Fixed - changed "nginx:latests" to "nginx:latest"
FROM nginx:latest

# Incorrect filename - changed "nginix.conf" to "nginx.conf"
COPY nginx.conf /etc/nginx/nginx.conf  

# First changed 'htmll' to 'html'  but later commented that COPY statement as it was unnecessary line
# COPY . /usr/share/nginx/html

# Incorrect way to expose port - changed "eighty" to 80
EXPOSE 80  

# Typo Fixed - corrected "daemon of;" to "daemon off;"
CMD ["nginx", "-g", "daemon off;"]  
