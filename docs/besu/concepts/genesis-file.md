---
description: ClishaChain genesis file

---

# Genesis file


ClishaChain Mainnet Genesis

  ```bash
{
  "config" : {
    "chainId" : 3890,
    "homesteadBlock" : 0,
    "eip150Block" : 0,
    "eip155Block" : 0,
    "eip158Block" : 0,
    "byzantiumBlock" : 0,
    "constantinopleBlock" : 0,
    "petersburgBlock" : 0,
    "istanbulBlock" : 0,
    "berlinBlock" : 0,
    "londonBlock" : 0,
    "qbft" : {
      "blockperiodseconds" : 2,
      "epochlength" : 28800,
      "requesttimeoutseconds" : 4,
      "blockreward" : "500000000000000000000",
      "baseFeePerGas" : "0x834"
    },
    "transitions" : {
      "qbft" : [ {
        "block" : 31536000,
        "blockreward" : "250000000000000000000"
      }, {
        "block" : 63072000,
        "blockreward" : "125000000000000000000"
      }, {
        "block" : 94608000,
        "blockreward" : "62500000000000000000"
      }, {
        "block" : 126144000,
        "blockreward" : "31250000000000000000"
      }, {
        "block" : 157680000,
        "blockreward" : "15625000000000000000"
      }, {
        "block" : 189216000,
        "blockreward" : "7812500000000000000"
      }, {
        "block" : 220752000,
        "blockreward" : "3900000000000000000"
      }, {
        "block" : 252288000,
        "blockreward" : "1950000000000000000"
      }, {
        "block" : 283824000,
        "blockreward" : "975000000000000000"
      }, {
        "block" : 315360000,
        "blockreward" : "487500000000000000"
      }, {
        "block" : 346896000,
        "blockreward" : "243750000000000000"
      }, {
        "block" : 378432000,
        "blockreward" : "121875000000000000"
      }, {
        "block" : 409968000,
        "blockreward" : "61035156250000000"
      }, {
        "block" : 1494768000,
        "blockreward" : "0"
      } ]
    }
  },
  "nonce" : "0x0",
  "timestamp" : "0x0",
  "gasLimit" : "0x1fffffffffffff",
  "difficulty" : "0x1",
  "mixHash" : "0x63746963616c2062797a616e74696e65206661756c7420746f6c6572616e6365",
  "coinbase" : "0x0000000000000000000000000000000000000000",
  "alloc" : {
    "0xaE51f2EfE70e57b994BE8F7f97C4dC824c51802a" : {
      "balance" : "1000000000000000000000000000"
    }
  },
  "extraData" : "0xf87aa00000000000000000000000000000000000000000000000000000000000000000f854949a1ddd7fd02b1df388b8633024e51ed668752b3a940bf216e4a3984d9a183af664a93d2dd43a100236946f302499d29fb51b24f7d3321097f3430334dfa59494fe9652de72a3694c793730289aedc01698aa91c080c0"
}

  ```
