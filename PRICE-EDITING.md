# RB Luxury Price Editing

Prices are stored in `prices-data.js` and use USD.

1. Open `prices-data.js` in the GitHub repository.
2. Click the pencil icon to edit the file.
3. Add one line per product using its product code:

```js
window.RB_PRICES = {
  "127299": 499.00,
  "127322": 359.00
};
```

4. Keep commas between entries. The last entry may omit the comma.
5. Click **Commit changes**. GitHub Pages will update automatically.

Products without a price continue to display **Price on request** and cannot start a fixed-amount payment.
