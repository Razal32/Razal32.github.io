# DyDx
Cтремится создать мощную и профессиональную биржу для торговли криптоактивами, где пользователи могут по-настоящему владеть своими сделками и, в конечном итоге, самой биржей.

Контракты:
Bridge(usdc) https://etherscan.io/address/0xD54f502e184B6B739d7D27a6410a67dc462D69c8 реализация https://etherscan.io/address/0x2C0df87E073755139101b35c0A51e065291cc2d3#code предусмотрена обновляемость
GpsStatementVerifier https://etherscan.io/address/0xC8c212f11f6ACca77A7afeB7282dEBa5530eb46C https://etherscan.io/address/0x894c4a12548FB18EaA48cF34f9Cd874Fc08b7FC3#code предусмотрена обновляемость
MemoryPageFactRegistry https://etherscan.io/address/0xEfbCcE4659db72eC6897F46783303708cf9ACef8
FriStatementContract https://etherscan.io/address/0xf6b83CcaDeee478FC372AF6ca7069b14FBc5E1B1
MerkleStatementContract https://etherscan.io/address/0x0d62bac5c346c78DC1b27107CAbC5F4DE057a830

Текущее развертывание сопряжено с некоторыми сопутствующими рисками:
Средства могут быть украдены, если контракт получает обновление вредоносного кода. Задержек при обновлении кода нет

