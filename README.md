# 🎬 Livepeer LPT Grant Calculator

A beautiful, responsive calculator designed specifically for Livepeer grant applicants to accurately convert USD amounts to LPT tokens using 60-day average pricing. This tool eliminates the guesswork and volatility concerns when preparing grant proposals.

## ✨ Features

🔥 **60-Day Average Pricing** - Uses historical data to smooth out price volatility  
💰 **Real-Time Price Data** - Fetches live LPT prices from CoinGecko API  
🎨 **Livepeer-Themed Design** - Beautiful gradient UI matching Livepeer's brand colors  
📱 **Responsive Design** - Works perfectly on desktop, tablet, and mobile  
⚡ **Fast & Reliable** - Built with React for optimal performance  
🔍 **Transparent Calculations** - Shows both current price and 60-day average

## 🚀 Live Demo

[**Try the Calculator →**](https://paulieb14.github.io/livepeer-lpt-grant-calculator/)

## 📋 How to Use

1. **Enter Your Grant Amount**: Input the USD amount you need for your grant proposal
2. **View Real-Time Data**: See both current LPT price and 60-day average
3. **Get LPT Amount**: Instantly see how much LPT you need to request
4. **Use in Your Proposal**: Copy the calculated LPT amount to your grant application

## 🎯 Why 60-Day Average?

Grant proposals benefit from using 60-day average pricing because:

- **Reduces Volatility Impact**: Crypto prices can be volatile day-to-day
- **Fair for All Parties**: Protects both applicants and the DAO from price swings
- **Industry Standard**: Many DAOs use historical averages for token grants
- **Transparent Process**: Clear methodology that everyone can verify

## 🛠️ Technical Details

- **Framework**: React 18 with Hooks
- **Styling**: Tailwind CSS with custom gradients
- **API**: CoinGecko API for price data
- **Icons**: Custom SVG icons inspired by Lucide
- **Hosting**: GitHub Pages ready

## 📦 Local Development

```bash
# Clone the repository
git clone https://github.com/PaulieB14/livepeer-lpt-grant-calculator.git

# Navigate to the project
cd livepeer-lpt-grant-calculator

# Open index.html in your browser
# Or serve with a local server:
python -m http.server 8000
# Then visit http://localhost:8000
```

## 🎨 Design Features

- **Gradient Backgrounds**: Beautiful blue-to-green gradients matching Livepeer's brand
- **Glass Morphism**: Modern frosted glass effects with backdrop blur
- **Smooth Animations**: Subtle loading states and hover effects
- **Accessible Colors**: High contrast ratios for readability
- **Mobile-First**: Responsive design that works on all screen sizes

## 📊 API Integration

### Current Price Endpoint
```
GET https://api.coingecko.com/api/v3/simple/price?ids=livepeer&vs_currencies=usd
```

### Historical Data Endpoint
```
GET https://api.coingecko.com/api/v3/coins/livepeer/market_chart?vs_currency=usd&days=60&interval=daily
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

### Ideas for Enhancement
- [ ] Add price chart visualization
- [ ] Export results to PDF
- [ ] Multiple timeframe averages (30d, 90d, 180d)
- [ ] Historical grant data analysis
- [ ] Integration with other price APIs as backup

## 📄 License

MIT License - feel free to use this tool and code for your own projects!

## 🙏 Acknowledgments

- **Livepeer Team** - For building an amazing decentralized video infrastructure
- **CoinGecko** - For providing reliable cryptocurrency price data
- **Livepeer Community** - For inspiring this tool through their grant activities

---

**Built with ❤️ for the Livepeer community**

*Helping grant applicants make accurate proposals since 2025*