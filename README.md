# Simple Loan Calculator

This repo contains a simple loan calculator app.

## Initial Setup

### Not using `docker`

`yarn install`

## Start Development

### Not using `docker`

`yarn dev`

### Using `docker`

`docker-compose up`

## Build for Production

### Not using `docker`

`yarn build` and we can find the build files inside `dist` directory, we can easily move the files to the webserver and set it up

### Using `docker`

`docker image build -t <image-name>:<tag> .`, if you are planning to push your image to docker hub, don't forget to name your image with your docker id as prefix like `ishakantony/loan-calculator-javascript:latest`.
