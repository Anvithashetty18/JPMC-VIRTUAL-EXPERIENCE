# JPMC Task 1:Interface with a stock price data feed
Starter repo for task 1 of the JPMC software engineering program

Purpose
We want to process the data feed of stock A and stock B’s price to enable us to analyse when trading for the stock should occur.

Acceptance Criteria

getDataPoint function should return correct tuple of stock name, bid_price, ask_price and price. Note: price of a stock = average of bid and ask
getRatio function should return the ratio of the two stock prices
main function should output correct stock info, prices and ratio

#commands
cd forage-jpmc-swe-task-1
git add .
git commit -m "Create Patch File"
git format-patch -1 HEAD #patch file of commit
