# 🏦 The SpankBank

!!! Important
    **Before you Stake**: Please read and understand the following SpankBank quirks and caveats! Staking in the SpankBank ***requires active participation***.

    - An address can only stake **once**. Ever.
    - The SpankBank and every staker operate on the same global clock broken into **30-day periods**.
    - Your stake will begin at the start of the **following** period.
    - You **cannot** withdraw SPANK at any point during the stake.
    - Check-ins begin at the start of the **following** period.
    - You **must** have checked-in for the period to be able to claim its BOOTY.
    - Check-ins require an Ethereum transaction (and its fee), but you can also extend your stake in that same transaction.
    - The amount of SPANK counted towards your stake will drop 5% each period _unless_ you choose to extend your stake when checking in.
    - Staking longer will allow more of your SPANK to be counted towards the stake. (See [SpankPoints](#spankpoints))

!!! note
    Full How-to Guides can be found here: [https://help.spankchain.com](https://spankchain.zendesk.com/hc/en-us/categories/360001952592-SpankBank)
<hr>

## SpankBank Overview

The SpankBank is a Merchant-Owned Credit System that powers the two-token SpankChain economic system.

   1. SPANK is a staking token which can be deposited with the SpankBank to earn newly minted BOOTY.

   2. BOOTY 🍑 is a stablecoin good for $1 worth of SpankChain services.

SpankChain will collect fees for using the camsite, payment hub, advertising network, and other services in BOOTY 🍑. The fees are sent to the SpankBank where they are counted and burned.

The SpankBank has a 30 day billing period. At the beginning of each new period, if the total BOOTY 🍑 supply is under the target supply (20x the total fees collected in the previous period), new BOOTY 🍑 is minted to reach the target supply and distributed proportionally to all SPANK stakers.

If let’s say there are 20,000 total BOOTY 🍑 in circulation, and in a given period 20,000 BOOTY 🍑 is transacted on the SpankChain camsite (some BOOTY 🍑 would be re-used and spent multiple times), we would take our 5% cut (1,000 BOOTY 🍑), and send it to SpankBank where it would be counted and burned, leaving only 19,000 BOOTY 🍑 remaining. The target supply would then be 20 x 1,000 BOOTY 🍑 in fees= 20,000 BOOTY 🍑, and so 1,000 new BOOTY 🍑 would be minted to get from 19,000 to 20,000 BOOTY 🍑 and it would be distributed to all SPANK stakers proportional to their SpankPoints.

<hr>

### SpankPoints

| Stake Duration (Periods)    | % of SPANK counted       |
| :-------------------------: | :----------------------: |
|            12               |             100%         |
|            11               |              95%         |
|            10               |              90%         |
|             9               |              85%         |
|             8               |              80%         |
|             7               |              75%         |
|             6               |              70%         |
|             5               |              65%         |
|             4               |              60%         |
|             3               |              55%         |
|             2               |              50%         |
|             1               |              45%         |

In order to earn the maximum BOOTY 🍑, a staker would need to stake for 12 periods, and then opt to extend their stake by 1 period during every check in.

If a staker stakes for 12 periods but doesn't opt to extend their stake during check ins, they would receive 100% of the BOOTY 🍑 for the first period, 95% for the second period, and so forth until they receive 45% during the final period.

<hr>

### BOOTY Burned 🔥🍑🔥 and Minted 💸🍑💸

| Period |    🔥🍑🔥      |   💸🍑💸   |
| :----: | :-----------:  | :-----: |
|    0   |  -- | [10,069](https://etherscan.io/tx/0xc6123eea98af9db149313005d9799eefd323baf1566adfaa53d25cc376229543) |
|    1   |  -- | -- |
|    2   |  -- | -- |
|    3   | [979.85](https://etherscan.io/tx/0x5a644a10ccd6321efde78531a36e92af1e92c496909e9131381d5fe94247f8bf) | [10,507.85](https://etherscan.io/tx/0x0ec465325f6d24ffe161d0da1779cbd496614e43a1f38d44aa77b08d55653d9e) |
|    4   | [400](https://etherscan.io/tx/0x2738086bee4fee62f7da6935078e4c2cc3904a3da76bd857d564426b7e421a58) | -- |
|    5   | [350](https://etherscan.io/tx/0xceaea06cea720fad8db57c955102faef7c880dc372f0ec8643f02c2da7f05ab8) | -- |
|    6   |  -- | -- |
|    7   | [1400](https://etherscan.io/tx/0xaefbd6d4cb5c6d1cd5109651ba9f4ae42b843e7614b984fe9cb3f75034ca583d) | [10,553.01](https://etherscan.io/tx/0x032e9cd9c2e281c17ddbd83bba821365fb0901da380edc66090c172069ec855e) |
|    8   | [986](https://etherscan.io/tx/0xeec6519189354e57a623caa2acdb13402c85c9909aee8a46dddfbec8acaa8f7a) | -- |
|    9   | [783](https://etherscan.io/tx/0x8fb738da9acc6aede6359a0102ae1f26938ebd34790a0888f98370671e7926b2) | -- |
|   10   | [673.09](https://etherscan.io/tx/0xd3cf062b78f25e6c2c41998caa8f671bdaca658cfd6f555f9465cdd36c25fdcb) | -- |