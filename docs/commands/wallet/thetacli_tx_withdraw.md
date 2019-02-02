## thetacli tx withdraw

withdraw stake to a validator or guardian

### Synopsis

withdraw stake to a validator or guardian

```
thetacli tx withdraw [flags]
```

### Examples

```
thetacli tx withdraw --chain="privatenet" --source=2E833968E5bB786Ae419c4d13189fB081Cc43bab --holder=2E833968E5bB786Ae419c4d13189fB081Cc43bab --purpose=0 --seq=8
```

### Options

```
      --chain string    Chain ID
      --fee string      Fee (default "1000000000000wei")
  -h, --help            help for withdraw
      --holder string   Holder of the stake
      --purpose uint8   Purpose of staking
      --seq uint        Sequence number of the transaction
      --source string   Source of the stake
      --wallet string   Wallet type (soft|nano) (default "soft")
```

### Options inherited from parent commands

```
      --config string   config path (default is /Users/<username>/.thetacli) (default "/Users/<username>/.thetacli")
```

### SEE ALSO

* [thetacli tx](thetacli_tx.md)	 - Manage transactions

###### Auto generated by spf13/cobra on 24-Jan-2019