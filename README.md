# NextJS Typescript Starter

`npm i`

## GCP CLI

1. Install gcloud: <https://cloud.google.com/sdk/docs/install>
2. Run `gcloud auth login` and sign in with your browser

## Start Dev

Run `npm run dev`

## Docker

### Install

1. Install Docker Desktop
2. Run `gcloud auth configure-docker`

### GCP

1. `Container Registry -> Enable`

### Extension

First install the Docker VSCode extension (Recommended)

### Building the image

1. Right click `Dockerfile` in repo root. Select `Build Image...`
2. Name the image: `gcr.io/<project-name>/<image-name>:latest`

### Pushing the image

1. Go to Docker extension tab
2. Right click on`Images -> gcr.io/<project-name>/<image-name> -> latest`, then `Push`

### Deploying

1. Go to Cloud Run: <https://console.cloud.google.com/run>
2. Create new service, and select your latest image when deploying
