# How to run locally
* Install tools

Instructions on how to install [Anchor](https://github.com/solana-foundation/anchor) can be found [here](https://www.anchor-lang.com/docs/installation).

* Install dependencies

Extract the zip file in your project's directory and run:
```
yarn
```

* ### Build
```
anchor build
```

* ### Test
```
anchor test
```

* ### Run client
```
anchor run client
```

**Note** You might need to adjust the client and test code to fully work in local Node environment since there are playground exclusive features, e.g. if you are using pg.wallets.myWallet, you'll need to manually load each keypair.

# Credits
Based on [Solana Developer Bootcamp 2024 - Learn Blockchain and Full Stack Web3 Development - Projects 1-9
](https://www.youtube.com/watch?v=amAq-WHAFs8)