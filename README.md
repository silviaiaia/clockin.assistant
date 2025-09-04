<img src="https://capsule-render.vercel.app/api?type=soft&color=0:FFD9EC,100:FF79BC&height=100&section=header&text=Beep%20🤖&fontSize=40&fontAlignY=60&animation=blinking" />

### This is a simple clock-in system.

I was tired of recording my working time every single day, so I made this! 
(with the help of Professor Claude and Professor Gemini)

🥤🥗🍔🍗🍟🥓 12:00-13:00 is my lunch break, so this period will not be counted as working time.

---

### Features

This system is browser-based, and built with pure HTML, CSS, and JavaScript. It allows users to track their work hours and calculate wages without needing a backend server, as all data is stored locally in the browser's localStorage.

- **Real-time Clock Display** : shows current time.

- **Clock-in/Clock-out Functionality** : records start and end times for work sessions.

- **Customizable Hourly Rate** : you can set and save your hourly wage.

- **Work Hours and Wage Calculation** : automatically calculates total work hours and estimated wage for each session (usually on a daily basis).

  - Work hours are rounded to the nearest half-hour (0.5 hours).

  - A one-hour lunch break is automatically deducted if the work period spans from 12:00 PM to 1:00 PM.

  - Wages are rounded to the nearest hundred.

- **Local Data Storage** : all records are saved in browser's localStorage, ensuring data persists even if you close the tab.

- **Reporting** : generate and export weekly or monthly work reports as a text file.

- **Data Management** :

  - Fix Records: recalculates work hours and wages for all records based on the current hourly rate.

  - Delete Records: allows you to delete individual work entries.

  - Clear All Data: provides an option to permanently delete all stored data.
 
---

### How to Use

1.  **Refer to this link** ⭢ https://silviaiaia.github.io/clockin-system
2.  **Set Your Hourly Wage** : Enter your hourly rate in the "Hourly wage" input field. This value will be saved automatically. The default value is 190.
3.  **Clock-in** : Click the "Clock-in" button when you start working. The status will change to "Clocked in - in work mode."
4.  **Clock-out** : Click the "Clock-out" button when your work session ends. The system will automatically calculate your work hours and wage, and add the record to the table below.
5.  **View Records** : Your records are displayed in the "Recent records" table. You can use the "Delete" button next to each entry to remove it.
6.  **Generate Reports** : Click "Export weekly report" or "Export monthly report" to download a summary of your work hours and earnings for the selected period.
7.  **Manage Data**:
    - If you change your hourly wage and want to update past records, click **"Fix records"**.
    - To permanently delete all data, click **"Clear all data"**.

---

### Technical Details

- **HTML** : Structures the page content and layout.

- **CSS** : Styles the user interface for a clean and modern look.

- **JavaScript** : Handles all the logic, including:

  - Managing the real-time clock.

  - Storing and retrieving data from localStorage.

  - Performing calculations for work hours and wages.

  - Dynamically updating the UI.

  - Generating and exporting report files.
 
---

### Important Notes

- This is a front-end only application. Data is stored exclusively on your local device's browser. If you use a different computer or browser, your data will not be available.

- Clearing your browser's cache or local storage will permanently delete all your clock-in records.

- The system currently deducts a fixed one-hour lunch break for work sessions that include the 12 PM to 1 PM period. This logic might need to be adjusted for more complex work schedules.

- The system currently does not have the function of calculating over-time paid, all work hours would be counted with the input wages.

  




