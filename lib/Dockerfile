

RUN git clone https://github.com/SamPandey001/Secktor-Md /root/SamPandey001

# Add the new git clone command for the Xcelsama repository
RUN git clone https://github.com/Xcelsama/STAR-MD /root/STAR-MD

WORKDIR /root/STAR-MD/

RUN npm install npm@latest
RUN npm install

EXPOSE 8000

CMD ["npm", "start"]
```
