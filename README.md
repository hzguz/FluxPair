# FluxPair

FluxPair is a currency converter application designed with a focus on visual aesthetics and user experience. It allows users to convert between multiple fiat and crypto currencies using real-time exchange rates.

## Features

- Real-Time Conversion: Instant currency conversion using up-to-date exchange rates.
- Multi-Currency Support: Supports a wide range of currencies including BRL, USD, EUR, GBP, BTC, and more.
- Saved Pairs: Users can save frequently used currency pairs for quick access.
- Smart Localization: Automatically detects user location to set the default language (English or Portuguese) and number formatting.
- Interactive UI: Features a split-screen design with dynamic lighting effects and smooth animations.
- Offline Capability: Caches exchange rates for offline usage.

## Tech Stack

- Framework: React 19 (Vite)
- Language: TypeScript
- Styling: Tailwind CSS
- Animation: Framer Motion
- Icons: Lucide React
- State Management: React Context API

## Getting Started

### Prerequisites

- Node.js (Latest LTS version recommended)
- Yarn 1.22.22

### Installation

1. Clone the repository
2. Install dependencies:
   yarn install

### Development

Start the development server:
yarn dev

### Build

Build the application for production:
yarn build

## Project Structure

- /src/components: UI components (CurrencyCard, CurrencySelector, etc.)
- /src/context: Global state management (CurrencyContext, LanguageContext)
- /src/lib: Utility functions and constants
- /public: Static assets

## License

This project is open source and available under the MIT License.
