[cw-sdk-node](../README.md) › [StreamClient](streamclient.md)

# Class: StreamClient

## Hierarchy

  ↳ [WebSocketClient](websocketclient.md)

  ↳ **StreamClient**

## Index

### Constructors

* [constructor](streamclient.md#constructor)

### Properties

* [connState](streamclient.md#protected-connstate)
* [subscriptions](streamclient.md#subscriptions)
* [defaultMaxListeners](streamclient.md#static-defaultmaxlisteners)

### Methods

* [addListener](streamclient.md#addlistener)
* [connect](streamclient.md#connect)
* [disconnect](streamclient.md#disconnect)
* [emit](streamclient.md#emit)
* [error](streamclient.md#error)
* [eventNames](streamclient.md#eventnames)
* [getMaxListeners](streamclient.md#getmaxlisteners)
* [getSubscriptions](streamclient.md#getsubscriptions)
* [listenerCount](streamclient.md#listenercount)
* [listeners](streamclient.md#listeners)
* [off](streamclient.md#off)
* [on](streamclient.md#on)
* [onConnect](streamclient.md#onconnect)
* [onDisconnect](streamclient.md#ondisconnect)
* [onError](streamclient.md#onerror)
* [onMarketUpdate](streamclient.md#onmarketupdate)
* [onPairUpdate](streamclient.md#onpairupdate)
* [onStateChange](streamclient.md#onstatechange)
* [once](streamclient.md#once)
* [prependListener](streamclient.md#prependlistener)
* [prependOnceListener](streamclient.md#prependoncelistener)
* [rawListeners](streamclient.md#rawlisteners)
* [removeAllListeners](streamclient.md#removealllisteners)
* [removeListener](streamclient.md#removelistener)
* [send](streamclient.md#send)
* [setMaxListeners](streamclient.md#setmaxlisteners)
* [state](streamclient.md#state)
* [subscribe](streamclient.md#subscribe)
* [unsubscribe](streamclient.md#unsubscribe)
* [listenerCount](streamclient.md#static-listenercount)

## Constructors

###  constructor

\+ **new StreamClient**(`opts`: Partial‹[StreamOpts](../interfaces/streamopts.md)›): *[StreamClient](streamclient.md)*

*Overrides [WebSocketClient](websocketclient.md).[constructor](websocketclient.md#constructor)*

Defined in websocket/StreamClient.ts:18

**Parameters:**

Name | Type |
------ | ------ |
`opts` | Partial‹[StreamOpts](../interfaces/streamopts.md)› |

**Returns:** *[StreamClient](streamclient.md)*

## Properties

### `Protected` connState

• **connState**: *symbol*

*Inherited from [WebSocketClient](websocketclient.md).[connState](websocketclient.md#protected-connstate)*

Defined in websocket/WebSocketClient.ts:58

___

###  subscriptions

• **subscriptions**: *object*

*Inherited from [WebSocketClient](websocketclient.md).[subscriptions](websocketclient.md#subscriptions)*

Defined in websocket/WebSocketClient.ts:47

#### Type declaration:

* \[ **key**: *string*\]: ClientSubscription

___

### `Static` defaultMaxListeners

▪ **defaultMaxListeners**: *number*

*Inherited from void*

Defined in /home/dave/src/cryptowatch/cw-sdk-node/node_modules/@types/node/events.d.ts:9

## Methods

###  addListener

▸ **addListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

*Overrides void*

Defined in /home/dave/src/cryptowatch/cw-sdk-node/node_modules/@types/node/events.d.ts:11

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  connect

▸ **connect**(): *void*

*Inherited from [WebSocketClient](websocketclient.md).[connect](websocketclient.md#connect)*

Defined in websocket/WebSocketClient.ts:101

**Returns:** *void*

___

###  disconnect

▸ **disconnect**(): *void*

*Inherited from [WebSocketClient](websocketclient.md).[disconnect](websocketclient.md#disconnect)*

Defined in websocket/WebSocketClient.ts:161

**Returns:** *void*

___

###  emit

▸ **emit**(`event`: string | symbol, ...`args`: any[]): *boolean*

*Inherited from void*

*Overrides void*

Defined in /home/dave/src/cryptowatch/cw-sdk-node/node_modules/@types/node/events.d.ts:23

**Parameters:**

Name | Type |
------ | ------ |
`event` | string &#124; symbol |
`...args` | any[] |

**Returns:** *boolean*

___

###  error

▸ **error**(`e`: string): *void*

*Inherited from [WebSocketClient](websocketclient.md).[error](websocketclient.md#error)*

Defined in websocket/WebSocketClient.ts:133

**Parameters:**

Name | Type |
------ | ------ |
`e` | string |

**Returns:** *void*

___

###  eventNames

▸ **eventNames**(): *Array‹string | symbol›*

*Inherited from void*

*Overrides void*

Defined in /home/dave/src/cryptowatch/cw-sdk-node/node_modules/@types/node/events.d.ts:24

**Returns:** *Array‹string | symbol›*

___

###  getMaxListeners

▸ **getMaxListeners**(): *number*

*Inherited from void*

*Overrides void*

Defined in /home/dave/src/cryptowatch/cw-sdk-node/node_modules/@types/node/events.d.ts:20

**Returns:** *number*

___

###  getSubscriptions

▸ **getSubscriptions**(): *ClientSubscription[]*

*Inherited from [WebSocketClient](websocketclient.md).[getSubscriptions](websocketclient.md#getsubscriptions)*

Defined in websocket/WebSocketClient.ts:173

**Returns:** *ClientSubscription[]*

___

###  listenerCount

▸ **listenerCount**(`type`: string | symbol): *number*

*Inherited from void*

*Overrides void*

Defined in /home/dave/src/cryptowatch/cw-sdk-node/node_modules/@types/node/events.d.ts:25

**Parameters:**

Name | Type |
------ | ------ |
`type` | string &#124; symbol |

**Returns:** *number*

___

###  listeners

▸ **listeners**(`event`: string | symbol): *Function[]*

*Inherited from void*

*Overrides void*

Defined in /home/dave/src/cryptowatch/cw-sdk-node/node_modules/@types/node/events.d.ts:21

**Parameters:**

Name | Type |
------ | ------ |
`event` | string &#124; symbol |

**Returns:** *Function[]*

___

###  off

▸ **off**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

*Overrides void*

Defined in /home/dave/src/cryptowatch/cw-sdk-node/node_modules/@types/node/events.d.ts:17

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  on

▸ **on**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

*Overrides void*

Defined in /home/dave/src/cryptowatch/cw-sdk-node/node_modules/@types/node/events.d.ts:12

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  onConnect

▸ **onConnect**(`fn`: function): *void*

*Inherited from [WebSocketClient](websocketclient.md).[onConnect](websocketclient.md#onconnect)*

Defined in websocket/WebSocketClient.ts:138

**Parameters:**

▪ **fn**: *function*

▸ (): *void*

**Returns:** *void*

___

###  onDisconnect

▸ **onDisconnect**(`fn`: function): *void*

*Inherited from [WebSocketClient](websocketclient.md).[onDisconnect](websocketclient.md#ondisconnect)*

Defined in websocket/WebSocketClient.ts:142

**Parameters:**

▪ **fn**: *function*

▸ (): *void*

**Returns:** *void*

___

###  onError

▸ **onError**(`fn`: function): *void*

*Inherited from [WebSocketClient](websocketclient.md).[onError](websocketclient.md#onerror)*

Defined in websocket/WebSocketClient.ts:150

**Parameters:**

▪ **fn**: *function*

▸ (`e`: Error): *void*

**Parameters:**

Name | Type |
------ | ------ |
`e` | Error |

**Returns:** *void*

___

###  onMarketUpdate

▸ **onMarketUpdate**(`fn`: function): *void*

Defined in websocket/StreamClient.ts:85

**Parameters:**

▪ **fn**: *function*

▸ (`m`: [MarketUpdate](../interfaces/marketupdate.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`m` | [MarketUpdate](../interfaces/marketupdate.md) |

**Returns:** *void*

___

###  onPairUpdate

▸ **onPairUpdate**(`fn`: function): *void*

Defined in websocket/StreamClient.ts:76

**Parameters:**

▪ **fn**: *function*

▸ (`m`: [PairUpdate](../interfaces/pairupdate.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`m` | [PairUpdate](../interfaces/pairupdate.md) |

**Returns:** *void*

___

###  onStateChange

▸ **onStateChange**(`fn`: function): *void*

*Inherited from [WebSocketClient](websocketclient.md).[onStateChange](websocketclient.md#onstatechange)*

Defined in websocket/WebSocketClient.ts:146

**Parameters:**

▪ **fn**: *function*

▸ (`s`: string): *void*

**Parameters:**

Name | Type |
------ | ------ |
`s` | string |

**Returns:** *void*

___

###  once

▸ **once**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

*Overrides void*

Defined in /home/dave/src/cryptowatch/cw-sdk-node/node_modules/@types/node/events.d.ts:13

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  prependListener

▸ **prependListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

*Overrides void*

Defined in /home/dave/src/cryptowatch/cw-sdk-node/node_modules/@types/node/events.d.ts:14

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  prependOnceListener

▸ **prependOnceListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

*Overrides void*

Defined in /home/dave/src/cryptowatch/cw-sdk-node/node_modules/@types/node/events.d.ts:15

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  rawListeners

▸ **rawListeners**(`event`: string | symbol): *Function[]*

*Inherited from void*

*Overrides void*

Defined in /home/dave/src/cryptowatch/cw-sdk-node/node_modules/@types/node/events.d.ts:22

**Parameters:**

Name | Type |
------ | ------ |
`event` | string &#124; symbol |

**Returns:** *Function[]*

___

###  removeAllListeners

▸ **removeAllListeners**(`event?`: string | symbol): *this*

*Inherited from void*

*Overrides void*

Defined in /home/dave/src/cryptowatch/cw-sdk-node/node_modules/@types/node/events.d.ts:18

**Parameters:**

Name | Type |
------ | ------ |
`event?` | string &#124; symbol |

**Returns:** *this*

___

###  removeListener

▸ **removeListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from void*

*Overrides void*

Defined in /home/dave/src/cryptowatch/cw-sdk-node/node_modules/@types/node/events.d.ts:16

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  send

▸ **send**(`data`: Buffer | Uint8Array): *void*

*Inherited from [WebSocketClient](websocketclient.md).[send](websocketclient.md#send)*

Defined in websocket/WebSocketClient.ts:154

**Parameters:**

Name | Type |
------ | ------ |
`data` | Buffer &#124; Uint8Array |

**Returns:** *void*

___

###  setMaxListeners

▸ **setMaxListeners**(`n`: number): *this*

*Inherited from void*

*Overrides void*

Defined in /home/dave/src/cryptowatch/cw-sdk-node/node_modules/@types/node/events.d.ts:19

**Parameters:**

Name | Type |
------ | ------ |
`n` | number |

**Returns:** *this*

___

###  state

▸ **state**(): *symbol*

*Inherited from [WebSocketClient](websocketclient.md).[state](websocketclient.md#state)*

Defined in websocket/WebSocketClient.ts:169

**Returns:** *symbol*

___

###  subscribe

▸ **subscribe**(`keys`: string[]): *void*

Defined in websocket/StreamClient.ts:44

**Parameters:**

Name | Type |
------ | ------ |
`keys` | string[] |

**Returns:** *void*

___

###  unsubscribe

▸ **unsubscribe**(`keys`: string[]): *void*

Defined in websocket/StreamClient.ts:60

**Parameters:**

Name | Type |
------ | ------ |
`keys` | string[] |

**Returns:** *void*

___

### `Static` listenerCount

▸ **listenerCount**(`emitter`: EventEmitter, `event`: string | symbol): *number*

*Inherited from void*

Defined in /home/dave/src/cryptowatch/cw-sdk-node/node_modules/@types/node/events.d.ts:8

**`deprecated`** since v4.0.0

**Parameters:**

Name | Type |
------ | ------ |
`emitter` | EventEmitter |
`event` | string &#124; symbol |

**Returns:** *number*
