<h1>Broker Application </h1>

<h2> Overview </h2>

This application has two templates which are Deemat and ShareRequest.</br>
First template which is the Deemat template is the central party which will issue shares to the user.
Deemat will have different choice and will provide shares to authorizes users. Unauthorized users will not get shares. The broker is the controller of the choice to provide authoziation.</br>
Do not get confused between Deemat and broker. Deemat account is the platform for user and broker interaction. Broker is the service provider. To buy shares the user must have a Deemat account.</br>
ShareRequest is the client side template using which the user will be able to request shares from the broker.</br>
In this application the total number of shares a broker can provide is fixed. Once the shares are sold to one of the user. The number of shares left with the broker to give to other users is updated.
so we cannot ask for any number of shares.</br>

<h2>Building </h2>

To Compile the project :

```
daml build
```






