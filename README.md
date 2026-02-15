#  ComfortBoard

**ComfortBoard** is a personal digital sanctuary designed for mental clarity, emotional reflection, and peace of mind. Built with a focus on rich aesthetics and empathetic interaction, it provides a safe space to untangle thoughts and visualize life's journey.

## Site URL

https://comfortboard.onrender.com/

##  Key Features

- ** Emotional Mapping**: A 2D infinite canvas where you can place stickers to categorize your thoughts into *Problems*, *Successes*, and *Insights*.
- ** AI Comfort Guide**: An empathetic digital companion powered by Gemini AI that analyzes your board and provides supportive, non-judgmental guidance.
- ** Atmospheric Sanctuary**: Integrated audio controller with ambient tracks (Rain, Ocean, Pink Noise) to help you focus or relax.
- ** Breathing Sync**: A dedicated box-breathing module with visual prompts to help manage stress in real-time.
- ** Daily Inspiration**: Curated quote of the day with a rating system to help you reflect on positive thoughts.

##  Tech Stack

- **Framework**: Next.js 15 (App Router)
- **Styling**: Tailwind CSS & Framer Motion
- **Database/Auth**: Supabase
- **AI**: Google Gemini Pro (Generative AI)
- **Icons**: Lucide React

##  Getting Started

1. **Clone the repository**
2. **Setup Environment Variables**:
   Create a `.env.local` file with:
   ```env
   NEXT_PUBLIC_SUPABASE_URL=your_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_key
   GEMINI_API_KEY=your_api_key
   ```
3. **Install dependencies**:
   ```bash
   npm install
   ```
4. **Run the development server**:
   ```bash
   npm run dev
   ```

##  Database Setup

To initialize the database, execute the SQL script from `supabase_schema.sql` in your Supabase SQL Editor. This will create the necessary tables and set up Row Level Security (RLS) policies:
- `profiles`: User profiles and settings.
- `stickers`: Board elements (Problems, Successes, Insights).
- `chat_history`: AI conversation records.
- `quote_ratings`: User feedback on daily quotes.

##  Privacy
Your thoughts are personal. ComfortBoard uses secure Supabase authentication to ensure that your board and chat history are visible only to you.

---
*Built with ❤️ for a calmer mind.*
