

## Installation

- Clone repo
- Run `npm install`

## Set up

- Create app in partner dashboard
- Create `.env` and `process.env` files in project root folder with the following:
```
SHOPIFY_API_KEY="{api key from partner dash}"
SHOPIFY_API_SECRET="{api secret from partner dash}"
HOST="abc123.ngrok.io" # use ngrok URL
SCOPES=read_products,read_customers
```

## Usage

- Start app with `npm run dev`
- Ensure Ngrok is running on your local machine
- Install app by visiting https://abc123.ngrok.io?shop=shop.myshopify.io (app might show a 500 error after Oauth callback, but it should still be installed)
