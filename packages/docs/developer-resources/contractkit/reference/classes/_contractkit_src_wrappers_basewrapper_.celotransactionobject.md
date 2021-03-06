# Class: CeloTransactionObject <**O**>

## Type parameters

▪ **O**

## Hierarchy

* **CeloTransactionObject**

## Index

### Constructors

* [constructor](_contractkit_src_wrappers_basewrapper_.celotransactionobject.md#constructor)

### Properties

* [defaultParams](_contractkit_src_wrappers_basewrapper_.celotransactionobject.md#optional-defaultparams)
* [txo](_contractkit_src_wrappers_basewrapper_.celotransactionobject.md#txo)

### Methods

* [send](_contractkit_src_wrappers_basewrapper_.celotransactionobject.md#send)
* [sendAndWaitForReceipt](_contractkit_src_wrappers_basewrapper_.celotransactionobject.md#sendandwaitforreceipt)

## Constructors

###  constructor

\+ **new CeloTransactionObject**(`kit`: [ContractKit](_contractkit_src_kit_.contractkit.md), `txo`: TransactionObject‹O›, `defaultParams?`: [CeloTransactionParams](../modules/_contractkit_src_wrappers_basewrapper_.md#celotransactionparams)): *[CeloTransactionObject](_contractkit_src_wrappers_basewrapper_.celotransactionobject.md)*

*Defined in [contractkit/src/wrappers/BaseWrapper.ts:244](https://github.com/celo-org/celo-monorepo/blob/master/packages/contractkit/src/wrappers/BaseWrapper.ts#L244)*

**Parameters:**

Name | Type |
------ | ------ |
`kit` | [ContractKit](_contractkit_src_kit_.contractkit.md) |
`txo` | TransactionObject‹O› |
`defaultParams?` | [CeloTransactionParams](../modules/_contractkit_src_wrappers_basewrapper_.md#celotransactionparams) |

**Returns:** *[CeloTransactionObject](_contractkit_src_wrappers_basewrapper_.celotransactionobject.md)*

## Properties

### `Optional` defaultParams

• **defaultParams**? : *[CeloTransactionParams](../modules/_contractkit_src_wrappers_basewrapper_.md#celotransactionparams)*

*Defined in [contractkit/src/wrappers/BaseWrapper.ts:248](https://github.com/celo-org/celo-monorepo/blob/master/packages/contractkit/src/wrappers/BaseWrapper.ts#L248)*

___

###  txo

• **txo**: *TransactionObject‹O›*

*Defined in [contractkit/src/wrappers/BaseWrapper.ts:247](https://github.com/celo-org/celo-monorepo/blob/master/packages/contractkit/src/wrappers/BaseWrapper.ts#L247)*

## Methods

###  send

▸ **send**(`params?`: [CeloTransactionParams](../modules/_contractkit_src_wrappers_basewrapper_.md#celotransactionparams)): *Promise‹[TransactionResult](_contractkit_src_utils_tx_result_.transactionresult.md)›*

*Defined in [contractkit/src/wrappers/BaseWrapper.ts:252](https://github.com/celo-org/celo-monorepo/blob/master/packages/contractkit/src/wrappers/BaseWrapper.ts#L252)*

send the transaction to the chain

**Parameters:**

Name | Type |
------ | ------ |
`params?` | [CeloTransactionParams](../modules/_contractkit_src_wrappers_basewrapper_.md#celotransactionparams) |

**Returns:** *Promise‹[TransactionResult](_contractkit_src_utils_tx_result_.transactionresult.md)›*

___

###  sendAndWaitForReceipt

▸ **sendAndWaitForReceipt**(`params?`: [CeloTransactionParams](../modules/_contractkit_src_wrappers_basewrapper_.md#celotransactionparams)): *Promise‹TransactionReceipt›*

*Defined in [contractkit/src/wrappers/BaseWrapper.ts:257](https://github.com/celo-org/celo-monorepo/blob/master/packages/contractkit/src/wrappers/BaseWrapper.ts#L257)*

send the transaction and waits for the receipt

**Parameters:**

Name | Type |
------ | ------ |
`params?` | [CeloTransactionParams](../modules/_contractkit_src_wrappers_basewrapper_.md#celotransactionparams) |

**Returns:** *Promise‹TransactionReceipt›*
