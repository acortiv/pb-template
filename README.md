## Clone the repository
To clone the repository, open your terminal and run the following command:

```
git clone https://github.com/acortiv/pb-template/new/main?filename=README.md
```

## Start PocketBase
To start PocketBase, run:

```
task start
```

## Start the NextJS client
To start the NextJS client, run:

```
npm run dev
```

## Deployment tips
For deployment, use fly.io for PocketBase and Vercel for NextJS. Ensure persistent data management by mounting the `pb_data` to a volume on fly.io, configured in `fly.toml`:

```
[mount]
  source = "pb_data"
  destination = "/path/on/container"
```
