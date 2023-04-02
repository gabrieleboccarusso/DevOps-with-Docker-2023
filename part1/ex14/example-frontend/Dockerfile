FROM node:16

WORKDIR /app

COPY . .

ENV REACT_APP_BACKEND_URL=http://localhost:8080

RUN npm install
RUN npm install -g serve
RUN npm run build


CMD serve -s -l 5000 build

# used command 
# docker run -p 5001:5000 <image-name>