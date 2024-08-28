# InvestmentGame
Toy Project based on COMP2000

Toy Project

Reach 1 billion through stocks, gambling, and savings

* Input player name
* Initial capital: 10,000 AUD
* When reaching 1 billion AUD, display a congratulatory message and end the game
* When capital is zero or negative, display a mocking message and end the game


# Main Menu Features
    - Check funds
    - Move to stocks / gambling / bank

# Stocks
    - Stock prices change every 5 seconds
    - If a stock price falls to zero or negative, it is delisted and the price is reset
    - Each stock's upper limit is 10 times the opening price for the day

    - Stock A
        - Initial purchase price: 100 AUD
        - Volatility: low, within +-5%
    - Stock B
        - Initial purchase price: 500 AUD
        - Volatility: medium-low, within +-10%
    - Stock C
        - Initial purchase price: 1500 AUD
        - Volatility: low, within +-5%
    - Stock D
        - Initial purchase price: 5000 AUD
        - Volatility: high, within +-30%
    - Stock E
        - Initial purchase price: 5000 AUD
        - Volatility: very high, within +-50%

# Casino
    - Each game lasts 2 seconds
    - Display messages during the game
    - There are 3 gambling options

    - Dice Game
        - Bet amount: 10~500 AUD
        - Compete with the computer using dice numbers
        - Winning probability: 50%
        - Winning: bet amount + 25%
    - Number Game (Small)
        - Bet amount: 500~10,000 AUD
        - The computer generates a random number between 1 and 5
        - Winning probability: 40%
        - Winning: bet amount * 2
        - Number of attempts: 2
    - Number Game (Large)
        - Bet amount: 2000 AUD~no limit
        - The computer generates a random number between 1 and 10
        - Winning probability: 20%
        - Winning: bet amount * 5
        - Number of attempts: 2

# Savings
    - When depositing money in the bank, interest is added every 5 seconds
    - Interest changes every 10 seconds within +-1%
    - Deposit / Withdraw functions
