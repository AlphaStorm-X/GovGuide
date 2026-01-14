# GovGuide 
**Simple Steps for Public Services - Premium Edition**

GovGuide is a modern, feature-rich web application designed to simplify government services for Indian citizens. It provides clear, step-by-step guidance, document checklists, fee information, and AI assistance for 10 essential government services.



**Live Demo**: https://govguide-in.netlify.app/

> **Note**: This is a **Simulation Mode** demo. No real data is sent to government portals.

---

## ✨ Features

### 🎨 Premium Design
- **Modern UI**: Beautiful gradient backgrounds, glassmorphism effects, and smooth animations
- **Google Fonts**: Premium Outfit typography for a professional look
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Dark Accents**: Vibrant color palette with purple and blue gradients

### 📋 Comprehensive Services
Browse and learn about **10 government services**:
- 👶 Birth Certificate
- 🚗 Driving License
- 💳 PAN Card
- 💑 Marriage Registration
- 🛂 Passport
- 🗳️ Voter ID Card
- 🌾 Ration Card
- 🆔 Aadhar Update
- 💰 Income Certificate
- 🏠 Property Registration

Each service includes:
- Step-by-step process guide
- Required documents checklist
- Fees and processing time
- Difficulty rating
- Related services

### 🔍 Smart Discovery
- **Category Filters**: Filter by Identity, Transport, Legal, or Welfare
- **Search Functionality**: Quickly find any service
- **Service Icons**: Visual recognition for easy browsing

### 🤖 AI Assistant
- **Context-Aware**: Understands which service you're viewing
- **Quick Suggestions**: Pre-defined questions for instant help
- **Intent Recognition**: Answers questions about documents, fees, time, and steps
- **Beautiful Chat UI**: Modern chat interface with gradient header

### 📊 Live Stats Dashboard
- **Animated Counters**: Numbers count up on page load
- **4 Key Metrics**: Citizens Assisted, Hours Saved, Active Services, Success Rate
- **Bar Chart**: Visual representation of service popularity
- **Real-time Feel**: Simulated live data updates

### ✅ Progress Tracking
- **Step Completion**: Mark steps as done while following the guide
- **Progress Percentage**: See how far you've progressed
- **Document Checklist**: Track which documents you've gathered
- **Visual Feedback**: Steps turn green when completed

---

## 🛠️ Tech Stack

- **Frontend**: React 19 (Vite)
- **UI Framework**: Chakra UI v2
- **Animations**: Framer Motion v6
- **Charts**: Recharts v2
- **Icons**: Lucide React
- **Routing**: React Router DOM v6

---

## 🏃‍♂️ How to Run

### Prerequisites
- Node.js 16+ installed
- npm or yarn package manager

### Installation

1. **Install Dependencies**
   ```bash
   npm install
   ```

2. **Start Development Server**
   ```bash
   npm run dev
   ```

3. **Open in Browser**
   Navigate to `http://localhost:5173` (or the URL shown in terminal)

### Build for Production

```bash
npm run build
```

The optimized build will be in the `dist` folder.

---

## 🎯 How to Use

### Browse Services
1. Visit the homepage
2. Use category filters or search to find a service
3. Click "Start Guide" on any service card

### Follow Step-by-Step Guide
1. Review the service details (time, fees, documents)
2. Check off required documents as you gather them
3. Expand each step in the accordion to see details
4. Mark steps as "Done" to track your progress

### Get AI Help
1. Click the "Ask AI" button (bottom right)
2. Use quick suggestions or type your own question
3. Get instant answers about documents, fees, time, or steps

### View Impact Stats
1. Click "Live Stats" in the navigation
2. See simulated metrics and service popularity
3. Explore the interactive bar chart

---



---

## 🤖 AI Simulation

The app includes a built-in AI handler that simulates intelligent responses:

**Try asking:**
- "What documents do I need?"
- "How much does it cost?"
- "How long does it take?"
- "What are the steps?"
- "Tell me about Passport"

The AI understands context and provides service-specific answers!

---

## 🎨 Design Highlights

### Color Palette
- **Primary**: Purple-Blue Gradient (#667eea → #764ba2)
- **Accent**: Teal-Green Gradient (#43e97b → #38f9d7)
- **Success**: Blue Gradient (#4facfe → #00f2fe)

### Key Features
- Glassmorphism navbar with backdrop blur
- Animated gradient hero section
- Hover lift effects on cards
- Smooth page transitions
- Custom gradient scrollbar
- Responsive mobile menu

---

## 📱 Mobile Support

Fully responsive design with:
- Hamburger menu for mobile navigation
- Touch-friendly buttons and cards
- Optimized layouts for small screens
- Smooth animations on all devices

---

## 🚀 Future Enhancements

Potential additions for production:
- [ ] Real backend API integration
- [ ] User authentication and profiles
- [ ] Application status tracking
- [ ] Document upload functionality
- [ ] Email/SMS notifications
- [ ] Multi-language support
- [ ] Print/Download guides as PDF
- [ ] Share service guides

---

## 📄 License

This is a demonstration project created for educational purposes.

---

## 👨‍💻 Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

### Adding New Services

Edit `src/data/mockServices.js` to add more services. Each service should include:
- Unique ID
- Title and description
- Category and icon
- Estimated time and fees
- Difficulty level
- Documents array
- Steps array
- Related services

---

## 🙏 Acknowledgments

- **Chakra UI** - For the excellent component library
- **Framer Motion** - For smooth animations
- **Recharts** - For beautiful data visualization
- **Lucide** - For clean, modern icons

---

## 📞 Contact

For questions or feedback about this demo:
- 📧 Email: [monikay7084@gmail.com]
- 🌐 GitHub: [https://github.com/AlphaStorm-X/GovGuide]

---

**Made with ❤️ for India** 🇮🇳

*Simplifying government services, one step at a time.*
