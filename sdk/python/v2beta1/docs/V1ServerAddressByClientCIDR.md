# V1ServerAddressByClientCIDR

ServerAddressByClientCIDR helps the client to determine the server address that they should use, depending on the clientCIDR that they match.

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**client_cidr** | **str** | The CIDR with which clients can match their IP to figure out the server address that they should use. | [default to '']
**server_address** | **str** | Address of this server, suitable for a client that matches the above CIDR. This can be a hostname, hostname:port, IP or IP:port. | [default to '']

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


