[AssumeUTXO](https://github.com/bitcoin/bitcoin/blob/master/doc/assumeutxo.md) dumps for fast Bitcoin Core synchronization
Created on Bitcoin Core 28
Mainnet(block 867266)-sha256 hash f42ca419d0da27c2ed54a2d7755521b1d5800510ea665b3415ba30dc8f8ca8a8
How to create own utxodump:

\>dumptxoutset "C:\Users\laptop\utxo_dump_mainnet_867266.dat"
```
{
  "coins_written": 186341963,
  "base_hash": "0000000000000000000267a42e80308fe0531a716eebf67256471e47f5cc5435",
  "base_height": 867266,
  "path": "C:\\Users\\laptop\\utxo_dump_mainnet_867266.dat",
  "txoutset_hash": "202c98a1083a752cc4a7abfd1047b8d8d20bea3d721476e5a551e4564534eb2b",
  "nchaintx": 1105088580
}
```
How to load:
\>loadutxoset "C:\Users\laptop\utxo_dump_mainnet_867266.dat"

Similar: [FastSync](https://github.com/btcpayserver/btcpayserver-docker/tree/master/contrib/FastSync)(BTCPay Server)
