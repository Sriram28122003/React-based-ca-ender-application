# React-based-calender-application
# Calendar Application for Communication Tracking

## Objective
This project is a React-based Calendar Application designed to help organizations efficiently track their communications with other companies. The tool centralizes past interactions, plans future communications, and manages the frequency of engagements using predefined schedules, ensuring timely and consistent follow-ups.

---
Live Demo: 

(srirammarka-entnt-react-calender-app.netlify.app)

---

## Features

### Admin Module
- **Company Management**: Add, edit, and delete companies with details such as:
  - Name, Location, LinkedIn Profile, Emails, Phone Numbers, Comments.
  - Communication Periodicity (e.g., every 2 weeks).
- **Communication Method Management**: Define and manage communication methods including:
  - Name, Description, Sequence, and Mandatory Flag.
  - Default methods in sequence: LinkedIn Post, LinkedIn Message, Email, Phone Call, Other.

### User Module
- **Dashboard**:
  - Grid view with rows for each company and columns for: 
    - Company Name.
    - Last Five Communications.
    - Next Scheduled Communication.
  - Color-coded highlights:
    - **Red**: Overdue communication.
    - **Yellow**: Communication due today.
  - Interactive tooltips on completed communications.
- **Communication Actions**:
  - Log communication for one or multiple companies.
  - Modal to select type, date, and notes for communication.
- **Notifications**:
  - Overdue Communications Grid.
  - Today’s Communications Grid.
  - Notification icon with a badge count.
- **Calendar View**:
  - Visualize past communications.
  - Manage upcoming schedules.

### Reporting and Analytics Module (Optional)
- Communication Frequency Report: Visual representation of communication methods over time.
- Engagement Effectiveness Dashboard: Metrics on the success of communication methods.
- Overdue Communication Trends: Trendline/heatmap of overdue communications.
- Downloadable Reports: Export as PDF or CSV.
- Real-Time Activity Log: Live feed of communication activities.

---

## Installation and Setup

### Prerequisites
Ensure you have the following installed:
- Node.js (>= 16.0.0)
- npm or yarn

### Steps to Set Up Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/calendar-application.git
   ```
2. Navigate to the project directory:
   ```bash
   cd calendar-application
   ```
3. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```
4. Start the development server:
   ```bash
   npm start
   # or
   yarn start
   ```
5. Open the application in your browser:
   ```
   http://localhost:3000
   ```

### Deployment
The application can be deployed on platforms like Vercel, Netlify, or GitHub Pages:
1. Build the project:
   ```bash
   npm run build
   # or
   yarn build
   ```
2. Follow the deployment instructions for your platform.

---

## Application Functionality
- Admins can manage companies and communication parameters.
- Users can visualize, log, and manage communications.
- Notifications ensure timely follow-ups.
- (Optional) Reports and analytics provide actionable insights.

### Sample Data
To test the application, use the provided sample data in the `src/sample-data` directory.

---

## Technology Stack
- **Frontend**: React, Tailwind CSS
- **State Management**: Redux (optional)
- **Calendar Library**: FullCalendar.js
- **Charting Library**: Chart.js (for analytics module)
- **Build Tool**: Vite/Webpack

---

## Known Limitations
- Analytics module is optional and might not be included in initial releases.
- Limited support for recurring events beyond predefined periodicity.

---

## Testing
- Run tests using:
  ```bash
  npm test
  # or
  yarn test
  ```
- Testing covers core functionality such as communication logging, overdue notifications, and calendar rendering.

---

## Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---


Repository: [GitHub Repository](https://github.com/your-username/calendar-application)
