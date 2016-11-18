# CredSSP
A cookbook to manage CredSSP authentication on Windows Servers

## Recipes

Default.rb does all the work. By default it forces the server role without a delegate computer

## Attributes

* `node[credssp][role]` Specifies whether to enable CredSSP as a client or as a server. Defaults to "Server".
* `node[credssp][delegate]` Specifies servers to which client credentials are delegated. Specify fully qualified domain names. Defaults to empty

## Requirements

1. Windows
