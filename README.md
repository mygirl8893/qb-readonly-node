# Start readonly nodes and connect to the network


# Prerequisites
- Parity
- Expose ports:
    - `8540`: http rpc
    - `8450`: websocket
    - `30300`: network discovery


## Steps

* Clone repo

* Start node
```bash
screen -dmS "Node" parity --config readnode.toml
```

* Add more bootnodes in `bootnodes.txt` if needed. One per line


## Note
Config Params for genesis:

- Production Chain:
```
networkId: 17224
ChainId: 17224
```


- Test Chain:
```
networkId: 17225
ChainId: 17225
```
