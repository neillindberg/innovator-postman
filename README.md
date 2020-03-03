# Introduction 
Here lies within a collection of Post Man that introduces:
1) Obtaining the endpoint to get a token from.
2) Use of the token endpoint to populate environmental variable 'access_token'.
3) RestAPI usage for _ItemType_ *User*, using Bearer Token to:
    - Add
    - Edit
    - Get
    - Delete

# Getting Started
There are two collection variables: base_url and version.
This was created to be flexible so that these procedures could be used in the confines of a local system as well as supporting the ability to interact with remote servers. Below are the defaults, but they may be edited once, at the top level of the collection:

*base_url* http://localhost/InnovatorServer

*version* 12

Sample usage:
`{{base_url}}{{version}}{{discovery_url}}`

...which results in:
http://localhost/InnovatorServer12/Server/OAuthServerDiscovery.aspx

Simply set version to an empty value if it is unwanted, and change base (to point to whatever server you wish).