[cw-sdk-node](README.md)

# cw-sdk-node

## Index

### Enumerations

* [Period](enums/period.md)

### Classes

* [MockServer](classes/mockserver.md)
* [OrderBook](classes/orderbook.md)
* [OrderBookWatcher](classes/orderbookwatcher.md)
* [RESTClient](classes/restclient.md)
* [RestError](classes/resterror.md)
* [SessionTracker](classes/sessiontracker.md)
* [SnapshotRetriever](classes/snapshotretriever.md)
* [StreamClient](classes/streamclient.md)
* [TradeClient](classes/tradeclient.md)
* [Updater](classes/updater.md)
* [WebSocketClient](classes/websocketclient.md)

### Interfaces

* [BrokerResponse](interfaces/brokerresponse.md)
* [CancelOrderOpts](interfaces/cancelorderopts.md)
* [CancelOrderResult](interfaces/cancelorderresult.md)
* [Credentials](interfaces/credentials.md)
* [Interval](interfaces/interval.md)
* [MarketUpdate](interfaces/marketupdate.md)
* [OHLC](interfaces/ohlc.md)
* [OrderBookDelta](interfaces/orderbookdelta.md)
* [OrderBookSnapshot](interfaces/orderbooksnapshot.md)
* [OrderBookSpread](interfaces/orderbookspread.md)
* [OrderDeltas](interfaces/orderdeltas.md)
* [Pair](interfaces/pair.md)
* [PairUpdate](interfaces/pairupdate.md)
* [PerformanceUpdate](interfaces/performanceupdate.md)
* [PlaceOrderOpt](interfaces/placeorderopt.md)
* [PriceParam](interfaces/priceparam.md)
* [PrivateOrder](interfaces/privateorder.md)
* [PrivatePosition](interfaces/privateposition.md)
* [PrivateTrade](interfaces/privatetrade.md)
* [PublicOrder](interfaces/publicorder.md)
* [PublicTrade](interfaces/publictrade.md)
* [RESTAllowance](interfaces/restallowance.md)
* [RESTErrorBody](interfaces/resterrorbody.md)
* [RESTOpts](interfaces/restopts.md)
* [RESTResponse](interfaces/restresponse.md)
* [ReconnectOpts](interfaces/reconnectopts.md)
* [Sparkline](interfaces/sparkline.md)
* [StreamOpts](interfaces/streamopts.md)
* [SubscriptionError](interfaces/subscriptionerror.md)
* [SubscriptionResult](interfaces/subscriptionresult.md)
* [Summary](interfaces/summary.md)
* [TradeOpts](interfaces/tradeopts.md)
* [TradeSessionAuth](interfaces/tradesessionauth.md)
* [TradeSubscription](interfaces/tradesubscription.md)
* [TrendlineUpdate](interfaces/trendlineupdate.md)
* [VWAPUpdate](interfaces/vwapupdate.md)
* [WebSocketOpts](interfaces/websocketopts.md)

### Type aliases

