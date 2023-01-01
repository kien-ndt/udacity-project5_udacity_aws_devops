FROM node:13.8.0
WORKDIR /usr/src/app
COPY . ./
RUN npm install
RUN npm run build
EXPOSE 3030
CMD ["npm", "run", "start:noncompile"]