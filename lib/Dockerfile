FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/ashenbro134/HI-BOT-MD/root/ashenbro134
WORKDIR /root/ashenbro134/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
