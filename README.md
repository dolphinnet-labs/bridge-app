# 🌊 AquaLink Bridge

<div align="center">

**The Ocean of Interoperability**

A modern, user-friendly cross-chain bridge interface built with Vue 3, enabling seamless asset transfers across multiple blockchain networks.

[![Vue](https://img.shields.io/badge/Vue-3.4+-4FC08D?style=flat-square&logo=vue.js&logoColor=white)](https://vuejs.org/)
[![Vite](https://img.shields.io/badge/Vite-5.2+-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Wagmi](https://img.shields.io/badge/Wagmi-Latest-FF6B6B?style=flat-square)](https://wagmi.sh/)
[![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)

</div>

---

## ✨ Features

- 🌐 **Multi-Chain Support** - Seamlessly bridge assets across AquaLink, Sepolia, Optimism, and more
- 💰 **Multi-Token Support** - Transfer ETH, USDT, AQUA, and other ERC-20 tokens
- 🎨 **Modern UI/UX** - Beautiful, responsive design with glassmorphism effects
- 🌍 **Internationalization** - Full support for English and Chinese (Simplified)
- 🔒 **Secure** - Built with industry-standard Web3 libraries (Wagmi, Ethers.js)
- 📱 **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- ⚡ **Real-time Updates** - WebSocket integration for instant transaction status updates
- 📊 **Transaction History** - Complete record of all bridge transactions

## 🚀 Quick Start

### Prerequisites

- Node.js >= 18.0.0
- npm, yarn, or pnpm

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/aqua-link.git

# Navigate to the project directory
cd aqua-link

# Install dependencies
npm install
# or
yarn install
# or
pnpm install
```

### Development

```bash
# Start the development server
npm run dev

# The application will be available at http://localhost:3000
```

### Build

```bash
# Build for production
npm run build

# Preview the production build
npm run preview
```

## 🛠️ Tech Stack

### Core Technologies
- **Vue 3** - Progressive JavaScript framework
- **Vite** - Next-generation frontend build tool
- **TypeScript** - Type-safe JavaScript

### Web3 & Blockchain
- **Wagmi** - React Hooks for Ethereum
- **Ethers.js** - Ethereum JavaScript library
- **Viem** - TypeScript Ethereum library

### UI & Styling
- **Element Plus** - Vue 3 component library
- **SCSS** - CSS preprocessor
- **Animate.css** - CSS animation library

### State Management & Routing
- **Pinia** - Vue state management
- **Vue Router** - Official router for Vue.js
- **Vue I18n** - Internationalization plugin

### Utilities
- **Axios** - HTTP client
- **BigNumber.js** - Arbitrary precision arithmetic
- **WebSocket** - Real-time communication

## 📁 Project Structure

```
aqua-link/
├── src/
│   ├── api/              # API service layer
│   │   ├── bridgePrice.js
│   │   ├── records.js
│   │   └── getGasFee.js
│   ├── assets/           # Static assets
│   │   ├── abi/          # Smart contract ABIs
│   │   ├── images/       # Images and icons
│   │   ├── json/         # Configuration files
│   │   └── ...
│   ├── components/       # Vue components
│   │   ├── navBar.vue
│   │   └── popup.vue
│   ├── languages/        # i18n translations
│   │   └── locales/
│   ├── router/           # Vue Router configuration
│   ├── stores/           # Pinia stores
│   ├── styles/           # Global styles and themes
│   ├── utils/            # Utility functions
│   ├── views/            # Page components
│   │   └── bridge/       # Bridge interface
│   ├── wagmi.ts          # Wagmi configuration
│   └── main.ts           # Application entry point
├── public/               # Public assets
├── index.html            # HTML template
├── vite.config.ts        # Vite configuration
├── package.json          # Dependencies
└── README.md             # This file
```

## ⚙️ Configuration

### Supported Networks

The bridge currently supports the following networks:

- **AquaLink Testnet** (Chain ID: 86606)
- **Sepolia Testnet** (Chain ID: 11155111)
- **Optimism** (Chain ID: 10)

### Supported Tokens

- **ETH** - Ethereum
- **USDT** - Tether USD
- **AQUA** - AquaLink native token

Network and token configurations can be modified in:
- `src/assets/json/networks.json`
- `src/assets/json/copy.json`

### Environment Variables

Create a `.env` file in the root directory:

```env
VITE_API_BASE_URL=https://bridge-api-testnet.aqualink.com/api
VITE_WS_URL=wss://bridge-indexer-ws-testnet.aqualink.com/ws
```

## 🎨 Design System

The application features a modern design system with:

- **Color Palette**: Ocean-inspired blue gradient theme
- **Typography**: Inter, Playfair Display, and custom fonts
- **Components**: Glassmorphism effects with backdrop blur
- **Animations**: Smooth transitions and micro-interactions

## 📱 Responsive Breakpoints

- **Desktop**: > 1000px
- **Tablet**: 768px - 1000px
- **Mobile**: < 768px

## 🔐 Security

- All transactions require explicit user approval
- Smart contract interactions are audited
- Private keys never leave the user's wallet

## 🌐 Internationalization

The application supports multiple languages:

- English (en-US)
- Chinese Simplified (zh-CN)

To add a new language, create a new locale file in `src/languages/locales/`.

## 📝 Scripts

```bash
# Development
npm run dev          # Start development server

# Build
npm run build        # Build for production

# Code Quality
npm run lint         # Run linter

# Preview
npm run preview      # Preview production build
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- **Website**: [https://aqualink.com](https://aqualink.com)
- **Explorer**: [https://explorer-testnet.aqualink.com](https://explorer-testnet.aqualink.com)
- **Documentation**: [https://docs.aqualink.com](https://docs.aqualink.com)

## 🙏 Acknowledgments

- [Vue.js](https://vuejs.org/) - Progressive JavaScript Framework
- [Wagmi](https://wagmi.sh/) - React Hooks for Ethereum
- [Element Plus](https://element-plus.org/) - Vue 3 Component Library
- [Vite](https://vitejs.dev/) - Next Generation Frontend Tooling

---

<div align="center">

Made with ❤️ by the AquaLink Team

**Building the future of cross-chain interoperability**

</div>