* [Asset](README.md#asset)
* [AssetBrief](README.md#assetbrief)
* [AssetDetails](README.md#assetdetails)
* [BrokerRequest](README.md#brokerrequest)
* [CandleData](README.md#candledata)
* [CandleDataRaw](README.md#candledataraw)
* [ChangeSummary](README.md#changesummary)
* [CredentialsType](README.md#credentialstype)
* [DeltaItem](README.md#deltaitem)
* [Exchange](README.md#exchange)
* [ExchangeBrief](README.md#exchangebrief)
* [ExchangeDescription](README.md#exchangedescription)
* [FundingType](README.md#fundingtype)
* [Instrument](README.md#instrument)
* [LiquiditySide](README.md#liquidityside)
* [LogLevel](README.md#loglevel)
* [Market](README.md#market)
* [MarketBrief](README.md#marketbrief)
* [MarketDescription](README.md#marketdescription)
* [MarketOHLC](README.md#marketohlc)
* [MarketOHLCRaw](README.md#marketohlcraw)
* [MarketOrderBookLiquidity](README.md#marketorderbookliquidity)
* [MarketSelector](README.md#marketselector)
* [MarketSymbol](README.md#marketsymbol)
* [OrderBookSnapshotRaw](README.md#orderbooksnapshotraw)
* [OrderBookState](README.md#orderbookstate)
* [OrderSide](README.md#orderside)
* [OrderType](README.md#ordertype)
* [PairBrief](README.md#pairbrief)
* [PairDetails](README.md#pairdetails)
* [Price](README.md#price)
* [PriceSummary](README.md#pricesummary)
* [Prices](README.md#prices)
* [PublicOrderRaw](README.md#publicorderraw)
* [Summaries](README.md#summaries)
* [Trade](README.md#trade)
* [TradeRaw](README.md#traderaw)

### Variables

* [DataPerformanceUpdate](README.md#const-dataperformanceupdate)
* [DataVWAPUpdate](README.md#const-datavwapupdate)
* [EventBalancesUpdate](README.md#const-eventbalancesupdate)
* [EventClientError](README.md#const-eventclienterror)
* [EventMarketUpdate](README.md#const-eventmarketupdate)
* [EventOrdersUpdate](README.md#const-eventordersupdate)
* [EventPairUpdate](README.md#const-eventpairupdate)
* [EventPositionsUpdate](README.md#const-eventpositionsupdate)
* [EventStateChange](README.md#const-eventstatechange)
* [EventSubscriptionResult](README.md#const-eventsubscriptionresult)
* [EventTradesUpdate](README.md#const-eventtradesupdate)
* [EventUnsubscriptionResult](README.md#const-eventunsubscriptionresult)
* [EventWSAuthResult](README.md#const-eventwsauthresult)
* [EventWSData](README.md#const-eventwsdata)
* [StateConnected](README.md#const-stateconnected)
* [StateConnecting](README.md#const-stateconnecting)
* [StateDisconnected](README.md#const-statedisconnected)
* [StateWaitingToReconnect](README.md#const-statewaitingtoreconnect)
* [badAPIKey](README.md#const-badapikey)
* [badNonce](README.md#const-badnonce)
* [errCancelOrderBadResponse](README.md#const-errcancelorderbadresponse)
* [errConnNotReady](README.md#const-errconnnotready)
* [errNotInitialized](README.md#const-errnotinitialized)
* [errPlaceOrderBadResponse](README.md#const-errplaceorderbadresponse)
* [expiredNonce](README.md#const-expirednonce)
* [validToken](README.md#const-validtoken)

### Functions

* [binarySearchOrders](README.md#binarysearchorders)
* [getConnOpts](README.md#getconnopts)
* [getDateFromMs](README.md#getdatefromms)
* [getDateFromNs](README.md#getdatefromns)
* [getDateFromSecs](README.md#getdatefromsecs)
* [getMockStreamServer](README.md#getmockstreamserver)
* [getMockWebSocketServer](README.md#getmockwebsocketserver)
* [getNumber](README.md#getnumber)
* [getString](README.md#getstring)
* [getTradeOpts](README.md#gettradeopts)
* [guardIsLong](README.md#guardislong)
* [keyToStreamSubscription](README.md#keytostreamsubscription)
* [loadRESTCredentials](README.md#loadrestcredentials)
* [loadStreamCredentials](README.md#loadstreamcredentials)
* [loadTradeCredentials](README.md#loadtradecredentials)
* [marketUpdateFromProto](README.md#marketupdatefromproto)
* [pairUpdateFromProto](README.md#pairupdatefromproto)
* [placeOrderOptToProto](README.md#placeorderopttoproto)
* [privateOrderFromProto](README.md#privateorderfromproto)
* [privatePositionFromProto](README.md#privatepositionfromproto)
* [privateTradeFromProto](README.md#privatetradefromproto)
* [sideFromProto](README.md#sidefromproto)
* [sortDeltaItems](README.md#sortdeltaitems)
* [subscriptionResultFromProto](README.md#subscriptionresultfromproto)
* [symbolString](README.md#symbolstring)
* [tradeSubscriptionToProto](README.md#tradesubscriptiontoproto)
* [transformSnapshot](README.md#transformsnapshot)
* [validateMonetaryValue](README.md#validatemonetaryvalue)
* [validateOrderSide](README.md#validateorderside)
* [validateOrderSideProto](README.md#validateordersideproto)
* [validateOrderType](README.md#validateordertype)
* [validateOrderTypeProto](README.md#validateordertypeproto)

### Object literals

* [ERROR_NOT_FOUND](README.md#const-error_not_found)
* [EXCHANGES](README.md#const-exchanges)
* [EXCHANGE_KRAKEN](README.md#const-exchange_kraken)
* [EXCHANGE_NOT_FOUND](README.md#const-exchange_not_found)
* [PAIRS_INDEX](README.md#const-pairs_index)
* [fundingTypeFromProto](README.md#const-fundingtypefromproto)
* [fundingTypeToProto](README.md#const-fundingtypetoproto)
* [mockDelta1](README.md#const-mockdelta1)
* [mockDelta2](README.md#const-mockdelta2)
* [mockDelta3](README.md#const-mockdelta3)
* [mockDelta4](README.md#const-mockdelta4)
* [mockDelta5](README.md#const-mockdelta5)
* [mockSnapshot](README.md#const-mocksnapshot)
* [orderTypeFromProto](README.md#const-ordertypefromproto)
* [orderTypeToProto](README.md#const-ordertypetoproto)
* [periodFromInt](README.md#const-periodfromint)
* [privateOrderSideFromProto](README.md#const-privateordersidefromproto)
* [privateOrderSideToProto](README.md#const-privateordersidetoproto)
* [publicOrderSideFromProto](README.md#const-publicordersidefromproto)
* [publicOrderSideToProto](README.md#const-publicordersidetoproto)

## Type aliases

###  Asset

Ƭ **Asset**: *object*

Defined in util/types/shared.ts:47

#### Type declaration:

___

###  AssetBrief

Ƭ **AssetBrief**: *Brief‹AssetBase›*

Defined in rest/types/data.ts:32

___

###  AssetDetails

Ƭ **AssetDetails**: *AssetBase & object*

Defined in rest/types/data.ts:33

___

###  BrokerRequest

Ƭ **BrokerRequest**: *PlaceOrderRequest | CancelOrderRequest*

Defined in websocket/types/trading.ts:70

___

###  CandleData

Ƭ **CandleData**: *object*

Defined in rest/types/data.ts:144

#### Type declaration:

___

###  CandleDataRaw

Ƭ **CandleDataRaw**: *[number, number, number, number, number, number]*

Defined in rest/types/data.ts:143

CandleData is an array of numbers in this order:
[ CloseTime, OpenPrice, HighPrice, LowPrice, ClosePrice, Volume ]

___

###  ChangeSummary

Ƭ **ChangeSummary**: *object*

Defined in rest/types/data.ts:67

#### Type declaration:

___

###  CredentialsType

Ƭ **CredentialsType**: *"stream" | "trade" | "REST"*

Defined in util/types/credentials.ts:11

___

###  DeltaItem

Ƭ **DeltaItem**: *object*

Defined in util/types/shared.ts:52

#### Type declaration:

___

###  Exchange

Ƭ **Exchange**: *object*

Defined in util/types/shared.ts:36

#### Type declaration:

___

###  ExchangeBrief

Ƭ **ExchangeBrief**: *Brief‹ExchangeBase›*

Defined in rest/types/data.ts:52

___

###  ExchangeDescription

Ƭ **ExchangeDescription**: *Description‹ExchangeBase›*

Defined in rest/types/data.ts:51

___

###  FundingType

Ƭ **FundingType**: *"spot" | "margin"*

Defined in websocket/types/trading.ts:28

___

###  Instrument

Ƭ **Instrument**: *object*

Defined in util/types/shared.ts:30

#### Type declaration:

___

###  LiquiditySide

Ƭ **LiquiditySide**: *object*

Defined in rest/types/data.ts:125

#### Type declaration:

___

###  LogLevel

Ƭ **LogLevel**: *"debug" | "info" | "warn" | "error" | "disabled"*

Defined in util/logger.ts:4

___

###  Market

Ƭ **Market**: *object*

Defined in util/types/shared.ts:41

Defined in websocket/types/markets.ts:15

#### Type declaration:

###  currencyPairID

• **currencyPairID**: *number*

Defined in websocket/types/markets.ts:18

###  exchangeID

• **exchangeID**: *number*

Defined in websocket/types/markets.ts:17

###  id

• **id**: *number*

Defined in websocket/types/markets.ts:16

___

###  MarketBrief

Ƭ **MarketBrief**: *Brief‹MarketBase›*

Defined in rest/types/data.ts:55

___

###  MarketDescription

Ƭ **MarketDescription**: *Description‹MarketBase›*

Defined in rest/types/data.ts:54

___

###  MarketOHLC

Ƭ **MarketOHLC**: *object*

Defined in rest/types/data.ts:157

#### Type declaration:

___

###  MarketOHLCRaw

Ƭ **MarketOHLCRaw**: *object*

Defined in rest/types/data.ts:153

#### Type declaration:

___

###  MarketOrderBookLiquidity

Ƭ **MarketOrderBookLiquidity**: *object*

Defined in rest/types/data.ts:134

#### Type declaration:

___

###  MarketSelector

Ƭ **MarketSelector**: *object | number*

Defined in util/types/shared.ts:59

___

###  MarketSymbol

Ƭ **MarketSymbol**: *object*

Defined in rest/types/data.ts:57

#### Type declaration:

___

###  OrderBookSnapshotRaw

Ƭ **OrderBookSnapshotRaw**: *object*

Defined in rest/types/data.ts:91

#### Type declaration:

___

###  OrderBookState

Ƭ **OrderBookState**: *object*

Defined in util/types/shared.ts:7

#### Type declaration:

___

###  OrderSide

Ƭ **OrderSide**: *"buy" | "sell"*

Defined in websocket/types/trading.ts:26

___

###  OrderType

Ƭ **OrderType**: *"market" | "limit"*

Defined in websocket/types/trading.ts:30

___

###  PairBrief

Ƭ **PairBrief**: *object*

Defined in rest/types/data.ts:40

#### Type declaration:

___

###  PairDetails

Ƭ **PairDetails**: *[PairBrief](README.md#pairbrief) & object*

Defined in rest/types/data.ts:47

___

###  Price

Ƭ **Price**: *object*

Defined in rest/types/data.ts:63

#### Type declaration:

___

###  PriceSummary

Ƭ **PriceSummary**: *object*

Defined in rest/types/data.ts:72

#### Type declaration:

___

###  Prices

Ƭ **Prices**: *object*

Defined in rest/types/data.ts:161

#### Type declaration:

* \[ **marketSymbol**: *string*\]: number

___

###  PublicOrderRaw

Ƭ **PublicOrderRaw**: *[number, number]*

Defined in rest/types/data.ts:89

PublicOrders are arrays of numbers in this order:
[ Price, Amount ]

___

###  Summaries

Ƭ **Summaries**: *object*

Defined in rest/types/data.ts:165

#### Type declaration:

* \[ **marketSymbol**: *string*\]: [Summary](interfaces/summary.md)

___

###  Trade

Ƭ **Trade**: *object*

Defined in rest/types/data.ts:102

#### Type declaration:

___

###  TradeRaw

Ƭ **TradeRaw**: *[number, number, number, number]*

Defined in rest/types/data.ts:101

Trades are arrays of numbers in this order:
[ ID, Timestamp, Price, Amount ]

## Variables

### `Const` DataPerformanceUpdate

• **DataPerformanceUpdate**: *unique symbol* =  Symbol('performance update')

Defined in websocket/constants.ts:19

___

### `Const` DataVWAPUpdate

• **DataVWAPUpdate**: *unique symbol* =  Symbol('vwap update')

Defined in websocket/constants.ts:18

___

### `Const` EventBalancesUpdate

• **EventBalancesUpdate**: *unique symbol* =  Symbol('balances update')

Defined in websocket/constants.ts:25

___

### `Const` EventClientError

• **EventClientError**: *unique symbol* =  Symbol('client error')

Defined in websocket/constants.ts:8

___

### `Const` EventMarketUpdate

• **EventMarketUpdate**: *unique symbol* =  Symbol('market update')

Defined in websocket/constants.ts:14

___

### `Const` EventOrdersUpdate

• **EventOrdersUpdate**: *unique symbol* =  Symbol('orders update')

Defined in websocket/constants.ts:22

___

### `Const` EventPairUpdate

• **EventPairUpdate**: *unique symbol* =  Symbol('pair update')

Defined in websocket/constants.ts:15

___

### `Const` EventPositionsUpdate

• **EventPositionsUpdate**: *unique symbol* =  Symbol('positions update')

Defined in websocket/constants.ts:24

___

### `Const` EventStateChange

• **EventStateChange**: *unique symbol* =  Symbol('state change')

Defined in websocket/constants.ts:9

___

### `Const` EventSubscriptionResult

• **EventSubscriptionResult**: *unique symbol* =  Symbol('subscription result')

Defined in websocket/constants.ts:17

___

### `Const` EventTradesUpdate

• **EventTradesUpdate**: *unique symbol* =  Symbol('trades update')

Defined in websocket/constants.ts:23

___

### `Const` EventUnsubscriptionResult

• **EventUnsubscriptionResult**: *unique symbol* =  Symbol('unsubscription result')

Defined in websocket/constants.ts:16

___

### `Const` EventWSAuthResult

• **EventWSAuthResult**: *unique symbol* =  Symbol('auth result')

Defined in websocket/constants.ts:11

___

### `Const` EventWSData

• **EventWSData**: *unique symbol* =  Symbol('websocket data')

Defined in websocket/constants.ts:10

___

### `Const` StateConnected

• **StateConnected**: *unique symbol* =  Symbol('connected')

Defined in websocket/constants.ts:4

___

### `Const` StateConnecting

• **StateConnecting**: *unique symbol* =  Symbol('connecting')

Defined in websocket/constants.ts:3

___

### `Const` StateDisconnected

• **StateDisconnected**: *unique symbol* =  Symbol('disconnected')

Defined in websocket/constants.ts:2

___

### `Const` StateWaitingToReconnect

• **StateWaitingToReconnect**: *unique symbol* =  Symbol('disconnected: waiting to reconnect')

Defined in websocket/constants.ts:5

___

### `Const` badAPIKey

• **badAPIKey**: *"bad-api-key"* = "bad-api-key"

Defined in websocket/__tests__/ws-test-server/index.ts:9

___

### `Const` badNonce

• **badNonce**: *"bad-nonce"* = "bad-nonce"

Defined in websocket/__tests__/ws-test-server/index.ts:10

___

### `Const` errCancelOrderBadResponse

• **errCancelOrderBadResponse**: *Error* =  new Error('cancel order failed: bad response')

Defined in websocket/errors.ts:5

___

### `Const` errConnNotReady

• **errConnNotReady**: *Error* =  new Error(
  "Connection not ready. Did you forget to call 'connect()'?"
)

Defined in websocket/errors.ts:8

___

### `Const` errNotInitialized

• **errNotInitialized**: *Error* =  new Error(
  'Trading is not yet initialized. Did you wait for onReady()?'
)

Defined in websocket/errors.ts:1

___

### `Const` errPlaceOrderBadResponse

• **errPlaceOrderBadResponse**: *Error* =  new Error('place order failed: bad response')

Defined in websocket/errors.ts:4

___

### `Const` expiredNonce

• **expiredNonce**: *"expired-nonce"* = "expired-nonce"

Defined in websocket/__tests__/ws-test-server/index.ts:11

___

### `Const` validToken

• **validToken**: *"55v1hv+29RY+xdtJBnFeyoFLjY4r+d8kmx761jCPWi5NgJJPqjPBp5SdqXjrTy/wBoRIcwGAUFVtpGrY7QAOLw=="* = "55v1hv+29RY+xdtJBnFeyoFLjY4r+d8kmx761jCPWi5NgJJPqjPBp5SdqXjrTy/wBoRIcwGAUFVtpGrY7QAOLw=="

Defined in websocket/__tests__/ws-test-server/index.ts:7

## Functions

###  binarySearchOrders

▸ **binarySearchOrders**(`orders`: [PublicOrder](interfaces/publicorder.md)[], `price`: string, `startIndex`: number, `reverse`: boolean): *object*

Defined in util/helpers.ts:68

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`orders` | [PublicOrder](interfaces/publicorder.md)[] | - |
`price` | string | - |
`startIndex` | number | - |
`reverse` | boolean | false |

**Returns:** *object*

___

###  getConnOpts

▸ **getConnOpts**(`extra?`: object): *[WebSocketOpts](interfaces/websocketopts.md)*

Defined in websocket/__tests__/ws-test-server/index.ts:13

**Parameters:**

Name | Type |
------ | ------ |
`extra?` | object |

**Returns:** *[WebSocketOpts](interfaces/websocketopts.md)*

___

###  getDateFromMs

▸ **getDateFromMs**(`n`: number | Long): *Date*

Defined in util/helpers.ts:22

**Parameters:**

Name | Type |
------ | ------ |
`n` | number &#124; Long |

**Returns:** *Date*

___

###  getDateFromNs

▸ **getDateFromNs**(`n`: number | Long): *Date*

Defined in util/helpers.ts:26

**Parameters:**

Name | Type |
------ | ------ |
`n` | number &#124; Long |

**Returns:** *Date*

___

###  getDateFromSecs

▸ **getDateFromSecs**(`n`: number | Long): *Date*

Defined in util/helpers.ts:18

**Parameters:**

Name | Type |
------ | ------ |
`n` | number &#124; Long |

**Returns:** *Date*

___

###  getMockStreamServer

▸ **getMockStreamServer**(): *Promise‹[MockServer](classes/mockserver.md)›*

Defined in websocket/__tests__/ws-test-server/index.ts:62

**Returns:** *Promise‹[MockServer](classes/mockserver.md)›*

___

###  getMockWebSocketServer

▸ **getMockWebSocketServer**(): *Promise‹[MockServer](classes/mockserver.md)›*

Defined in websocket/__tests__/ws-test-server/index.ts:54

**Returns:** *Promise‹[MockServer](classes/mockserver.md)›*

___

###  getNumber

▸ **getNumber**(`n`: number | Long): *number*

Defined in util/helpers.ts:10

**Parameters:**

Name | Type |
------ | ------ |
`n` | number &#124; Long |

**Returns:** *number*

___

###  getString

▸ **getString**(`n`: number | Long): *string*

Defined in util/helpers.ts:14

**Parameters:**

Name | Type |
------ | ------ |
`n` | number &#124; Long |

**Returns:** *string*

___

###  getTradeOpts

▸ **getTradeOpts**(`connOpts?`: object, `tradeSubs?`: object[]): *[TradeOpts](interfaces/tradeopts.md)*

Defined in websocket/__tests__/ws-test-server/index.ts:36

**Parameters:**

Name | Type |
------ | ------ |
`connOpts?` | object |
`tradeSubs?` | object[] |

**Returns:** *[TradeOpts](interfaces/tradeopts.md)*

___

###  guardIsLong

▸ **guardIsLong**(`value`: number | Long): *boolean*

Defined in util/helpers.ts:6

**Parameters:**

Name | Type |
------ | ------ |
`value` | number &#124; Long |

**Returns:** *boolean*

___

###  keyToStreamSubscription

▸ **keyToStreamSubscription**(`key`: string): *ClientSubscription*

Defined in websocket/proto/keyToStreamSubscription.ts:3

**Parameters:**

Name | Type |
------ | ------ |
`key` | string |

**Returns:** *ClientSubscription*

___

###  loadRESTCredentials

▸ **loadRESTCredentials**(`opts?`: Partial‹[RESTOpts](interfaces/restopts.md)›): *object*

Defined in util/credentials.ts:102

**Parameters:**

Name | Type |
------ | ------ |
`opts?` | Partial‹[RESTOpts](interfaces/restopts.md)› |

**Returns:** *object*

___

###  loadStreamCredentials

▸ **loadStreamCredentials**(`opts`: Partial‹[StreamOpts](interfaces/streamopts.md)›): *[StreamOpts](interfaces/streamopts.md)*

Defined in util/credentials.ts:58

**Parameters:**

Name | Type |
------ | ------ |
`opts` | Partial‹[StreamOpts](interfaces/streamopts.md)› |

**Returns:** *[StreamOpts](interfaces/streamopts.md)*

___

###  loadTradeCredentials

▸ **loadTradeCredentials**(`opts`: Partial‹[TradeOpts](interfaces/tradeopts.md)›): *[TradeOpts](interfaces/tradeopts.md)*

Defined in util/credentials.ts:80

**Parameters:**

Name | Type |
------ | ------ |
`opts` | Partial‹[TradeOpts](interfaces/tradeopts.md)› |

**Returns:** *[TradeOpts](interfaces/tradeopts.md)*

___

###  marketUpdateFromProto

▸ **marketUpdateFromProto**(`marketUpdate`: MarketUpdateMessage): *[MarketUpdate](interfaces/marketupdate.md) | null*

Defined in websocket/proto/marketUpdateFromProto.ts:275

**Parameters:**

Name | Type |
------ | ------ |
`marketUpdate` | MarketUpdateMessage |

**Returns:** *[MarketUpdate](interfaces/marketupdate.md) | null*

___

###  pairUpdateFromProto

▸ **pairUpdateFromProto**(`pairUpdate`: IPairUpdateMessage | null | undefined): *[PairUpdate](interfaces/pairupdate.md) | null*

Defined in websocket/proto/pairUpdateFromProto.ts:5

**Parameters:**

Name | Type |
------ | ------ |
`pairUpdate` | IPairUpdateMessage &#124; null &#124; undefined |

**Returns:** *[PairUpdate](interfaces/pairupdate.md) | null*

___

###  placeOrderOptToProto

▸ **placeOrderOptToProto**(`orderOpts`: Partial‹[PlaceOrderOpt](interfaces/placeorderopt.md)›): *IPrivateOrder*

Defined in websocket/proto/placeOrderOptToProto.ts:14

**Parameters:**

Name | Type |
------ | ------ |
`orderOpts` | Partial‹[PlaceOrderOpt](interfaces/placeorderopt.md)› |

**Returns:** *IPrivateOrder*

___

###  privateOrderFromProto

▸ **privateOrderFromProto**(`privateOrder`: IPrivateOrder): *[PrivateOrder](interfaces/privateorder.md) | null*

Defined in websocket/proto/privateOrderFromProto.ts:11

**Parameters:**

Name | Type |
------ | ------ |
`privateOrder` | IPrivateOrder |

**Returns:** *[PrivateOrder](interfaces/privateorder.md) | null*

___

###  privatePositionFromProto

▸ **privatePositionFromProto**(`position`: IPrivatePosition): *[PrivatePosition](interfaces/privateposition.md) | null*

Defined in websocket/proto/privatePositionFromProto.ts:9

**Parameters:**

Name | Type |
------ | ------ |
`position` | IPrivatePosition |

**Returns:** *[PrivatePosition](interfaces/privateposition.md) | null*

___

###  privateTradeFromProto

▸ **privateTradeFromProto**(`trade`: IPrivateTrade): *[PrivateTrade](interfaces/privatetrade.md) | null*

Defined in websocket/proto/privateTradeFromProto.ts:9

**Parameters:**

Name | Type |
------ | ------ |
`trade` | IPrivateTrade |

**Returns:** *[PrivateTrade](interfaces/privatetrade.md) | null*

___

###  sideFromProto

▸ **sideFromProto**(`side`: number | Side): *[OrderSide](README.md#orderside) | null*

Defined in websocket/proto/sideFromProto.ts:5

**Parameters:**

Name | Type |
------ | ------ |
`side` | number &#124; Side |

**Returns:** *[OrderSide](README.md#orderside) | null*

___

###  sortDeltaItems

▸ **sortDeltaItems**(`i`: [DeltaItem](README.md#deltaitem), `j`: [DeltaItem](README.md#deltaitem), `reverse`: boolean): *number*

Defined in util/helpers.ts:49

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`i` | [DeltaItem](README.md#deltaitem) | - |
`j` | [DeltaItem](README.md#deltaitem) | - |
`reverse` | boolean | false |

**Returns:** *number*

___

###  subscriptionResultFromProto

▸ **subscriptionResultFromProto**(`subResult`: ISubscriptionResult | IUnsubscriptionResult): *[SubscriptionResult](interfaces/subscriptionresult.md) | null*

Defined in websocket/proto/subscriptionResultFromProto.ts:14

**Parameters:**

Name | Type |
------ | ------ |
`subResult` | ISubscriptionResult &#124; IUnsubscriptionResult |

**Returns:** *[SubscriptionResult](interfaces/subscriptionresult.md) | null*

___

###  symbolString

▸ **symbolString**(`s`: symbol): *string*

Defined in util/helpers.ts:31

**Parameters:**

Name | Type |
------ | ------ |
`s` | symbol |

**Returns:** *string*

___

###  tradeSubscriptionToProto

▸ **tradeSubscriptionToProto**(`tradeSubscription`: [TradeSubscription](interfaces/tradesubscription.md)): *ClientSubscription*

Defined in websocket/proto/tradeSubscriptionToProto.ts:4

**Parameters:**

Name | Type |
------ | ------ |
`tradeSubscription` | [TradeSubscription](interfaces/tradesubscription.md) |

**Returns:** *ClientSubscription*

___

###  transformSnapshot

▸ **transformSnapshot**(`orderBook`: [OrderBookSnapshotRaw](README.md#orderbooksnapshotraw)): *[OrderBookSnapshot](interfaces/orderbooksnapshot.md)*

Defined in util/helpers.ts:35

**Parameters:**

Name | Type |
------ | ------ |
`orderBook` | [OrderBookSnapshotRaw](README.md#orderbooksnapshotraw) |

**Returns:** *[OrderBookSnapshot](interfaces/orderbooksnapshot.md)*

___

###  validateMonetaryValue

▸ **validateMonetaryValue**(`n`: string): *boolean*

Defined in websocket/proto/validators.ts:27

**Parameters:**

Name | Type |
------ | ------ |
`n` | string |

**Returns:** *boolean*

___

###  validateOrderSide

▸ **validateOrderSide**(`s`: string): *boolean*

Defined in websocket/proto/validators.ts:11

**Parameters:**

Name | Type |
------ | ------ |
`s` | string |

**Returns:** *boolean*

___

###  validateOrderSideProto

▸ **validateOrderSideProto**(`s`: number): *boolean*

Defined in websocket/proto/validators.ts:15

**Parameters:**

Name | Type |
------ | ------ |
`s` | number |

**Returns:** *boolean*

___

###  validateOrderType

▸ **validateOrderType**(`t`: string): *boolean*

Defined in websocket/proto/validators.ts:19

**Parameters:**

Name | Type |
------ | ------ |
`t` | string |

**Returns:** *boolean*

___

###  validateOrderTypeProto

▸ **validateOrderTypeProto**(`t`: Type): *boolean*

Defined in websocket/proto/validators.ts:23

**Parameters:**

Name | Type |
------ | ------ |
`t` | Type |

**Returns:** *boolean*

## Object literals

### `Const` ERROR_NOT_FOUND

### ▪ **ERROR_NOT_FOUND**: *object*

Defined in rest/__mocks__/data/index.ts:136

###  error

• **error**: *string* = "Route not found"

Defined in rest/__mocks__/data/index.ts:137

▪ **allowance**: *object*

Defined in rest/__mocks__/data/index.ts:138

* **cost**: *number* = 123456

* **remaining**: *number* = 1234567890

* **upgrade**: *string* = "Upgrade for a higher allowance, starting at $15/month for 16 seconds/hour. https://cryptowat.ch/pricing"

___

### `Const` EXCHANGES

### ▪ **EXCHANGES**: *object*

Defined in rest/__mocks__/data/index.ts:1

###  result

• **result**: *object[]* =  [
    {
      id: 4,
      symbol: 'kraken',
      name: 'Kraken',
      route: 'https://api.cryptowat.ch/exchanges/kraken',
      active: true
    },
    {
      id: 9,
      symbol: 'quoine',
      name: 'Quoine',
      route: 'https://api.cryptowat.ch/exchanges/quoine',
      active: true
    },
    {
      id: 22,
      symbol: 'mtgox',
      name: 'Mt. Gox',
      route: 'https://api.cryptowat.ch/exchanges/mtgox',
      active: false
    }
  ]

Defined in rest/__mocks__/data/index.ts:2

▪ **allowance**: *object*

Defined in rest/__mocks__/data/index.ts:25

* **cost**: *number* = 123456

* **remaining**: *number* = 1234567890

* **upgrade**: *string* = "Upgrade for a higher allowance, starting at $15/month for 16 seconds/hour. https://cryptowat.ch/pricing"

___

### `Const` EXCHANGE_KRAKEN

### ▪ **EXCHANGE_KRAKEN**: *object*

Defined in rest/__mocks__/data/index.ts:33

▪ **allowance**: *object*

Defined in rest/__mocks__/data/index.ts:41

* **cost**: *number* = 123456

* **remaining**: *number* = 1234567890

* **upgrade**: *string* = "Upgrade for a higher allowance, starting at $15/month for 16 seconds/hour. https://cryptowat.ch/pricing"

▪ **result**: *object*

Defined in rest/__mocks__/data/index.ts:34

* **active**: *boolean* = true

* **id**: *number* = 4

* **name**: *string* = "Kraken"

* **symbol**: *string* = "kraken"

* **routes**: *object*

  * **markets**: *string* = "https://api.cryptowat.ch/markets/kraken"

___

### `Const` EXCHANGE_NOT_FOUND

### ▪ **EXCHANGE_NOT_FOUND**: *object*

Defined in rest/__mocks__/data/index.ts:146

###  error

• **error**: *string* = "Exchange not found"

Defined in rest/__mocks__/data/index.ts:147

▪ **allowance**: *object*

Defined in rest/__mocks__/data/index.ts:148

* **cost**: *number* = 123456

* **remaining**: *number* = 1234567890

* **upgrade**: *string* = "Upgrade for a higher allowance, starting at $15/month for 16 seconds/hour. https://cryptowat.ch/pricing"

___

### `Const` PAIRS_INDEX

### ▪ **PAIRS_INDEX**: *object*

Defined in rest/__mocks__/data/index.ts:49

###  result

• **result**: *object[]* =  [
    {
      id: 984,
      symbol: '1stbtc',
      base: {
        id: 404,
        symbol: '1st',
        name: 'FirstBlood',
        fiat: false,
        route: 'https://api.cryptowat.ch/assets/1st'
      },
      quote: {
        id: 60,
        symbol: 'btc',
        name: 'Bitcoin',
        fiat: false,
        route: 'https://api.cryptowat.ch/assets/btc'
      },
      route: 'https://api.cryptowat.ch/pairs/1stbtc'
    },
    {
      id: 809,
      symbol: '1steth',
      base: {
        id: 404,
        symbol: '1st',
        name: 'FirstBlood',
        fiat: false,
        route: 'https://api.cryptowat.ch/assets/1st'
      },
      quote: {
        id: 77,
        symbol: 'eth',
        name: 'Ethereum',
        fiat: false,
        route: 'https://api.cryptowat.ch/assets/eth'
      },
      route: 'https://api.cryptowat.ch/pairs/1steth'
    },
    {
      id: 2543,
      symbol: 'abbcbtc',
      base: {
        id: 1189,
        symbol: 'abbc',
        name: 'ABBC Coin',
        fiat: false,
        route: 'https://api.cryptowat.ch/assets/abbc'
      },
      quote: {
        id: 60,
        symbol: 'btc',
        name: 'Bitcoin',
        fiat: false,
        route: 'https://api.cryptowat.ch/assets/btc'
      },
      route: 'https://api.cryptowat.ch/pairs/abbcbtc'
    },
    {
      id: 2542,
      symbol: 'abbceth',
      base: {
        id: 1189,
        symbol: 'abbc',
        name: 'ABBC Coin',
        fiat: false,
        route: 'https://api.cryptowat.ch/assets/abbc'
      },
      quote: {
        id: 77,
        symbol: 'eth',
        name: 'Ethereum',
        fiat: false,
        route: 'https://api.cryptowat.ch/assets/eth'
      },
      route: 'https://api.cryptowat.ch/pairs/abbceth'
    }
  ]

Defined in rest/__mocks__/data/index.ts:50

▪ **allowance**: *object*

Defined in rest/__mocks__/data/index.ts:128

* **cost**: *number* = 123456

* **remaining**: *number* = 1234567890

* **upgrade**: *string* = "Upgrade for a higher allowance, starting at $15/month for 16 seconds/hour. https://cryptowat.ch/pricing"

___

### `Const` fundingTypeFromProto

### ▪ **fundingTypeFromProto**: *object*

Defined in websocket/proto/constants.ts:24

###  0

• **0**: *"spot"* = "spot"

Defined in websocket/proto/constants.ts:25

###  1

• **1**: *"margin"* = "margin"

Defined in websocket/proto/constants.ts:26

___

### `Const` fundingTypeToProto

### ▪ **fundingTypeToProto**: *object*

Defined in websocket/proto/constants.ts:29

###  margin

• **margin**: *number* = 1

Defined in websocket/proto/constants.ts:31

###  spot

• **spot**: *number* = 0

Defined in websocket/proto/constants.ts:30

___

### `Const` mockDelta1

### ▪ **mockDelta1**: *object*

Defined in orderbook/__mocks__/data/deltas.ts:3

###  seqNum

• **seqNum**: *number* = 1012075

Defined in orderbook/__mocks__/data/deltas.ts:4

▪ **asks**: *object*

Defined in orderbook/__mocks__/data/deltas.ts:12

* **remove**: *string[]* =  ['8.8092', '8.8045', '8.8088', '8.8008']

* **set**: *object[]* =  [
      { price: '8.8124', amount: '85.77432774' },
      { price: '9.1', amount: '75.97997644' },
      { price: '8.8173', amount: '100' },
      { price: '8.8165', amount: '171.54865549' }
    ]

▪ **bids**: *object*

Defined in orderbook/__mocks__/data/deltas.ts:5

* **remove**: *string[]* =  ['8.469']

* **set**: *object[]* =  [
      { price: '8.6554', amount: '129' },
      { price: '8.6551', amount: '128' }
    ]

___

### `Const` mockDelta2

### ▪ **mockDelta2**: *object*

Defined in orderbook/__mocks__/data/deltas.ts:23

###  seqNum

• **seqNum**: *number* = 1012076

Defined in orderbook/__mocks__/data/deltas.ts:24

▪ **asks**: *object*

Defined in orderbook/__mocks__/data/deltas.ts:34

* **remove**: *undefined[]* =  []

* **set**: *undefined[]* =  []

▪ **bids**: *object*

Defined in orderbook/__mocks__/data/deltas.ts:25

* **remove**: *string[]* =  ['8.47', '8.7493']

* **set**: *object[]* =  [
      { price: '8.7569', amount: '4.48485416' },
      { price: '8.7399', amount: '22.6' },
      { price: '8.6654', amount: '204.29443169' },
      { price: '8.6514', amount: '0.6' }
    ]

___

### `Const` mockDelta3

### ▪ **mockDelta3**: *object*

Defined in orderbook/__mocks__/data/deltas.ts:37

###  seqNum

• **seqNum**: *number* = 1012077

Defined in orderbook/__mocks__/data/deltas.ts:38

▪ **asks**: *object*

Defined in orderbook/__mocks__/data/deltas.ts:40

* **remove**: *undefined[]* =  []

* **set**: *undefined[]* =  []

▪ **bids**: *object*

Defined in orderbook/__mocks__/data/deltas.ts:39

* **remove**: *string[]* =  ['8.7569']

* **set**: *object[]* =  [{ price: '8.7563', amount: '4.48743395' }]

___

### `Const` mockDelta4

### ▪ **mockDelta4**: *object*

Defined in orderbook/__mocks__/data/deltas.ts:43

###  seqNum

• **seqNum**: *number* = 1012078

Defined in orderbook/__mocks__/data/deltas.ts:44

▪ **asks**: *object*

Defined in orderbook/__mocks__/data/deltas.ts:52

* **remove**: *string[]* =  ['9.1', '8.8165', '8.8173']

* **set**: *object[]* =  [
      { price: '8.8628', amount: '85.77432774' },
      { price: '9.01', amount: '75.97997644' },
      { price: '9.12', amount: '171.54865549' }
    ]

▪ **bids**: *object*

Defined in orderbook/__mocks__/data/deltas.ts:45

* **remove**: *string[]* =  ['8.4747', '8.6551', '8.7604', '8.7605']

* **set**: *object[]* =  [
      { price: '8.7561', amount: '20' },
      { price: '8.7564', amount: '9.86958519' }
    ]

___

### `Const` mockDelta5

### ▪ **mockDelta5**: *object*

Defined in orderbook/__mocks__/data/deltas.ts:62

###  seqNum

• **seqNum**: *number* = 1012079

Defined in orderbook/__mocks__/data/deltas.ts:63

▪ **asks**: *object*

Defined in orderbook/__mocks__/data/deltas.ts:73

* **remove**: *undefined[]* =  []

* **set**: *undefined[]* =  []

▪ **bids**: *object*

Defined in orderbook/__mocks__/data/deltas.ts:64

* **remove**: *string[]* =  ['8.4792']

* **set**: *object[]* =  [
      { price: '8.7607', amount: '58.77510615' },
      { price: '8.7606', amount: '61.52150127' },
      { price: '8.7366', amount: '158.6' },
      { price: '8.6548', amount: '128' }
    ]

___

### `Const` mockSnapshot

### ▪ **mockSnapshot**: *object*

Defined in orderbook/__mocks__/data/snapshot.ts:3

###  asks

• **asks**: *object[]* =  [
      { price: "8.7809", amount: "163.60328108" },
      { price: "8.781", amount: "19.27353983" },
      { price: "8.7862", amount: "432.0974938" },
      { price: "8.7883", amount: "57.67162692" },
      { price: "8.8018", amount: "126.7" },
      { price: "8.804", amount: "104.3" },
      { price: "8.8058", amount: "925.05095381" },
      { price: "8.8059", amount: "99.1" },
      { price: "8.8068", amount: "400" },
      { price: "8.8069", amount: "89.23898104" },
      { price: "8.8078", amount: "26.9" },
      { price: "8.8123", amount: "17.5" },
      { price: "8.8124", amount: "85.77432774" },
      { price: "8.8165", amount: "171.54865549" },
      { price: "8.8173", amount: "100" },
      { price: "8.8188", amount: "625.9" },
      { price: "8.8249", amount: "52.21812045" },
      { price: "8.8256", amount: "104.5073552" },
      { price: "8.8327", amount: "23.3127832" },
      { price: "8.8328", amount: "1" },
      { price: "8.8348", amount: "156.78157851" },
      { price: "8.8366", amount: "50" },
      { price: "8.8457", amount: "3072" },
      { price: "8.8533", amount: "16.26428571" },
      { price: "8.8539", amount: "3075.3" },
      { price: "8.8563", amount: "2107.5" },
      { price: "8.8591", amount: "16.26428571" },
      { price: "8.8628", amount: "16.26428571" },
      { price: "8.8645", amount: "16.26428571" },
      { price: "8.8646", amount: "2722.3" },
      { price: "8.8801", amount: "3532.66428571" },
      { price: "8.8863", amount: "127" },
      { price: "8.8865", amount: "257" },
      { price: "8.8966", amount: "50" },
      { price: "8.897", amount: "3108.7" },
      { price: "8.8988", amount: "41.96739555" },
      { price: "8.902", amount: "2.85" },
      { price: "8.906", amount: "38.46153846" },
      { price: "8.9069", amount: "7.02095431" },
      { price: "8.9071", amount: "24.20968387" },
      { price: "8.9074", amount: "4537.3" },
      { price: "8.9151", amount: "8" },
      { price: "8.9204", amount: "3058.9" },
      { price: "8.9239", amount: "5867.1" },
      { price: "8.9261", amount: "3098.1" },
      { price: "8.9276", amount: "7.68163237" },
      { price: "8.9286", amount: "28.7715086" },
      { price: "8.9291", amount: "5.58844647" },
      { price: "8.93", amount: "3005.7504" },
      { price: "8.9328", amount: "38.46153846" },
      { price: "8.9389", amount: "1.92405" },
      { price: "8.939", amount: "1" },
      { price: "8.9403", amount: "8" },
      { price: "8.9483", amount: "8.34231044" },
      { price: "8.9485", amount: "2" },
      { price: "8.95", amount: "53.33333333" },
      { price: "8.952", amount: "2.84" },
      { price: "8.9564", amount: "0.6" },
      { price: "8.9584", amount: "7570.5" },
      { price: "8.9595", amount: "38.46153846" },
      { price: "8.96", amount: "3" },
      { price: "8.9621", amount: "11.38122554" },
      { price: "8.969", amount: "9.0029885" },
      { price: "8.9714", amount: "37.89515806" },
      { price: "8.9848", amount: "2" },
      { price: "8.9863", amount: "38.46153846" },
      { price: "8.9878", amount: "9778.8" },
      { price: "8.9897", amount: "9.66366657" },
      { price: "8.9929", amount: "42.45698279" },
      { price: "8.9959", amount: "3" },
      { price: "9", amount: "22.27032292" },
      { price: "9.0004", amount: "250" },
      { price: "9.0012", amount: "200" },
      { price: "9.002", amount: "2.8" },
      { price: "9.01", amount: "333" },
      { price: "9.0103", amount: "10.32434463" },
      { price: "9.0111", amount: "2" },
      { price: "9.0125", amount: "6316.2" },
      { price: "9.013", amount: "38.46153846" },
      { price: "9.0143", amount: "47.01880752" },
      { price: "9.0204", amount: "6309.4" },
      { price: "9.0227", amount: "2" },
      { price: "9.031", amount: "10.9850227" },
      { price: "9.0357", amount: "51.58063225" },
      { price: "9.0397", amount: "38.46153846" },
      { price: "9.0402", amount: "5.5197848" },
      { price: "9.0501", amount: "1.9004" },
      { price: "9.0517", amount: "11.64570076" },
      { price: "9.052", amount: "3.56" },
      { price: "9.0558", amount: "1" },
      { price: "9.0571", amount: "56.14245698" },
      { price: "9.0578", amount: "5" },
      { price: "9.0665", amount: "38.46153846" },
      { price: "9.0724", amount: "12.30637883" },
      { price: "9.0786", amount: "60.70428171" },
      { price: "9.0792", amount: "2" },
      { price: "9.0931", amount: "12.96705689" },
      { price: "9.0932", amount: "38.46153846" },
      { price: "9.099", amount: "0.80556638" },
      { price: "9.1", amount: "75.97997644" },
      { price: "9.1138", amount: "13.62773495" },
      { price: "9.1192", amount: "0.80556638" },
      { price: "9.12", amount: "38.46153846" },
      { price: "9.1288", amount: "190" },
      { price: "9.1293", amount: "0.80556638" },
      { price: "9.1345", amount: "14.28841302" },
      { price: "9.1394", amount: "0.80556638" },
      { price: "9.1413", amount: "11.15809911" },
      { price: "9.1495", amount: "0.80556638" },
      { price: "9.1515", amount: "5.45260887" },
      { price: "9.152", amount: "3.85" },
      { price: "9.1552", amount: "14.94909108" },
      { price: "9.1596", amount: "0.80556638" },
      { price: "9.1614", amount: "1.87731" },
      { price: "9.1621", amount: "7.5" },
      { price: "9.1697", amount: "0.80556638" },
      { price: "9.1711", amount: "27" },
      { price: "9.1759", amount: "15.60976915" },
      { price: "9.1798", amount: "0.80556638" },
      { price: "9.1899", amount: "0.80556638" },
      { price: "9.1966", amount: "16.27044721" },
      { price: "9.2", amount: "0.80556638" },
      { price: "9.202", amount: "3.65" },
      { price: "9.21", amount: "60" },
      { price: "9.2101", amount: "0.80556638" },
      { price: "9.2129", amount: "5.5" },
      { price: "9.2172", amount: "16.93112528" },
      { price: "9.2202", amount: "0.80556638" },
      { price: "9.2217", amount: "2" },
      { price: "9.2253", amount: "400" },
      { price: "9.2303", amount: "0.80556638" },
      { price: "9.2379", amount: "17.59180334" },
      { price: "9.24", amount: "100" },
      { price: "9.2404", amount: "0.80556638" },
      { price: "9.2442", amount: "2" },
      { price: "9.2466", amount: "2" },
      { price: "9.2487", amount: "3" },
      { price: "9.25", amount: "10" },
      { price: "9.2505", amount: "0.80556638" },
      { price: "9.252", amount: "3.72" },
      { price: "9.258", amount: "2" },
      { price: "9.2586", amount: "18.2524814" },
      { price: "9.2606", amount: "0.80556638" },
      { price: "9.2658", amount: "2" },
      { price: "9.2665", amount: "5.38498821" },
      { price: "9.2686", amount: "5" },
      { price: "9.2706", amount: "8" },
      { price: "9.2707", amount: "0.80556638" },
      { price: "9.2727", amount: "1.85479" },
      { price: "9.2744", amount: "2" },
      { price: "9.2747", amount: "1" },
      { price: "9.2753", amount: "3133.4" },
      { price: "9.278", amount: "2" },
      { price: "9.2793", amount: "18.91315947" },
      { price: "9.2799", amount: "2" },
      { price: "9.2808", amount: "0.80556638" },
      { price: "9.2878", amount: "2" },
      { price: "9.29", amount: "633" },
      { price: "9.2903", amount: "2" },
      { price: "9.2909", amount: "0.80556638" },
      { price: "9.2986", amount: "2" },
      { price: "9.3", amount: "59.57382753" },
      { price: "9.301", amount: "0.80556638" },
      { price: "9.302", amount: "7.05" },
      { price: "9.305", amount: "8.35383" },
      { price: "9.3111", amount: "0.80556638" },
      { price: "9.3129", amount: "2" },
      { price: "9.3212", amount: "0.80556638" },
      { price: "9.3241", amount: "10.93936312" },
      { price: "9.3285", amount: "10.3169" },
      { price: "9.3293", amount: "1.920203" },
      { price: "9.33", amount: "2" },
      { price: "9.3313", amount: "0.80556638" },
      { price: "9.3389", amount: "2" },
      { price: "9.34", amount: "6.667225" },
      { price: "9.3413", amount: "2" },
      { price: "9.3414", amount: "0.80556638" },
      { price: "9.349", amount: "50" },
      { price: "9.35", amount: "0.58214" },
      { price: "9.3515", amount: "0.80556638" },
      { price: "9.352", amount: "7.59000001" },
      { price: "9.3541", amount: "2" },
      { price: "9.3556", amount: "2" },
      { price: "9.3575", amount: "6" },
      { price: "9.36", amount: "513.1304" },
      { price: "9.3616", amount: "0.80556638" },
      { price: "9.3633", amount: "2" },
      { price: "9.3651", amount: "2" },
      { price: "9.3656", amount: "1.6" },
      { price: "9.3668", amount: "3144.8" },
      { price: "9.3688", amount: "3" },
      { price: "9.369", amount: "2" },
      { price: "9.37", amount: "2" },
      { price: "9.3717", amount: "0.80556638" },
      { price: "9.3754", amount: "2" },
      { price: "9.3765", amount: "2" },
      { price: "9.377", amount: "2" },
      { price: "9.38", amount: "1" },
      { price: "9.381", amount: "5.31925383" },
      { price: "9.3818", amount: "0.80556638" },
      { price: "9.384", amount: "1.83279" },
      { price: "9.3877", amount: "2" },
      { price: "9.3878", amount: "2" },
      { price: "9.388", amount: "2" },
      { price: "9.3891", amount: "2" },
      { price: "9.39", amount: "109.89" },
      { price: "9.3919", amount: "0.80556638" },
      { price: "9.3988", amount: "2" },
      { price: "9.4", amount: "49.0519" },
      { price: "9.402", amount: "10.47556639" },
      { price: "9.4038", amount: "3" },
      { price: "9.4072", amount: "2" },
      { price: "9.4121", amount: "0.80556638" },
      { price: "9.42", amount: "20" },
      { price: "9.4222", amount: "0.80556638" },
      { price: "9.4239", amount: "2" },
      { price: "9.4262", amount: "5" },
      { price: "9.4323", amount: "0.80556638" },
      { price: "9.4388", amount: "2" },
      { price: "9.439", amount: "185" },
      { price: "9.4396", amount: "2" },
      { price: "9.4424", amount: "0.80556638" },
      { price: "9.4432", amount: "2" },
      { price: "9.449", amount: "100" },
      { price: "9.452", amount: "6.55" },
      { price: "9.4525", amount: "0.80556638" },
      { price: "9.4528", amount: "3073.9" },
      { price: "9.454", amount: "2" },
      { price: "9.4622", amount: "1" },
      { price: "9.4626", amount: "0.80556638" },
      { price: "9.4727", amount: "0.80556638" },
      { price: "9.4754", amount: "2" },
      { price: "9.4784", amount: "5" },
      { price: "9.4828", amount: "0.80556638" },
      { price: "9.49", amount: "5" },
      { price: "9.4929", amount: "0.80556638" },
      { price: "9.4975", amount: "2" },
      { price: "9.5", amount: "101" },
      { price: "9.5017", amount: "5.25168904" },
      { price: "9.502", amount: "6.59" },
      { price: "9.503", amount: "0.80556638" },
      { price: "9.5131", amount: "0.80556638" },
      { price: "9.5144", amount: "8.49717" },
      { price: "9.5152", amount: "8" },
      { price: "9.519", amount: "100" },
      { price: "9.5194", amount: "5" },
      { price: "9.5232", amount: "0.80556638" },
      { price: "9.5333", amount: "0.80556638" },
      { price: "9.5434", amount: "0.80556638" },
      { price: "9.547", amount: "5" },
      { price: "9.55", amount: "259.6873" },
      { price: "9.552", amount: "7.17000001" },
      { price: "9.5535", amount: "0.80556638" },
      { price: "9.5636", amount: "0.80556638" },
      { price: "9.5737", amount: "0.80556638" },
      { price: "9.5774", amount: "1.58525005" },
      { price: "9.5838", amount: "0.80556638" },
      { price: "9.5845", amount: "3074.7" },
      { price: "9.5939", amount: "0.80556638" },
      { price: "9.6", amount: "17.86742712" },
      { price: "9.602", amount: "6.9" },
      { price: "9.6041", amount: "0.80556638" },
      { price: "9.6142", amount: "0.80556638" },
      { price: "9.615", amount: "6" },
      { price: "9.6205", amount: "5.1868015" },
      { price: "9.6243", amount: "0.80556638" },
      { price: "9.625", amount: "4" },
      { price: "9.63", amount: "10" },
      { price: "9.6341", amount: "1" },
      { price: "9.6344", amount: "0.80556638" },
      { price: "9.6445", amount: "0.80556638" },
      { price: "9.6474", amount: "1" },
      { price: "9.65", amount: "2148.575999" },
      { price: "9.652", amount: "6.89" },
      { price: "9.6546", amount: "0.80556638" },
      { price: "9.6646", amount: "500" },
      { price: "9.6647", amount: "0.80556638" },
      { price: "9.6748", amount: "0.80556638" },
      { price: "9.677", amount: "2" },
      { price: "9.6838", amount: "5" },
      { price: "9.6849", amount: "0.80556638" },
      { price: "9.695", amount: "0.80556638" },
      { price: "9.699", amount: "1" },
      { price: "9.7002", amount: "2" },
      { price: "9.702", amount: "6.91" },
      { price: "9.7051", amount: "0.80556638" },
      { price: "9.7087", amount: "50" },
      { price: "9.7152", amount: "0.80556638" },
      { price: "9.7225", amount: "2" },
      { price: "9.7253", amount: "0.80556638" },
      { price: "9.7284", amount: "8.56147" },
      { price: "9.73", amount: "10" },
      { price: "9.7354", amount: "0.80556638" },
      { price: "9.7397", amount: "5.12333807" },
      { price: "9.7455", amount: "0.80556638" },
      { price: "9.7461", amount: "15" },
      { price: "9.747", amount: "5" },
      { price: "9.7481", amount: "2" },
      { price: "9.75", amount: "3" },
      { price: "9.752", amount: "7.5" },
      { price: "9.7556", amount: "0.80556638" },
      { price: "9.7657", amount: "0.80556638" },
      { price: "9.7758", amount: "0.80556638" },
      { price: "9.777", amount: "19.97" },
      { price: "9.7811", amount: "2" },
      { price: "9.7859", amount: "0.80556638" },
      { price: "9.79", amount: "200" },
      { price: "9.796", amount: "0.80556638" },
      { price: "9.8", amount: "200" },
      { price: "9.8014", amount: "25" },
      { price: "9.802", amount: "5.93000001" },
      { price: "9.8061", amount: "0.80556638" },
      { price: "9.8107", amount: "18.6834" },
      { price: "9.8115", amount: "2" },
      { price: "9.8162", amount: "0.80556638" },
      { price: "9.82", amount: "1000" },
      { price: "9.8263", amount: "0.80556638" },
      { price: "9.83", amount: "31.0728" },
      { price: "9.8339", amount: "2" },
      { price: "9.8364", amount: "0.80556638" },
      { price: "9.842", amount: "100" },
      { price: "9.8453", amount: "2" },
      { price: "9.8465", amount: "0.80556638" },
      { price: "9.847", amount: "5" },
      { price: "9.85", amount: "3" },
      { price: "9.852", amount: "5.97" },
      { price: "9.8531", amount: "1" },
      { price: "9.8566", amount: "0.80556638" },
      { price: "9.8639", amount: "5.05881121" },
      { price: "9.8667", amount: "0.80556638" },
      { price: "9.8683", amount: "15" },
      { price: "9.8725", amount: "6" },
      { price: "9.875", amount: "2" },
      { price: "9.8768", amount: "0.80556638" },
      { price: "9.88", amount: "2" },
      { price: "9.8869", amount: "0.80556638" },
      { price: "9.897", amount: "0.80556638" },
      { price: "9.8978", amount: "2" },
      { price: "9.902", amount: "5.72" },
      { price: "9.9031", amount: "2" },
      { price: "9.9071", amount: "0.80556638" },
      { price: "9.9126", amount: "2" },
      { price: "9.9172", amount: "0.80556638" },
      { price: "9.9183", amount: "300" },
      { price: "9.926", amount: "2" },
      { price: "9.9273", amount: "0.80556638" },
      { price: "9.93", amount: "10.422238" },
      { price: "9.9313", amount: "2" },
      { price: "9.9374", amount: "0.80556638" },
      { price: "9.9431", amount: "2" },
      { price: "9.9473", amount: "8.63557" },
      { price: "9.9475", amount: "0.80556638" },
      { price: "9.949", amount: "200" },
      { price: "9.95", amount: "400" },
      { price: "9.952", amount: "5.73" },
      { price: "9.9543", amount: "12.73205217" },
      { price: "9.9554", amount: "2" },
      { price: "9.9576", amount: "0.80556638" },
      { price: "9.963", amount: "100" },
      { price: "9.964", amount: "100" },
      { price: "9.9677", amount: "0.80556638" },
      { price: "9.9712", amount: "2" },
      { price: "9.9723", amount: "3" },
      { price: "9.9778", amount: "0.80556638" },
      { price: "9.9846", amount: "3" },
      { price: "9.9879", amount: "0.80556638" },
      { price: "9.9882", amount: "4.99588952" },
      { price: "9.9888", amount: "20" },
      { price: "9.99", amount: "200" },
      { price: "9.9946", amount: "3" },
      { price: "9.998", amount: "0.80556638" },
      { price: "10", amount: "189.17839" },
      { price: "10.002", amount: "5.26" },
      { price: "10.008", amount: "0.80556638" },
      { price: "10.012", amount: "2" },
      { price: "10.018", amount: "0.80556638" },
      { price: "10.023", amount: "2" },
      { price: "10.028", amount: "0.80556638" },
      { price: "10.038", amount: "0.80556638" },
      { price: "10.044", amount: "2" },
      { price: "10.046", amount: "2" },
      { price: "10.048", amount: "0.80556638" },
      { price: "10.05", amount: "11.999" },
      { price: "10.051", amount: "2" },
      { price: "10.052", amount: "5.73" },
      { price: "10.058", amount: "2" },
      { price: "10.059", amount: "0.80556638" },
      { price: "10.069", amount: "0.80556638" },
      { price: "10.079", amount: "2.80556638" },
      { price: "10.081", amount: "50" },
      { price: "10.086", amount: "10" },
      { price: "10.089", amount: "0.80556638" },
      { price: "10.09", amount: "2" },
      { price: "10.099", amount: "0.80556638" },
      { price: "10.1", amount: "202" },
      { price: "10.102", amount: "5.84" },
      { price: "10.11", amount: "4.93540333" },
      { price: "10.12", amount: "1" },
      { price: "10.123", amount: "202" },
      { price: "10.124", amount: "200" },
      { price: "10.125", amount: "104" },
      { price: "10.13", amount: "6" },
      { price: "10.137", amount: "0.75" },
      { price: "10.142", amount: "50" },
      { price: "10.15", amount: "25.5" },
      { price: "10.152", amount: "5.37" },
      { price: "10.159", amount: "45" },
      { price: "10.171", amount: "8.7193" },
      { price: "10.2", amount: "8" },
      { price: "10.202", amount: "5.13" },
      { price: "10.21", amount: "1992" },
      { price: "10.22", amount: "109.062229" },
      { price: "10.222", amount: "1" },
      { price: "10.24", amount: "5.27284463" },
      { price: "10.25", amount: "126.5" },
      { price: "10.252", amount: "4.92" },
      { price: "10.255", amount: "0.61" },
      { price: "10.264", amount: "0.4" },
      { price: "10.276", amount: "8" },
      { price: "10.286", amount: "2" },
      { price: "10.3", amount: "122" },
      { price: "10.302", amount: "5.36" },
      { price: "10.314", amount: "1.06996343" },
      { price: "10.32", amount: "1" },
      { price: "10.331", amount: "0.4" },
      { price: "10.348", amount: "180" },
      { price: "10.349", amount: "20" },
      { price: "10.35", amount: "3" },
      { price: "10.352", amount: "5.37" },
      { price: "10.355", amount: "57.180762" },
      { price: "10.363", amount: "3.5" },
      { price: "10.368", amount: "4.81288579" },
      { price: "10.374", amount: "30" },
      { price: "10.375", amount: "2" },
      { price: "10.38", amount: "0.4" },
      { price: "10.389", amount: "2.0031602" },
      { price: "10.39", amount: "5" },
      { price: "10.4", amount: "2" },
      { price: "10.402", amount: "5.14" },
      { price: "10.405", amount: "20" },
      { price: "10.411", amount: "188.86258389" },
      { price: "10.43", amount: "100" },
      { price: "10.447", amount: "50" },
      { price: "10.45", amount: "6.5" },
      { price: "10.452", amount: "4.92" },
      { price: "10.453", amount: "2" },
      { price: "10.455", amount: "3103.9" },
      { price: "10.463", amount: "2.58692026" },
      { price: "10.472", amount: "1" },
      { price: "10.476", amount: "0.6" },
      { price: "10.492", amount: "20" },
      { price: "10.498", amount: "4.75300903" },
      { price: "10.5", amount: "94.828447" },
      { price: "10.502", amount: "4.93" },
      { price: "10.51", amount: "25.63" },
      { price: "10.52", amount: "1" },
      { price: "10.538", amount: "3.06095099" },
      { price: "10.543", amount: "50" },
      { price: "10.55", amount: "1024.99698026" },
      { price: "10.552", amount: "4.93" },
      { price: "10.572", amount: "12" },
      { price: "10.6", amount: "11.88032835" },
      { price: "10.602", amount: "4.94" },
      { price: "10.612", amount: "3.31552304" },
      { price: "10.629", amount: "4.69460379" },
      { price: "10.63", amount: "26" },
      { price: "10.643", amount: "2" },
      { price: "10.65", amount: "50" },
      { price: "10.652", amount: "4.94" },
      { price: "10.677", amount: "15" },
      { price: "10.685", amount: "175" },
      { price: "10.687", amount: "3.35063643" },
      { price: "10.699", amount: "0.5" },
      { price: "10.7", amount: "2.425" },
      { price: "10.702", amount: "5.43" },
      { price: "10.713", amount: "140.84925" },
      { price: "10.751", amount: "4.64111032" },
      { price: "10.752", amount: "6.03" },
      { price: "10.761", amount: "3.64910022" },
      { price: "10.8", amount: "205.75867788" },
      { price: "10.802", amount: "6.04" },
      { price: "10.806", amount: "1" },
      { price: "10.811", amount: "2" },
      { price: "10.836", amount: "4.73761522" },
      { price: "10.847", amount: "0.4" },
      { price: "10.85", amount: "10" },
      { price: "10.852", amount: "5.78" },
      { price: "10.87", amount: "10" },
      { price: "10.88", amount: "104" },
      { price: "10.885", amount: "5" },
      { price: "10.894", amount: "54.5802928" },
      { price: "10.9", amount: "7.2" },
      { price: "10.902", amount: "5.79" },
      { price: "10.91", amount: "119.29743021" },
      { price: "10.916", amount: "4" },
      { price: "10.92", amount: "23" },
      { price: "10.934", amount: "2" },
      { price: "10.95", amount: "12.8" },
      { price: "10.952", amount: "5.82" },
      { price: "10.963", amount: "10" },
      { price: "10.98", amount: "100" },
      { price: "10.984", amount: "170" },
      { price: "10.99", amount: "30" },
      { price: "11", amount: "590.32339048" },
      { price: "11.002", amount: "6.51" },
      { price: "11.016", amount: "3" },
      { price: "11.028", amount: "4.5247843" },
      { price: "11.037", amount: "15" },
      { price: "11.049", amount: "10" },
      { price: "11.052", amount: "6.2" },
      { price: "11.08", amount: "20" },
      { price: "11.1", amount: "2" },
      { price: "11.117", amount: "10" },
      { price: "11.123", amount: "2" },
      { price: "11.135", amount: "2" },
      { price: "11.144", amount: "2" },
      { price: "11.15", amount: "1" },
      { price: "11.152", amount: "5.59" },
      { price: "11.154", amount: "2" },
      { price: "11.161", amount: "2" },
      { price: "11.164", amount: "4.46938882" },
      { price: "11.2", amount: "1" },
      { price: "11.202", amount: "5.62" },
      { price: "11.21", amount: "10" },
      { price: "11.245", amount: "1.001708" },
      { price: "11.25", amount: "1" },
      { price: "11.252", amount: "5.94" },
      { price: "11.3", amount: "12" },
      { price: "11.302", amount: "5.6" },
      { price: "11.303", amount: "4.41454233" },
      { price: "11.326", amount: "618.4" },
      { price: "11.35", amount: "1" },
      { price: "11.352", amount: "5.98" },
      { price: "11.365", amount: "0.490051" },
      { price: "11.38", amount: "5.22914" },
      { price: "11.394", amount: "5" },
      { price: "11.4", amount: "1" },
      { price: "11.402", amount: "7" },
      { price: "11.41", amount: "115" },
      { price: "11.431", amount: "10" },
      { price: "11.435", amount: "0.4" },
      { price: "11.441", amount: "4.36141155" },
      { price: "11.45", amount: "105" },
      { price: "11.452", amount: "6.62" },
      { price: "11.461", amount: "2.87964739" },
      { price: "11.47", amount: "10" },
      { price: "11.5", amount: "4" },
      { price: "11.502", amount: "6.06" },
      { price: "11.55", amount: "1" },
      { price: "11.551", amount: "20" },
      { price: "11.552", amount: "4.34" },
      { price: "11.57", amount: "10.0684826" },
      { price: "11.589", amount: "4.30577936" },
      { price: "11.59", amount: "20" },
      { price: "11.593", amount: "10" },
      { price: "11.599", amount: "0.5" },
      { price: "11.6", amount: "110.52597" },
      { price: "11.602", amount: "3.82" },
      { price: "11.621", amount: "4" },
      { price: "11.648", amount: "160" },
      { price: "11.65", amount: "1" },
      { price: "11.652", amount: "3.46000001" },
      { price: "11.662", amount: "15" },
      { price: "11.69", amount: "1.996" },
      { price: "11.7", amount: "102" },
      { price: "11.702", amount: "3.48" },
      { price: "11.727", amount: "1" },
      { price: "11.734", amount: "4.25228219" },
      { price: "11.744", amount: "200" },
      { price: "11.75", amount: "2" },
      { price: "11.752", amount: "3.5" },
      { price: "11.782", amount: "183.0403" },
      { price: "11.789", amount: "0.4" },
      { price: "11.8", amount: "106.999" },
      { price: "11.802", amount: "4.17" },
      { price: "11.81", amount: "20" },
      { price: "11.823", amount: "10" },
      { price: "11.824", amount: "55" },
      { price: "11.85", amount: "1" },
      { price: "11.852", amount: "4.4" },
      { price: "11.877", amount: "4.20117215" },
      { price: "11.88", amount: "35" },
      { price: "11.886", amount: "1" },
      { price: "11.9", amount: "204.612401" },
      { price: "11.902", amount: "4.07" },
      { price: "11.91", amount: "4.643997" },
      { price: "11.95", amount: "1" },
      { price: "11.952", amount: "3.48" },
      { price: "11.984", amount: "10" },
      { price: "11.99", amount: "0.4" },
      { price: "11.995", amount: "50" },
      { price: "11.997", amount: "1.45" },
      { price: "11.999", amount: "23.42311344" },
      { price: "12", amount: "41.5174626" },
      { price: "12.002", amount: "3.52" },
      { price: "12.01", amount: "20" },
      { price: "12.015", amount: "1" },
      { price: "12.03", amount: "4.14778241" },
      { price: "12.05", amount: "1" },
      { price: "12.052", amount: "3" },
      { price: "12.053", amount: "71.42857143" },
      { price: "12.059", amount: "1.0989" },
      { price: "12.06", amount: "0.4" },
      { price: "12.078", amount: "20" },
      { price: "12.1", amount: "6" },
      { price: "12.102", amount: "3" },
      { price: "12.107", amount: "71.42857143" },
      { price: "12.15", amount: "1" },
      { price: "12.152", amount: "3" },
      { price: "12.161", amount: "71.42857143" },
      { price: "12.165", amount: "0.444709" },
      { price: "12.178", amount: "4.0974352" },
      { price: "12.184", amount: "120" },
      { price: "12.196", amount: "625.7" },
      { price: "12.202", amount: "3" },
      { price: "12.208", amount: "8.07192" },
      { price: "12.215", amount: "71.42857143" },
      { price: "12.248", amount: "4.27572" },
      { price: "12.25", amount: "1" },
      { price: "12.251", amount: "1" },
      { price: "12.268", amount: "8.07192" },
      { price: "12.269", amount: "71.42857143" },
      { price: "12.281", amount: "5" },
      { price: "12.29", amount: "200" },
      { price: "12.305", amount: "30" },
      { price: "12.308", amount: "1" },
      { price: "12.323", amount: "74.32451143" },
      { price: "12.328", amount: "1" },
      { price: "12.33", amount: "4.04696588" },
      { price: "12.346", amount: "1" },
      { price: "12.36", amount: "5" },
      { price: "12.365", amount: "1.99999285" },
      { price: "12.376", amount: "71.42857143" },
      { price: "12.396", amount: "2" },
      { price: "12.398", amount: "4" },
      { price: "12.4", amount: "25.14" },
      { price: "12.408", amount: "4" },
      { price: "12.422", amount: "2" },
      { price: "12.43", amount: "80.39017143" },
      { price: "12.443", amount: "2" },
      { price: "12.457", amount: "2" },
      { price: "12.458", amount: "2" },
      { price: "12.463", amount: "250" },
      { price: "12.464", amount: "250" },
      { price: "12.465", amount: "176" },
      { price: "12.476", amount: "2" },
      { price: "12.483", amount: "3.99740048" },
      { price: "12.484", amount: "71.42857143" },
      { price: "12.486", amount: "2" },
      { price: "12.49", amount: "2" },
      { price: "12.491", amount: "50" },
      { price: "12.5", amount: "70.61938" },
      { price: "12.51", amount: "2.88" },
      { price: "12.518", amount: "20" },
      { price: "12.56", amount: "1.261404" },
      { price: "12.568", amount: "2" },
      { price: "12.57", amount: "75" },
      { price: "12.6", amount: "2.554825" },
      { price: "12.619", amount: "25" },
      { price: "12.62", amount: "10.6998" },
      { price: "12.622", amount: "1.73620951" },
      { price: "12.641", amount: "3.94745299" },
      { price: "12.643", amount: "20" },
      { price: "12.676", amount: "2.117492" },
      { price: "12.677", amount: "2" },
      { price: "12.7", amount: "751.579804" },
      { price: "12.702", amount: "0.4995" },
      { price: "12.708", amount: "10" },
      { price: "12.728", amount: "0.5" },
      { price: "12.73", amount: "1.996" },
      { price: "12.75", amount: "2" },
      { price: "12.76", amount: "20" },
      { price: "12.765", amount: "1.78312476" },
      { price: "12.78", amount: "8" },
      { price: "12.8", amount: "23.952" },
      { price: "12.84", amount: "20" },
      { price: "12.841", amount: "10" },
      { price: "12.85", amount: "30" },
      { price: "12.88", amount: "1.10889" },
      { price: "12.899", amount: "140" },
      { price: "12.9", amount: "4" },
      { price: "12.918", amount: "10" },
      { price: "12.94", amount: "20" },
      { price: "12.963", amount: "100" },
      { price: "12.964", amount: "100" },
      { price: "12.965", amount: "100" },
      { price: "13", amount: "287.45078495" },
      { price: "13.009", amount: "20" },
      { price: "13.03", amount: "20.79999" },
      { price: "13.053", amount: "1.73972604" },
      { price: "13.073", amount: "5.28" },
      { price: "13.089", amount: "1" },
      { price: "13.1", amount: "2" },
      { price: "13.141", amount: "2.1" },
      { price: "13.151", amount: "4" },
      { price: "13.16", amount: "0.4" },
      { price: "13.163", amount: "250" },
      { price: "13.164", amount: "250" },
      { price: "13.165", amount: "100" },
      { price: "13.19", amount: "1.71160938" },
      { price: "13.2", amount: "13" },
      { price: "13.21", amount: "25" },
      { price: "13.225", amount: "8" },
      { price: "13.231", amount: "20" },
      { price: "13.24", amount: "38.794058" },
      { price: "13.25", amount: "2" },
      { price: "13.287", amount: "1" },
      { price: "13.3", amount: "32.262023" },
      { price: "13.32", amount: "220" },
      { price: "13.33", amount: "5" },
      { price: "13.339", amount: "1.69092517" },
      { price: "13.35", amount: "35" },
      { price: "13.387", amount: "51.16470624" },
      { price: "13.4", amount: "53" },
      { price: "13.422", amount: "2.91435" },
      { price: "13.45", amount: "40.99" },
      { price: "13.455", amount: "1.68165314" },
      { price: "13.469", amount: "0.5" },
      { price: "13.48", amount: "6.72713772" },
      { price: "13.489", amount: "1.6850124" },
      { price: "13.495", amount: "811.319886" },
      { price: "13.5", amount: "109.149708" },
      { price: "13.556", amount: "16.97352089" },
      { price: "13.58", amount: "9.78111233" },
      { price: "13.6", amount: "104" },
      { price: "13.674", amount: "3.84615" },
      { price: "13.7", amount: "101" },
      { price: "13.742", amount: "20" },
      { price: "13.75", amount: "17" },
      { price: "13.77", amount: "1.82278481" },
      { price: "13.778", amount: "19.3318163" },
      { price: "13.8", amount: "116.5" },
      { price: "13.807", amount: "2" },
      { price: "13.825", amount: "10" },
      { price: "13.85", amount: "30" },
      { price: "13.86", amount: "10" },
      { price: "13.87", amount: "1" },
      { price: "13.874", amount: "10.55" },
      { price: "13.9", amount: "102.5" },
      { price: "13.95", amount: "40" },
      { price: "13.99", amount: "26" },
      { price: "13.998", amount: "0.6" },
      { price: "14", amount: "312.23908287" },
      { price: "14.026", amount: "1" },
      { price: "14.07", amount: "122.976434" },
      { price: "14.1", amount: "2" },
      { price: "14.112", amount: "4" },
      { price: "14.113", amount: "50" },
      { price: "14.12", amount: "22.881675" },
      { price: "14.181", amount: "110" },
      { price: "14.2", amount: "2" },
      { price: "14.235", amount: "1" },
      { price: "14.3", amount: "4.50000013" },
      { price: "14.4", amount: "22" },
      { price: "14.41", amount: "313.4900017" },
      { price: "14.45", amount: "40" },
      { price: "14.487", amount: "50" },
      { price: "14.496", amount: "100" },
      { price: "14.5", amount: "75.956593" },
      { price: "14.52", amount: "0.989" },
      { price: "14.6", amount: "2" },
      { price: "14.63", amount: "5" },
      { price: "14.7", amount: "10.0829001" },
      { price: "14.75", amount: "2" },
      { price: "14.764", amount: "10.593442" },
      { price: "14.77", amount: "5" },
      { price: "14.79", amount: "4.887412" },
      { price: "14.8", amount: "5.8" },
      { price: "14.829", amount: "26.13834" },
      { price: "14.83", amount: "1" },
      { price: "14.854", amount: "31.66" },
      { price: "14.89", amount: "10" },
      { price: "14.9", amount: "2.4" },
      { price: "14.902", amount: "0.4" },
      { price: "14.93", amount: "104" },
      { price: "14.961", amount: "5" },
      { price: "14.997", amount: "1.35" },
      { price: "15", amount: "844.382955" },
      { price: "15.01", amount: "14" },
      { price: "15.03", amount: "50" },
      { price: "15.039", amount: "0.5" },
      { price: "15.066", amount: "0.5" },
      { price: "15.1", amount: "8" },
      { price: "15.11", amount: "5" },
      { price: "15.12", amount: "20" },
      { price: "15.15", amount: "20" },
      { price: "15.2", amount: "8" },
      { price: "15.204", amount: "1" },
      { price: "15.235", amount: "50" },
      { price: "15.238", amount: "10" },
      { price: "15.251", amount: "30" },
      { price: "15.288", amount: "30" },
      { price: "15.3", amount: "13" },
      { price: "15.313", amount: "200" },
      { price: "15.4", amount: "8.7" },
      { price: "15.424", amount: "20" },
      { price: "15.45", amount: "2.5" },
      { price: "15.474", amount: "2" },
      { price: "15.487", amount: "50" },
      { price: "15.5", amount: "11" },
      { price: "15.503", amount: "0.7" },
      { price: "15.524", amount: "118.600075" },
      { price: "15.56", amount: "18.49715" },
      { price: "15.6", amount: "181.405912" },
      { price: "15.607", amount: "0.7" },
      { price: "15.621", amount: "50" },
      { price: "15.67", amount: "49.92" },
      { price: "15.68", amount: "22.3180294" },
      { price: "15.682", amount: "1.82278481" },
      { price: "15.69", amount: "0.4" },
      { price: "15.7", amount: "8" },
      { price: "15.71", amount: "0.7" },
      { price: "15.779", amount: "9.98" },
      { price: "15.78", amount: "10" },
      { price: "15.794", amount: "3.83333333" },
      { price: "15.8", amount: "8" },
      { price: "15.814", amount: "0.7" },
      { price: "15.83", amount: "10" },
      { price: "15.84", amount: "5" },
      { price: "15.9", amount: "69.390035" },
      { price: "15.917", amount: "0.7" },
      { price: "15.947", amount: "50" },
      { price: "15.963", amount: "1" },
      { price: "15.972", amount: "10" },
      { price: "15.988", amount: "100" },
      { price: "16", amount: "62.167552" },
      { price: "16.021", amount: "0.7" },
      { price: "16.05", amount: "10" },
      { price: "16.08", amount: "50" },
      { price: "16.1", amount: "8" },
      { price: "16.124", amount: "0.7" },
      { price: "16.139", amount: "5.16666667" },
      { price: "16.16", amount: "25" },
      { price: "16.176", amount: "6" },
      { price: "16.177", amount: "10" },
      { price: "16.2", amount: "5" },
      { price: "16.228", amount: "0.7" },
      { price: "16.3", amount: "5" },
      { price: "16.331", amount: "0.7" },
      { price: "16.379", amount: "2" },
      { price: "16.4", amount: "5" },
      { price: "16.431", amount: "10" },
      { price: "16.434", amount: "0.7" },
      { price: "16.45", amount: "50" },
      { price: "16.477", amount: "1.5" },
      { price: "16.48", amount: "1" },
      { price: "16.483", amount: "4.125" },
      { price: "16.5", amount: "61.10000015" },
      { price: "16.538", amount: "0.7" },
      { price: "16.582", amount: "2" },
      { price: "16.597", amount: "2" },
      { price: "16.6", amount: "10.8" },
      { price: "16.621", amount: "20" },
      { price: "16.641", amount: "0.7" },
      { price: "16.7", amount: "55.457711" },
      { price: "16.736", amount: "3" },
      { price: "16.745", amount: "0.7" },
      { price: "16.748", amount: "20" },
      { price: "16.75", amount: "200" },
      { price: "16.786", amount: "0.5728" },
      { price: "16.8", amount: "65.6" },
      { price: "16.828", amount: "2.29166667" },
      { price: "16.848", amount: "0.7" },
      { price: "16.9", amount: "55" },
      { price: "16.914", amount: "2" },
      { price: "16.945", amount: "5" },
      { price: "16.952", amount: "0.7" },
      { price: "16.959", amount: "1" },
      { price: "16.96", amount: "0.5" },
      { price: "16.98", amount: "3.039885" },
      { price: "16.992", amount: "20" },
      { price: "16.996", amount: "3" },
      { price: "17", amount: "151" },
      { price: "17.041", amount: "50" },
      { price: "17.055", amount: "0.7" },
      { price: "17.08", amount: "50" },
      { price: "17.1", amount: "5" },
      { price: "17.116", amount: "22" },
      { price: "17.159", amount: "0.7" },
      { price: "17.17", amount: "30" },
      { price: "17.172", amount: "2.20833333" },
      { price: "17.2", amount: "5" },
      { price: "17.233", amount: "10" },
      { price: "17.257", amount: "7.220788" },
      { price: "17.262", amount: "0.7" },
      { price: "17.3", amount: "5.9842148" },
      { price: "17.366", amount: "0.7" },
      { price: "17.38", amount: "10" },
      { price: "17.4", amount: "55" },
      { price: "17.43", amount: "1" },
      { price: "17.45", amount: "12.924652" },
      { price: "17.469", amount: "0.7" },
      { price: "17.484", amount: "20" },
      { price: "17.49", amount: "50" },
      { price: "17.499", amount: "20" },
      { price: "17.5", amount: "106" },
      { price: "17.517", amount: "3.875" },
      { price: "17.549", amount: "100" },
      { price: "17.572", amount: "1.2" },
      { price: "17.6", amount: "5" },
      { price: "17.65", amount: "30" },
      { price: "17.654", amount: "10" },
      { price: "17.666", amount: "15" },
      { price: "17.676", amount: "0.7" },
      { price: "17.7", amount: "2524" },
      { price: "17.704", amount: "0.5" },
      { price: "17.737", amount: "1000" },
      { price: "17.779", amount: "0.7" },
      { price: "17.8", amount: "35" },
      { price: "17.861", amount: "4.83333333" },
      { price: "17.883", amount: "0.7" },
      { price: "17.89", amount: "50" },
      { price: "17.9", amount: "5.4" },
      { price: "17.972", amount: "0.6" },
      { price: "17.986", amount: "0.7" },
      { price: "17.99", amount: "25" },
      { price: "17.998", amount: "30.44944474" },
      { price: "18", amount: "1071.837566" },
      { price: "18.05", amount: "0.4" },
      { price: "18.08", amount: "50" },
      { price: "18.09", amount: "0.7" },
      { price: "18.1", amount: "5" },
      { price: "18.103", amount: "1.82278481" },
      { price: "18.132", amount: "50" },
      { price: "18.182", amount: "18" },
      { price: "18.193", amount: "0.7" },
      { price: "18.2", amount: "5" },
      { price: "18.206", amount: "3.66666667" },
      { price: "18.214", amount: "0.6" },
      { price: "18.231", amount: "9.98" },
      { price: "18.28", amount: "150" },
      { price: "18.281", amount: "25.698303" },
      { price: "18.297", amount: "0.7" },
      { price: "18.3", amount: "7.5" },
      { price: "18.33", amount: "30" },
      { price: "18.333", amount: "1000" },
      { price: "18.349", amount: "10" },
      { price: "18.4", amount: "5.7" },
      { price: "18.428", amount: "10" },
      { price: "18.449", amount: "49.95" },
      { price: "18.45", amount: "10" },
      { price: "18.497", amount: "0.4" },
      { price: "18.5", amount: "161" },
      { price: "18.55", amount: "2.5" },
      { price: "18.59", amount: "863.18" },
      { price: "18.6", amount: "6" },
      { price: "18.606", amount: "10" },
      { price: "18.625", amount: "20" },
      { price: "18.632", amount: "10" },
      { price: "18.643", amount: "2" },
      { price: "18.644", amount: "0.6" },
      { price: "18.649", amount: "700" },
      { price: "18.685", amount: "300" },
      { price: "18.7", amount: "5.5" },
      { price: "18.72", amount: "13" },
      { price: "18.752", amount: "31.223536" },
      { price: "18.757", amount: "20" },
      { price: "18.779", amount: "20" },
      { price: "18.78", amount: "100" },
      { price: "18.8", amount: "5.5" },
      { price: "18.868", amount: "0.5" },
      { price: "18.888", amount: "8" },
      { price: "18.889", amount: "20.99636839" },
      { price: "18.9", amount: "7.9" },
      { price: "18.922", amount: "29.972997" },
      { price: "18.931", amount: "0.2994" },
      { price: "18.95", amount: "18" },
      { price: "18.953", amount: "68.92" },
      { price: "18.99", amount: "100" },
      { price: "19", amount: "210.90378938" },
      { price: "19.1", amount: "7.4" },
      { price: "19.2", amount: "7.4" },
      { price: "19.278", amount: "1" },
      { price: "19.28", amount: "20" },
      { price: "19.3", amount: "7.4" },
      { price: "19.379", amount: "2" },
      { price: "19.385", amount: "34" },
      { price: "19.4", amount: "128.362" },
      { price: "19.437", amount: "1.11412101" },
      { price: "19.444", amount: "25.195709" },
      { price: "19.45", amount: "10" },
      { price: "19.47", amount: "50" },
      { price: "19.49", amount: "7.992" },
      { price: "19.5", amount: "130.68741272" },
      { price: "19.503", amount: "0.525" },
      { price: "19.562", amount: "1.1272959" },
      { price: "19.6", amount: "26.5" },
      { price: "19.604", amount: "0.7037498" },
      { price: "19.621", amount: "28.61" },
      { price: "19.68", amount: "15" },
      { price: "19.7", amount: "9.4" },
      { price: "19.744", amount: "20" },
      { price: "19.772", amount: "32" },
      { price: "19.8", amount: "70.1347183" },
      { price: "19.85", amount: "0.8894" },
      { price: "19.88", amount: "7.992" },
      { price: "19.89", amount: "27.972" },
      { price: "19.9", amount: "13" }
    ]

Defined in orderbook/__mocks__/data/snapshot.ts:5

###  bids

• **bids**: *object[]* =  [
      { price: "8.7605", amount: "58.77510615" },
      { price: "8.7604", amount: "61.52150127" },
      { price: "8.76", amount: "14.8" },
      { price: "8.7563", amount: "4.48743395" },
      { price: "8.7561", amount: "29.86958519" },
      { price: "8.7505", amount: "400" },
      { price: "8.7458", amount: "50" },
      { price: "8.7399", amount: "22.6" },
      { price: "8.7379", amount: "626" },
      { price: "8.7373", amount: "501.39561737" },
      { price: "8.737", amount: "75" },
      { price: "8.7367", amount: "22.7" },
      { price: "8.7339", amount: "134.7" },
      { price: "8.7283", amount: "100" },
      { price: "8.7275", amount: "889.93528089" },
      { price: "8.7274", amount: "432.14531246" },
      { price: "8.7272", amount: "1003.61076691" },
      { price: "8.7256", amount: "100" },
      { price: "8.7204", amount: "85.78904474" },
      { price: "8.7196", amount: "36.37" },
      { price: "8.719", amount: "6.41393514" },
      { price: "8.717", amount: "171.65171866" },
      { price: "8.7148", amount: "3072.1" },
      { price: "8.7138", amount: "1504.82404315" },
      { price: "8.7105", amount: "259.73134619" },
      { price: "8.7082", amount: "0.00022773" },
      { price: "8.7036", amount: "2.9172627" },
      { price: "8.7", amount: "149.6" },
      { price: "8.6868", amount: "52.57667655" },
      { price: "8.6836", amount: "53.30040736" },
      { price: "8.681", amount: "369.75139" },
      { price: "8.6806", amount: "2105.2" },
      { price: "8.68", amount: "27" },
      { price: "8.6763", amount: "50" },
      { price: "8.6745", amount: "3075.4" },
      { price: "8.67", amount: "27.51004303" },
      { price: "8.6654", amount: "204.29443169" },
      { price: "8.6653", amount: "5" },
      { price: "8.665", amount: "200" },
      { price: "8.6649", amount: "2722.3" },
      { price: "8.66", amount: "9.088" },
      { price: "8.6559", amount: "421.16710499" },
      { price: "8.6558", amount: "4.47068595" },
      { price: "8.6554", amount: "129" },
      { price: "8.6551", amount: "128" },
      { price: "8.6549", amount: "127" },
      { price: "8.6545", amount: "1.9483" },
      { price: "8.6533", amount: "3108.8" },
      { price: "8.6515", amount: "34.67606773" },
      { price: "8.6514", amount: "0.6" },
      { price: "8.6507", amount: "8.67553245" },
      { price: "8.65", amount: "2" },
      { price: "8.6494", amount: "3516.4" },
      { price: "8.6361", amount: "4.79525666" },
      { price: "8.6338", amount: "73.22086955" },
      { price: "8.6291", amount: "4542.1" },
      { price: "8.6252", amount: "127" },
      { price: "8.6187", amount: "5" },
      { price: "8.6141", amount: "11.60885004" },
      { price: "8.6098", amount: "50.00735589" },
      { price: "8.6096", amount: "3098.2" },
      { price: "8.6069", amount: "7.22599269" },
      { price: "8.6055", amount: "5867.1" },
      { price: "8.6011", amount: "5.72975917" },
      { price: "8.6", amount: "50" },
      { price: "8.5793", amount: "14.80781086" },
      { price: "8.5787", amount: "7578.6" },
      { price: "8.5763", amount: "2" },
      { price: "8.554", amount: "15" },
      { price: "8.5517", amount: "15.73994253" },
      { price: "8.5498", amount: "3059" },
      { price: "8.5489", amount: "9789.4" },
      { price: "8.5485", amount: "10" },
      { price: "8.5459", amount: "2" },
      { price: "8.5454", amount: "1.97318" },
      { price: "8.5427", amount: "1" },
      { price: "8.542", amount: "8" },
      { price: "8.541", amount: "250" },
      { price: "8.5373", amount: "200" },
      { price: "8.5241", amount: "16.67207419" },
      { price: "8.524", amount: "38.46153848" },
      { price: "8.5236", amount: "6309.4" },
      { price: "8.5224", amount: "4" },
      { price: "8.519", amount: "40" },
      { price: "8.5165", amount: "6316.2" },
      { price: "8.5151", amount: "3148.9" },
      { price: "8.5112", amount: "4" },
      { price: "8.5111", amount: "20" },
      { price: "8.51", amount: "25" },
      { price: "8.5075", amount: "2.13439" },
      { price: "8.5031", amount: "14" },
      { price: "8.501", amount: "11" },
      { price: "8.5", amount: "99.5" },
      { price: "8.4972", amount: "4" },
      { price: "8.4966", amount: "17.60420586" },
      { price: "8.4964", amount: "5.80036374" },
      { price: "8.493", amount: "43.452913" },
      { price: "8.4892", amount: "200" },
      { price: "8.489", amount: "5" },
      { price: "8.4792", amount: "50" },
      { price: "8.4747", amount: "10.32056544" },
      { price: "8.429", amount: "10.4965682" },
      { price: "8.4196", amount: "2" },
      { price: "8.4138", amount: "20.40060084" },
      { price: "8.4112", amount: "3" },
      { price: "8.4", amount: "9.612583" },
      { price: "8.3999", amount: "10" },
      { price: "8.3916", amount: "5.94639699" },
      { price: "8.3897", amount: "9.81471716" },
      { price: "8.3892", amount: "1" },
      { price: "8.3862", amount: "21.3327325" },
      { price: "8.3852", amount: "9.10879556" },
      { price: "8.3847", amount: "5" },
      { price: "8.381", amount: "50" },
      { price: "8.375", amount: "4" },
      { price: "8.3684", amount: "3.77840909" },
      { price: "8.361", amount: "0.4" },
      { price: "8.3586", amount: "22.26486416" },
      { price: "8.35", amount: "10.40213" },
      { price: "8.3437", amount: "8.63996995" },
      { price: "8.34", amount: "1" },
      { price: "8.331", amount: "23.19699582" },
      { price: "8.33", amount: "2" },
      { price: "8.3295", amount: "400" },
      { price: "8.3272", amount: "2.02488" },
      { price: "8.32", amount: "1" },
      { price: "8.31", amount: "4" },
      { price: "8.3034", amount: "24.12912748" },
      { price: "8.303", amount: "25.087" },
      { price: "8.3", amount: "652.61953" },
      { price: "8.2877", amount: "6.02090569" },
      { price: "8.2825", amount: "3133.5" },
      { price: "8.2796", amount: "12.07786671" },
      { price: "8.2759", amount: "25.06125915" },
      { price: "8.2583", amount: "50" },
      { price: "8.25", amount: "137.43213" },
      { price: "8.2483", amount: "25.9933908" },
      { price: "8.2385", amount: "13.44760157" },
      { price: "8.23", amount: "200" },
      { price: "8.224", amount: "8.18095964" },
      { price: "8.2232", amount: "8.28949646" },
      { price: "8.2207", amount: "26.92552247" },
      { price: "8.2185", amount: "400" },
      { price: "8.2181", amount: "2.05175" },
      { price: "8.21", amount: "900" },
      { price: "8.2084", amount: "1" },
      { price: "8.206", amount: "10" },
      { price: "8.2006", amount: "5" },
      { price: "8.2", amount: "515" },
      { price: "8.1931", amount: "27.85765413" },
      { price: "8.19", amount: "1" },
      { price: "8.1862", amount: "40" },
      { price: "8.1852", amount: "6.096348" },
      { price: "8.1847", amount: "8.31350501" },
      { price: "8.1842", amount: "3.94886364" },
      { price: "8.181", amount: "20" },
      { price: "8.18", amount: "1" },
      { price: "8.1787", amount: "3" },
      { price: "8.17", amount: "3" },
      { price: "8.1655", amount: "28.78978579" },
      { price: "8.1523", amount: "3074" },
      { price: "8.1379", amount: "29.72191745" },
      { price: "8.13", amount: "200" },
      { price: "8.1294", amount: "2.626479" },
      { price: "8.125", amount: "2" },
      { price: "8.118", amount: "1" },
      { price: "8.115", amount: "5" },
      { price: "8.1103", amount: "30.65404911" },
      { price: "8.109", amount: "4.97936" },
      { price: "8.1069", amount: "2" },
      { price: "8.1", amount: "41.4464" },
      { price: "8.0839", amount: "6.1727356" },
      { price: "8.0828", amount: "31.58618078" },
      { price: "8.081", amount: "3" },
      { price: "8.0765", amount: "8.0816726" },
      { price: "8.0686", amount: "50" },
      { price: "8.068", amount: "50" },
      { price: "8.06", amount: "1250" },
      { price: "8.0552", amount: "32.51831244" },
      { price: "8.05", amount: "15" },
      { price: "8.047", amount: "50" },
      { price: "8.0375", amount: "1" },
      { price: "8.0297", amount: "10" },
      { price: "8.0276", amount: "33.45044409" },
      { price: "8.0221", amount: "3144.9" },
      { price: "8.02", amount: "10" },
      { price: "8.0162", amount: "8.4361387" },
      { price: "8.01", amount: "0.4" },
      { price: "8.004", amount: "5" },
      { price: "8", amount: "431.00380392" },
      { price: "7.99", amount: "1" },
      { price: "7.9838", amount: "6.25008034" },
      { price: "7.975", amount: "1" },
      { price: "7.9276", amount: "7.95984656" },
      { price: "7.913", amount: "7.97612697" },
      { price: "7.9125", amount: "1" },
      { price: "7.906", amount: "20" },
      { price: "7.9", amount: "1" },
      { price: "7.8926", amount: "2" },
      { price: "7.8911", amount: "500" },
      { price: "7.89", amount: "3" },
      { price: "7.885", amount: "6.32839423" },
      { price: "7.88", amount: "10.29271613" },
      { price: "7.873", amount: "4" },
      { price: "7.8691", amount: "1" },
      { price: "7.85", amount: "1" },
      { price: "7.8194", amount: "10" },
      { price: "7.8103", amount: "5" },
      { price: "7.81", amount: "50" },
      { price: "7.8085", amount: "5" },
      { price: "7.8051", amount: "3074.8" },
      { price: "7.8", amount: "206" },
      { price: "7.7955", amount: "5" },
      { price: "7.7911", amount: "0.75" },
      { price: "7.7875", amount: "7.40768938" },
      { price: "7.7833", amount: "11.91626957" },
      { price: "7.78", amount: "212.2" },
      { price: "7.777", amount: "40" },
      { price: "7.7711", amount: "65.019417" },
      { price: "7.7614", amount: "2.044316" },
      { price: "7.75", amount: "10" },
      { price: "7.725", amount: "1" },
      { price: "7.7209", amount: "6" },
      { price: "7.717", amount: "2" },
      { price: "7.71", amount: "101" },
      { price: "7.705", amount: "500" },
      { price: "7.7", amount: "1.9" },
      { price: "7.6911", amount: "6.48797811" },
      { price: "7.688", amount: "2" },
      { price: "7.6867", amount: "16.44996596" },
      { price: "7.6625", amount: "1" },
      { price: "7.66", amount: "16.833963" },
      { price: "7.6513", amount: "1" },
      { price: "7.65", amount: "60" },
      { price: "7.6381", amount: "50" },
      { price: "7.6214", amount: "1.97" },
      { price: "7.61", amount: "10" },
      { price: "7.6091", amount: "5" },
      { price: "7.6", amount: "230.760554" },
      { price: "7.59", amount: "48.97481282" },
      { price: "7.57", amount: "25" },
      { price: "7.5675", amount: "1.074251" },
      { price: "7.5375", amount: "1" },
      { price: "7.53", amount: "25" },
      { price: "7.5253", amount: "40.33164" },
      { price: "7.522", amount: "100" },
      { price: "7.5179", amount: "5" },
      { price: "7.5174", amount: "345.64665972" },
      { price: "7.512", amount: "100" },
      { price: "7.509", amount: "1.4" },
      { price: "7.5054", amount: "5" },
      { price: "7.5", amount: "317.74824" },
      { price: "7.4898", amount: "1.66666667" },
      { price: "7.475", amount: "1" },
      { price: "7.4125", amount: "1" },
      { price: "7.4023", amount: "1" },
      { price: "7.4", amount: "9.5" },
      { price: "7.3732", amount: "2" },
      { price: "7.37", amount: "2" },
      { price: "7.3649", amount: "10" },
      { price: "7.364", amount: "100" },
      { price: "7.3534", amount: "2" },
      { price: "7.35", amount: "1" },
      { price: "7.3363", amount: "5" },
      { price: "7.3212", amount: "1" },
      { price: "7.32", amount: "50" },
      { price: "7.2875", amount: "1" },
      { price: "7.25", amount: "10" },
      { price: "7.225", amount: "1" },
      { price: "7.2241", amount: "0.6" },
      { price: "7.215", amount: "50" },
      { price: "7.2", amount: "132" },
      { price: "7.199", amount: "1000" },
      { price: "7.197", amount: "4.5" },
      { price: "7.17", amount: "14" },
      { price: "7.1625", amount: "1" },
      { price: "7.161", amount: "20" },
      { price: "7.1572", amount: "1" },
      { price: "7.1518", amount: "13.982" },
      { price: "7.15", amount: "214" },
      { price: "7.1475", amount: "8.613335" },
      { price: "7.1471", amount: "5" },
      { price: "7.1429", amount: "1" },
      { price: "7.13", amount: "71.108012" },
      { price: "7.1132", amount: "5" },
      { price: "7.11", amount: "53.44214281" },
      { price: "7.1", amount: "43.5019" },
      { price: "7.099", amount: "1000" },
      { price: "7.095", amount: "60" },
      { price: "7.09", amount: "100" },
      { price: "7.0886", amount: "2" },
      { price: "7.0773", amount: "0.90893478" },
      { price: "7.0677", amount: "8" },
      { price: "7.0649", amount: "1" },
      { price: "7.05", amount: "3" },
      { price: "7.041", amount: "3" },
      { price: "7.03", amount: "48.944379" },
      { price: "7.0298", amount: "10" },
      { price: "7.0169", amount: "20" },
      { price: "7.011", amount: "20" },
      { price: "7.01", amount: "4" },
      { price: "7.0082", amount: "28" },
      { price: "7", amount: "710.973257" },
      { price: "6.999", amount: "300" },
      { price: "6.9907", amount: "1.43045856" },
      { price: "6.9774", amount: "5.192559" },
      { price: "6.95", amount: "50" },
      { price: "6.944", amount: "2" },
      { price: "6.9372", amount: "3104" },
      { price: "6.9356", amount: "1" },
      { price: "6.93", amount: "0.7" },
      { price: "6.9222", amount: "5" },
      { price: "6.9162", amount: "721.205362" },
      { price: "6.9091", amount: "60" },
      { price: "6.8749", amount: "0.5" },
      { price: "6.8712", amount: "2" },
      { price: "6.8635", amount: "10" },
      { price: "6.85", amount: "50" },
      { price: "6.819", amount: "0.4" },
      { price: "6.81", amount: "900" },
      { price: "6.8036", amount: "2.184916" },
      { price: "6.8", amount: "191.983984" },
      { price: "6.789", amount: "200" },
      { price: "6.78", amount: "7" },
      { price: "6.7724", amount: "200" },
      { price: "6.761", amount: "2.8" },
      { price: "6.75", amount: "35" },
      { price: "6.71", amount: "2.6" },
      { price: "6.7", amount: "255" },
      { price: "6.6964", amount: "5" },
      { price: "6.66", amount: "15" },
      { price: "6.6293", amount: "2" },
      { price: "6.6232", amount: "1" },
      { price: "6.61", amount: "20.18761" },
      { price: "6.6", amount: "3" },
      { price: "6.57", amount: "76.225267" },
      { price: "6.555", amount: "50" },
      { price: "6.53", amount: "60" },
      { price: "6.5257", amount: "2.542735" },
      { price: "6.51", amount: "1250" },
      { price: "6.5", amount: "38.99" },
      { price: "6.4522", amount: "10" },
      { price: "6.45", amount: "12.01" },
      { price: "6.42", amount: "54.5" },
      { price: "6.41", amount: "2.6" },
      { price: "6.4", amount: "39.658144" },
      { price: "6.3118", amount: "20" },
      { price: "6.3", amount: "1" },
      { price: "6.299", amount: "5.003321" },
      { price: "6.2759", amount: "218.132223" },
      { price: "6.275", amount: "2.5" },
      { price: "6.2722", amount: "2.184916" },
      { price: "6.27", amount: "1" },
      { price: "6.25", amount: "10" },
      { price: "6.2498", amount: "11" },
      { price: "6.2162", amount: "30" },
      { price: "6.21", amount: "1" },
      { price: "6.2057", amount: "20" },
      { price: "6.2", amount: "7" },
      { price: "6.19", amount: "100" },
      { price: "6.18", amount: "20" },
      { price: "6.1481", amount: "1" },
      { price: "6.11", amount: "2.6" },
      { price: "6.1", amount: "15.97" },
      { price: "6.0885", amount: "16.61663" },
      { price: "6.07", amount: "1" },
      { price: "6.0694", amount: "618.5" },
      { price: "6.0606", amount: "20" },
      { price: "6.06", amount: "1" },
      { price: "6.05", amount: "10" },
      { price: "6.04", amount: "1" },
      { price: "6.028", amount: "2" },
      { price: "6.0186", amount: "15" },
      { price: "6.0146", amount: "5" },
      { price: "6.01", amount: "41.4" },
      { price: "6", amount: "275.14683201" },
      { price: "5.9986", amount: "50" },
      { price: "5.9266", amount: "1" },
      { price: "5.9", amount: "9.32" },
      { price: "5.87", amount: "1" },
      { price: "5.8499", amount: "100" },
      { price: "5.821", amount: "1.01" },
      { price: "5.8108", amount: "50" },
      { price: "5.81", amount: "2.6" },
      { price: "5.8", amount: "50.24137" },
      { price: "5.7885", amount: "15" },
      { price: "5.7648", amount: "90" },
      { price: "5.7634", amount: "5.011486" },
      { price: "5.76", amount: "14" },
      { price: "5.75", amount: "215" },
      { price: "5.7488", amount: "1" },
      { price: "5.748", amount: "40" },
      { price: "5.7367", amount: "10" },
      { price: "5.7311", amount: "2" },
      { price: "5.7122", amount: "30" },
      { price: "5.71", amount: "2.1" },
      { price: "5.703", amount: "1" },
      { price: "5.7", amount: "26.654743" },
      { price: "5.68", amount: "20" },
      { price: "5.66", amount: "10" },
      { price: "5.6338", amount: "7" },
      { price: "5.613", amount: "10" },
      { price: "5.6", amount: "3.5" },
      { price: "5.5886", amount: "2" },
      { price: "5.588", amount: "1" },
      { price: "5.57", amount: "1" },
      { price: "5.5658", amount: "200" },
      { price: "5.55", amount: "36.043936" },
      { price: "5.5322", amount: "250.7616" },
      { price: "5.532", amount: "8" },
      { price: "5.51", amount: "2.6" },
      { price: "5.5", amount: "36.2" },
      { price: "5.44", amount: "15.11" },
      { price: "5.4326", amount: "0.4" },
      { price: "5.4", amount: "10" },
      { price: "5.35", amount: "110" },
      { price: "5.345", amount: "50" },
      { price: "5.3275", amount: "5" },
      { price: "5.272", amount: "100" },
      { price: "5.27", amount: "101" },
      { price: "5.25", amount: "10" },
      { price: "5.21", amount: "2.6" },
      { price: "5.2015", amount: "625.8" },
      { price: "5.1907", amount: "1" },
      { price: "5.149", amount: "16.31" },
      { price: "5.1167", amount: "5" },
      { price: "5.112", amount: "2" },
      { price: "5.1", amount: "9" },
      { price: "5.07", amount: "1270.46118487" },
      { price: "5.0426", amount: "5" },
      { price: "5.031", amount: "6" },
      { price: "5.0109", amount: "132" },
      { price: "5.01", amount: "102" },
      { price: "5", amount: "253.7" },
      { price: "4.9761", amount: "1.106" },
      { price: "4.8133", amount: "5" },
      { price: "4.81", amount: "2.6" },
      { price: "4.786", amount: "30" },
      { price: "4.75", amount: "10" },
      { price: "4.73", amount: "50" },
      { price: "4.6516", amount: "21.74952" },
      { price: "4.65", amount: "50" },
      { price: "4.636", amount: "75.5" },
      { price: "4.6", amount: "2005" },
      { price: "4.5", amount: "60" },
      { price: "4.42", amount: "119.117498" },
      { price: "4.4", amount: "4" },
      { price: "4.2846", amount: "1" },
      { price: "4.2045", amount: "12" },
      { price: "4.17", amount: "100" },
      { price: "4.1588", amount: "1" },
      { price: "4.12", amount: "100" },
      { price: "4.11", amount: "500" },
      { price: "4.1", amount: "24.39024" },
      { price: "4.05", amount: "100" },
      { price: "4.02", amount: "204.1209825" },
      { price: "4", amount: "342.25" },
      { price: "3.9292", amount: "10" },
      { price: "3.9175", amount: "0.55" },
      { price: "3.84", amount: "750" },
      { price: "3.81", amount: "10" },
      { price: "3.7811", amount: "900" },
      { price: "3.77", amount: "3" },
      { price: "3.753", amount: "10" },
      { price: "3.75", amount: "30" },
      { price: "3.711", amount: "400" },
      { price: "3.6", amount: "3.68" },
      { price: "3.5", amount: "10" },
      { price: "3.4883", amount: "8600.12842858" },
      { price: "3.4366", amount: "73.13023" },
      { price: "3.3024", amount: "1" },
      { price: "3.24", amount: "316.436" },
      { price: "3.23", amount: "200" },
      { price: "3.22", amount: "100" },
      { price: "3.19", amount: "35" },
      { price: "3.1089", amount: "181.83611256" },
      { price: "3.1", amount: "100" },
      { price: "3.08", amount: "100" },
      { price: "3.0414", amount: "25" },
      { price: "3.03", amount: "100" },
      { price: "3", amount: "185.703892" },
      { price: "2.9", amount: "4" },
      { price: "2.8737", amount: "17.60237" },
      { price: "2.86", amount: "461.92" },
      { price: "2.8", amount: "25" },
      { price: "2.76", amount: "7" },
      { price: "2.56", amount: "206.78609095" },
      { price: "2.55", amount: "50" },
      { price: "2.5315", amount: "228.37452213" },
      { price: "2.5001", amount: "150" },
      { price: "2.5", amount: "133.540001" },
      { price: "2.4876", amount: "2.213" },
      { price: "2.4248", amount: "25" },
      { price: "2.2", amount: "50" },
      { price: "2.1928", amount: "1" },
      { price: "2.12", amount: "5" },
      { price: "2.089", amount: "25" },
      { price: "2.0639", amount: "80" },
      { price: "2.04", amount: "100" },
      { price: "2.01", amount: "30" },
      { price: "2", amount: "150" },
      { price: "1.99", amount: "2000" },
      { price: "1.96", amount: "1.00203196" },
      { price: "1.816", amount: "20" },
      { price: "1.8", amount: "10.99181" },
      { price: "1.76", amount: "5" },
      { price: "1.6604", amount: "476.8454582" },
      { price: "1.623", amount: "100" },
      { price: "1.56", amount: "400" },
      { price: "1.5", amount: "21" },
      { price: "1.416", amount: "0.4" },
      { price: "1.3181", amount: "604.9319526" },
      { price: "1.2917", amount: "3.87" },
      { price: "1.2443", amount: "4.425" },
      { price: "1.22", amount: "10" },
      { price: "1.16", amount: "5.9" },
      { price: "1.11", amount: "100" },
      { price: "1.1", amount: "25" },
      { price: "1.056", amount: "300" },
      { price: "1.05", amount: "1000" },
      { price: "1.0381", amount: "773.78481077" },
      { price: "1.03", amount: "1" },
      { price: "1.02", amount: "50" },
      { price: "1", amount: "4159.33267378" },
      { price: "0.917", amount: "1000" },
      { price: "0.91", amount: "29" },
      { price: "0.8921", amount: "6722.687923" },
      { price: "0.88996", amount: "1127.75143388" },
      { price: "0.88", amount: "2000" },
      { price: "0.7", amount: "200" },
      { price: "0.64587", amount: "7.74" },
      { price: "0.62218", amount: "8.85" },
      { price: "0.61", amount: "10" },
      { price: "0.60723", amount: "2134.43436788" },
      { price: "0.5506", amount: "798" },
      { price: "0.53", amount: "100" },
      { price: "0.5", amount: "21" },
      { price: "0.47834", amount: "1" },
      { price: "0.402", amount: "8" },
      { price: "0.4", amount: "10" },
      { price: "0.35", amount: "200" },
      { price: "0.32294", amount: "15.48" },
      { price: "0.31101", amount: "17.704" },
      { price: "0.31", amount: "15" },
      { price: "0.3", amount: "162" },
      { price: "0.27624", amount: "3738.65642253" },
      { price: "0.211", amount: "25" },
      { price: "0.21", amount: "100" },
      { price: "0.2", amount: "1034" },
      { price: "0.18", amount: "100" },
      { price: "0.16147", amount: "30.97" },
      { price: "0.15", amount: "480" },
      { price: "0.14315", amount: "100" },
      { price: "0.13", amount: "100" },
      { price: "0.12424", amount: "9673.23953171" },
      { price: "0.123", amount: "10000" },
      { price: "0.12177", amount: "415.41597" },
      { price: "0.11606", amount: "1.22519873" },
      { price: "0.11", amount: "1000.2" },
      { price: "0.101", amount: "50" },
      { price: "0.1", amount: "92.2117" },
      { price: "0.080734", amount: "61.93" },
      { price: "0.08", amount: "5000" },
      { price: "0.067", amount: "14.42989328" },
      { price: "0.053", amount: "1000" },
      { price: "0.040367", amount: "123.86" },
      { price: "0.04", amount: "100" },
      { price: "0.03", amount: "317" },
      { price: "0.025", amount: "50000" },
      { price: "0.0211", amount: "250" },
      { price: "0.020184", amount: "247.73" },
      { price: "0.02", amount: "231.269157" },
      { price: "0.014315", amount: "1000" },
      { price: "0.013", amount: "4000" },
      { price: "0.011", amount: "1600" },
      { price: "0.010001", amount: "2" },
      { price: "0.01", amount: "7649.974133" },
      { price: "0.0073752", amount: "0.491488" },
      { price: "0.005", amount: "4000" },
      { price: "0.0046101", amount: "1" },
      { price: "0.0041", amount: "1000" },
      { price: "0.004", amount: "1000" },
      { price: "0.003", amount: "1667" },
      { price: "0.00211", amount: "1250" },
      { price: "0.002", amount: "10000" },
      { price: "0.0011", amount: "5000" },
      { price: "0.001", amount: "11000" },
      { price: "0.00099263", amount: "4" },
      { price: "0.000698", amount: "1000" },
      { price: "0.000411", amount: "20000" },
      { price: "0.00041", amount: "10000" },
      { price: "0.0004", amount: "10000" },
      { price: "0.00035", amount: "60000" },
      { price: "0.00034", amount: "10000" },
      { price: "0.00033", amount: "10000" },
      { price: "0.00032", amount: "10000" },
      { price: "0.00031", amount: "10000" },
      { price: "0.0003", amount: "10000" },
      { price: "0.00029", amount: "10000" },
      { price: "0.00028", amount: "10000" },
      { price: "0.00027", amount: "10000" },
      { price: "0.00026", amount: "10000" },
      { price: "0.00025", amount: "10000" },
      { price: "0.00024", amount: "12000" },
      { price: "0.00023", amount: "10000" },
      { price: "0.00022", amount: "10000" },
      { price: "0.000211", amount: "5000" },
      { price: "0.00021", amount: "10000" },
      { price: "0.00020077", amount: "10000" },
      { price: "0.0002", amount: "12000" },
      { price: "0.00019", amount: "10000" },
      { price: "0.00017", amount: "7000" },
      { price: "0.0001", amount: "24000" },
      { price: "0.000024", amount: "10000" },
      { price: "0.000022", amount: "10000" },
      { price: "0.00002", amount: "30000" },
      { price: "0.00001", amount: "230000" },
      { price: "0.000002", amount: "10000" },
      { price: "0.000001", amount: "60000" },
      { price: "1.1e-7", amount: "100000" },
      { price: "1e-7", amount: "140000" }
    ]

Defined in orderbook/__mocks__/data/snapshot.ts:1005

###  seqNum

• **seqNum**: *number* = 1012077

Defined in orderbook/__mocks__/data/snapshot.ts:4

___

### `Const` orderTypeFromProto

### ▪ **orderTypeFromProto**: *object*

Defined in websocket/proto/constants.ts:34

###  0

• **0**: *"market"* = "market"

Defined in websocket/proto/constants.ts:35

###  1

• **1**: *"limit"* = "limit"

Defined in websocket/proto/constants.ts:36

___

### `Const` orderTypeToProto

### ▪ **orderTypeToProto**: *object*

Defined in websocket/proto/constants.ts:50

###  limit

• **limit**: *number* = 1

Defined in websocket/proto/constants.ts:52

###  market

• **market**: *number* = 0

Defined in websocket/proto/constants.ts:51

___

### `Const` periodFromInt

### ▪ **periodFromInt**: *object*

Defined in websocket/proto/constants.ts:82

###  14400

• **14400**: *[Period4H](enums/period.md#period4h)* =  Period.Period4H

Defined in websocket/proto/constants.ts:90

###  180

• **180**: *[Period3M](enums/period.md#period3m)* =  Period.Period3M

Defined in websocket/proto/constants.ts:84

###  1800

• **1800**: *[Period30M](enums/period.md#period30m)* =  Period.Period30M

Defined in websocket/proto/constants.ts:87

###  21600

• **21600**: *[Period6H](enums/period.md#period6h)* =  Period.Period6H

Defined in websocket/proto/constants.ts:91

###  259200

• **259200**: *[Period3D](enums/period.md#period3d)* =  Period.Period3D

Defined in websocket/proto/constants.ts:94

###  300

• **300**: *[Period5M](enums/period.md#period5m)* =  Period.Period5M

Defined in websocket/proto/constants.ts:85

###  3600

• **3600**: *[Period1H](enums/period.md#period1h)* =  Period.Period1H

Defined in websocket/proto/constants.ts:88

###  43200

• **43200**: *[Period12H](enums/period.md#period12h)* =  Period.Period12H

Defined in websocket/proto/constants.ts:92

###  60

• **60**: *[Period1M](enums/period.md#period1m)* =  Period.Period1M

Defined in websocket/proto/constants.ts:83

###  604800

• **604800**: *[Period1W](enums/period.md#period1w)* =  Period.Period1W

Defined in websocket/proto/constants.ts:95

###  7200

• **7200**: *[Period2H](enums/period.md#period2h)* =  Period.Period2H

Defined in websocket/proto/constants.ts:89

###  86400

• **86400**: *[Period1D](enums/period.md#period1d)* =  Period.Period1D

Defined in websocket/proto/constants.ts:93

###  900

• **900**: *[Period15M](enums/period.md#period15m)* =  Period.Period15M

Defined in websocket/proto/constants.ts:86

___

### `Const` privateOrderSideFromProto

### ▪ **privateOrderSideFromProto**: *object*

Defined in websocket/proto/constants.ts:4

###  0

• **0**: *"sell"* = "sell"

Defined in websocket/proto/constants.ts:5

###  1

• **1**: *"buy"* = "buy"

Defined in websocket/proto/constants.ts:6

___

### `Const` privateOrderSideToProto

### ▪ **privateOrderSideToProto**: *object*

Defined in websocket/proto/constants.ts:9

###  buy

• **buy**: *number* = 1

Defined in websocket/proto/constants.ts:11

###  sell

• **sell**: *number* = 0

Defined in websocket/proto/constants.ts:10

___

### `Const` publicOrderSideFromProto

### ▪ **publicOrderSideFromProto**: *object*

Defined in websocket/proto/constants.ts:14

###  0

• **0**: *"buy"* = "buy"

Defined in websocket/proto/constants.ts:15

###  1

• **1**: *"sell"* = "sell"

Defined in websocket/proto/constants.ts:16

___

### `Const` publicOrderSideToProto

### ▪ **publicOrderSideToProto**: *object*

Defined in websocket/proto/constants.ts:19

###  buy

• **buy**: *number* = 0

Defined in websocket/proto/constants.ts:20

###  sell

• **sell**: *number* = 1

Defined in websocket/proto/constants.ts:21
