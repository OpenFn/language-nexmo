# _⚠️ MOVED TO [OpenFn/adaptors](https://github.com/OpenFn/adaptors)! ⚠️_

**N.B.: New versions are available at:
https://github.com/OpenFn/adaptors/tree/main/packages/nexmo**

# Language Nexmo (Archived)

Language Pack for building expressions and operations to interact with the Nexmo API.

Documentation
-------------
## sendSMS

#### sample configuration
```json
{
  "apiKey": "mYaP1K3y",
  "apiSecret": "supersecret"
}
```

#### sample expression
```js
sendSMS(
  "OpenFn",
  "0123456789",
  "HelloWorld!")
```

Development
-----------

Clone the repo, run `npm install`.

Run tests using `npm run test` or `npm run test:watch`

Build the project using `make`.
