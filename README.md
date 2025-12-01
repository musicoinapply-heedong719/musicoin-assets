# Musicoin Assets Repository

The **Musicoin Assets Repository** serves as the authoritative source for all visual and metadata resources associated with the **Musicoin 3.0 ecosystem**.  
It centralizes token logos, multi-format icon sets, branding materials, and integration-ready metadata to ensure a consistent identity across wallets, explorers, and decentralized platforms.

## Purpose

This repository is designed to provide:

- **Official token logos** in multiple resolutions  
- **Standardized branding assets** for partner platforms  
- **Icon sets** used across Musicoin wallet, DEX interfaces, block explorers, and third-party services  
- **Metadata files**, including ERC-20 Token List compatible JSON  
- A stable and long-term hosting location for logo URLs using **GitHub Raw links**

By maintaining these elements in a unified structure, the Musicoin ecosystem ensures seamless recognition and visual consistency across every platform.

## Repository Structure

musicoin-assets/
 ├── logo/
 │    ├── musicoin-1024.png
 │    ├── musicoin-64.png
 │    ├── musicoin-128.png
 │    └── musicoin-256.png
 ├── tokenlist/
 │    └── musicoin-tokenlist.json
 └── README.md

## Raw File Access (GitHub CDN)

All assets in this repository can be accessed using GitHub Raw URLs, which are ideal for wallet integration, token lists, and explorer submissions.

Example:

https://raw.githubusercontent.com/<username>/musicoin-assets/main/logo/musicoin-256.png

Replace <username> with your GitHub account name.

## Token List Integration

```json
{
  "name": "Musicoin Token List",
  "logoURI": "[https://raw.githubusercontent.com/<username>/musicoin-assets/main/logo/musicoin-256.png](https://raw.githubusercontent.com/musicoinapply-heedong719/musicoin-assets/main/logo/musicoin-256.png)",
  "tokens": [
    {
      "chainId": 137,
      "address": "0xYourTokenAddressHere",
      "name": "Musicoin 3.0",
      "symbol": "MUSIC",
      "decimals": 18,
      "logoURI": "[https://raw.githubusercontent.com/<username>/musicoin-assets/main/logo/musicoin-256.png](https://raw.githubusercontent.com/musicoinapply-heedong719/musicoin-assets/main/logo/musicoin-256.png)"
    }
  ],
  "version": {
    "major": 1,
    "minor": 0,
    "patch": 0
  }
}
```

This format is compatible with:

- Uniswap  
- QuickSwap  
- MetaMask  
- Trust Wallet  
- CoinGecko/CMC Token Lists  
- Most cross-chain DEX aggregators  

## Usage Guidelines

- Always reference the **256×256 PNG** version for the primary token icon.  
- Use GitHub Raw links for maximum compatibility with wallets and explorers.  
- Ensure new versions of logos or metadata follow semantic versioning.  
- Only high-quality and verified assets should be included in this repository.

## Contribution

Only trusted contributors within the Musicoin development team may submit updates.  
All changes should be reviewed before merging to maintain consistency and reliability.

## License

All assets in this repository are provided for use by the official Musicoin ecosystem and its partners.  
Commercial or unauthorized usage outside the Musicoin network is prohibited without permission.

## Contact

For integration support or partnership inquiries, please reach out via the official Musicoin communication channels.
