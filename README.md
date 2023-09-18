# Stock Exchange Order Book System

## Project Description:

In the world of financial markets, stock exchanges are essential platforms where buyers and sellers trade stocks and other financial instruments. Building a Stock Exchange Order Book System is a challenging and impactful project that demonstrates your expertise as a quant developer. This system will handle incoming orders for various stocks, manage order book data, and provide real-time market information to traders.

## Key Features:

* Order Processing: The system will process incoming orders, which can be either buy or sell orders for different stocks. Each order will include details such as order type (buy or sell), order ID, stock symbol, price, and quantity.

* Order Book Management: Maintain a centralized order book for each stock symbol. The order book will keep track of all open orders for a particular stock, including buy and sell orders. Each order entry will store relevant information, such as order ID, price, and quantity.

* Order Matching: Implement a matching engine that matches buy and sell orders based on price-time priority. When a buy order's price matches or exceeds a sell order's price (for the same stock), a trade is executed, and both orders are removed from the order book.

* Order Cancellation: Allow traders to cancel their open orders by specifying the order ID. Canceled orders should be removed from the order book.

* Market Data View: Provide traders with real-time market data, including the best bid and ask prices, trading volume, and other relevant statistics for each stock.

## Input/Output:

Orders will arrive as a stream of events similar to the original problem statement, with commands like ADD to add orders, DEL to delete orders, and DEL_PRICE to delete orders at a specific price level. Traders can also request a market view for a specific stock, which will display the order book, best bid and ask prices, and other market data.

## Coding Tasks:

* Create data structures to represent orders, order books, and market data.
* Implement methods for adding orders, deleting orders, and updating the order book.
* Develop a matching engine to execute trades when buy and sell orders match.
* Implement order cancellation functionality.
* Calculate and update real-time market statistics.

By successfully completing this project, I can showcase your skills in algorithmic trading, order book management, and real-time market data handling on my quant developer resume. It demonstrates my ability to work with financial data, optimize trading algorithms, and contribute to the development of trading systems, which are highly sought-after skills in the finance industry. Additionally, it highlights your proficiency in data structures and algorithms, crucial for quantitative development roles.