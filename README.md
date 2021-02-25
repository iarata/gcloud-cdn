# 👷 `gcloud-cdn` GCloud-CDN Worker

A script for using Google Cloud Storage as a CDN in Cloudflare Worker

[`index.js`](https://github.com/iarata/gcloud-cdn/blob/main/index.js) is the content of the Workers script.


## Usage

Replace `[YOUR_BUCKET_NAME]` in [`index.js`](https://github.com/iarata/gcloud-cdn/blob/main/index.js) with your own bucket name.

Replace `[YOUR_CLOUDFLARE_ACCOUNT_ID]` in [`wrangler.toml`](https://github.com/iarata/gcloud-cdn/blob/main/wrangler.toml) with your cloudflare 


## Publish

Publish your Cloudflare Worker by typing below commands in terminal:

```console
$ wrangler build
$ wrangler publish
```
