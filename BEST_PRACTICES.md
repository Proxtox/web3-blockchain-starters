# Best Practices

Recommendations when using or building on these starters.

## General
- Always audit smart contracts before mainnet deployment
- Start with testnets (Base Sepolia, Arc testnet, Solana devnet, etc.)
- Write comprehensive tests
- Use environment variables for sensitive data

## Frontend
- Use established wallet connection libraries (RainbowKit, Privy, @solana/wallet-adapter)
- Handle loading and error states properly
- Add transaction confirmation feedback

## Cross-Chain
- Be careful with bridge selection and liquidity
- Test failure and recovery scenarios thoroughly
- Consider using CCTP where possible for stablecoins

## Security
- Follow the principle of least privilege
- Add emergency pause mechanisms where appropriate
- Monitor for unusual activity

## Documentation
- Keep READMEs and guides up to date
- Add clear examples
- Document any custom changes you make

Following these practices will help you build more reliable and secure applications.