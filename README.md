# arbr-geovision-server
attaching totems to geocached tree logins to interact with charged particle containers

### apis
- seed point of interest with tree: input(chargedParticleAddress, mode = ('nfc' || 'geo'), ?NFCid, ?{lng, lat}), returns (true | false)
- get charged particle address: input(mode = ('nfc' || 'geo'), ?NFCid, ?{lng, lat}), returns (address)
- get recommended nfts: input(tarot), returns ([nfts])
