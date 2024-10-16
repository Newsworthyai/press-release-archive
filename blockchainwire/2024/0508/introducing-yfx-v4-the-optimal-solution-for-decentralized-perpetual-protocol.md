# Introducing YFX V4, The Optimal Solution for Decentralized Perpetual Protocol

The current decentralized perpetual protocols are mainly divided into 4 modes: The PvPool mode adopted by GMX, YFX, gTrade, etc., the centralized order book trading with the decentralized margin mode like Dydx, Apex, Pancake, the leveraged token trading mode of Uniswap by Perpetual Protocol, and the mode of developing a separate public chain dedicated for trading.

As one of the earliest launched decentralized perpetual contract protocols, YFX started in 2020. After three years of development and three version iterations, YFX handed over the project to the geek community in early 2024, jointly managed by the anonymous representative 0xEuler and multiple technical community developers. The new team conducted a comprehensive design and development of the YFX product, and released YFX V4 to the public.

![](https://blockchainwire.s3.amazonaws.com/MediaXAgency/editor_image/96f1876e-eb0f-4d82-8d53-f19b0d1013c5.jpeg)

Story of YFX

V1: Development of YFX V1 began in 2020 and was first released at the beginning of 2021. As one of the pioneers of decentralized perpetual contract products, YFX introduced the PvPool trading model, bringing Contract for Difference (CFD) onto the blockchain. After nearly three years of development in the decentralized perpetual contract industry, trading models such as PvPool, and centralized price feeding have been adopted by leading protocols like GMX and GNS.

V2: In the YFX V2 version, we added features such as position merging, funding fees, limit orders, and stop-loss/take-profit, successfully transitioning from CFDs to true perpetual contracts.

V3: YFX V3 included additions like ChainLink price feeds, dual position mode, interest, invitation systems, and merged liquidity pools, making the protocol more comprehensive.

Features of YFX V4

1. LP Leverage

Unlike traditional CEXs like Binance and BitMex, where traders (Takers) and market makers (Makers) trade in the same model and can engage in up to 100x leverage trading, in most decentralized perpetual contract products including YFX, GMX, and GNS, traders trade with liquidity pools, preventing Makers from using leverage. This results in low capital efficiency for LPs.

YFX V4 introduces an innovative solution to this issue by providing leverage to LPs, allowing them to use up to 200x leverage when adding liquidity. This means LPs can buy the liquidity pool’s YLP at 200x leverage, multiplying their profits by 200 times when the YLP price increases, though this also introduces greater risk.

1. Fair Index Price Oracle:

In the product design of YFX V4, we further optimized by introducing real-time prices from two leading market oracles, ChainLink and PYTH, as the index price for YFX, ensuring the fairness and transparency of index prices.

ChainLink solution: We use ChainLink’s DataStream and Automation to execute market orders and determine if limit orders, stop-loss/take-profit, and liquidation should be triggered.

Pyth solution: We accept real-time prices published by PYTH and verify signatures using Pyth’s official contracts.

1. New LPB-AMM

In YFX V4, we introduce a new LP Balance Automated Market Maker (LP-AMM) model. The trading depth for users is determined by the LP Balance. The more LP Balance there is, the better the trading depth for users, and vice versa.

In the classic UniSwap AMM model, the x*y=k curve is used to calculate the market’s liquidity. In the LP-AMP model of YFX, we introduce a new y=kx+b function and use a segmented function to simulate the depth chart in CEX, ultimately achieving a depth chart similar to the one below.

1. Premium, Market Price

The V4 system adjusts the Premium and Market Price based on the net direction of traders’ positions, aiming to maintain a balance between long and short positions. Specifically, when traders’ net positions are long, the Premium is positive, and the Market Price is higher than the Index Price. This increases the cost of opening new long positions, suppressing the formation of new long positions.

1. New Earning System

YFX will initiate its first mining event after migrating to Arbitrum, including YFX Staking, Position Mining, LP Mining, Trade Mining, and Invite Mining.

Under this incentive system, all platform participants, including Traders, Makers, and inviters, will receive appropriate rewards.

1. Up to 70% Referral Rebate

Thanks to YFX being a decentralized exchange, every transaction fee can be returned in real-time to the inviter’s address, allowing us to execute any rebate strategy transparently. YFX V4 designed a tiered referral system that offers up to 20% fee discounts and 75% fee rebates. High ratio rebates facilitate better cooperation with community nodes, making it easier for YFX to acquire trading users and build a large trading community.

Conclusion:

In summary, YFX V4, as a decentralized perpetual contract protocol, is committed to providing a fair, efficient trading environment. It introduces various innovative mechanisms, such as LP Leverage, LPB-AMM, and Premium, aimed at optimizing capital efficiency, increasing trading depth, and maintaining overall market balance and stability. Through a series of designs and optimizations, YFX V4 aims to offer users a fair, transparent, liquid, and innovation-driven decentralized perpetual contract trading experience.

Website: https://www.yfx.com/?ref=PR

Telegram: https://t.me/YFX_COM

Twitter: https://twitter.com/YFX_COM

Medium: https://yfxdefi.medium.com/

Contact:

0xEuler Ludwig

Email: contact@yfx.com

Disclaimer: The information provided in this press release is not a solicitation for investment, nor is it intended as investment advice, financial advice, or trading advice. It is strongly recommended you practice due diligence, including consultation with a professional financial advisor, before investing in or trading cryptocurrency and securities. 

---

[Original/Source Press Release](https://blockchainwire.io/press-release/introducing-yfx-v4-the-optimal-solution-for-decentralized-perpetual-protocol)
                    

[Newsramp.com TLDR](https://newsramp.com/curated-news/yfx-v4-introduces-innovative-mechanisms-for-decentralized-perpetual-contract-trading/6045ebceb8223e29c07cc01ec94dedb9) 

 



[Reddit Post](https://www.reddit.com/r/GamingNewsRamp/comments/1cn11jl/yfx_v4_introduces_innovative_mechanisms_for/) 



![Blockchain Registration](https://cdn.newsramp.app/blockchainwire/qrcode/245/8/noraqbjY.webp)