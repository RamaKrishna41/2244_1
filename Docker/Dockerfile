# FROM <image-name>:<tag> -> default tag is latest
FROM ubuntu

# RUN apt-get install nginx -> to run command that install a web server
RUN apt-get update \ 
    && apt-get install -y nginx

# COPY script.sh /tmp/  -> to copy local file to /tmp/ folder
# CMD ["bash", "/tmp/script.sh"] -> to run the file

# CMD [] -> executes commands when container started (python hello_world.py -> ["python", "hello_world.py"])
CMD ["nginx", "-g", "daemon off;"]