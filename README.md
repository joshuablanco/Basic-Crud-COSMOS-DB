# Basic-Crud-COSMOS-DB
this is a basic CRUD for documents in AZURE COSMOS DB, you should be able to define your own app config for establishing a connection with your own DB, there is a method that defines a storage proceeding. the app config (xml) you could define it as: &lt;?xml version="1.0" encoding = "utf-8"?> &lt;configuration>     &lt;appSettings>         &lt;add key="accountEndPoint" value = "your uri"/>         &lt;add key ="accountKey" value=" key generated by AZURE" />     &lt;/appSettings>  &lt;/configuration> you could define it as an app setting json... as you want.