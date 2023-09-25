---
sidebar_position: 2
---

# EAS Contracts

Deployments
Please note that you can also import and use the addresses directly in your code using the @ethereum-attestation-service/eas-contracts/deployments deployment artifacts corresponding to your desired network.

## 🛳️ Deployments
:::tip We have deployed on the following chains:
- **Testnets**: Sepolia, Base Goerli, Optimism Goerli, Arbitrum Goerli, Linea Goerli
- **Mainnets**: Ethereum Mainnet, Arbitrum, Optimism, Base, Linea
:::

## Mainnets

### Ethereum 
Version `v0.26`

:::info EAS
- **Contract Address:** [0xA1207F3BBa224E2c9c3c6D5aF63D0eb1582Ce587](https://etherscan.io/address/0xA1207F3BBa224E2c9c3c6D5aF63D0eb1582Ce587)
- **Deployment and ABI:** [EAS.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/mainnet/EAS.json)
:::

:::info SchemaRegistry
- **Contract Address:** [0xA7b39296258348C78294F95B872b282326A97BDF](https://etherscan.io/address/0xA7b39296258348C78294F95B872b282326A97BDF)
- **Deployment and ABI:** [SchemaRegistry.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/mainnet/SchemaRegistry.json)
:::

### Optimism
EAS is natively integrated as two predeploy addresses on the OP Stack. Any future OP Stack chains deployed will automatically include the EAS contracts at Genesis.

![Predeploy](./img/predeploy.png)

Version `v1.0.1`:

:::info EAS
- **Contract Address:** [0x4200000000000000000000000000000000000021](https://optimistic.etherscan.io/address/0x4200000000000000000000000000000000000021)
- **Deployment and ABI:** [EAS.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/optimism/EAS.json)
:::

:::info SchemaRegistry
- **Contract Address:** [0x4200000000000000000000000000000000000020](https://optimistic.etherscan.io/address/0x4200000000000000000000000000000000000020)
- **Deployment and ABI:** [SchemaRegistry.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/optimism/SchemaRegistry.json)
:::

### Base
Version `v1.0.1`:

:::info EAS
- **Contract Address:** [0x4200000000000000000000000000000000000021](https://basescan.org/address/0x4200000000000000000000000000000000000021)
- **Deployment and ABI:** [EAS.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/optimism/SchemaRegistry.json)
:::

:::info SchemaRegistry
- **Contract Address:** [0x4200000000000000000000000000000000000020](https://basescan.org/address/0x4200000000000000000000000000000000000020)
- **Deployment and ABI:** [SchemaRegistry.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/arbitrum-one/SchemaRegistry.json)
:::


### Arbitrum One
Version `v0.26`:

:::info EAS
- **Contract Address:** [0xbD75f629A22Dc1ceD33dDA0b68c546A1c035c458](https://arbiscan.io/address/0xbD75f629A22Dc1ceD33dDA0b68c546A1c035c458)
- **Deployment and ABI:** [EAS.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/arbitrum-one/EAS.json)
:::

:::info SchemaRegistry
- **Contract Address:** [0xA310da9c5B885E7fb3fbA9D66E9Ba6Df512b78eB](https://arbiscan.io/address/0xA310da9c5B885E7fb3fbA9D66E9Ba6Df512b78eB)
- **Deployment and ABI:** [SchemaRegistry.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/arbitrum-one/SchemaRegistry.json)
:::

### Linea
Version `v1.2.0`:

:::info EAS
- **Contract Address:** [0xaEF4103A04090071165F78D45D83A0C0782c2B2a](https://lineascan.build/address/0xaEF4103A04090071165F78D45D83A0C0782c2B2a)
- **Deployment and ABI:** [EAS.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/linea/EAS.json)
:::

:::info SchemaRegistry
- **Contract Address:** [0x55D26f9ae0203EF95494AE4C170eD35f4Cf77797](https://lineascan.build/address/0x55D26f9ae0203EF95494AE4C170eD35f4Cf77797)
- **Deployment and ABI:** [SchemaRegistry.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/linea/SchemaRegistry.json)
:::


## Testnets

### Sepolia
Version `v0.26`:

:::info EAS
- **Contract Address:** [0xC2679fBD37d54388Ce493F1DB75320D236e1815e](https://sepolia.etherscan.io/address/0xC2679fBD37d54388Ce493F1DB75320D236e1815e)
- **Deployment and ABI:** [EAS.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/sepolia/EAS.json)
:::

:::info SchemaRegistry
- **Contract Address:** [0x0a7E2Ff54e76B8E6659aedc9103FB21c038050D0](https://sepolia.etherscan.io/address/0x0a7E2Ff54e76B8E6659aedc9103FB21c038050D0)
- **Deployment and ABI:** [SchemaRegistry.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/sepolia/SchemaRegistry.json)
:::


### Optimism Goerli
Version `v1.0.1`:

:::info EAS
- **Contract Address:** [0x4200000000000000000000000000000000000021](https://goerli-optimism.etherscan.io/address/0x4200000000000000000000000000000000000021)
- **Deployment and ABI:** [EAS.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/optimism-goerli/EAS.json)
:::

:::info SchemaRegistry
- **Contract Address:** [0x4200000000000000000000000000000000000020](https://goerli-optimism.etherscan.io/address/0x4200000000000000000000000000000000000020)
- **Deployment and ABI:** [SchemaRegistry.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/optimism-goerli/SchemaRegistry.json)
:::



### Base Goerli
Version `v0.27`:

:::info EAS
- **Contract Address:** [0xAcfE09Fd03f7812F022FBf636700AdEA18Fd2A7A](https://goerli.basescan.org/address/0xAcfE09Fd03f7812F022FBf636700AdEA18Fd2A7A)
- **Deployment and ABI:** [EAS.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/base-goerli/EAS.json)
:::

:::info SchemaRegistry
- **Contract Address:** [0x720c2bA66D19A725143FBf5fDC5b4ADA2742682E](https://goerli.basescan.org/address/0x720c2bA66D19A725143FBf5fDC5b4ADA2742682E)
- **Deployment and ABI:** [SchemaRegistry.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/base-goerli/SchemaRegistry.json)
:::


### Arbitrum Goerli
Version `v1.1.0`:

:::info EAS
- **Contract Address:** [0xaEF4103A04090071165F78D45D83A0C0782c2B2a](https://github.com/goerli.arbiscan.io/address/0xaEF4103A04090071165F78D45D83A0C0782c2B2a)
- **Deployment and ABI:** [EAS.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/arbitrum-goerli/EAS.json)
:::

:::info SchemaRegistry
- **Contract Address:** [0x55D26f9ae0203EF95494AE4C170eD35f4Cf77797](https://github.com/goerli.arbiscan.io/address/0x55D26f9ae0203EF95494AE4C170eD35f4Cf77797)
- **Deployment and ABI:** [SchemaRegistry.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/arbitrum-goerli/SchemaRegistry.json)
:::


### Linea Goerli
Version `v1.2.0`:

:::info EAS
- **Contract Address:** [0xaEF4103A04090071165F78D45D83A0C0782c2B2a](https://goerli.lineascan.build/address/0xaEF4103A04090071165F78D45D83A0C0782c2B2a)
- **Deployment and ABI:** [EAS.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/linea-goerli/EAS.json)
:::

:::info SchemaRegistry
- **Contract Address:** [0x55D26f9ae0203EF95494AE4C170eD35f4Cf77797](https://goerli.lineascan.build/address/0x55D26f9ae0203EF95494AE4C170eD35f4Cf77797)
- **Deployment and ABI:** [SchemaRegistry.json](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/deployments/linea-goerli/SchemaRegistry.json)
:::

## Installation
```bash
pnpm add @ethereum-attestation-service/eas-contracts
```

## Testing
Testing the protocol is possible via multiple approaches:

### Unit Tests
You can run the full test suite via:

```bash
pnpm test
```
### Test Coverage
Latest Test Coverage Report (2023-08-31)
- 100% Statements 313/313
- 100% Branches 160/160
- 100% Functions 105/105
- 100% Lines 450/450

| File                              | % Stmts | % Branch | % Funcs | % Lines | Uncovered Lines |
|-----------------------------------|---------|----------|---------|---------|-----------------|
| contracts/                        | 100     | 100      | 100     | 100     |                 |
|   Common.sol                      | 100     | 100      | 100     | 100     |                 |
|   EAS.sol                         | 100     | 100      | 100     | 100     |                 |
|   IEAS.sol                        | 100     | 100      | 100     | 100     |                 |
|   ISchemaRegistry.sol             | 100     | 100      | 100     | 100     |                 |
|   SchemaRegistry.sol              | 100     | 100      | 100     | 100     |                 |
|   Semver.sol                      | 100     | 100      | 100     | 100     |                 |
| contracts/eip1271/                | 100     | 100      | 100     | 100     |                 |
|   EIP1271Verifier.sol             | 100     | 100      | 100     | 100     |                 |
| contracts/eip712/proxy/           | 100     | 100      | 100     | 100     |                 |
|   EIP712Proxy.sol                 | 100     | 100      | 100     | 100     |                 |
| contracts/eip712/proxy/examples/  | 100     | 100      | 100     | 100     |                 |
|   PermissionedEIP712Proxy.sol     | 100     | 100      | 100     | 100     |                 |
| contracts/resolver/               | 100     | 100      | 100     | 100     |                 |
|   ISchemaResolver.sol             | 100     | 100      | 100     | 100     |                 |
|   SchemaResolver.sol              | 100     | 100      | 100     | 100     |                 |
| contracts/resolver/examples/     | 100     | 100      | 100     | 100     |                 |
|   AttestationResolver.sol         | 100     | 100      | 100     | 100     |                 |
|   AttesterResolver.sol            | 100     | 100      | 100     | 100     |                 |
|   DataResolver.sol                | 100     | 100      | 100     | 100     |                 |
|   ExpirationTimeResolver.sol      | 100     | 100      | 100     | 100     |                 |
|   PayingResolver.sol              | 100     | 100      | 100     | 100     |                 |
|   RecipientResolver.sol           | 100     | 100      | 100     | 100     |                 |
|   RevocationResolver.sol          | 100     | 100      | 100     | 100     |                 |
|   TokenResolver.sol               | 100     | 100      | 100     | 100     |                 |
|   ValueResolver.sol               | 100     | 100      | 100     | 100     |                 |
| All files                         | 100     | 100      | 100     | 100     |                 |


### Instructions
In order to audit the test coverage of the full test suite, run:

```bash 
pnpm test:coverage
```

### Profiling
You can profile the gas costs of all of the user-focused flows via:

```bash
pnpm test:profile
```

## Deploying
The contracts have built-in support for deployments on different chains and mainnet forks. You can deploy the project by:

```bash
pnpm deploy
```
There’s also a special deployment mode which deploys the protocol to a mainnet fork, with additional goodies. It can be run via:

```bash
pnpm deploy:fork
```
The framework was inspired and adopted from [Bancor V3](https://github.com/bancorprotocol/contracts-v3).

## License
EAS is open source and distributed under the MIT License (see [LICENSE](https://github.com/ethereum-attestation-service/eas-contracts/blob/master/LICENSE)).