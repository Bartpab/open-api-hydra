# AcceptConsentRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**grant_access_token_audience** | Option<**Vec<String>**> | GrantedAudience sets the audience the user authorized the client to use. Should be a subset of `requested_access_token_audience`. | [optional]
**grant_scope** | Option<**Vec<String>**> | GrantScope sets the scope the user authorized the client to use. Should be a subset of `requested_scope`. | [optional]
**remember** | Option<**bool**> | Remember, if set to true, tells ORY Hydra to remember this consent authorization and reuse it if the same client asks the same user for the same, or a subset of, scope. | [optional]
**remember_for** | Option<**i64**> | RememberFor sets how long the consent authorization should be remembered for in seconds. If set to `0`, the authorization will be remembered indefinitely. | [optional]
**session** | Option<[**crate::models::ConsentRequestSession**](consentRequestSession.md)> |  | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


