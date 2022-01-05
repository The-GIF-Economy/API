# GIF Economy API (do not distribute)

## List Artists

```sh
https://gifeconomy.com/artistsinfo?
```

```javascript
[
  {
    "user": "justin@place.com",
    "sub": "justin@place.com",
    "addresses": [
      "ZUEYHSSVXF7C2DQFU3TRWKPUR23J2UBEYYPAXYBOXOCD72KYZ5EBUMYTQY"
    ],
    "email": "justin@place.com",
    "name": "justin@place.com",
    "nickname": "iamthejustin",
    "emailVerified": true,
    "reddit": "",
    "storename": "JtK Media",
    "storedescription": "",
    "location": "",
    "description": "",
    "sellerimg": "/profimg/a11c1a4dad56da416bda334ad2135c0e",
    "address": "ZUEYHSSVXF7C2DQFU3TRWKPUR23J2UBEYYPAXYBOXOCD72KYZ5EBUMYTQY"
  }
]
```

Please display nickname not email, or if nickname is defaulting to email, just first part to not display full email.


## List Sales

```sh
https://gifeconomy.com/listsales?user=ithkuil@gmail.com
```

```javascript
[
  {
    "price": "0",
    "quantity": 2,
    "escrow": "IRFC7MSG5BC3IFITVALTHRNMACINV3GPDNUUGTUQXXSWF75NYHLKDLOLEQ",
    "unitname": "JELLY4",
    "royalty": "0",
    "priceMinusRoyalty": "0",
    "assetid": "380135265",
    "url": "https://gifeconj.mypinata.cloud/ipfs/bafybeih4r2za3wgsytybo3uf4aiyadyz5wngreyeg2pvm7kqzdpipk7mwu",
    "creator": "RMONE54GR6CYOJREKZQNFCZAUGJHSPBUJNFRBTXS4NKNQL3NJQIHVCS53M",
    "seller": "RMONE54GR6CYOJREKZQNFCZAUGJHSPBUJNFRBTXS4NKNQL3NJQIHVCS53M",
    "title": "Jelly test",
    "clawback": "AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAY5HFKQ",
    "total": "5",
    "numForSale": "4",
    "amount": "5",
    "note": "test\r\n{__ unlockable content at https://gifeconomy.com/ __}",
    "name": "ithkuil@place.com",
    "user": "ithkuil@place.com",
    "sub": "ithkuil@place.com",
    "addresses": [
      "MRHLCEX2WSIW5ATDJEPDVOTXRP23BQJFN7FP6RXAJP2YJSPKOKOLLALUEI",
      "RMONE54GR6CYOJREKZQNFCZAUGJHSPBUJNFRBTXS4NKNQL3NJQIHVCS53M",
      "7KFKY7ZKGERQZF5WI7MTUFKKOC25EQCHFDTJURDLWS56Y77ZNKWAI4RA2I"
    ],
    "mimetype": "image/jpeg",
    "nickname": "runvncnick"
  }
]
```

Link to sale page:

```sh
https://gifeconomy.com/sale_{assetid}{wallet address}

e.g.

https://gifeconomy.com/sale_414511808RMONE54GR6CYOJREKZQNFCZAUGJHSPBUJNFRBTXS4NKNQL3NJQIHVCS53M
```


## List Auctions

```sh
https://gifeconomy.com/listauctions2?user=ithkuil@gmail.com 
```

Also please display nickname not email, or if nickname is defaulting to email, just first part to not display full email.

If there is a bid it will be under `{obj}.HighBid`

```javascript
[{"appID":351872851,"assetid":"325367103","url":"https://gifeconj.mypinata.cloud/ipfs/bafybeibaeexk6b4azge5p643epcuwxkvyeyl5exkb7mxygrq5ritvg24h4","creator":"RMONE54GR6CYOJREKZQNFCZAUGJHSPBUJNFRBTXS4NKNQL3NJQIHVCS53M","title":"Jason test auction nick 2","clawback":"AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAY5HFKQ","unitname":"JLT5119","total":"2","amount":"1","description":"","opening":"100000","duration":"0.1","user":"ithkuil@place.com","sub":"ithkuil@place.com","addresses":["MRHLCEX2WSIW5ATDJEPDVOTXRP23BQJFN7FP6RXAJP2YJSPKOKOLLALUEI","RMONE54GR6CYOJREKZQNFCZAUGJHSPBUJNFRBTXS4NKNQL3NJQIHVCS53M","7KFKY7ZKGERQZF5WI7MTUFKKOC25EQCHFDTJURDLWS56Y77ZNKWAI4RA2I"],"mimetype":"image/png","nickname":"runvncnick","AssetID":325367103,"Duration":360,"Build":"59.0906_0136PM","Opening":100000,"dbg":"create\r","Escrow":"HJX5WJQGHJQHXEFF3XKRAO7JS6PSTYJYM5LDQILMTDJKWGGAUIAA3KPLY4","Creator":"RMONE54GR6CYOJREKZQNFCZAUGJHSPBUJNFRBTXS4NKNQL3NJQIHVCS53M","Seller":"RMONE54GR6CYOJREKZQNFCZAUGJHSPBUJNFRBTXS4NKNQL3NJQIHVCS53M","initialized":1}][
  {
    "appID": 351872851,
    "assetid": "325367103",
    "url": "https://gifeconj.mypinata.cloud/ipfs/bafybeibaeexk6b4azge5p643epcuwxkvyeyl5exkb7mxygrq5ritvg24h4",
    "creator": "RMONE54GR6CYOJREKZQNFCZAUGJHSPBUJNFRBTXS4NKNQL3NJQIHVCS53M",
    "title": "Jason test auction nick 2",
    "clawback": "AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAY5HFKQ",
    "unitname": "JLT5119",
    "total": "2",
    "amount": "1",
    "description": "",
    "opening": "100000",
    "duration": "0.1",
    "user": "ithkuil@place.com",
    "sub": "ithkuil@place.com",
    "addresses": [
      "MRHLCEX2WSIW5ATDJEPDVOTXRP23BQJFN7FP6RXAJP2YJSPKOKOLLALUEI",
      "RMONE54GR6CYOJREKZQNFCZAUGJHSPBUJNFRBTXS4NKNQL3NJQIHVCS53M",
      "7KFKY7ZKGERQZF5WI7MTUFKKOC25EQCHFDTJURDLWS56Y77ZNKWAI4RA2I"
    ],
    "mimetype": "image/png",
    "nickname": "runvncnick",
    "AssetID": 325367103,
    "Duration": 360,
    "Build": "59.0906_0136PM",
    "Opening": 100000,
    "dbg": "create\r",
    "Escrow": "HJX5WJQGHJQHXEFF3XKRAO7JS6PSTYJYM5LDQILMTDJKWGGAUIAA3KPLY4",
    "Creator": "RMONE54GR6CYOJREKZQNFCZAUGJHSPBUJNFRBTXS4NKNQL3NJQIHVCS53M",
    "Seller": "RMONE54GR6CYOJREKZQNFCZAUGJHSPBUJNFRBTXS4NKNQL3NJQIHVCS53M",
    "initialized": 1
  }
]
```

Link to auction page: 

```sh
https://gifeconomy.com/auction_{appID}

e.g.

https://gifeconomy.com/auction_351872851
```

