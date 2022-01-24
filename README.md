# **Installation**

npm i cashfree-dropjs

Note: add --save if you are using npm < 5.0.0

# Documentation

Drop is our pre-built UI solution for accepting payments. Drop works by displaying payment components we call as drops at any place you want in your page. It can either display all the payment components at one place or different places depending on your need. Read more on:
[https://docs.cashfree.com/docs/javascript-integration]

## Basic Implementation:
```
import { cashfreeProd, cashfreeSandbox } from 'cashfree-dropjs';

let testCashfree = new cashfreeSandbox.Cashfree();
let prodCashfree = new cashfreeProd.Cashfree();

testCashfree.initialiseDropin(element, {
    orderToken,
    onSuccess: function,
    onFailure: function,
    components,
    style,
});
```

