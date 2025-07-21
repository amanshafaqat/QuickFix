🔧 QuickFix – Home Troubleshooting Companion
QuickFix is a modern, mobile-friendly troubleshooting app designed to help users find instant solutions for common household issues. With a sleek UI, robust search, safety-first content, and personalized features like favorites and history, QuickFix is your go-to toolkit for everyday problems.

🚀 Live Preview
https://leafy-shortbread-d37315.netlify.app/

📱 Features
✅ Add Fix – Instantly find solutions as you type

🔍 Smart Search – Get real-time matching results with detailed previews

⭐ Favorites – Save and manage frequently used fixes

🧠 Troubleshooting DB – Over 15+ household items with structured guides

⚠️ Safety Tips – Integrated precautions and warnings

📱 Responsive Design – Optimized for all screen sizes

📂 Local Storage – Remembers your fixes using AsyncStorage

📤 Share Functionality – Share any solution with others instantly

🎨 Modern UI – Clean, tab-based layout with intuitive navigation

🛠️ Project Structure
yaml
Copy
Edit
QuickFix/
│
├── app/                   # All app screens and navigation
│   ├── _layout.tsx
│   ├── +not-found.tsx
│   ├── solution-detail.tsx
│   └── (tabs)/
│       ├── _layout.tsx
│       ├── index.tsx           # Dashboard (Home)
│       ├── categories.tsx
│       ├── add-fix.tsx
│       ├── search.tsx
│       ├── favorites.tsx
│       └── history.tsx
│
├── components/
│   ├── CategoryIcon.tsx
│   ├── LoadingSpinner.tsx
│   └── EmptyState.tsx
│
├── constants/
│   ├── Colors.ts
│   └── Layout.ts
│
├── hooks/
│   └── useFrameworkReady.ts
│
├── types/
│   └── index.ts
│
├── utils/
│   ├── storage.ts
│   └── troubleshootingData.ts
│
├── config files:
│   ├── package.json
│   ├── app.json
│   ├── tsconfig.json
│   ├── .prettierrc
│   ├── .npmrc
│   ├── .gitignore
│   └── expo-env.d.ts
│
├── README.md
├── LICENSE
📦 Tech Stack
Framework: Expo + React Native

Language: TypeScript

Storage: AsyncStorage

Navigation: Expo Router

Styling: Custom + Layout Constants

🧪 Getting Started
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/quickfix.git
cd quickfix
Install dependencies

bash
Copy
Edit
npm install
Run the app

bash
Copy
Edit
npm run dev
Ensure you have Expo CLI installed. If not:

bash
Copy
Edit
npm install -g expo-cli
📁 Local Development Notes
Update categories and fixes in utils/troubleshootingData.ts

Modify storage logic in utils/storage.ts

Add new types in types/index.ts

📜 License
This project is licensed under the MIT License.
Feel free to use, modify, and share!

🤝 Contributing
Pull requests are welcome!
If you find any bugs or want to add features, feel free to open an issue or PR.

👤 Author
Aman Shafaqat

