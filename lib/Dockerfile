FROM quay.io/suhailtechinfo/suhail-v2
RUN git clone https://github.com/Bladeh4x/BLADE-MD /root/BLADE-MD
WORKDIR /root/BLADE-MD/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
 
