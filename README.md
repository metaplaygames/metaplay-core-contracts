
# Staking Deploy

- deploy Staking
  npx hardhat run scripts/deployStaking.ts --network bsct
- call staking.setTokenPerBlock
- call staking.setToken
- call staking.startStaking

# LPMining Deploy

- deploy LPMining
  npx hardhat run scripts/deployLPMining.ts --network bsct
- call LPMining.add(1000, lp, false)
- call LPMining.setTokenPerBlock

# Testnet addresses

- Staking https://testnet.bscscan.com/address/0x846B36be13B4f09972e7102Ee6E09d801c853C61
- LPMining https://testnet.bscscan.com/address/0x7c48fFe90EE9BD019621d9C3B601BA217a65B35f

# Mainnet addresses

- PLAY STAKING: https://bscscan.com/address/0x5D627dd87F1c583e3C15024ca675770D412809F1
- PLAY-BUSD LPMining: https://bscscan.com/address/0x87c1cb0A58AEa9F0Dea1A7445be4BA6c07E20E91
