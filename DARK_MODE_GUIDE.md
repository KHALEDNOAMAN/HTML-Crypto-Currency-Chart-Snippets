# Dark Mode for Crypto Charts

## Quick Implementation
Add this CSS to enable dark mode:

```css
@media (prefers-color-scheme: dark) {
    body { background: #1a1a2e; color: #e0e0e0; }
    .chart-container { background: #16213e; border: 1px solid #0f3460; }
}
```

## TradingView Dark Theme
```javascript
new TradingView.widget({
    theme: "dark",
    backgroundColor: "#1a1a2e",
    gridColor: "#0f3460",
    // ... rest of config
});
```

## Popular Crypto Color Schemes
| Coin | Brand Color | Dark BG Accent |
|------|-------------|----------------|
| BTC | #f7931a | #2d1f00 |
| ETH | #627eea | #1a1f3a |
| SOL | #9945ff | #1f0a3a |
| BNB | #f0b90b | #2d2500 |
