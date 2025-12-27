🌦️ Weather Application:-
A responsive and modern Weather Dashboard that provides real-time weather information. Users can check the temperature, humidity, wind speed, and weather conditions for any city worldwide.

✨ Features:
Real-time Data: Fetches live weather information using the OpenWeatherMap API.
Dark/Light Mode: Includes a theme toggle for a personalized user experience.
Responsive Design: Fully optimized for both mobile and desktop screens using Glassmorphism UI.

🚀 Live Demo:
You can view the live application here:
👉https://kpporwal.github.io/Weather-App/

🛠️ Technologies Used:
HTML5 - For the application structure.
CSS3 - For styling, animations, and the glassmorphism effect.
JavaScript (ES6) - For API integration and DOM manipulation.
OpenWeatherMap API - For fetching live weather data.
/_ --- Mobile Specific Styles (Max width 480px) --- _/
@media (max-width: 480px) {
#weatherApp {
width: 90% !important; /_ Box ko screen ke andar rakhne ke liye _/
max-width: 360px;
padding: 20px 15px;
margin: 20px auto;
display: block;
}

    .search {
        display: flex !important;
        flex-direction: row; /* Input aur Button ek line mein rahenge */
        align-items: center;
        justify-content: space-between;
        gap: 8px;
        width: 100%;
    }

    .search input {
        flex: 1; /* Input jitni jagah bachi hai le lega */
        min-width: 0; /* Overflow rokne ke liye zaroori hai */
        height: 45px;
        font-size: 14px;
        padding: 0 10px;
        border-radius: 25px;
    }

    .search button {
        width: 90px !important; /* Button ki width limit kar di taaki bahar na nikle */
        height: 45px;
        font-size: 11px;
        font-weight: bold;
        padding: 5px;
        white-space: normal; /* Text ko 2 lines mein wrap karega agar bada hai */
        line-height: 1.2;
        border-radius: 25px;
        display: flex;
        align-items: center;
        justify-content: center;
        text-align: center;
        flex-shrink: 0; /* Button ko pichakne se rokega */
    }

    .temp {
        font-size: 50px;
        margin: 15px 0;
    }

    .city {
        font-size: 26px;
    }

    .details {
        display: flex;
        justify-content: space-around;
        width: 100%;
        margin-top: 25px;
    }

    .col {
        text-align: center;
    }

    .col img {
        width: 35px; /* Icons ka size chota kiya */
    }

}
