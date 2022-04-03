# n8n example

This example deploys a self-hosted version of [n8n](https://n8n.io/) on http://railway.app platform.
Internally it uses a PostgreSQL database to store the data.

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2Frailwayapp-starters%2Fn8n&plugins=postgresql&envs=USERNAME%2CPASSWORD%2CPORT&PORTDesc=The+port+to+listen+on.+%28You+don%27t+need+to+change%29&PORTDefault=5678)

You should set the variables on Railway Deploy Dashboard.

Variables:  

- USERNAME
- PASSWORD
- PORT
- WEBHOOK_URL

Configure a CNAME from you DNS Managment to make Webhooks works correctly, example:  n8n.yourdomain.com.br

example:



## ✨ Features

- n8n
- PostgreSQL

## 💁‍♀️ How to use

- Click the Railway button 👆
- Add the required environment variables
- Deploy

## 📝 Notes

- Source repo: https://github.com/n8n-io/n8n
- Docs: https://docs.n8n.io/
