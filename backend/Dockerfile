FROM node:13.8.0
WORKDIR /usr/src/app
COPY . ./
RUN npm run build
RUN npm install
EXPOSE 3030
CMD ["npm", "run", "start:noncompile"]