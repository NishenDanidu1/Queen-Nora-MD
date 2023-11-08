FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/NishenDanidu1/Queen-Nora-MD /root/NishenDanidu1
WORKDIR /root/NishenDanidu1/
RUN npm install npm@10.2.3
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
