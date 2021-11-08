FROM fusuf/whatsasena:latest

RUN git clone https://github.com/zeeshanlashari213/ZEESHAN LASHARI /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audio

CMD ["node", "bot.js"]
