
FROM atq/fabric-server

LABEL ca.atq.version="0.01"

# Create app directory
WORKDIR /usr/src/app
COPY . .

EXPOSE 4000

#CMD ["/bin/sh"]
CMD [ "npm", "start" ]
