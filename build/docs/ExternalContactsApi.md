---
title: ExternalContactsApi
---
# platformClient.ExternalContactsApi

All URIs are relative to *https://api.mypurecloud.com*

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
[**deleteExternalcontactsContact**](ExternalContactsApi.html#deleteExternalcontactsContact) | **DELETE** /api/v2/externalcontacts/contacts/{contactId} | Delete an external contact
[**deleteExternalcontactsContactNote**](ExternalContactsApi.html#deleteExternalcontactsContactNote) | **DELETE** /api/v2/externalcontacts/contacts/{contactId}/notes/{noteId} | Delete a note for an external contact
[**deleteExternalcontactsOrganization**](ExternalContactsApi.html#deleteExternalcontactsOrganization) | **DELETE** /api/v2/externalcontacts/organizations/{externalOrganizationId} | Delete an external organization
[**deleteExternalcontactsOrganizationNote**](ExternalContactsApi.html#deleteExternalcontactsOrganizationNote) | **DELETE** /api/v2/externalcontacts/organizations/{externalOrganizationId}/notes/{noteId} | Delete a note for an external organization
[**deleteExternalcontactsOrganizationTrustor**](ExternalContactsApi.html#deleteExternalcontactsOrganizationTrustor) | **DELETE** /api/v2/externalcontacts/organizations/{externalOrganizationId}/trustor | Unlink the Trustor for this External Organization
[**deleteExternalcontactsRelationship**](ExternalContactsApi.html#deleteExternalcontactsRelationship) | **DELETE** /api/v2/externalcontacts/relationships/{relationshipId} | Delete a relationship
[**getExternalcontactsContact**](ExternalContactsApi.html#getExternalcontactsContact) | **GET** /api/v2/externalcontacts/contacts/{contactId} | Fetch an external contact
[**getExternalcontactsContactNote**](ExternalContactsApi.html#getExternalcontactsContactNote) | **GET** /api/v2/externalcontacts/contacts/{contactId}/notes/{noteId} | Fetch a note for an external contact
[**getExternalcontactsContactNotes**](ExternalContactsApi.html#getExternalcontactsContactNotes) | **GET** /api/v2/externalcontacts/contacts/{contactId}/notes | List notes for an external contact
[**getExternalcontactsContacts**](ExternalContactsApi.html#getExternalcontactsContacts) | **GET** /api/v2/externalcontacts/contacts | Search for external contacts
[**getExternalcontactsOrganization**](ExternalContactsApi.html#getExternalcontactsOrganization) | **GET** /api/v2/externalcontacts/organizations/{externalOrganizationId} | Fetch an external organization
[**getExternalcontactsOrganizationContacts**](ExternalContactsApi.html#getExternalcontactsOrganizationContacts) | **GET** /api/v2/externalcontacts/organizations/{externalOrganizationId}/contacts | Search for external contacts in an external organization
[**getExternalcontactsOrganizationNote**](ExternalContactsApi.html#getExternalcontactsOrganizationNote) | **GET** /api/v2/externalcontacts/organizations/{externalOrganizationId}/notes/{noteId} | Fetch a note for an external organization
[**getExternalcontactsOrganizationNotes**](ExternalContactsApi.html#getExternalcontactsOrganizationNotes) | **GET** /api/v2/externalcontacts/organizations/{externalOrganizationId}/notes | List notes for an external organization
[**getExternalcontactsOrganizationRelationships**](ExternalContactsApi.html#getExternalcontactsOrganizationRelationships) | **GET** /api/v2/externalcontacts/organizations/{externalOrganizationId}/relationships | Fetch a relationship for an external organization
[**getExternalcontactsOrganizations**](ExternalContactsApi.html#getExternalcontactsOrganizations) | **GET** /api/v2/externalcontacts/organizations | Search for external organizations
[**getExternalcontactsRelationship**](ExternalContactsApi.html#getExternalcontactsRelationship) | **GET** /api/v2/externalcontacts/relationships/{relationshipId} | Fetch a relationship
[**getExternalcontactsReversewhitepageslookup**](ExternalContactsApi.html#getExternalcontactsReversewhitepageslookup) | **GET** /api/v2/externalcontacts/reversewhitepageslookup | Lookup contacts and externalOrganizations based on an attribute
[**postExternalcontactsContactNotes**](ExternalContactsApi.html#postExternalcontactsContactNotes) | **POST** /api/v2/externalcontacts/contacts/{contactId}/notes | Create a note for an external contact
[**postExternalcontactsContacts**](ExternalContactsApi.html#postExternalcontactsContacts) | **POST** /api/v2/externalcontacts/contacts | Create an external contact
[**postExternalcontactsOrganizationNotes**](ExternalContactsApi.html#postExternalcontactsOrganizationNotes) | **POST** /api/v2/externalcontacts/organizations/{externalOrganizationId}/notes | Create a note for an external organization
[**postExternalcontactsOrganizations**](ExternalContactsApi.html#postExternalcontactsOrganizations) | **POST** /api/v2/externalcontacts/organizations | Create an external organization
[**postExternalcontactsRelationships**](ExternalContactsApi.html#postExternalcontactsRelationships) | **POST** /api/v2/externalcontacts/relationships | Create a relationship
[**putExternalcontactsContact**](ExternalContactsApi.html#putExternalcontactsContact) | **PUT** /api/v2/externalcontacts/contacts/{contactId} | Update an external contact
[**putExternalcontactsContactNote**](ExternalContactsApi.html#putExternalcontactsContactNote) | **PUT** /api/v2/externalcontacts/contacts/{contactId}/notes/{noteId} | Update a note for an external contact
[**putExternalcontactsConversation**](ExternalContactsApi.html#putExternalcontactsConversation) | **PUT** /api/v2/externalcontacts/conversations/{conversationId} | Associate an external contact with a conversation
[**putExternalcontactsOrganization**](ExternalContactsApi.html#putExternalcontactsOrganization) | **PUT** /api/v2/externalcontacts/organizations/{externalOrganizationId} | Update an external organization
[**putExternalcontactsOrganizationNote**](ExternalContactsApi.html#putExternalcontactsOrganizationNote) | **PUT** /api/v2/externalcontacts/organizations/{externalOrganizationId}/notes/{noteId} | Update a note for an external organization
[**putExternalcontactsOrganizationTrustorTrustorId**](ExternalContactsApi.html#putExternalcontactsOrganizationTrustorTrustorId) | **PUT** /api/v2/externalcontacts/organizations/{externalOrganizationId}/trustor/{trustorId} | Links a Trustor with an Extenral Organization
[**putExternalcontactsRelationship**](ExternalContactsApi.html#putExternalcontactsRelationship) | **PUT** /api/v2/externalcontacts/relationships/{relationshipId} | Update a relationship
{: class="table table-striped"}

<a name="deleteExternalcontactsContact"></a>

# null deleteExternalcontactsContact(contactId)

DELETE /api/v2/externalcontacts/contacts/{contactId}

Delete an external contact



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var contactId = "contactId_example"; // String | ExternalContact ID

apiInstance.deleteExternalcontactsContact(contactId)
  .then(function() {
    console.log('deleteExternalcontactsContact returned successfully.');
  })
  .catch(function(error) {
  	console.log('There was a failure calling deleteExternalcontactsContact');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **contactId** | **String**| ExternalContact ID |  |
{: class="table table-striped"}

### Return type

null (empty response body)

<a name="deleteExternalcontactsContactNote"></a>

# null deleteExternalcontactsContactNote(contactId, noteId)

DELETE /api/v2/externalcontacts/contacts/{contactId}/notes/{noteId}

Delete a note for an external contact



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var contactId = "contactId_example"; // String | ExternalContact Id

var noteId = "noteId_example"; // String | Note Id

apiInstance.deleteExternalcontactsContactNote(contactId, noteId)
  .then(function() {
    console.log('deleteExternalcontactsContactNote returned successfully.');
  })
  .catch(function(error) {
  	console.log('There was a failure calling deleteExternalcontactsContactNote');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **contactId** | **String**| ExternalContact Id |  |
 **noteId** | **String**| Note Id |  |
{: class="table table-striped"}

### Return type

null (empty response body)

<a name="deleteExternalcontactsOrganization"></a>

# null deleteExternalcontactsOrganization(externalOrganizationId)

DELETE /api/v2/externalcontacts/organizations/{externalOrganizationId}

Delete an external organization



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var externalOrganizationId = "externalOrganizationId_example"; // String | External Organization ID

apiInstance.deleteExternalcontactsOrganization(externalOrganizationId)
  .then(function() {
    console.log('deleteExternalcontactsOrganization returned successfully.');
  })
  .catch(function(error) {
  	console.log('There was a failure calling deleteExternalcontactsOrganization');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **externalOrganizationId** | **String**| External Organization ID |  |
{: class="table table-striped"}

### Return type

null (empty response body)

<a name="deleteExternalcontactsOrganizationNote"></a>

# null deleteExternalcontactsOrganizationNote(externalOrganizationId, noteId)

DELETE /api/v2/externalcontacts/organizations/{externalOrganizationId}/notes/{noteId}

Delete a note for an external organization



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var externalOrganizationId = "externalOrganizationId_example"; // String | External Organization Id

var noteId = "noteId_example"; // String | Note Id

apiInstance.deleteExternalcontactsOrganizationNote(externalOrganizationId, noteId)
  .then(function() {
    console.log('deleteExternalcontactsOrganizationNote returned successfully.');
  })
  .catch(function(error) {
  	console.log('There was a failure calling deleteExternalcontactsOrganizationNote');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **externalOrganizationId** | **String**| External Organization Id |  |
 **noteId** | **String**| Note Id |  |
{: class="table table-striped"}

### Return type

null (empty response body)

<a name="deleteExternalcontactsOrganizationTrustor"></a>

# null deleteExternalcontactsOrganizationTrustor(externalOrganizationId)

DELETE /api/v2/externalcontacts/organizations/{externalOrganizationId}/trustor

Unlink the Trustor for this External Organization



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var externalOrganizationId = "externalOrganizationId_example"; // String | External Organization ID

apiInstance.deleteExternalcontactsOrganizationTrustor(externalOrganizationId)
  .then(function() {
    console.log('deleteExternalcontactsOrganizationTrustor returned successfully.');
  })
  .catch(function(error) {
  	console.log('There was a failure calling deleteExternalcontactsOrganizationTrustor');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **externalOrganizationId** | **String**| External Organization ID |  |
{: class="table table-striped"}

### Return type

null (empty response body)

<a name="deleteExternalcontactsRelationship"></a>

# null deleteExternalcontactsRelationship(relationshipId)

DELETE /api/v2/externalcontacts/relationships/{relationshipId}

Delete a relationship



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var relationshipId = "relationshipId_example"; // String | Relationship Id

apiInstance.deleteExternalcontactsRelationship(relationshipId)
  .then(function() {
    console.log('deleteExternalcontactsRelationship returned successfully.');
  })
  .catch(function(error) {
  	console.log('There was a failure calling deleteExternalcontactsRelationship');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **relationshipId** | **String**| Relationship Id |  |
{: class="table table-striped"}

### Return type

null (empty response body)

<a name="getExternalcontactsContact"></a>

# [**ExternalContact**](ExternalContact.html) getExternalcontactsContact(contactId, opts)

GET /api/v2/externalcontacts/contacts/{contactId}

Fetch an external contact



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var contactId = "contactId_example"; // String | ExternalContact ID

var opts = { 
  'expand': ["expand_example"] // [String] | which fields, if any, to expand (externalOrganization,externalDataSources)
};
apiInstance.getExternalcontactsContact(contactId, opts)
  .then(function(data) {
    console.log(`getExternalcontactsContact success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling getExternalcontactsContact');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **contactId** | **String**| ExternalContact ID |  |
 **expand** | [**[String]**](String.html)| which fields, if any, to expand (externalOrganization,externalDataSources) | [optional] <br />**Values**: externalOrganization, externalDataSources |
{: class="table table-striped"}

### Return type

[**ExternalContact**](ExternalContact.html)

<a name="getExternalcontactsContactNote"></a>

# [**Note**](Note.html) getExternalcontactsContactNote(contactId, noteId, opts)

GET /api/v2/externalcontacts/contacts/{contactId}/notes/{noteId}

Fetch a note for an external contact



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var contactId = "contactId_example"; // String | ExternalContact Id

var noteId = "noteId_example"; // String | Note Id

var opts = { 
  'expand': ["expand_example"] // [String] | which fields, if any, to expand
};
apiInstance.getExternalcontactsContactNote(contactId, noteId, opts)
  .then(function(data) {
    console.log(`getExternalcontactsContactNote success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling getExternalcontactsContactNote');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **contactId** | **String**| ExternalContact Id |  |
 **noteId** | **String**| Note Id |  |
 **expand** | [**[String]**](String.html)| which fields, if any, to expand | [optional] <br />**Values**: author, externalDataSources |
{: class="table table-striped"}

### Return type

[**Note**](Note.html)

<a name="getExternalcontactsContactNotes"></a>

# [**NoteListing**](NoteListing.html) getExternalcontactsContactNotes(contactId, opts)

GET /api/v2/externalcontacts/contacts/{contactId}/notes

List notes for an external contact



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var contactId = "contactId_example"; // String | ExternalContact Id

var opts = { 
  'pageSize': 20, // Number | Page size
  'pageNumber': 1, // Number | Page number
  'sortOrder': "sortOrder_example", // String | Sort order
  'expand': ["expand_example"] // [String] | which fields, if any, to expand
};
apiInstance.getExternalcontactsContactNotes(contactId, opts)
  .then(function(data) {
    console.log(`getExternalcontactsContactNotes success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling getExternalcontactsContactNotes');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **contactId** | **String**| ExternalContact Id |  |
 **pageSize** | **Number**| Page size | [optional] [default to 20] |
 **pageNumber** | **Number**| Page number | [optional] [default to 1] |
 **sortOrder** | **String**| Sort order | [optional]  |
 **expand** | [**[String]**](String.html)| which fields, if any, to expand | [optional] <br />**Values**: author, externalDataSources |
{: class="table table-striped"}

### Return type

[**NoteListing**](NoteListing.html)

<a name="getExternalcontactsContacts"></a>

# [**ContactListing**](ContactListing.html) getExternalcontactsContacts(opts)

GET /api/v2/externalcontacts/contacts

Search for external contacts



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var opts = { 
  'pageSize': 20, // Number | Page size
  'pageNumber': 1, // Number | Page number
  'q': "q_example", // String | User supplied search keywords (no special syntax is currently supported)
  'sortOrder': "sortOrder_example", // String | Sort order
  'expand': ["expand_example"] // [String] | which fields, if any, to expand
};
apiInstance.getExternalcontactsContacts(opts)
  .then(function(data) {
    console.log(`getExternalcontactsContacts success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling getExternalcontactsContacts');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **pageSize** | **Number**| Page size | [optional] [default to 20] |
 **pageNumber** | **Number**| Page number | [optional] [default to 1] |
 **q** | **String**| User supplied search keywords (no special syntax is currently supported) | [optional]  |
 **sortOrder** | **String**| Sort order | [optional]  |
 **expand** | [**[String]**](String.html)| which fields, if any, to expand | [optional] <br />**Values**: externalOrganization, externalDataSources |
{: class="table table-striped"}

### Return type

[**ContactListing**](ContactListing.html)

<a name="getExternalcontactsOrganization"></a>

# [**ExternalOrganization**](ExternalOrganization.html) getExternalcontactsOrganization(externalOrganizationId, opts)

GET /api/v2/externalcontacts/organizations/{externalOrganizationId}

Fetch an external organization



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var externalOrganizationId = "externalOrganizationId_example"; // String | External Organization ID

var opts = { 
  'expand': "expand_example", // String | which fields, if any, to expand (externalDataSources)
  'includeTrustors': true // Boolean | (true or false) whether or not to include trustor information embedded in the externalOrganization
};
apiInstance.getExternalcontactsOrganization(externalOrganizationId, opts)
  .then(function(data) {
    console.log(`getExternalcontactsOrganization success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling getExternalcontactsOrganization');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **externalOrganizationId** | **String**| External Organization ID |  |
 **expand** | **String**| which fields, if any, to expand (externalDataSources) | [optional] <br />**Values**: externalDataSources |
 **includeTrustors** | **Boolean**| (true or false) whether or not to include trustor information embedded in the externalOrganization | [optional]  |
{: class="table table-striped"}

### Return type

[**ExternalOrganization**](ExternalOrganization.html)

<a name="getExternalcontactsOrganizationContacts"></a>

# [**ContactListing**](ContactListing.html) getExternalcontactsOrganizationContacts(externalOrganizationId, opts)

GET /api/v2/externalcontacts/organizations/{externalOrganizationId}/contacts

Search for external contacts in an external organization



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var externalOrganizationId = "externalOrganizationId_example"; // String | External Organization ID

var opts = { 
  'pageSize': 20, // Number | Page size
  'pageNumber': 1, // Number | Page number
  'q': "q_example", // String | User supplied search keywords (no special syntax is currently supported)
  'sortOrder': "sortOrder_example", // String | Sort order
  'expand': ["expand_example"] // [String] | which fields, if any, to expand (externalOrganization)
};
apiInstance.getExternalcontactsOrganizationContacts(externalOrganizationId, opts)
  .then(function(data) {
    console.log(`getExternalcontactsOrganizationContacts success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling getExternalcontactsOrganizationContacts');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **externalOrganizationId** | **String**| External Organization ID |  |
 **pageSize** | **Number**| Page size | [optional] [default to 20] |
 **pageNumber** | **Number**| Page number | [optional] [default to 1] |
 **q** | **String**| User supplied search keywords (no special syntax is currently supported) | [optional]  |
 **sortOrder** | **String**| Sort order | [optional]  |
 **expand** | [**[String]**](String.html)| which fields, if any, to expand (externalOrganization) | [optional] <br />**Values**: externalOrganization |
{: class="table table-striped"}

### Return type

[**ContactListing**](ContactListing.html)

<a name="getExternalcontactsOrganizationNote"></a>

# [**Note**](Note.html) getExternalcontactsOrganizationNote(externalOrganizationId, noteId, opts)

GET /api/v2/externalcontacts/organizations/{externalOrganizationId}/notes/{noteId}

Fetch a note for an external organization



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var externalOrganizationId = "externalOrganizationId_example"; // String | External Organization Id

var noteId = "noteId_example"; // String | Note Id

var opts = { 
  'expand': ["expand_example"] // [String] | which fields, if any, to expand
};
apiInstance.getExternalcontactsOrganizationNote(externalOrganizationId, noteId, opts)
  .then(function(data) {
    console.log(`getExternalcontactsOrganizationNote success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling getExternalcontactsOrganizationNote');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **externalOrganizationId** | **String**| External Organization Id |  |
 **noteId** | **String**| Note Id |  |
 **expand** | [**[String]**](String.html)| which fields, if any, to expand | [optional] <br />**Values**: author, externalDataSources |
{: class="table table-striped"}

### Return type

[**Note**](Note.html)

<a name="getExternalcontactsOrganizationNotes"></a>

# [**NoteListing**](NoteListing.html) getExternalcontactsOrganizationNotes(externalOrganizationId, opts)

GET /api/v2/externalcontacts/organizations/{externalOrganizationId}/notes

List notes for an external organization



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var externalOrganizationId = "externalOrganizationId_example"; // String | External Organization Id

var opts = { 
  'pageSize': 20, // Number | Page size
  'pageNumber': 1, // Number | Page number
  'sortOrder': "sortOrder_example", // String | Sort order
  'expand': ["expand_example"] // [String] | which fields, if any, to expand
};
apiInstance.getExternalcontactsOrganizationNotes(externalOrganizationId, opts)
  .then(function(data) {
    console.log(`getExternalcontactsOrganizationNotes success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling getExternalcontactsOrganizationNotes');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **externalOrganizationId** | **String**| External Organization Id |  |
 **pageSize** | **Number**| Page size | [optional] [default to 20] |
 **pageNumber** | **Number**| Page number | [optional] [default to 1] |
 **sortOrder** | **String**| Sort order | [optional]  |
 **expand** | [**[String]**](String.html)| which fields, if any, to expand | [optional] <br />**Values**: author, externalDataSources |
{: class="table table-striped"}

### Return type

[**NoteListing**](NoteListing.html)

<a name="getExternalcontactsOrganizationRelationships"></a>

# [**RelationshipListing**](RelationshipListing.html) getExternalcontactsOrganizationRelationships(externalOrganizationId, opts)

GET /api/v2/externalcontacts/organizations/{externalOrganizationId}/relationships

Fetch a relationship for an external organization



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var externalOrganizationId = "externalOrganizationId_example"; // String | External Organization ID

var opts = { 
  'pageSize': 20, // Number | Page size
  'pageNumber': 1, // Number | Page number
  'expand': "expand_example", // String | which fields, if any, to expand
  'sortOrder': "sortOrder_example" // String | Sort order
};
apiInstance.getExternalcontactsOrganizationRelationships(externalOrganizationId, opts)
  .then(function(data) {
    console.log(`getExternalcontactsOrganizationRelationships success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling getExternalcontactsOrganizationRelationships');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **externalOrganizationId** | **String**| External Organization ID |  |
 **pageSize** | **Number**| Page size | [optional] [default to 20] |
 **pageNumber** | **Number**| Page number | [optional] [default to 1] |
 **expand** | **String**| which fields, if any, to expand | [optional] <br />**Values**: externalDataSources |
 **sortOrder** | **String**| Sort order | [optional]  |
{: class="table table-striped"}

### Return type

[**RelationshipListing**](RelationshipListing.html)

<a name="getExternalcontactsOrganizations"></a>

# [**ExternalOrganizationListing**](ExternalOrganizationListing.html) getExternalcontactsOrganizations(opts)

GET /api/v2/externalcontacts/organizations

Search for external organizations



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var opts = { 
  'pageSize': 20, // Number | Page size
  'pageNumber': 1, // Number | Page number
  'q': "q_example", // String | Search query
  'sortOrder': "sortOrder_example", // String | Sort order
  'expand': ["expand_example"], // [String] | which fields, if any, to expand
  'includeTrustors': true // Boolean | (true or false) whether or not to include trustor information embedded in the externalOrganization
};
apiInstance.getExternalcontactsOrganizations(opts)
  .then(function(data) {
    console.log(`getExternalcontactsOrganizations success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling getExternalcontactsOrganizations');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **pageSize** | **Number**| Page size | [optional] [default to 20] |
 **pageNumber** | **Number**| Page number | [optional] [default to 1] |
 **q** | **String**| Search query | [optional]  |
 **sortOrder** | **String**| Sort order | [optional]  |
 **expand** | [**[String]**](String.html)| which fields, if any, to expand | [optional] <br />**Values**: externalDataSources |
 **includeTrustors** | **Boolean**| (true or false) whether or not to include trustor information embedded in the externalOrganization | [optional]  |
{: class="table table-striped"}

### Return type

[**ExternalOrganizationListing**](ExternalOrganizationListing.html)

<a name="getExternalcontactsRelationship"></a>

# [**Relationship**](Relationship.html) getExternalcontactsRelationship(relationshipId, opts)

GET /api/v2/externalcontacts/relationships/{relationshipId}

Fetch a relationship



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var relationshipId = "relationshipId_example"; // String | Relationship Id

var opts = { 
  'expand': "expand_example" // String | which fields, if any, to expand
};
apiInstance.getExternalcontactsRelationship(relationshipId, opts)
  .then(function(data) {
    console.log(`getExternalcontactsRelationship success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling getExternalcontactsRelationship');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **relationshipId** | **String**| Relationship Id |  |
 **expand** | **String**| which fields, if any, to expand | [optional] <br />**Values**: externalDataSources |
{: class="table table-striped"}

### Return type

[**Relationship**](Relationship.html)

<a name="getExternalcontactsReversewhitepageslookup"></a>

# [**ReverseWhitepagesLookupResult**](ReverseWhitepagesLookupResult.html) getExternalcontactsReversewhitepageslookup(lookupVal, opts)

GET /api/v2/externalcontacts/reversewhitepageslookup

Lookup contacts and externalOrganizations based on an attribute



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var lookupVal = "lookupVal_example"; // String | User supplied value to lookup contacts/externalOrganizations (supports email addresses, e164 phone numbers, Twitter screen names)

var opts = { 
  'expand': ["expand_example"] // [String] | which field, if any, to expand
};
apiInstance.getExternalcontactsReversewhitepageslookup(lookupVal, opts)
  .then(function(data) {
    console.log(`getExternalcontactsReversewhitepageslookup success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling getExternalcontactsReversewhitepageslookup');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **lookupVal** | **String**| User supplied value to lookup contacts/externalOrganizations (supports email addresses, e164 phone numbers, Twitter screen names) |  |
 **expand** | [**[String]**](String.html)| which field, if any, to expand | [optional] <br />**Values**: contacts.externalOrganization, externalDataSources |
{: class="table table-striped"}

### Return type

[**ReverseWhitepagesLookupResult**](ReverseWhitepagesLookupResult.html)

<a name="postExternalcontactsContactNotes"></a>

# [**Note**](Note.html) postExternalcontactsContactNotes(contactId, opts)

POST /api/v2/externalcontacts/contacts/{contactId}/notes

Create a note for an external contact



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var contactId = "contactId_example"; // String | ExternalContact Id

var opts = { 
  'body': new platformClient.Note() // Note | ExternalContact
};
apiInstance.postExternalcontactsContactNotes(contactId, opts)
  .then(function(data) {
    console.log(`postExternalcontactsContactNotes success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling postExternalcontactsContactNotes');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **contactId** | **String**| ExternalContact Id |  |
 **body** | [**Note**](Note.html)| ExternalContact | [optional]  |
{: class="table table-striped"}

### Return type

[**Note**](Note.html)

<a name="postExternalcontactsContacts"></a>

# [**ExternalContact**](ExternalContact.html) postExternalcontactsContacts(opts)

POST /api/v2/externalcontacts/contacts

Create an external contact



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var opts = { 
  'body': new platformClient.ExternalContact() // ExternalContact | ExternalContact
};
apiInstance.postExternalcontactsContacts(opts)
  .then(function(data) {
    console.log(`postExternalcontactsContacts success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling postExternalcontactsContacts');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | [**ExternalContact**](ExternalContact.html)| ExternalContact | [optional]  |
{: class="table table-striped"}

### Return type

[**ExternalContact**](ExternalContact.html)

<a name="postExternalcontactsOrganizationNotes"></a>

# [**Note**](Note.html) postExternalcontactsOrganizationNotes(externalOrganizationId, opts)

POST /api/v2/externalcontacts/organizations/{externalOrganizationId}/notes

Create a note for an external organization



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var externalOrganizationId = "externalOrganizationId_example"; // String | External Organization Id

var opts = { 
  'body': new platformClient.Note() // Note | ExternalContact
};
apiInstance.postExternalcontactsOrganizationNotes(externalOrganizationId, opts)
  .then(function(data) {
    console.log(`postExternalcontactsOrganizationNotes success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling postExternalcontactsOrganizationNotes');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **externalOrganizationId** | **String**| External Organization Id |  |
 **body** | [**Note**](Note.html)| ExternalContact | [optional]  |
{: class="table table-striped"}

### Return type

[**Note**](Note.html)

<a name="postExternalcontactsOrganizations"></a>

# [**ExternalOrganization**](ExternalOrganization.html) postExternalcontactsOrganizations(opts)

POST /api/v2/externalcontacts/organizations

Create an external organization



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var opts = { 
  'body': new platformClient.ExternalOrganization() // ExternalOrganization | ExternalOrganization
};
apiInstance.postExternalcontactsOrganizations(opts)
  .then(function(data) {
    console.log(`postExternalcontactsOrganizations success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling postExternalcontactsOrganizations');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | [**ExternalOrganization**](ExternalOrganization.html)| ExternalOrganization | [optional]  |
{: class="table table-striped"}

### Return type

[**ExternalOrganization**](ExternalOrganization.html)

<a name="postExternalcontactsRelationships"></a>

# [**Relationship**](Relationship.html) postExternalcontactsRelationships(opts)

POST /api/v2/externalcontacts/relationships

Create a relationship



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var opts = { 
  'body': new platformClient.Relationship() // Relationship | Relationship
};
apiInstance.postExternalcontactsRelationships(opts)
  .then(function(data) {
    console.log(`postExternalcontactsRelationships success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling postExternalcontactsRelationships');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | [**Relationship**](Relationship.html)| Relationship | [optional]  |
{: class="table table-striped"}

### Return type

[**Relationship**](Relationship.html)

<a name="putExternalcontactsContact"></a>

# [**ExternalContact**](ExternalContact.html) putExternalcontactsContact(contactId, opts)

PUT /api/v2/externalcontacts/contacts/{contactId}

Update an external contact



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var contactId = "contactId_example"; // String | ExternalContact ID

var opts = { 
  'body': new platformClient.ExternalContact() // ExternalContact | ExternalContact
};
apiInstance.putExternalcontactsContact(contactId, opts)
  .then(function(data) {
    console.log(`putExternalcontactsContact success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling putExternalcontactsContact');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **contactId** | **String**| ExternalContact ID |  |
 **body** | [**ExternalContact**](ExternalContact.html)| ExternalContact | [optional]  |
{: class="table table-striped"}

### Return type

[**ExternalContact**](ExternalContact.html)

<a name="putExternalcontactsContactNote"></a>

# [**Note**](Note.html) putExternalcontactsContactNote(contactId, noteId, opts)

PUT /api/v2/externalcontacts/contacts/{contactId}/notes/{noteId}

Update a note for an external contact



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var contactId = "contactId_example"; // String | ExternalContact Id

var noteId = "noteId_example"; // String | Note Id

var opts = { 
  'body': new platformClient.Note() // Note | Note
};
apiInstance.putExternalcontactsContactNote(contactId, noteId, opts)
  .then(function(data) {
    console.log(`putExternalcontactsContactNote success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling putExternalcontactsContactNote');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **contactId** | **String**| ExternalContact Id |  |
 **noteId** | **String**| Note Id |  |
 **body** | [**Note**](Note.html)| Note | [optional]  |
{: class="table table-striped"}

### Return type

[**Note**](Note.html)

<a name="putExternalcontactsConversation"></a>

# null putExternalcontactsConversation(conversationId, opts)

PUT /api/v2/externalcontacts/conversations/{conversationId}

Associate an external contact with a conversation



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var conversationId = "conversationId_example"; // String | Conversation ID

var opts = { 
  'body': new platformClient.ConversationAssociation() // ConversationAssociation | ConversationAssociation
};
apiInstance.putExternalcontactsConversation(conversationId, opts)
  .then(function() {
    console.log('putExternalcontactsConversation returned successfully.');
  })
  .catch(function(error) {
  	console.log('There was a failure calling putExternalcontactsConversation');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String**| Conversation ID |  |
 **body** | [**ConversationAssociation**](ConversationAssociation.html)| ConversationAssociation | [optional]  |
{: class="table table-striped"}

### Return type

null (empty response body)

<a name="putExternalcontactsOrganization"></a>

# [**ExternalOrganization**](ExternalOrganization.html) putExternalcontactsOrganization(externalOrganizationId, opts)

PUT /api/v2/externalcontacts/organizations/{externalOrganizationId}

Update an external organization



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var externalOrganizationId = "externalOrganizationId_example"; // String | External Organization ID

var opts = { 
  'body': new platformClient.ExternalOrganization() // ExternalOrganization | ExternalOrganization
};
apiInstance.putExternalcontactsOrganization(externalOrganizationId, opts)
  .then(function(data) {
    console.log(`putExternalcontactsOrganization success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling putExternalcontactsOrganization');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **externalOrganizationId** | **String**| External Organization ID |  |
 **body** | [**ExternalOrganization**](ExternalOrganization.html)| ExternalOrganization | [optional]  |
{: class="table table-striped"}

### Return type

[**ExternalOrganization**](ExternalOrganization.html)

<a name="putExternalcontactsOrganizationNote"></a>

# [**Note**](Note.html) putExternalcontactsOrganizationNote(externalOrganizationId, noteId, opts)

PUT /api/v2/externalcontacts/organizations/{externalOrganizationId}/notes/{noteId}

Update a note for an external organization



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var externalOrganizationId = "externalOrganizationId_example"; // String | External Organization Id

var noteId = "noteId_example"; // String | Note Id

var opts = { 
  'body': new platformClient.Note() // Note | Note
};
apiInstance.putExternalcontactsOrganizationNote(externalOrganizationId, noteId, opts)
  .then(function(data) {
    console.log(`putExternalcontactsOrganizationNote success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling putExternalcontactsOrganizationNote');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **externalOrganizationId** | **String**| External Organization Id |  |
 **noteId** | **String**| Note Id |  |
 **body** | [**Note**](Note.html)| Note | [optional]  |
{: class="table table-striped"}

### Return type

[**Note**](Note.html)

<a name="putExternalcontactsOrganizationTrustorTrustorId"></a>

# [**ExternalOrganization**](ExternalOrganization.html) putExternalcontactsOrganizationTrustorTrustorId(externalOrganizationId, trustorId)

PUT /api/v2/externalcontacts/organizations/{externalOrganizationId}/trustor/{trustorId}

Links a Trustor with an Extenral Organization



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var externalOrganizationId = "externalOrganizationId_example"; // String | External Organization ID

var trustorId = "trustorId_example"; // String | Trustor ID

apiInstance.putExternalcontactsOrganizationTrustorTrustorId(externalOrganizationId, trustorId)
  .then(function(data) {
    console.log(`putExternalcontactsOrganizationTrustorTrustorId success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling putExternalcontactsOrganizationTrustorTrustorId');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **externalOrganizationId** | **String**| External Organization ID |  |
 **trustorId** | **String**| Trustor ID |  |
{: class="table table-striped"}

### Return type

[**ExternalOrganization**](ExternalOrganization.html)

<a name="putExternalcontactsRelationship"></a>

# [**Relationship**](Relationship.html) putExternalcontactsRelationship(relationshipId, opts)

PUT /api/v2/externalcontacts/relationships/{relationshipId}

Update a relationship



### Example

~~~ javascript
var platformClient = require('purecloud-platform-client-v2');

// Configure OAuth2 access token for authorization: PureCloud Auth
platformClient.ApiClient.instance.authentications['PureCloud Auth'].accessToken = 'YOUR ACCESS TOKEN';

var apiInstance = new platformClient.ExternalContactsApi();

var relationshipId = "relationshipId_example"; // String | Relationship Id

var opts = { 
  'body': new platformClient.Relationship() // Relationship | Relationship
};
apiInstance.putExternalcontactsRelationship(relationshipId, opts)
  .then(function(data) {
    console.log(`putExternalcontactsRelationship success! data: ${data}`);
  })
  .catch(function(error) {
  	console.log('There was a failure calling putExternalcontactsRelationship');
    console.error(error);
  });

~~~

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **relationshipId** | **String**| Relationship Id |  |
 **body** | [**Relationship**](Relationship.html)| Relationship | [optional]  |
{: class="table table-striped"}

### Return type

[**Relationship**](Relationship.html)
