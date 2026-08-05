# AI Trip planner
![preview](/public/AI-Trip planner.png)

# AI Trip Planner ✈️

An AI-powered travel planning application that transforms user ideas into personalized, day-by-day travel itineraries. Users can describe their trip requirements in natural language, and the AI generates an interactive travel plan that can be customized, reordered, and managed easily.

## 🚀 Features

- 🤖 AI-Powered Itinerary Generation
  - Generate personalized travel plans using AI based on destination, duration, interests, and preferences.

- 🗓️ Day-by-Day Travel Planning
  - View structured daily itineraries with activities, locations, and recommendations.

- ✨ Interactive Experience
  - Expand and collapse itinerary sections.
  - Remove unwanted activities.
  - Reorder travel stops using drag-and-drop.

- 🧠 Smart AI Response Handling
  - Converts unpredictable AI responses into structured and reliable UI components.
  - Handles incomplete or invalid AI-generated data gracefully.

- 📱 Responsive Design
  - Optimized for desktop, tablet, and mobile devices.
 
  ## 🛠️ Tech Stack

### Frontend
- React.js
- TypeScript
- Vite
- Tailwind CSS
- React Hooks

💡 How It Works

1. User enters trip details:
   - Destination
   - Number of days
   - Budget
   - Travel interests
   - Preferred activities

2. The application sends the request to an AI model.

3. The AI generates a structured itinerary.

Example:

```json
{
  "destination": "Paris",
  "days": [
    {
      "day": 1,
      "activities": [
        "Visit Eiffel Tower",
        "Explore Louvre Museum"
      ]
    }
  ]
}
```

4. The application converts the AI response into editable UI components.

5. Users can customize their travel plan before finalizing.
 
 PROJECT STRUCTURE 
 ai-trip-planner/
│
├── src/
│   ├── components/
│   │   ├── TripForm.tsx
│   │   ├── ItineraryCard.tsx
│   │   ├── ActivityItem.tsx
│   │
│   ├── pages/
│   │   └── Home.tsx
│   │
│   ├── services/
│   │   └── aiService.ts
│   │
│   ├── hooks/
│   │
│   ├── types/
│   │
│   └── App.tsx
│
├── public/
├── package.json
├── README.md
└── .env
