# credit-site-db

## Install

First you must install all the packages:
```
$ npm run install
```

## Configure

Then you must create `local.json` near `default.json` and set your databases credentials into it. 

Example:
```json
{
  "database": {
    "credit_site": {
      "urn": "postgres://postgres:linux@127.0.0.1:5432/credit_site"
    }
  }
}
```

## Apply

To create new tables you must enter the following command:

```
$ npm run migrate
```

To insert some data into the tables you must enter the following command:

```
$ npm run seed
```
