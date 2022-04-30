FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Carlox-ser-mass-ser/LiLLY-V2
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/nijin-husni/media

CMD ["node", "bot.js"]
