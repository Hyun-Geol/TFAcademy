"# TFAcademy" 

#Token �����

- 1. Ʈ���� ��ũ�� faucet ��û�ϱ�.

https://www.rinkeby.io/#faucet 

- 2. truffle package ��ġ�ϱ�

https://www.trufflesuite.com/docs/truffle/quickstart

```
npm install -g truffle
mkdir mytoken
cd mytoken
truffle init
```

- 3. openzepplin ��ġ�ϱ�

`npm install zeppelin-solidity`

- 4. myToken ��Ʈ��Ʈ �ۼ�

```
contract/mytoken.sol
migrations/2_deploy_mytoken.js
```


- 5. ��Ʈ�� ���� / ���÷���

truffle.js (or truffle-config.js) �� rinkeby config �ֱ�.

```
truffle deploy --network rinkeby
```

contract address ���� explorer���� token contract Ȯ���ϱ�.

- 6. explorer ���� �����ּ� / contract �ּ� Ȯ���ϱ�

https://rinkeby.etherscan.io/

- 7. MyetherWallet ���� rinkeby network �����ϰ�, ��ū Ȯ���ϱ�.

- 8. ��ū ������ �ޱ�.



