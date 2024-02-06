# Centralized-Exchange-Platform-Built-with-Golang

Cex platform written in golang for crypto exchange, order books, etc. integration of Automated Market Maker (AMM) to enable liquidity provision and automated trading for users, enhancing the efficiency and liquidity of the platform.

### Features
- Automated Market Maker (AMM): Enable liquidity provision and automated trading for users.
- User Registration: Users can register with their private keys.
- Order Placement: Place both market and limit orders.
- Orderbook Management: Efficient management of orderbooks for various markets.
- User Order Tracking: Keep track of users' orders and trades.
- Secure Transactions: Utilize Ethereum blockchain for secure and transparent transactions.

### Installation
Install Go: Ensure you have Go installed on your system. You can download it from the official Go website.

Clone the Repository: Clone the Crypto CEX Package Server repository from GitHub:

```
git clone https://github.com/ayoseun/Centralized-Exchange-Platform-Built-with-Golang.git
```
Install Dependencies: Navigate to the project directory and install dependencies:
```bash
cd Centralized-Exchange-Platform-Built-with-Golang
```
```go
go mod tidy
```
Build the Server: Build the server binary:

```go
go build -o Centralized-Exchange-Platform-Built-with-Golang
```
or run Makefile

```bash
make
```
Start the Server: Start the server:

```bash
./Centralized-Exchange-Platform-Built-with-Golang
```

### Usage

1. Register Users: Users can be registered with their private keys using the provided API.

2. Place Orders: Users can place both market and limit orders via the provided API endpoints.

3. Get Orderbook: Retrieve orderbook data for specific markets using the appropriate API endpoint.

4. Get User Orders: Get a list of orders placed by a specific user using the provided API endpoint.

5. Cancel Orders: Users can cancel their orders using the provided API endpoint.

6. Get Best Bid/Ask: Get the best bid/ask price for a specific market using the respective API endpoints.

7. Get Trades: Retrieve trade history for a specific market using the provided API endpoint.


### Contributing

Contributions to the Crypto CEX Package Server are welcome! To contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch (git checkout -b feature/my-feature).
3. Make your changes and commit them (git commit -am 'Add new feature').
4. Push to the branch (git push origin feature/my-feature).
5. Create a new Pull Request.

### License

This project is licensed under the MIT License. See the LICENSE file for details.