FROM node
LABEL maintainer vunhattan84@gmail.com
RUN git clone https://github.com/tanvn/todo.git
WORKDIR todo
RUN npm install
#RUN chmod -R 777 /todo
EXPOSE 8000
CMD ["npm","start"]

