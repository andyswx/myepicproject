# Solana Smart Contract for Pinterest-on-Solana-app

Switch to Solana Devnet
```$solana config set --url devnet```

Add a balance
```$ solana airdrop 2```

Check your balance
```solana balance```

Step 1
```$ anchor build```

Step 2
```solana address -k target/deploy/myepicproject-keypair.json```

Step 3
Copy id to lib.rs
```declare_id!("Fg6PaFpoGXkYsidMpWTK6W2BeZ7FEfcYkg476zPFsLnS");```

Step 4
```$ anchor test```

Step 5
To deploy to Solana Devnet
```$ anchor deploy```