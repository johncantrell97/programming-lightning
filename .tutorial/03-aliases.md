# Aliases

The repl comes with a couple aliases that will be useful as we being to program lightning.  Let's take a minute to get familiar and give some of them a try.


## Get a new address

👉 Try generating a new bitcoin address:
```
newaddress
```

You should get a random `bc1...` address like this:
```
bcrt1qcu3y00evy6fs9ush9rpn7ckfl3qznxldteaj35
```

<br/><br/>
## Fund an address

👉 Fund the address generated in the previous command:

```
fund bcrt1qcu3y00evy6fs9ush9rpn7ckfl3qznxldteaj35
```

It will send 1 bitcoin to the provided address.  This is really useful to fund our on-chain wallet that our node will use when opening and closing lightning channels.

<br/><br/>
## Mine blocks

After broadcasting a transaction we will need blocks to be mined.

👉 Try mining 6 blocks to make sure our funding in the last step is sufficiently confirmed:

```
mine 6
```

Mining blocks is useful when you need confirmations on any transaction but in this workshop it will be useful when opening and closing lightning channels.