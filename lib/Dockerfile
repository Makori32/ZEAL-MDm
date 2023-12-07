FROM quay.io/maherzubair/sigma-md:beta
RUN git clone https://github.com/zealgraphix/ZEAL-MD/root/zealgraphix
WORKDIR /root/zealgraphix/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
