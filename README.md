# synthswap-tokenlist

### Whitelisting instructions

- Fork this repo
  ```
  gh repo clone synthswapdev/synth-tokenlist
  ```
- Create a folder under *assets/{tokenAddress}*
- Add token's icon (logo.png) under the folder created in the previous step
- Add token's info in the *tokenlist.json* file, in this format:
- Bump the patch version one iteration
  ```
  {
      "name": [token_name],
      "address": [token_address],
      "symbol": [token_symbol],
      "decimals": [token_decimals],
      "chainId": 8453,
      "logoURI": "https://raw.githubusercontent.com/synthswapdev/synth-tokenlist/main/assets/[token_address]/logo.png"
  }
  ```
- Make a Pull Request to this repo including all of the above.

<br>

