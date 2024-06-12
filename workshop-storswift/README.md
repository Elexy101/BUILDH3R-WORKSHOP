I made a simple deploy message on Aleo Blockchain, I was able to deploy using the snarkos to generate the transaction on-chain.

Aleo txn: [at1082hac3xs5sdgy3vpl5x9vrnj4ajrlejvagr44znwxp6zzx4ggqsc4sy20](https://explorer.aleo.org/transaction/at1082hac3xs5sdgy3vpl5x9vrnj4ajrlejvagr44znwxp6zzx4ggqsc4sy20?tab=fee)

Aleo address: aleo1az8p9vlllyqwtj0c2g9svkd0e5v0p3zzdflwwrpa7kpe8xrfxgfqqpru7m

Deploy command: `snarkos developer deploy "message_elexy.aleo" --private-key APrivateKey123 --query "https://api.explorer.aleo.org/v1" --path "./build/" --broadcast "https://api.explorer.aleo.org/v1/testnet/transaction/broadcast" --priority-fee 1000000 --network 1`

- Replace `APrivateKey123` with your actual private key for the transaction to work

# NETWORK MODE
- `1` -> Testnet ID
- `2` -> Canary ID
- `0` -> Mainnet ID

### PREVIEW
![Screenshot from 2024-06-12 01-35-56](https://github.com/Elexy101/BUILDH3R-WORKSHOP/assets/24855083/4d155008-135b-4d06-892b-6f4e653e2fb6)
