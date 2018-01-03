# How to reproduce the problem

Start parcel on a terminal session:

```bash
parcel index.html
```

You will already see the problem when bundling. To avoid the error leave the content of `renderer.js` commented out. Now it should work just fine.

Start the electron app in another session:

```bash
npm start
```
