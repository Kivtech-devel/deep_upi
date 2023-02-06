# Deep Linking UPI


```sh
**Uri uri =
    new Uri.Builder()
        .scheme("upi")
        .authority("pay")
        .appendQueryParameter("pa", "your-merchant-vpa@xxx")       // virtual ID 
        .appendQueryParameter("pn", "your-merchant-name")          // name
        .appendQueryParameter("mc", "your-merchant-code")          // optional
        .appendQueryParameter("tr", "your-transaction-ref-id")     // optional
        .appendQueryParameter("tn", "your-transaction-note")       // any note about payment
        .appendQueryParameter("am", "your-order-amount")           // amount
        .appendQueryParameter("cu", "INR")                         // currency
        .appendQueryParameter("url", "your-transaction-url")       // optional
        .build();**

```

