FROM mhart/alpine-node:8

# Add app source files
ADD src /src

WORKDIR /src

#install node modules
RUN yarn

CMD ["yarn", "start"]
