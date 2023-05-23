# DeFi Guardian

# Rate Limiter Smart Contract

This is a rate limiter smart contract implemented in Solidity. The purpose of this contract is to prevent hacks or misuse of funds by enforcing withdrawal limits and withdrawal periods for specific tokens. The contract allows only authorized contracts to interact with it. We take an agnostic approach to the internals of what is happening within the DeFi application. 

DeFi Gaurdian provides a walled garden for your users, an assurance that in the event of a hack, only the maximum rate limit percentage will be drained. 

![DeFi Guardian](https://github.com/diyahir/ETH-TOKYO-2023-Rate-Limits/assets/32445955/8de3f2f5-5085-4cd1-856c-688cc9084d06)


# Testing 

```bash
forge test
```

## Features

- Supports multiple tokens with individual withdrawal limits and periods.
- Records inflows of tokens and locks them for withdrawal if rate limit hit.
- Enforces withdrawal limits and periods to prevent excessive fund withdrawals.
- Allows the contract owner to register tokens, override limits, and transfer admin privileges.
- Provides a convenient function for guarded contracts to record inflows and withdraw available funds.

## License

The smart contract is licensed under the UNLICENSED license.

**Note:** The provided smart contract is a simplified example and might not cover all security considerations and edge cases. It is always recommended to conduct a thorough security review and testing before deploying any smart contract in a production environment.



