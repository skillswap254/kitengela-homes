# 🏠 Kitengela Homes

> **Find your next home in Kitengela, Kenya** - Community-powered rental listings by renters, for renters.

[![Live Demo](https://img.shields.io/badge/demo-live-green.svg)](https://kitengela-homes.vercel.app)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.3-blue.svg)](https://reactjs.org/)
[![Supabase](https://img.shields.io/badge/Supabase-Latest-green.svg)](https://supabase.com/)

---

## 🌟 Why Kitengela Homes?

Traditional rental platforms prioritize landlords and agents. **We prioritize renters.**

- ✅ **Authentic Listings**: Only verified tenants can post, ensuring real experiences
- ✅ **Transparent Costs**: See all fees upfront - rent, deposit, water, electricity, garbage
- ✅ **Community Verified**: Peer reviews from actual residents
- ✅ **Mobile-First**: Optimized for 3G speeds and small screens
- ✅ **No Hidden Fees**: 100% free for renters and landlords

---

## 🚀 Features

### Current (MVP 2026)
- 🔍 Browse rental listings without signup
- 📱 Mobile-responsive design with bottom navigation
- 🔐 Secure authentication (email/password + magic links)
- 📝 Post listings with multiple images
- 🏷️ Advanced filters (price, location, amenities)
- 💬 Direct contact via WhatsApp/Phone
- 🎨 Modern UI with Kenya-inspired color palette

### Coming Soon
- ⭐ Ratings & reviews system
- ✅ Landlord verification dashboard
- 🗺️ Interactive map view
- 📊 Price trends & analytics
- 🔔 Save favorites & get notifications
- 🌍 Multi-language support (English + Swahili)

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | React 18 + TypeScript + Vite |
| **Styling** | Tailwind CSS |
| **Backend** | Supabase (PostgreSQL + Auth + Storage) |
| **Deployment** | Vercel |
| **Testing** | Vitest + Playwright |
| **CI/CD** | GitHub Actions |
| **Security** | Snyk + Semgrep |

---

## 📦 Project Structure

kitengela-homes/
├── src/
│   ├── components/     # Reusable UI components
│   ├── pages/          # Page components (routes)
│   ├── lib/            # Supabase client & API helpers
│   ├── hooks/          # Custom React hooks
│   ├── types/          # TypeScript definitions
│   └── utils/          # Helper functions
├── tests/              # Unit & E2E tests
├── public/             # Static assets
└── supabase/           # Database migrations & functions

---

## 🚦 Getting Started

### Prerequisites
- Node.js 18+ ([Download](https://nodejs.org/))
- npm or pnpm
- Supabase account ([Sign up free](https://supabase.com/))

### Installation

1. **Clone the repository**
```bash
   git clone https://github.com/YOUR_USERNAME/kitengela-homes.git
   cd kitengela-homes
```

2. **Install dependencies**
```bash
   npm install
```

3. **Set up environment variables**
```bash
   cp .env.example .env
```
   Then edit `.env` and add your Supabase credentials:
```env
   VITE_SUPABASE_URL=your_supabase_project_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

4. **Run database migrations**
```bash
   npx supabase login
   npx supabase link --project-ref your_project_ref
   npx supabase db push
```

5. **Start development server**
```bash
   npm run dev
```

6. **Open your browser**

http://localhost:5173

---

## 🧪 Testing
```bash
# Run unit tests
npm run test

# Run E2E tests
npm run test:e2e

# Run security scans
npm run security:check
```

---

## 🚀 Deployment

The app auto-deploys to Vercel on every push to `main` branch.

**Manual deployment:**
```bash
npm run build
vercel --prod
```

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add amazing feature'`)
4. **Push to branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request**

### Contribution Guidelines
- Follow the existing code style (ESLint + Prettier)
- Write tests for new features
- Update documentation as needed
- Keep commits atomic and well-described

---

## 📊 Roadmap

### Phase 1: MVP ✅ (2026)
- [x] User authentication
- [x] Browse & search listings
- [x] Post listings with images
- [x] Mobile-responsive design
- [x] Deploy to production

### Phase 2: Verification (2026)
- [ ] Tenant verification badges
- [ ] Landlord verification workflow
- [ ] Automated moderation queue
- [ ] Email notifications

### Phase 3: Community (2026)
- [ ] Ratings & reviews
- [ ] Q&A on listings
- [ ] Neighborhood guides
- [ ] User reputation system

### Phase 4: Monetization (2026)
- [ ] Featured listings
- [ ] Premium accounts
- [ ] Ad placements

---

## 📸 Screenshots

### Home Page
![Home Page](./docs/screenshots/home.png)

### Listing Detail
![Listing Detail](./docs/screenshots/listing-detail.png)

### Post Listing
![Post Listing](./docs/screenshots/post-listing.png)

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👥 Team

**Creator & Lead Developer**
- Skill Swap 254 (https://github.com/skillswap254)

**Contributors**
- See [CONTRIBUTORS.md](CONTRIBUTORS.md)

---

## 💬 Support

- 📧 Email: skillswap254@proton.me
- 💬 WhatsApp: +254 XXX XXX XXX
- 🐛 Issues: [GitHub Issues](https://github.com/skillswap254/kitengela-homes/issues)
- 💡 Feature Requests: [Discussions](https://github.com/skillswap254/kitengela-homes/discussions)

---

## 🙏 Acknowledgments

- Inspired by the need for transparent, renter-friendly housing platforms in Kenya
- Built with amazing open-source tools (React, Supabase, Tailwind)
- Special thanks to the Kitengela community for testing and feedback

---

## 📈 Stats

![GitHub stars](https://img.shields.io/github/stars/skillswap254/kitengela-homes?style=social)
![GitHub forks](https://img.shields.io/github/forks/skillswap254/kitengela-homes?style=social)
![GitHub issues](https://img.shields.io/github/issues/skillswap254/kitengela-homes)

---

**Made with ❤️ in Kitengela, Kenya**
