#Getting Started:

In your terminal run:

$ git clone https://github.com/acortiv/pb-template/new/main?filename=README.md

To start Pocket base run:

$ task start

To start the NextJS client run:

$ npm run dev

For quickly shipping to Prod:

Use fly.io for PB & Vercel for NextJS.  For persistent data, be sure to mount the pb_data to a volume on fly.io using the [mount] tag in fly.toml.
