# Finsense - AI-Powered Personal Finance Management System

Finsense is an intelligent personal and family financial management system designed to help users achieve their financial goals and improve financial well-being. Through AI technology, the system provides personalized financial analysis, recommendations, and action plans.

## Key Features

- 🤖 AI-Driven Financial Analysis
- 📊 Personal/Family Finance Tracking
- 🎯 Customized Financial Goal Setting
- 📈 Smart Financial Planning Recommendations
- 📰 Financial News and Knowledge Integration
- 💰 Conservative Investment Advice (After reaching specific financial goals)

## Tech Stack

### Frontend
- Next.js 15
- TailwindCSS
- TypeScript
- ShadcnUI

### Backend
- Python
- FastAPI
- Docker

## Getting Started

### Prerequisites
- Node.js 18.17 or later
- npm, yarn, or pnpm
- Git

### Frontend Setup

1. Clone the repository:
```bash
git clone https://github.com/tech-leon/finsense.git
cd finsense
```

2. Install dependencies:
```bash
npm install
```

3. Copy the `.env.example` file to `.env` and add necessary environment variables:
```bash
NEXT_PUBLIC_OPENAI_API_KEY=your_api_key
```

4. Start the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.

### Backend Setup

1. Navigate to the backend directory:
```bash
cd backend
```

2. Create and activate a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. Install Python dependencies:
```bash
pip install -r requirements.txt
```

4. Start the FastAPI server:
```bash
uvicorn main:app --reload
```

## Docker Deployment

...

## Development

- Frontend code can be modified in the `app` directory
- Components can be found in the `components` directory
- Styles are managed with TailwindCSS

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.

## Contributors

- [Leon](https://github.com/tech-leon)
- [Zoe](https://github.com/zoetech0202)
- [Moshe](https://github.com/mmiSSo-01)
