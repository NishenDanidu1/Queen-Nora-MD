FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/NishenDanidu1/Queen-Nora-MD /root/NishenDanidu1
WORKDIR /root/NishenDanidu1/nora
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
