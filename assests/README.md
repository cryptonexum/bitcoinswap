
# Bitcoin Swap Assets

bitcoin Swap is first Swap build for BRC-20, Where you can swap your tokens inside ordinals.


## Guidde to Listing Your asset

Contributions are always welcome!

Please adhere to this project's `code of conduct`.

1. Take Fork of
https://github.com/bitcoin-swap/bitcoinswap/tree/main/assests

2. Create Folder with your inscription Tick in UpperCase letters  only eg . for Ordinals "ORDI"

3. Under Tick Folder add your logo(required)
logo size should be `200x200`px with transparent background
file Name : `logo.png` only

4. Add `info.json` file in below format
```
    {
    "name": "Ordi Token",
    "tick": "ORDI",
    "id": "b61b0172d95e266c18aea0c624db987e971a5d6d4ebc2aaed85da4642d635735i0",
    "website": "https://ordinals.com/",
    "description": "ORDI aims to create an ecosystem of products ranging from casino platforms to innovative NFT collections and applications. ORDI holders get dividends.",
    "status": "active",
    "market": {
      "coingecko-id":"ordinals",
      "coinmarketcap-id":"ordi"
    },
    "links": [
    ],
    "tags": [
    ]
  }
  ```
Description:
1. name (required): Name of your inscription
2. tick (required): tick of your inscription
3. id (required): your inscriptionId
4. website(required): your project website
5. description(required): your project description
6. status(required): keep it `active` always
7. market-> coingecko-id (optional): mention your `ApiId` from coingecko page your token page
8. market-> coinmarketcap-id (optional): enter youtr instcription tick in lowercase eg. `ordi`
9. links: (optional)
```
eg links:
"links": [
    "name": "",
    "url":""
    ],

  accepted names: (twitter,telegram-chat,telegram-channel,facebook,instagram,discord,github)
```

10. tags: (optional)
```
Accepted tags:
(text,nft,brc20)
```


