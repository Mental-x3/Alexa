FROM quay.io/lyfe00011/md:beta
RUN git clone https://github.com/Mental-x3/Alexa /5hefin/Alexa/
WORKDIR /5hefin/Alexa/
RUN yarn install --network-concurrency 1
CMD ["node", "index.js"]