сайт(https://dydx.exchange/)
социалки(https://dydx.exchange/blog, https://twitter.com/dydxprotocol, https://discord.gg/Tuze6tY, https://youtube.com/c/dydxprotocol, https://reddit.com/r/dydxprotocol/, https://linkedin.com/company/dydx)
эндпоинты приложения(https://trade.dydx.exchange/, https://margin.dydx.exchange/)
доки(https://docs.starkware.co/starkex-docs-v2/, https://docs.dydx.exchange/)
код(https://github.com/starkware-libs/starkex-contracts, https://github.com/dydxprotocol/)

Вкусные ссылочки:
Enforcing Consistency on the On-Chain State - StarkEx documentation https://docs.starkware.co/starkex-v3/starkex-deep-dive/off-chain-state#enforcing-consistency-on-the-on-chain-state
STARK Core Engine Deep Dive
https://medium.com/starkware/starkdex-deep-dive-the-stark-core-engine-497942d0f0ab
ZK-Rollup - StarkEx documentation
https://docs.starkware.co/starkex-v3/starkex-deep-dive/data-availability-modes#zk-rollup
UpdatePerpetualState.sol#L82 - Etherscan source code
https://etherscan.io/address/0xdf9c117cad37f2ed8c99e36a40317d8cc340d4a0#code#F35#L82
Operator - StarkEx documentation
https://docs.starkware.co/starkex-v3/starkex-deep-dive/smart-contracts-1/contract-management#operator
Censorship Prevention - StarkEx documentation
https://docs.starkware.co/starkex-v3/architecture/overview#8-censorship-prevention
Forced Trade - StarkEx documentation
https://docs.starkware.co/starkex-v3/starkex-deep-dive/regular-flows/flows-for-off-chain-accounts/forced-operations/perpetual-trading-forced-withdrawal-and-forced-trade#forced-trade
Withdrawal - StarkEx documentation
https://docs.starkware.co/starkex-v3/starkex-deep-dive/regular-flows/flows-for-off-chain-accounts/withdrawal
Forced Operations - StarkEx documentation
https://docs.starkware.co/starkex-v3/starkex-deep-dive/regular-flows/flows-for-off-chain-accounts/forced-operations
Forced Withdrawal - StarkEx documentation
https://docs.starkware.co/starkex-v3/starkex-deep-dive/smart-contracts-1/in-spot-trading/in-perpetual-trading
Full Withdrawal - StarkEx documentation
https://docs.starkware.co/starkex-v3/starkex-deep-dive/smart-contracts-1/in-spot-trading/in-spot-trading

# Loopring
Решение Loopring zkRollup предлагает те же гарантии безопасности, что и основная сеть Ethereum, с большим увеличением масштабируемости: пропускная способность увеличена в 1000 раз, а стоимость снижена до 0,1% от L1.

Контракты:
Exchange https://etherscan.io/address/0x0BABA1Ad5bE3a5C0a66E7ac838a129Bf948f1eA4 https://etherscan.io/address/0x3c294fCF74129d649325F8995afC2f9CfaFAB9dA#code admin: https://etherscan.io/address/0xDd2A08a1c1A28c1A571E098914cA10F2877D9c97#code
DefaultDepositContract(https://etherscan.io/address/0x674bdf20A0F284D710BC40872100128e2d66Bd3f) DAI, ETH, LINK, LRC, MKR, USDC, USDT, WBTC
Owner https://etherscan.io/address/0x153CdDD727e407Cb951f728F24bEB9A5FaaA8512

Текущее развертывание сопряжено с некоторыми сопутствующими рисками:
Средства могут быть украдены, если контракт получает обновление вредоносного кода. Задержек при обновлении кода нет

сайт(https://loopring.org/)
социалки(https://loopring.org/#/blog, https://medium.com/loopring-protocol, https://twitter.com/loopringorg, https://discord.gg/KkYccYp, https://youtube.com/c/loopring, https://weibo.com/loopringfoundation, https://reddit.com/r/loopringorg/, https://loopring.substack.com/)
эндпоинты(https://exchange.loopring.io/)
доки(https://github.com/Loopring/protocols/blob/master/packages/loopring_v3/DESIGN.md)
код(https://github.com/Loopring/protocols)

Вкусные ссылочки:
Operators - Loopring design doc
https://github.com/Loopring/protocols/blob/master/packages/loopring_v3/DESIGN.md#operators
Introduction - Loopring design doc
https://github.com/Loopring/protocols/blob/master/packages/loopring_v3/DESIGN.md#introduction
ExchangeV3.sol#L315-L322 - Loopring source code
https://github.com/Loopring/protocols/blob/master/packages/loopring_v3/contracts/core/impl/ExchangeV3.sol#L315-L322
LoopringIOExchangeOwner.sol#L123-L126 - Loopring source code
https://github.com/Loopring/protocols/blob/master/packages/loopring_v3/contracts/aux/access/LoopringIOExchangeOwner.sol#L123-L126
Forced Withdrawals - Loopring design doc
https://github.com/Loopring/protocols/blob/master/packages/loopring_v3/DESIGN.md#forced-withdrawals
Forced Request Handling - Loopring design doc
https://github.com/Loopring/protocols/blob/master/packages/loopring_v3/DESIGN.md#forced-request-handling
Withdraw - Loopring design doc
https://github.com/Loopring/protocols/blob/master/packages/loopring_v3/DESIGN.md#withdraw

# ZKSpace


# ZKSync
zkSync — это ориентированная на пользователя роллап-платформа zk от Matter Labs, работающая в основной сети Ethereum.

Контракты:
UpgradeGatekeeper https://etherscan.io/address/0x38A43F4330f24fe920F943409709fc9A6084C939
Governance https://etherscan.io/address/0x34460C0EB5074C29A9F6FE13b8e7E23A0D08aF01 https://etherscan.io/address/0x9a97008ccCbDEc3413F9304602427e66895996A0#code https://etherscan.io/address/0x38A43F4330f24fe920F943409709fc9A6084C939#code
Verifier https://etherscan.io/address/0x5290E9582B4FB706EaDf87BB1c129e897e04d06D https://etherscan.io/address/0xEF974376054490C8d87b8438b4cEC00391ac05b9#code https://etherscan.io/address/0x38A43F4330f24fe920F943409709fc9A6084C939#code
ZkSync https://etherscan.io/address/0xaBEA9132b05A70803a4E85094fD0e1800777fBEF https://etherscan.io/address/0xd61dFf4b146e8e6bDCDad5C48e72D0bA85D94DbC#code https://etherscan.io/address/0x38A43F4330f24fe920F943409709fc9A6084C939#code DAI, ETH, GLM, USDC, USDT, WBTC, UPGRADE_NOTICE_PERIOD 1209600 ~14 дней
ZkSyncNFTFactory https://etherscan.io/address/0x7C770595a2Be9A87CF49B35eA9bC534f1a59552D https://etherscan.io/address/0x7C770595a2Be9A87CF49B35eA9bC534f1a59552D#code
TokenGovernance https://etherscan.io/address/0x5140Cc54Bb876aBE1ba67d15AC66Ad2D42FDf46A https://etherscan.io/address/0x5140Cc54Bb876aBE1ba67d15AC66Ad2D42FDf46A#code



сайт(https://zksync.io/)
социалки(https://medium.com/matter-labs, https://gitter.im/matter-labs/zksync, https://discord.gg/px2aR7w, https://t.me/zksync, https://twitter.com/zksync)
эндпоинты(https://wallet.zksync.io/)
доки(https://zksync.io/dev/)
код(https://github.com/matter-labs/zksync)

Вкусные ссылочки:
Validity proofs - zkSync FAQ
https://zksync.io/faq/security.html#validity-proofs
Cryptography used - zkSync FAQ
https://zksync.io/faq/security.html#cryptography-used
Overview - zkSync documentation
https://zksync.io/dev/#overview
How decentralized is zkSync - zkSync FAQ
https://zksync.io/faq/decentralization.html#how-decentralized-is-zksync
Priority queue - zkSync FAQ
https://zksync.io/faq/security.html#priority-queue
Withdrawing funds - zkSync documentation
https://zksync.io/dev/payments/basic.html#flow
README.md - zkSync Exit Tool
https://github.com/matter-labs/zksync/tree/master/infrastructure/exit-tool
