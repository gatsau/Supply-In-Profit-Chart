# BTC Supply in Profit/Loss Chart

Interactive chart visualizing Bitcoin's price alongside the percentage of supply currently in profit or loss.

![Chart Preview](https://img.shields.io/badge/Live-Chart-blue)

## Features

- **Real On-Chain Data**: Supply metrics sourced from [CheckOnChain](https://charts.checkonchain.com) (Jan 2013 - present)
- **Historical Price Data**: From [CryptoCompare](https://cryptocompare.com) (2009 - present)
- **Logarithmic Price Scale**: $0.01 to $200k
- **Dual Y-Axis**: Price (left) and % of supply (right)
- **Time Range Filters**: 1Y, 3Y, 5Y, ALL
- **Interactive Tooltips**: Hover for detailed values
- **Market Cycle Indicators**: Shows current phase based on supply metrics

## How It Works

- **Green Line (Supply in Profit)**: Percentage of BTC supply that was last moved at a price lower than current
- **Red Line (Supply in Loss)**: Percentage of BTC supply that was last moved at a price higher than current
- When both lines meet at 50%, exactly half the supply is in profit and half is in loss

## Data Sources

| Metric | Source | Coverage |
|--------|--------|----------|
| BTC Price | CryptoCompare | 2009 - Present |
| Supply in Profit/Loss | CheckOnChain | Jan 2013 - Present |

## Usage

Simply open `index.html` in a browser, or serve locally:

```bash
python3 -m http.server 8080
# Visit http://localhost:8080
```

## Live Demo

Visit: [https://gatsau.github.io/Supply-In-Profit-Chart/](https://gatsau.github.io/Supply-In-Profit-Chart/)

## License

MIT
