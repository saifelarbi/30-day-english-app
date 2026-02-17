# 🎓 30-Day English Learning App
## Develop Your English Skills Through Daily Speaking & Work Practice

<div align="center">

![Status](https://img.shields.io/badge/Status-Active%20Development-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-brightgreen)

**An innovative daily English learning app combining speaking practice, vocabulary building, and practical work skills development.**

[Features](#-features) • [Tech Stack](#-tech-stack) • [Getting Started](#-getting-started) • [Project Structure](#-project-structure) • [Roadmap](#-roadmap)

</div>

---

## 📱 Overview

**30-Day English Learning App** is a mobile application designed to help users improve their English proficiency through:

- **Daily Audio Recordings:** Record yourself speaking about daily topics (3-5 minutes)
- **Smart Vocabulary Tracking:** Learn 5 new words + work-related terminology each day
- **Mistake Logging:** Track pronunciation and grammar errors for improvement
- **Work Skills Integration:** Combine English learning with practical workplace skills
- **Progress Analytics:** Visualize your 30-day journey with charts and statistics
- **Structured Curriculum:** 30 carefully designed topics from basic to advanced

---

## ✨ Key Features

### 🎤 Daily Speaking Practice
- Voice recording with built-in recorder
- Playback and comparison with native speakers
- Duration tracking (target: 3-5 minutes/day)
- Audio file storage and organization

### 📝 Vocabulary Management
- Daily word list (5 new words)
- Interactive vocabulary cards
- Pronunciation guides
- Work-related terminology focus
- Spaced repetition scheduling

### ❌ Mistake Tracking
- Log pronunciation errors
- Grammar mistake tracking
- Common words to review
- Weekly mistake summary
- AI-powered correction suggestions (future)

### 📊 Progress Analytics
- Daily completion rate
- Speaking time statistics
- Vocabulary retention metrics
- Weekly/monthly progress charts
- Streak tracking (consecutive days)

### 💼 Work Skills Module
- Daily work-related tasks
- Practical client communication templates
- Project-specific vocabulary
- Professional email examples
- Meeting preparation guides

### 🎯 Structured Curriculum (30 Days)
**Days 1-10:** Foundation
- Talking about yourself & work
- Daily routines, hobbies, problems
- Food, travel, weather

**Days 11-20:** Expansion
- Sports, health, news, learning, family
- Shopping, technology, transport
- Challenges, culture

**Days 21-30:** Mastery
- Jobs & careers, future projects, events
- Personal goals, finance, online learning
- Communication & achievements

### 📲 Push Notifications
- Daily reminders at custom time (default: 13:30)
- Streak notifications
- Weekly summary reports
- Motivational messages

### ☁️ Cloud Sync
- Backup recordings to cloud
- Cross-device synchronization
- Data recovery
- Account management

---

## 🏗️ Tech Stack

### Frontend
- **Framework:** Flutter / React Native
- **Language:** Dart / JavaScript (TypeScript)
- **UI Components:** Material Design 3
- **State Management:** Provider / Redux
- **Audio Recording:** flutter_sound / react-native-audio-recorder

### Backend
- **Framework:** Node.js / Django / FastAPI
- **Database:** PostgreSQL / MongoDB
- **Authentication:** Firebase Auth / JWT
- **File Storage:** AWS S3 / Google Cloud Storage
- **Analytics:** Firebase Analytics / Mixpanel

### APIs & Services
- **Audio Processing:** Whisper API (OpenAI) for transcription
- **Pronunciation Check:** Google Cloud Speech API
- **Grammar Correction:** LanguageTool API / GPT API
- **Translation:** Google Translate API
- **Push Notifications:** Firebase Cloud Messaging

### DevOps
- **CI/CD:** GitHub Actions / GitLab CI
- **Build:** Gradle (Android) / Xcode (iOS)
- **Distribution:** Google Play Store / Apple App Store
- **Monitoring:** Sentry / LogRocket

---

## 📊 Project Structure

```
30-day-english-app/
├── mobile/
│   ├── android/              # Android-specific code
│   ├── ios/                  # iOS-specific code
│   ├── lib/                  # Flutter/React code
│   │   ├── screens/          # UI screens
│   │   ├── widgets/          # Reusable components
│   │   ├── services/         # API & business logic
│   │   ├── models/           # Data models
│   │   ├── utils/            # Helper functions
│   │   └── main.dart         # Entry point
│   └── pubspec.yaml          # Dependencies
│
├── backend/
│   ├── api/                  # API routes
│   ├── models/               # Database models
│   ├── services/             # Business logic
│   ├── middleware/           # Authentication, logging
│   ├── controllers/          # Request handlers
│   └── config/               # Configuration
│
├── docs/
│   ├── ARCHITECTURE.md       # System design
│   ├── API.md                # API documentation
│   ├── SETUP.md              # Development setup
│   └── CURRICULUM.md         # 30-day curriculum
│
├── tests/
│   ├── unit/
│   ├── widget/
│   └── integration/
│
├── .github/
│   └── workflows/            # CI/CD pipelines
│
├── docker-compose.yml        # Local development
├── .env.example              # Environment variables
├── README.md                 # This file
└── LICENSE                   # MIT License
```

---

## 🚀 Getting Started

### Prerequisites
- Flutter SDK 3.0+ OR React Native 0.70+
- Node.js 18+ (for backend)
- PostgreSQL 13+ OR MongoDB 5+
- Android Studio / Xcode (for native development)
- Git

### Local Development Setup

**1. Clone Repository**
```bash
git clone https://github.com/saifelarbi/30-day-english-app.git
cd 30-day-english-app
```

**2. Setup Backend**
```bash
cd backend
npm install
cp .env.example .env
npm run dev
```

**3. Setup Mobile (Flutter)**
```bash
cd mobile
flutter pub get
flutter run
```

**4. Setup Database**
```bash
docker-compose up -d
npm run migrate  # Run migrations
```

**5. Environment Variables**
```bash
# .env
DATABASE_URL=postgresql://user:password@localhost:5432/english_app
JWT_SECRET=your_secret_key
OPENAI_API_KEY=your_api_key
FIREBASE_API_KEY=your_firebase_key
AWS_S3_BUCKET=your_bucket
```

---

## 📈 Features Breakdown

### Phase 1: MVP (Weeks 1-4)
- [x] Basic recording functionality
- [x] Daily lesson display
- [x] Notes & mistakes logging
- [x] Simple progress tracking
- [x] Push notifications

### Phase 2: Enhanced (Weeks 5-8)
- [ ] Audio playback with speed control
- [ ] Vocabulary flashcards
- [ ] Weekly progress charts
- [ ] Work skills templates
- [ ] Cloud backup

### Phase 3: Advanced (Weeks 9-12)
- [ ] AI pronunciation feedback
- [ ] Grammar correction
- [ ] Leaderboard & gamification
- [ ] Social sharing
- [ ] Premium features

### Phase 4: Premium (Future)
- [ ] 1-on-1 tutor matching
- [ ] Live group classes
- [ ] Advanced analytics
- [ ] Custom learning paths
- [ ] Corporate team features

---

## 🎯 Use Cases

### 👤 Individual Learners
- Busy professionals wanting daily English improvement
- Job seekers preparing for interviews
- Freelancers improving client communication
- Students building work-relevant skills

### 🏢 Corporate Training
- Employee English programs
- Client-facing team development
- International communication skills
- Onboarding training modules

### 🎓 Educational Institutions
- Classroom supplementary tool
- Homework tracking system
- Student progress monitoring
- Speaking practice evidence

---

## 📊 Analytics & Metrics

The app tracks:
- **Speaking Time:** Daily, weekly, total hours
- **Vocabulary Learned:** Retention rate, review frequency
- **Consistency:** Streak count, completion rate
- **Audio Quality:** Recording clarity, length metrics
- **Error Patterns:** Common mistakes, improvement areas
- **Engagement:** Daily active users, session duration

---

## 🤝 Contributing

Contributions are welcome! Please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

---

## 📝 Curriculum Details

### Day 1-5: Foundation
- **Day 1:** Talking about yourself & work
- **Day 2:** Daily routines
- **Day 3:** Hobbies & interests
- **Day 4:** Current projects
- **Day 5:** Weekend plans

### Day 6-10: Early Expansion
- **Day 6:** Workplace & tools
- **Day 7:** Problems & solutions
- **Day 8:** Food & eating habits
- **Day 9:** Travel & future plans
- **Day 10:** Weather & daily news

### Day 11-20: Building Skills
- Days focused on: Sports, health, news, learning, family
- Introduction of: Business terms, technology vocabulary
- Practice with: Transport, time management, cultural topics

### Day 21-30: Mastery
- Complex topics: Jobs, projects, finance
- Advanced: Online learning, formal communication
- Celebration: Achievements review & next steps planning

---

## 🎨 Design Philosophy

- **Simple & Intuitive:** Minimal learning curve
- **Consistent:** Material Design 3 compliance
- **Accessible:** WCAG 2.1 AA standards
- **Mobile-First:** Optimized for small screens
- **Fast:** Sub-2 second load times

---

## 📜 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Saif Elarbi**
- GitHub: [@saifelarbi](https://github.com/saifelarbi)
- Email: saif@example.com
- LinkedIn: [Saif Elarbi](https://linkedin.com/in/saifelarbi)

---

## 📞 Support

- **Issues:** [GitHub Issues](https://github.com/saifelarbi/30-day-english-app/issues)
- **Discussions:** [GitHub Discussions](https://github.com/saifelarbi/30-day-english-app/discussions)
- **Email:** support@30dayenglish.app

---

## 🙏 Acknowledgments

- Inspired by proven language learning methodologies
- Built with community feedback
- Powered by open-source technologies

---

## 📱 Download

- **Coming Soon:** Google Play Store
- **Coming Soon:** Apple App Store
- **Beta:** [TestFlight Link](#)

---

**Made with ❤️ to help you master English in 30 days**

⭐ If you find this project helpful, please star it on GitHub!

