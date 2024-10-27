

✔️ Auto tap

✔️ Auto task

✔️ Auto spin

✔️ Auto upgrade card


# 🛠️ Instructions:

## REQUIREMENTS: NODEJS MUST BE INSTALLED

Run the following command to install the necessary modules:

`npm install`

Create two files: [data.txt](data.txt) and [proxy.txt](proxy.txt)

For those using multiple accounts, it's recommended to use a proxy (if using only one account, there's no need to create the proxy.txt file).

# Proxy format:

http://user:pass@ip:port

# Get data:

In the data.txt file, you need to have the following format:

query_id=xxx or user=xxxx

![Capture](https://github.com/user-attachments/assets/6db0b3ed-86fe-4cf7-b9c3-9dde4c0f2efb)

# Configuration option in config.json

```js
{
    "maxUpgradePrice": 500000
}
```

# Run the tool using the command:

noproxy:

`node dropee.js`

proxy:

`node dropee-proxy.js`