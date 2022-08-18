ARG NODE_VERSION

FROM node:${NODE_VERSION} AS base

RUN mkdir /node_modules \
  && chown node:node -R /node_modules
