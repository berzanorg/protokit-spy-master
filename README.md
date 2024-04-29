# Protokit Spy Master

This repository is created using Protokit for Mina Navigators Learn To Earn Challange 3.

Install dependencies:

```shell
pnpm install
```

Run tests:

```shell
pnpm run test --filter=chain
```

# About Privacy

> In the current architecture, the centralized sequencer sees every detail of messages.
> To add privacy, a [`ZkProgram`](https://docs.minaprotocol.com/zkapps/tutorials/recursion#zkprogram) can be developed and the message verification logic can be handles inside, then the zk proofs it generates can be used as parameters of runtime methods to privately verify if the computation done is correct.
