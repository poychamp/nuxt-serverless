# nuxt-serverless

Deploy Nuxt Serverless to AWS

## Installation and Deployment

### Install Serverless
`npm i -g serverless`

### Install Dependencies
`npm install`

### Setup Serverless Credentials
`serverless config credentials --provider aws --key xxxxxxxxxxxxxx --secret xxxxxxxxxxxxxx`

### Deploy
#### Staging
`npm run deploy-staging`
#### Production
`npm run deploy-prod`

## Configuration
See `serverless.yml`
