# 🔦 Spotlight – AI Powered Webinar Streaming & Sales Platform

Spotlight is an AI-powered webinar platform designed to help marketers and business owners go beyond just hosting presentations. With interactive CTAs, breakout rooms, and AI sales agents, Spotlight turns your webinars into real-time lead converters.

---


## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Features

- 🎥 Live Webinars with OBS/WebRTC support  
- 🛒 In-stream CTAs to sell products or book calls  
- 🧠 AI Sales Agents to engage and close leads  
- 🔀 Breakout Rooms for one-on-one AI conversations  
- 📊 Lead Tracking & Sales Pipelines  
- 🧩 Customizable AI Agent Behavior  
- 💰 Stripe Payment Integration  
- 🌓 Minimal & Beautiful Dark UI  
- 📼 Access to Webinar Recordings (Upcoming)

---


## Tech Stack

- **Frontend**: Next.js 15, TailwindCSS, Shadcn UI  
- **Backend**: Node.js, Express  
- **Database**: PostgreSQL + Prisma  
- **Authentication**: Clerk  
- **AI Agents**: OpenAI GPT-4 + Pinecone  
- **Payments**: Stripe  
- **Deployment**: Docker, Railway/Vercel  
- **Emailing**: Resend  

---

## Getting Started

```bash
# Clone the repo
git clone https://github.com/yourusername/spotlight.git
cd spotlight
```

# Install dependencies
```
npm install
```

# Start the dev server
```
npm run dev
```

---

## Environment Variables
Create a `.env` file in the root directory and add the following:

```
DATABASE_URL=your_postgres_url
CLERK_SECRET_KEY=your_clerk_key
OPENAI_API_KEY=your_openai_key
PINECONE_API_KEY=your_pinecone_key
STRIPE_SECRET_KEY=your_stripe_key
RESEND_API_KEY=your_resend_key
NEXT_PUBLIC_BASE_URL=http://localhost:3000
```

---

## Usage

1. Create a webinar from your dashboard.
2. Share the live webinar link with your audience.
3. Add in-stream CTAs like "Book a Call" or "Buy Now" using the editor.
4. Enable breakout rooms for high-intent leads to interact with the AI sales agent.
5. Train your AI sales agent using a custom prompt.
6. Monitor lead activity, track progress through your sales funnel, and follow up as needed.

---

## Contributing

We welcome contributions from the community! Here's how you can help:

- 🐛 Report bugs
- ✨ Suggest features
- 📂 Submit pull requests

Please fork the repo and create a branch for your feature or bug fix. Once done, open a PR with a clear explanation of your changes.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

Built with ❤️ by [Tushar Bhardwaj](https://tushar-bhardwaj.vercel.app)

Want to collaborate or have questions?  
Reach out via my [Portfolio](https://tushar-bhardwaj.vercel.app)

