# Solana / MemeCoin Distribution

## overview

-This Sol/Token distribution works from a single wallet to multiple wallets in a way that remains undetectable by Bubble Maps. The setup works reliably with around 30–35 wallets in batch.

A single Solana transaction has a maximum size of 1232 bytes.
Since one account public key is 32 bytes, this theoretically allows for 1232 / 32 ≈ 38 accounts per transaction.
In practice, after accounting for instructions, signatures, and overhead, the realistic limit is around 30–35 wallets per transaction.
Because this distribution is implemented by smart contract.

- It can be customisable with new features
- It is under private mode if you need let's chat on [telegram](https://t.me/roswellecho)
- I've tested it in new creasted 3 wallets. It was undetectable by bubblemap
https://solscan.io/account/FbSJne5B7t4fE6ajVP81v4KAEgxVwp2VxriX6ATWGsXH
https://solscan.io/account/9ZzawEW6nQWjocMGcTHs9UEVFvkV9XRJkVV5d7VGHbEJ
https://solscan.io/account/DebW5tjr6eMgsk4TqwPebvFW3UzSdNQNchvE9kZcX34

## how it works

Create an ATA
Distribute SOL by wrapping it into WSOL
Unwrap WSOL
Distribute SOL to newly created wallets
Close the ATA
