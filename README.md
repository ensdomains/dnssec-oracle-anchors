# dnssec-oracle-anchors

DNS proof of root domain used for DNSSEC Oracle and other utilities

## Install

```
yarn add @ensdomains/dnssec-oracle-anchors
```

## Usage

```
const { realEntries, dummyEntry, encode } import '@ensdomains/dnssec-oracle-anchors'
// Pass it to DNSSEC oracle deployment argement
await deploy(DNSSEC, encode(realEntries))
```