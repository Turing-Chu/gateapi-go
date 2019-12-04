# BatchOrder

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** | User defined information. If not empty, must follow the rules below:  1. prefixed with &#x60;t-&#x60; 2. no longer than 16 bytes without &#x60;t-&#x60; prefix 3. can only include 0-9, A-Z, a-z, underscore(_), hyphen(-) or dot(.)  | [optional] 
**Succeeded** | **bool** | Whether order succeeds | [optional] 
**Label** | **string** | Error label, empty string if order succeeds | [optional] 
**Message** | **string** | Detailed error message, empty string if order succeeds | [optional] 
**Id** | **string** | Order ID | [optional] 
**CreateTime** | **string** | Order creation time | [optional] 
**Status** | **string** | Order status  - &#x60;open&#x60;: to be filled - &#x60;closed&#x60;: filled - &#x60;cancelled&#x60;: cancelled | [optional] 
**CurrencyPair** | **string** | Currency pair | [optional] 
**Type** | **string** | Order type. limit - limit order | [optional] [default to TYPE_LIMIT]
**Account** | **string** | Account type. spot - use spot account; margin - use margin account | [optional] [default to ACCOUNT_SPOT]
**Side** | **string** | Order side | [optional] 
**Amount** | **string** | Trade amount | [optional] 
**Price** | **string** | Order price | [optional] 
**TimeInForce** | **string** | Time in force | [optional] [default to TIME_IN_FORCE_GTC]
**Left** | **string** | Amount left to fill | [optional] 
**FillPrice** | **string** | Fill price of the order | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

