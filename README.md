## ⛓📊🐍 blockchain science - python edition

<br>

### my cryptography experiments

* **[fixed-graph-py, generate zero-knowledge proof symbolic graphs](https://github.com/autistic-symposium/blockchain-science-py/tree/main/fixed-graph-py)**:
    * in zkps we want to prove a statement where `f` evaluated at `x_i` results in `(y_1,...,y_n)`, i.e., `f(x_1, ..., x_n) = (y_1, ..., y_n)`
    * this can be expressed as a fixed computational graph, where relationships between nodes are related by operations such as **multiplication or addition**
    * in addition, some nodes can be related with an **equality relationship** on which the node's value is computed outside of the graph and constrained by a **hint**

<br>

* **[magick-py, a simple private information retrieval CLI tool](magick-py/):**
  * learn and run experiments to understand **zero-knowledge private information retrieval** through step-by-step mathematical calculations

<br>


-----

### my trading bots and strategies


* **[cointegration trading bots and CLI](cointegration-bots):**
  * run **highly customized** trading bots with **statistical algorithmic strategies** such as **cointegration**
  * it includes an option for **docker deployment**

<br>

* **[quantitative defi study](quantitative_defi):**
  * a comprehensive study on data sources for quantitative defi, including **[yfinance](https://pypi.org/project/yfinance/), [panda_datareader](https://pandas-datareader.readthedocs.io/en/latest/), [alpha_advantage](https://www.alphavantage.co/), [CoinAPI](https://www.coinapi.io/),** and **[quandl](https://data.nasdaq.com/publishers/QDL)**
  * the data from every source is prepared, and then the **mean, skew, kurtosis, percentage change, and other statistics are calculated**
  * plots for **prices, return, and candles** for each data set

<br>

----


### my jupyter notebooks


* **[extracting on-chain data from a list of ethereum public addresses](on-chain-data-by-address):**
    * given a list of **public addresses**, extract the current **token balance**, and parse the **transaction history** for token transfers/swaps

<br>

* **[transfer events analysis through ethereum RPC API's `eth_getLogs`](transfer-events-analysis):**
    * leverage **[infura](https://docs.infura.io/infura/)**'s rpc url to retrieve and parse transfer events logs for a given erc20 token, calculating balances and token holders

<br>

* **[leveraging uniswap subgraph to extract token pair information](uniswap-data):**
    * utilize the **graph explorer** to access **uniswap subgraph** and analyze the **UNI and WETH token pair** data

<br>

* **[DEXs analysis: PMM dodo, AMM uniswap V2, AMM curve stableswap](dexs-equations-analysis):**
    * maths && plots go-to for **decentralized exchanges analysis**

<br>
    
* **[retrieving DAO tokens and pools data](dao-data):**
    * utilize the **graph explorer** to analyze the data related to a list of **DAO tokens**

<br>

* **[messari API for token market data](messari-assets-data):**
    * utilize **[messari API](https://messari.io/api)** to retrieve **market data** for a list of tokens

<br>

* **[leveraging moralis API to extract on-chain transactions, tokens, events, defi](moralis-tokens-and-txs):**
    * **moralis API** is a nice wrapper for several **on-chain calls** that would instead use several other native APIs and tools

<br>


---

### external resources


* **[crypto market data apis list](https://mixedanalytics.com/knowledge-base/top-free-crypto-apis/)**
* **[coinmarketcap historical data](https://coinmarketcap.com/currencies/ethereum/historical-data/)**
* **[uniswap extractooor data](https://www.uniswap.shippooor.xyz/)**
* **[the autistic symposium's blockchain infrastructure design](https://github.com/autistic-symposium/blockchain-infrastructure-design)**



