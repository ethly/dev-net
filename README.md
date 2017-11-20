# Ethereum Development Network

Scripts for easier setup and launch of a private development network.

## Init network

```sh
./init.sh
```
Script will create a private network with 1 account:
```
ID: 0x4Eb84C3BCc0c1C4Cc9d90b415D9FE42532Fe9AdC
Passphrase: 123
Private Key: `0x875f96badbdd3d6c575bd8db6a41bf42a1dc079f8f4b811caa0823ed5322fb24`
Balance: 10^22
```

## Start mining:
```sh
./mine.sh
```
Note that speed of mining is quite high, so don't left the miner running for a long time

## Launch console:
```sh
./console.sh
```

## Drop network:
```sh
rm -rf geth
```
