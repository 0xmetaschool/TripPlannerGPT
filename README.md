# Trip Planner GPT
TripPlannerGPT is your ultimate AI-powered trip planning assistant. Forget the hassle of research and logistics—this app creates personalized travel itineraries in seconds. Whether you're a spontaneous adventurer or a meticulous planner, TripPlannerGPT is your perfect travel companion.

Built with Next.js and powered by OpenAI API, this template helps you build an AI-driven platform to make travel planning intuitive, quick, and fun.


## Live Demo

[https://trip-planner-gpt.vercel.app/](https://trip-planner-gpt.vercel.app/)

## Features

- Generate personalized travel itineraries including best hotels and meals using AI
- Customize plans based on destination, duration, budget, and trip companions
- Interactive Google map integration to explore recommended places
- Download a pdf of the generated trip plan

## Technologies Used

- Next.js and React for Frontend and Backend
- OpenAI API with GPT models for AI-Powered Features
- Clerk authentication for Authorization

## Use Cases

- Create detailed, day-by-day travel itineraries tailored to your preferences
- Explore curated recommendations for attractions, restaurants, and accommodations
- Stay within your budget with cost-efficient travel options
- Download and revisit your itineraries for future trips

### Installation Steps

1. Clone the repository:
 
```
git clone https://github.com/0xmetaschool/TripPlannerGPT.git
```

2. Navigate to the project directory:
```
cd TripPlannerGPT
```

3. Install dependencies:
```
npm install
```

4. Set up environment variables:

Create an .env file in the root directory. Add the following variables:
```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=

OPENAI_API_KEY=

NEXT_PUBLIC_PEXELS_API_KEY=
```

5. Run the development server:
```
npm run dev
```
Open your browser and navigate to `http://localhost:3000`.

## Screenshots

<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/0xmetaschool/TripPlannerGPT/blob/main/public/trip-planner-gpt-template-homepage.png?raw=true" alt="TriviaPlannerGPT homepage screenshot" style="width: 49%; border: 2px solid black;" />
  <img src="https://github.com/0xmetaschool/TripPlannerGPT/blob/main/public/trip-planner-gpt-template-popular-destination.png?raw=true" alt="TripPlannerGPT popular destination screenshot" style="width: 49%; border: 2px solid black;" />
</div>
<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/0xmetaschool/TripPlannerGPT/blob/main/public/trip-planner-gpt-template-dashboard.png?raw=true" alt="TripPlannerGPT dashboard screenshot" style="width: 49%; border: 2px solid black;" />
  <img src="https://github.com/0xmetaschool/TripPlannerGPT/blob/main/public/trip-planner-gpt-template-custom-trip-plan.png?raw=true" alt="TripPlannerGPT custom trip plan screenshot" style="width: 49%; border: 2px solid black;" />
</div>


## How to Use the Application

1. Sign in using your Google account
2. Enter your travel preferences like destination, duration, and budget
3. View your AI-generated itinerary, complete with detailed daily plans
4. Download to save your trip plans
5. Use the interactive map to explore nearby attractions


## Contributing

We love contributions! Here's how you can help make the project even better:

- Fork the project (gh repo fork https://github.com/0xmetaschool/TripPlannerGPT/fork)
- Create your feature branch (git checkout -b feature/AmazingFeature)
- Commit your changes (git commit -m 'Add some AmazingFeature')
- Push to the branch (git push origin feature/AmazingFeature)
- Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/0xmetaschool/TripPlannerGPT/blob/main/LICENSE) file for details.

## Contact

Please open an issue in the GitHub repository for any queries or support.
