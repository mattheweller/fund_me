# fund_me

Tutorial source: https://github.com/smartcontractkit/full-blockchain-solidity-course-py#lesson-2-storage-factory

Covers the following: 

# Lesson 6: [Brownie Fund Me](https://github.com/PatrickAlphaC/brownie_fund_me)
💻 Code: https://github.com/PatrickAlphaC/brownie_fund_me

### Introduction
- Setup
### Dependencies, Deploying, and Networks
- Dependencies
- [chainlink-brownie-contracts](https://github.com/smartcontractkit/chainlink-brownie-contracts)
- remappings
- Deploy Script (V1)
- `helpful_scripts.py`
- `__init__.py`
- Deploy to Rinkeby
- Contract Verification (`publish_source`)
  - The Manual Way
    - "Flattening"
  - The Programatic Way
    - Getting an [Etherscan API Key](https://etherscan.io/apis)
    - `ETHERSCAN_TOKEN`
  - Interacting with Etherscan
- Deploying to Local Chains
- Introduction to Mocking 
- Constructor Parameters
- `networks` in our `brownie-config.yaml`
- Copying [Mock Contracts from chainlink-mix](https://github.com/smartcontractkit/chainlink-mix)
- Deploying and using our mock
- Refactoring
- Deploying to a persistent ganache
- brownie attach
- Adding a persistent brownie network
- resetting a network build
### Funding and Withdrawing Python Scripts
- Whoops! Let's fix an issue...
- Fund Script
- Withdraw Script
### Testing across networks
- `test_can_fund_and_withdraw`
- default networks
- pytest `pip install pytest`
- pytest.skip
- brownie exceptions
- `mainnet-fork`
- Custom mainnet fork
- Adding a development brownie network
  - `brownie networks add development mainnet-fork-dev cmd=ganache-cli host=http://127.0.0.1 fork='https://infura.io/v3/$WEB3_INFURA_PROJECT_ID' accounts=10 mnemonic=brownie port=8545`
- [Alchemy](https://www.alchemy.com/)
- `brownie test --network mainnet-fork`
- brownie ganache vs local ganache vs mainnet-fork vs testnet...
### Git
- [Installing Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- Creating a repository 
- [First time with git](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)
- [Adding our project to github](https://docs.github.com/en/github/importing-your-projects-to-github/importing-source-code-to-github/adding-an-existing-project-to-github-using-the-command-line)
- Tweet it out!