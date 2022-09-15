---
description: "Build on Bulldogswap and need help? let us know."
---

## ✨ Building on Bulldogswap and DogeChain

## **Bulldogswap Mainnet Contracts:**

`Mainnet Deployed @ https://exchange.Bulldogswap.dog`

**Router Address**: `0x09C5b9EC02866A512235c478b841e4Cdbbf9C996`

**Factory Address**: `0x58e08Fec721c3aecc2010928937291A7B33D9e95`

**Multicall Address**: `0xBBa16192B6F91765ABDFb795934835113D6d552B`

**WWDOGE Address**: `0xB7ddC6414bf4F5515b52D8BdD69973Ae205ff101`

## How to get your token LOGO on Bulldogswap:

### 1. Image for the Token Logo <a id="1-image-for-the-token-logo"></a>

> - **File Extension**: `png` . Uppercase `PNG` is considered invalid
> - **File Name**：`logo.png`
> - **Size**: `256px by 256px`
> - **Background**: Transparent is a must

### 2. Token Information File <a id="2-token-information-file"></a>

> - Fork the repository and add the token information (example below) to Bulldogswap.tokenlist.json
> - Create a folder under assets/{blockchainName}/{tokenAddress}
> - Add the token icon (logo.png) under the folder created in the previous step
> - Add the token information in the Bulldogswap.tokenlist.json file, in the format shown below

The sample below shows what information has to be included on the `bswap.tokenlist.json` file.  
Please make sure that the details are accurate and follows the formatting.  
The contract address should follow the checksum address format \(see next requirement\).

```
{
       "chainId":2000,
       "address":"0xD21690CFbD4321c75B99d3c1ad7Fbcc1ECa162C2",
       "name":"Bswap Token",
       "symbol":"BSWAP",
       "decimals":18,
       "logoURI":"https://raw.githubusercontent.com/bulldogswapdog/bswap-token-list/main/assets/dogechain/0xD21690CFbD4321c75B99d3c1ad7Fbcc1ECa162C2/logo.png"

},

```

## How to get your LOGO Approved

Fork and Submit @ [https://github.com/yodedex/Bulldogswap-default-tokenlist](https://github.com/yodedex/Bulldogswap-default-tokenlist)

The Pull request will be screened before it gets added to the repository. In order to get approved, your submission must meet the following requirements.

- **Project has a website.**
- **Has a social media presence.**
- **Project must have some trading volume (ie. > $ 20k). This is subject to per project review**
- **Verified Contract on DogeChain Explorer.**
- **Detailed Token Information.**
