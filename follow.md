

**Project Prompt for Cursor AI: Ramadan Calendar and Prayer Times in Bongao, Tawi-Tawi**

**Objective:**  
Create a dynamic Ramadan calendar and prayer time countdown for 2025 and future years that fetches data via a public API. The app should focus on displaying the Ramadan timetable and prayer times in Bongao, Tawi-Tawi, Philippines. The project should work without a backend and rely solely on API calls and frontend rendering.

**Requirements:**

1. **API Integration:**
   - Use a reliable prayer times API (e.g., Aladhan API or IslamicFinder API) to fetch prayer times based on latitude and longitude for Bongao, Tawi-Tawi.
   - Fetch data for the Islamic Hijri calendar for Ramadan (e.g., Umm Al-Qura or similar).
   - API results must support specific coordinates:  
     Latitude: `5.0295`, Longitude: `119.7738` (Bongao, Tawi-Tawi).

2. **Features:**
   - Display the Ramadan calendar with Hijri and Gregorian dates.
   - Display daily prayer times (Fajr, Dhuhr, Asr, Maghrib, Isha).
   - Countdown timer for the next prayer.
   - Highlight the current day's prayers and countdown in real-time.

3. **Frontend Only (No Backend):**
   - Use a lightweight framework or vanilla JavaScript for the frontend.
   - Make API calls directly from the frontend to retrieve and display data.
   - Ensure cross-origin requests (CORS) are handled properly.

4. **UI/UX:**
   - Simple and clean user interface with focus on usability.
   - Separate sections for:
     - Ramadan Calendar.
     - Today’s Prayer Times with countdown.
   - Responsive design for mobile and desktop users.

5. **Additional Details:**
   - Option to select the year for Ramadan calendar.
   - Include a time zone conversion feature to adjust for Bongao’s time zone (PST/UTC+8).
   - Provide fallback messaging if the API fails or there’s no internet connection.

**Deliverables:**
- A single-page application (SPA) that is lightweight and functional.
- Documentation on how to configure the app and replace API keys if necessary.
- Commented code for easy maintenance.

**Reference APIs:**
https://www.islamicfinder.us/index.php/api/calendar
https://www.islamicfinder.us/index.php/api/prayer_times

**Output Preview:**
- Ramadan Calendar: Table format showing prayer times for each day of Ramadan.
- Today’s Prayer Countdown: Dynamic display with time remaining until the next prayer.

---

This prompt ensures you’ll have a clear direction for your project while staying lightweight and API-driven.