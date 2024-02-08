FROM quay.io/sampandey001/secktor 
 RUN git clone https://github.com/Xcelsama/EXCEL-MDX/root/Xcelsama
 WORKDIR /root/Xcelsama/ 
 RUN npm install npm@latest 
 RUN npm install 
 EXPOSE 8000 
 CMD ["npm", "start"]