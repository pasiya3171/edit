FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/pasiya3171/edit /root//pasiya3171
WORKDIR /root/pasiya3171/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
