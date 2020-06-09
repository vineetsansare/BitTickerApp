# BitTickerApp
Simple POC for Poloneix APIs in iOS (swift)

## About App

This is a simple app which basically fetches a tickerData from the Poloniex API, and parses the JSON response into models which are `Codable` structs & ultimately displaying it in a tableView. 

## Note for the Reviewers

**Covered all required activities**
- [x] Project name “BitTicker”. 
- [x] Need to create a Registration and Login pages (you can use any data source or 3rd party to store the data).
- [x] Implement a service called “BitPoloniexService” that connects to Poloniex WebSocket and asks for the ticker info. Implemented WebSocketManager.
- [x] Need to create a model for the ticker.
- [x] A “Trade Highlight” UI/Layout that has an input of a number to be compared with latest price value. This will prefix the element with an Up/Down arrow and change the color to Green/Red depending on the number if it’s positive or negative.

- [x] Render the ticker info into two different custom UI/Views design. The user can switch between these two views as a Default and a second custom UI/View.
Please note that "UI/View '' is a business requirement and not component name meant to see Two different designs for the trading UI and its up to you to design the UI they way you think is appropriate and related to the case.
- [x] Clear README.md that explains how the code and the test can be run

## Running the app

Once you have clonned the app to your local system, you can fire-up the app by opening _BitTickerApp.xcworkspace_ file.

## Important Info 
> _To demonstrate that I also have knowledge on using Cocoapods, I'm using Starscream for connecting websocket api of tickerData._ 

### Screenshots

![1](https://user-images.githubusercontent.com/6418402/84205424-26390280-aabe-11ea-9baf-557675c3492c.png)
![2](https://user-images.githubusercontent.com/6418402/84205431-289b5c80-aabe-11ea-834c-47fe4956d802.png)
![3](https://user-images.githubusercontent.com/6418402/84205434-2a652000-aabe-11ea-8d79-dbd23b58c873.png)
