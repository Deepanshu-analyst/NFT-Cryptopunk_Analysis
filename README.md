<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cryptopunk NFT Analysis Project</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        header {
            background: #333;
            color: #fff;
            padding: 1.5em;
            text-align: center;
        }

        h1 {
            margin: 0;
            font-size: 2em;
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }

        .star-section {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 1.5em;
            margin-bottom: 1.5em;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .section-title {
            color: #555;
            font-size: 1.8em;
            border-bottom: 3px solid #333;
            padding-bottom: 0.5em;
            margin-bottom: 1em;
        }

        .highlight {
            color: #e67e22;
            font-weight: bold;
        }

        .key-feature-list, .findings-list {
            list-style-type: none;
            padding-left: 0;
        }

        .key-feature-list li, .findings-list li {
            padding: 0.5em 0;
            color: #555;
        }

        footer {
            text-align: center;
            padding: 1em;
            background: #333;
            color: #fff;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        a {
            color: #e67e22;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <header>
        <h1>Cryptopunk NFT Analysis Project</h1>
        <p>A comprehensive data analysis project on Cryptopunk NFTs</p>
    </header>

    <div class="container">
        <section class="star-section">
            <h2 class="section-title">💡 Situation</h2>
            <p>
                The NFT market has exploded in popularity, especially for unique collectibles like Cryptopunks. However, the market’s rapid evolution has made it difficult to understand the trends, price fluctuations, and significant transactions that define the Cryptopunk space.
            </p>
            <p>
                This project aims to provide clarity into these trends, targeting investors, collectors, and enthusiasts who seek to make informed decisions in the NFT landscape.
            </p>
        </section>

        <section class="star-section">
            <h2 class="section-title">🎯 Task</h2>
            <p>
                To analyze historical Cryptopunk sales data from 2018-2021, focusing on:
            </p>
            <ul class="key-feature-list">
                <li>Price trends and significant sales</li>
                <li>Transaction volumes and wallet activity</li>
                <li>Identification of high-value assets and market behavior patterns</li>
            </ul>
        </section>

        <section class="star-section">
            <h2 class="section-title">🚀 Action</h2>
            <p>
                The following steps were taken to achieve the project's goals:
            </p>
            <ul class="key-feature-list">
                <li><span class="highlight">Data Extraction and Transformation:</span> SQL queries were used to structure and analyze Cryptopunk sales data across several key metrics.</li>
                <li><span class="highlight">Trend Analysis:</span> Applied moving averages to smooth price trends and identify peak price periods.</li>
                <li><span class="highlight">Transaction Analysis:</span> Detailed analysis of wallet activity and high-value transactions, focusing on user behavior and high-frequency wallets.</li>
                <li><span class="highlight">Visualizations:</span> Created charts to illustrate ETH price distributions, top transactions, and market trends over time.</li>
            </ul>
        </section>

        <section class="star-section">
            <h2 class="section-title">🏆 Result</h2>
            <p>
                The analysis uncovered critical insights into the Cryptopunk NFT market:
            </p>
            <ul class="findings-list">
                <li>There was a <span class="highlight">25% increase in sales</span> from 2019 to 2021, showing growth in demand for Cryptopunk NFTs.</li>
                <li>Identified <span class="highlight">top 5 highest-value transactions</span>, with CryptoPunk #1139 topping the list at $194,000 USD.</li>
                <li><span class="highlight">Wallet Analysis:</span> Wallet "0x1919db36..." had the highest activity with over 130 transactions, revealing patterns of active market participation.</li>
                <li><span class="highlight">Transaction Timing:</span> Tuesdays and Thursdays saw the highest transaction volumes and prices, indicating a mid-week peak in trading activity.</li>
                <li><span class="highlight">Monthly Sales Volume:</span> Monthly volumes ranged from $1M - $2.5M, with peaks surpassing $3M, indicating strong demand during specific periods.</li>
            </ul>
            <p>
                This analysis enables potential investors to make better-informed decisions by identifying valuable trends, high-performing NFTs, and strategic transaction periods.
            </p>
        </section>

        <section class="star-section">
            <h2 class="section-title">🔗 Access the Project</h2>
            <p>
                Explore the complete analysis and SQL scripts on GitHub: 
                <a href="https://github.com/Deepanshu-analyst/NFT-Cryptopunk_Analysis" target="_blank">NFT-Cryptopunk Analysis</a>
            </p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Deepanshu's NFT Cryptopunk Analysis Project</p>
    </footer>

</body>
</html>
