FROM python:3.12.3-alpine
                
LABEL Role=site-groupe
        
LABEL Server=python-http
       
RUN mkdir /groupe

COPY apply /groupe
           
WORKDIR /groupe
   
VOLUME ["/data"]

CMD python3 -m http.server 8089
