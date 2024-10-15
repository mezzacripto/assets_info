# DonkeSwap Assets Repository
> This is the repository for the DonkeSwap token assets.

This repository hosts the assets for the DonkeSwap tokens list, which includes both the list itself and the associated token logos.

## How to Contribute

1. Begin by forking the repository (<https://github.com/donkelabs/assets_info/fork>).
2. Proceed to create your feature branch by executing `git checkout -b new-token/[token_symbol]`.
3. Incorporate your token into the `sei-evm-tokens-mainnet.json` file.
4. Add your token logo to the `logos` directory. It should follow the convention `[token_address]/logo.png`. It's crucial to ensure that the `[token_address]` folder name is an exact match (including case) with the `address` value in the `sei-evm-tokens-mainnet.json` file.
5. Stage your changes with `git add .`.
6. Commit your changes by executing `git commit -m 'Add token'`.
7. Push your changes to the branch with `git push origin new-token/[token_symbol]`.
8. Finally, create a new Pull Request.

Please remember that only the `sei-evm-tokens-mainnet.json` file and the `logos` directory should be modified. Refrain from modifying or adding any other files or directories.
