#### Inventor quantification ([FMZ.COM](https://www.fmz.com)) is the largest digital currency quantification trading platform in China. It supports Javascript/Python/C++/MAI language/visualization, five programming languages, the platform strategy fully supports all of currencies in [BW.COM](https://www.bw.io), and can quickly start quantitative trading.

Please refer to the "User Center - API Setting" page for apikey application and modification.

Please refer to the [**FAQ**](https://github.com/bw-exchange/api_docs_cn/issues) for frequently asked questions.

##

Users with excellent maker strategies and high trading volume are welcome to participate in long-term market making projects. 
The specific rates are as follows:


|User Level|Net assets (equivalent BTC)|30-day trading volume (equivalent BTC)|Maker fee|Taker fee|
|----|:---:|----:|----:|----:|
|**Level 1**|<50|<500|0.10%|0.10%|
|**Level 2**|>=80|>=1000|0|0|



When calculating the fee level, users need to meet both net assets and 30-day trading conditions.

If your BW spot account meets the requirements of **Level 2**, please provide the following information to email:


* BW (spot) market maker application: **support@bw.com**
> 1. Provide uid (uid without commission relationship)
>2. Provide screenshot proof of trading volume from maker of other trading platforms (such as trading volume within 30 days, or VIP level, etc.)
>3. A brief explanation of market-making methods, no details required

**Marketmaker programs do not support VIP, volume related activities or any form of commission rebate**


##

# Spot

## WebSocket market, trade push API

> Address: wss://kline.bw.com/websocket

* [Subscribe illustration](https://github.com/bw-exchange/api_docs_cn/wiki/WebSocket-API-%E8%AE%A2%E9%98%85%E8%AF%B4%E6%98%8E)
* [API Reference](https://github.com/bw-exchange/api_docs_cn/wiki/WebSocket-API-Reference)
* [Error code](https://github.com/bw-exchange/api_docs_cn/wiki/WebSocket-API-%E9%94%99%E8%AF%AF%E7%A0%81)
* Code sample: [Java](https://github.com/bw-exchange/api/tree/master/java) [Python](https://github.com/bw-exchange/api/tree/master/python) [Nodejs](https://github.com/bw-exchange/api_docs_cn/blob/master/nodejsDemo/websocketDemo.js)

## REST market, trading API

> Domain address: https://www.bw.com

* [REST API request specification](https://github.com/bw-exchange/api_docs_cn/wiki/REST-API-%E8%AF%B7%E6%B1%82%E8%AF%B4%E6%98%8E)
* [Signature authentication (important, please read carefully)](https://github.com/bw-exchange/api_docs_cn/wiki/REST-API-%E7%AD%BE%E5%90%8D%E8%AE%A4%E8%AF%81(%E9%87%8D%E8%A6%81%EF%BC%8C%E8%AF%B7%E4%BB%94%E7%BB%86%E9%98%85%E8%AF%BB))
* [API Reference](https://github.com/bw-exchange/api_docs_cn/wiki/REST-API-Reference)
* [Error code](https://github.com/bw-exchange/api_docs_cn/wiki/REST-API--%E9%94%99%E8%AF%AF%E7%A0%81)
* Code sample: [Java](https://github.com/bw-exchange/api/tree/master/java) [Python](https://github.com/bw-exchange/api/tree/master/python) [Nodejs](https://github.com/bw-exchange/api_docs_cn/blob/master/nodejsDemo/restApiDemo.js)
