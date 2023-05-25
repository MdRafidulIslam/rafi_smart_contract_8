## rafi_smart_contract_8

### Oracle and chainlink

Decentralized oracles such as Chainlink are required to facilitate the conversion of Ethereum to USD.The value of Ethereum in USD is determined outside of the blockchain and requires the use of decentralized oracle networks to obtain the price of one Ether in terms of USD. It is important to note that blockchains are deterministic systems that cannot directly interact with real-world data or events. They are unable to perform external computations or reach a consensus on certain aspects like random number generation through API calls. This issue, known as the Oracle problem or smart contract connectivity problem, cannot be solved by replacing smart contracts with traditional agreements that rely on real-world data and interactions.

features of chainlink<br>

1.Chainlink data feeds: Chainlink data feeds are utilized in the DeFi space, supporting a substantial value of more than $50 billion. The mechanism involves a network of Chainlink nodes that gather data from various exchanges and data providers. These nodes collaborate to determine the accurate asset price and transmit it as a single transaction to a reference contract, price feed contract, or data contract. Smart contracts leverage this pricing information to drive their decentralized finance (DeFi) applications.

For a more illustrative demonstration, you can observe this example by accessing the following URL: https://data.chain.link/. On this website, you have the ability to switch between different networks and explore various price feeds.<br>

![e1](https://github.com/MdRafidulIslam/rafi_smart_contract_8/assets/86659473/a0998d28-8a4b-4ad3-8908-430c5d766dd7)

Figure1:current price of different blockchain currency in terms of USD

![e2](https://github.com/MdRafidulIslam/rafi_smart_contract_8/assets/86659473/1c7d6b68-a7eb-4868-b6f5-712691523549)

Figure2: users paying oracle gas<br>


Data feeds are utilized by some of the most prominent protocols in the industry, including:

Synthetic (synthetic assets) with a total value secured of 3 billion USD.
SushiSwap (Decentralized Exchange) with a total value secured of 3 billion USD.
Compound (lending and borrowing) with a total value secured of 10 billion USD.
AAVE (lending and borrowing) with a total value secured of 15 billion USD.
To explore an example, you can visit the following link: https://docs.chain.link/.

![e3](https://github.com/MdRafidulIslam/rafi_smart_contract_8/assets/86659473/fcaa54b9-b5c3-4c90-8ab9-8030ffbc5b82)

Figure3: this example contract is used to get the latest price of bitcoin in terms of USD<br>
