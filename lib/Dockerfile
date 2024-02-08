FROM quay.io/xcelsama/STAR
RUN git clone https://github.com/Xcelsama/STAR-MD/root/Xcelsama
WORKDIR /root/xcelsama/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
