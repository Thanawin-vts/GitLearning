FROM nginx:1.17.1-alpine

WORKDIR /prj-basics-final
COPY ../package*.json ./
RUN npm install
COPY .. ./
# RUN ng build
CMD ["ng", "build"]

# RUN cd ..
# WORKDIR /app

# RUN cd ..
# COPY package*.json ./
# RUN npm install
# RUN npm install -g @angular/cli

# COPY . .

# RUN cd ..

# RUN ng build
# RUN ng serve --host 192.168.0.62

# CMD ["ng", "serve", "--host", "192.168.0.62"]