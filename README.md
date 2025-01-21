# Airbnb Clone

A fully responsive Airbnb clone built with modern web technologies. This project replicates core Airbnb functionalities and UI components using NextJS, TypeScript, and Tailwind CSS.

## 🚀 Features

- Responsive design that works on desktop and mobile
- Property listing and search functionality
- Date range picker for booking
- Interactive map integration
- User authentication
- Booking management system
- Responsive image galleries
- Clean and modern UI matching Airbnb's design aesthetic

## 🛠️ Built With

- [Next.js](https://nextjs.org/) - React framework for production
- [TypeScript](https://www.typescriptlang.org/) - Static type checking
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [React Date Range](https://github.com/hypeserver/react-date-range) - Date picker component
- [MapBox](https://www.mapbox.com/) - Maps and location services

## 📋 Prerequisites

Make sure you have the following installed:
- Node.js (v14 or higher)
- npm or yarn package manager

## 🔧 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/airbnb-clone.git
cd airbnb-clone
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Set up environment variables:
Create a `.env.local` file in the root directory and add your environment variables:
```env
NEXT_PUBLIC_MAPBOX_TOKEN=your_mapbox_token_here
```

4. Run the development server:
```bash
npm run dev
# or
yarn dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## 🚀 Building for Production

1. Create a production build:
```bash
npm run build
# or
yarn build
```

2. Start the production server:
```bash
npm start
# or
yarn start
```

## 🔧 Common Issues and Solutions

### OpenSSL Error on Build
If you encounter an OpenSSL error during build, set the Node options:
```bash
set NODE_OPTIONS=--openssl-legacy-provider  # Windows
export NODE_OPTIONS=--openssl-legacy-provider  # Unix
```

### Outdated Browserslist
If you see a browserslist warning, update the database:
```bash
npx browserslist@latest --update-db
```

## 🎨 Project Structure

```
airbnb-clone/
├── components/        # Reusable UI components
├── pages/            # Next.js pages
├── public/           # Static assets
├── styles/          # Global styles and Tailwind config
├── types/           # TypeScript type definitions
└── utils/           # Helper functions and utilities
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## 👏 Acknowledgments

- Inspired by [Airbnb](https://www.airbnb.com/)
- Original design by Airbnb team
- Built as a learning project to demonstrate modern web development practices

## 🔗 Links (under maintenance)

- [Live Demo](https://your-demo-link.com)
- [Original Repository](https://github.com/edwintantawi/airbnb-web-clone)
- [Portfolio](https://your-portfolio.com)

---
⭐️ Star this repo if you find it helpful!
