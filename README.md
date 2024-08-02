Configuração da Metamask

Foram criadas as contas:
Account Test 1, Account Test 2  e adicionada as redes Binance Smart Chain
e BNB Smart Chain Testnet. 

O Faucet foi obtido e importado através da BNB CHAIN.

Link: https://www.bnbchain.org/en/testnet-faucet


Address: Account Test 1
0x125c17B8c617f4E7F2f4AB14a20A2524bcbD88d6

Token Contract (WITH 18 Decimals)
0xd66c6b4f0be8ce5b39d52e0fd1344c389929b378

Address: Account Test 2
0x4eb1ACb86FF8Dc66785D46Cae0144087C5c4a1bC

Token Contract (WITH 18 Decimals)
0xd66c6b4f0be8ce5b39d52e0fd1344c389929b378


Desenvolvimento Smart contract

O Smart contract "EDDIEToken.sol" no padrão ERC-20 foi desenvolvido
e implementado com Remix - Ethereum IDE


Como Funciona:

O contrato é inicializado com um nome, símbolo, e quantidade total de tokens. O total é atribuído a um endereço específico.

Usuários podem transferir tokens entre si.
Usuários podem autorizar outros endereços a gastar uma quantidade específica de seus tokens.
Endereços autorizados podem usar a função transferFrom para mover tokens em nome do dono autorizado.

O contrato usa operações matemáticas seguras para evitar problemas com overflow e underflow, prevenindo
comportamentos inesperados e falhas de segurança.

O contrato permite que outros contratos chamem a função approveAndCall, o que é útil para integrar com contratos que precisam saber sobre a aprovação e realizar ações adicionais com os tokens.


Links: 
https://metamask.io/
https://rpc.info/
https://remix.ethereum.org/
https://www.bnbchain.org/en/testnet-faucet
https://testnet.bscscan.com
