FROM fusuf/whatsasena:latest

RUN git clone https://github.com/TEDZO123/ASLU-SIR-3 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/TEDZO123/ASLU-SIR-3.5

CMD ["node", "bot.js"]
