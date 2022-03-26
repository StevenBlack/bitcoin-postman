# bitcoin-postman

Using Postman to query your Bitcoin node.

## Status

Under development. Not ready for general consumption just yet.

## Implementation

This collection implements some of the functions documented in the [Bitcoin RPC API Reference](https://developer.bitcoin.org/reference/rpc/index.html).

## Environment variables

This collection uses Postman environment variables.  Here's what I've got:

![2021-10-26_23-52-42](https://user-images.githubusercontent.com/80144/138998059-266808f3-fd1e-4b86-9a6a-36b5cf80f5c3.png)

No quote symbols are required in any environment variable.

## Progress

This collection is a work in progress.

### Key
* ✅ = presently working
* ❌ = presently broken
* 🟡 = exists but is still sketch

### Blockchain RPCs
* `getbestblockhash ✅`
* `getblock ✅`
* `getblockchaininfo ✅`
* `getblockcount ✅`
* `getblockfilter ❌`
* `getblockhash ✅`
* `getblockheader ✅`
* `getblockstats ✅`
* `getchaintips ✅`
* `getchaintxstats ✅`
* `getdifficulty ✅`
* `getmempoolancestors`
* `getmempooldescendants`
* `getmempoolentry`
* `getmempoolinfo ✅`
* `getrawmempool ✅`
* `gettxout ✅`
* `gettxoutproof`
* `gettxoutsetinfo`
* `preciousblock `
* `pruneblockchain`
* `savemempool`
* `scantxoutset`
* `verifychain`
* `verifytxoutproof`

### Control RPCs
* `getmemoryinfo ✅`
* `getrpcinfo ✅`
* `help ✅`
* `logging`
* `stop`
* `uptime ✅`

### Generating RPCs
* `generateblock`
* `generatetoaddress`
* `generatetodescriptor`

### Mining RPCs
* `getblocktemplate ✅`
* `getmininginfo ✅`
* `getnetworkhashps ✅`
* `prioritisetransaction`
* `submitblock`
* `submitheader`

### Network RPCs
* `addnode`
* `clearbanned`
* `disconnectnode`
* `getaddednodeinfo`
* `getconnectioncount ✅`
* `getnettotals ✅`
* `getnetworkinfo ✅`
* `getnodeaddresses`
* `getpeerinfo ✅`
* `listbanned ✅`
* `ping ✅`
* `setban`
* `setnetworkactive`

### Rawtransactions RPCs
* `analyzepsbt`
* `combinepsbt`
* `combinerawtransaction`
* `converttopsbt`
* `createpsbt`
* `createrawtransaction`
* `decodepsbt`
* `decoderawtransaction`
* `decodescript`
* `finalizepsbt`
* `fundrawtransaction`
* `getrawtransaction`
* `joinpsbts`
* `sendrawtransaction`
* `signrawtransactionwithkey`
* `testmempoolaccept`
* `utxoupdatepsbt`

### Util RPCs
* `createmultisig`
* `deriveaddresses`
* `estimatesmartfee`
* `getdescriptorinfo`
* `getindexinfo`
* `signmessagewithprivkey`
* `validateaddress`
* `verifymessage`

### Wallet RPCs
Note: the wallet RPCs are only available if Bitcoin Core was built with wallet support, which is the default.

* `abandontransaction`
* `abortrescan`
* `addmultisigaddress`
* `backupwallet`
* `bumpfee`
* `createwallet`
* `dumpprivkey`
* `dumpwallet`
* `encryptwallet`
* `getaddressesbylabel`
* `getaddressinfo`
* `getbalance`
* `getbalances`
* `getnewaddress`
* `getrawchangeaddress`
* `getreceivedbyaddress`
* `getreceivedbylabel`
* `gettransaction`
* `getunconfirmedbalance`
* `getwalletinfo 🟡`
* `importaddress`
* `importdescriptors`
* `importmulti`
* `importprivkey`
* `importprunedfunds`
* `importpubkey`
* `importwallet`
* `keypoolrefill`
* `listaddressgroupings`
* `listlabels`
* `listlockunspent`
* `listreceivedbyaddress`
* `listreceivedbylabel`
* `listsinceblock`
* `listtransactions 🟡`
* `listunspent`
* `listwalletdir ✅`
* `listwallets ✅`
* `loadwallet ✅`
* `lockunspent`
* `psbtbumpfee`
* `removeprunedfunds`
* `rescanblockchain`
* `send`
* `sendmany`
* `sendtoaddress`
* `sethdseed`
* `setlabel`
* `settxfee`
* `setwalletflag`
* `signmessage`
* `signrawtransactionwithwallet`
* `unloadwallet ✅`
* `upgradewallet`
* `walletcreatefundedpsbt`
* `walletlock`
* `walletpassphrase`
* `walletpassphrasechange`
* `walletprocesspsbt`
