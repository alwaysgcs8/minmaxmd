# MinMaxMD

MinMaxMD is a mobile-first personal finance tracker built with React and Tailwind CSS. It features a beautiful "liquid" UI, local storage persistence, and integrated AI capabilities powered by Google Gemini.

![MinMaxMD Banner](https://via.placeholder.com/1200x600/0ea5e9/ffffff?text=MinMaxMD+Financial+Tracker)

## Features

*   **Dashboard**: Real-time view of total balance, monthly income, and expenses with a parallax liquid card effect.
*   **Transactions**: Add income and expenses with recurring options (Daily, Weekly, Monthly, Yearly).
*   **Analytics**: Visual breakdown of spending by category and linear projections for monthly/yearly outcomes.
*   **Budget Limits**: Set soft limits for specific categories to track spending health.
*   **AI Advisor**: (Experimental) Integrated Gemini API structure for financial insights.
*   **Offline First**: All data is persisted locally in the browser.
*   **Dark Mode**: Fully responsive dark/light theme switching.

## Tech Stack

*   **Framework**: React 18+ (TypeScript)
*   **Styling**: Tailwind CSS
*   **Icons**: Lucide React
*   **Charts**: Recharts
*   **AI**: Google GenAI SDK (Gemini)
*   **Build Tool**: Vite

## Setup & Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/minmaxmd.git
    cd minmaxmd
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Environment Configuration**
    Create a `.env` file in the root directory and add your Google Gemini API key:
    ```env
    API_KEY=your_google_api_key_here
    ```

4.  **Run Development Server**
    ```bash
    npm run dev
    ```

## Project Structure

*   `/components`: UI components (Dashboard, Analytics, Forms).
*   `/services`: Logic for Storage (LocalStorage) and AI (Gemini).
*   `/types`: TypeScript interfaces for Transactions and State.

## License

MIT
