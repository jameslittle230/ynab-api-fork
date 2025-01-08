# SaveTransactionWithIdOrImportIdAllOf

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | Option<**String**> | If specified, this id will be used to lookup a transaction by its `id` for the purpose of updating the transaction itself. If not specified, an `import_id` should be supplied. | [optional]
**import_id** | Option<**String**> | If specified, this id will be used to lookup a transaction by its `import_id` for the purpose of updating the transaction itself. If not specified, an `id` should be supplied.  You may not provide both an `id` and an `import_id` and updating an `import_id` on an existing transaction is not allowed. | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


