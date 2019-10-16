#### Inventor quantification ([FMZ.COM](https://www.fmz.com)) is the largest digital currency quantification trading platform in China. It supports Javascript/Python/C++/MAI language/visualization, five programming languages, the platform strategy fully supports all of currencies in [BW.COM](https://www.bw.io), and can quickly start quantitative trading.

Please refer to the "user center - API Settings" page for apikey application and modification.

Please refer to the [**Issues**](https://github.com/bw-exchange/api_docs_en/issues) for frequently asked questions.

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

* [Subscribe  instructions](https://github.com/bw-exchange/api_docs_en/wiki/WebSocket-API-Subscribe-instructions)
* [API Reference](https://github.com/bw-exchange/api_docs_en/wiki/WebSocket-API-Reference)
* [Error code](https://github.com/bw-exchange/api_docs_en/wiki/WebSocket-API-ErrorCode)
* Code sample: [Java](https://github.com/bw-exchange/api/tree/master/java) [Python](https://github.com/bw-exchange/api/tree/master/python) [Nodejs](https://github.com/bw-exchange/api_docs_cn/blob/master/nodejsDemo/websocketDemo.js)

## REST market, trading API

> The root url is: https://www.bw.com

* [REST API request specification](https://github.com/bw-exchange/api_docs_en/wiki/REST_introduction)
* [Signature authentication (important, please read carefully)](https://github.com/bw-exchange/api_docs_en/wiki/REST_authentication)
* [API Reference](https://github.com/bw-exchange/api_docs_en/wiki/REST_api_reference)
* [Error code](https://github.com/bw-exchange/api_docs_en/wiki/REST_api_error_code)
* Code sample: [Java](https://github.com/bw-exchange/api/tree/master/java) [Python](https://github.com/bw-exchange/api/tree/master/python) [Nodejs](https://github.com/bw-exchange/api_docs_cn/blob/master/nodejsDemo/restApiDemo.js)
