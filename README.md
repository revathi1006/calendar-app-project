Project Name: Calendar Application for Communication Tracking

Deployment Link of project on Vercel: calendar-app-project.vercel.app

To install Dependencies: npm install

To start the development server: npm start

Description: This application helps organizations manage and track communications with external companies effectively. It features an admin panel for configuring communication methods and a user dashboard for managing and visualizing tasks. Optional analytics provide actionable insights into performance.

Objective: The project involves developing a React-based Calendar Application designed for communication tracking with companies. The application ensures timely follow-ups and consistent engagement by maintaining logs of past interactions and planning future communications. It provides an intuitive interface for managing communication tasks and generating insights through analytics. The application will include: An Admin Module for setting up companies and communication parameters. A User Module for visualizing, managing, and performing communication tasks. A Reporting and Analytics Module for actionable insights (optional). It is critical to emphasize usability, clarity, and efficient data handling.

Detailed Requirements: Admin Module- This module allows administrators to configure the application and manage its foundational data.

Company Management- Admins should be able to add, edit, and delete companies. Each company entry should include: Name: Name of the company. Location: Physical or operational location. LinkedIn Profile: A link to the company’s LinkedIn page. Emails: One or more email addresses for communication. Phone Numbers: Contact numbers for representatives. Comments: Notes or additional information about the company. Communication Periodicity: The default time interval for scheduled communications (e.g., every 2 weeks).

Communication Method Management- Admins should define the available communication methods in the system. Each method should include: Name: E.g., "Visit" or "LinkedIn Post." Description: E.g., "Visit to company premises." Sequence: Determines the order of communication (e.g., LinkedIn Post → LinkedIn Message → Email → Phone Call → Other). Mandatory Flag: Indicates whether a communication method is mandatory in the sequence. By default, the system should include these methods in the following order: LinkedIn Post LinkedIn Message Email Phone Call Other

User Module- This module is the primary interface for end-users, enabling them to view, manage, and perform communication tasks.

Dashboard- The dashboard provides a grid-like view where each row represents a company. Columns include: Company Name: The name of the company. Last Five Communications: A summary of the five most recent communications, including the type (e.g., "LinkedIn Post") and date (e.g., "5th September"). Next Scheduled Communication: The type and date of the next planned communication. Color-Coded Highlights: Red Highlight: Indicates overdue communication. Yellow Highlight: Indicates communication due today. Users can disable or override highlights for specific companies or communications as needed. Interactive Features Hover Effect: When hovering over a completed communication, a tooltip should display the notes or comments recorded for that communication.

Communication Action- Users can select a specific company or multi-select multiple companies. Click on a "Communication Performed" button to log a new communication. In the action modal: Select Type of Communication: E.g., LinkedIn Post, Email. Input Date of Communication: Date when the communication occurred. Add Notes: Additional comments about the communication. Upon submission, this action will reset any existing highlights (red or yellow) for the selected company/companies.

Notifications- A dedicated section displays overdue and due communications: Overdue Communications Grid: Lists companies with overdue actions. Today’s Communications Grid: Lists companies with tasks due today. The notification icon should display a badge with the count of overdue and due communications.

Calendar View- A calendar interface that allows users to: View Past Communications: Dates and methods of previous interactions. View and Manage Upcoming Communications: Scheduled dates and methods for future interactions.

Reporting and Analytics Module: This module provides actionable insights and performance metrics related to company communications. Features: Communication Frequency Report- A visual representation (e.g., bar chart or pie chart) showing the frequency of each communication method (e.g., LinkedIn Post, Email) used over a selected time frame. Users can filter by company, date range, or communication method.

Engagement Effectiveness Dashboard- Track and display which communication methods are most effective in terms of response or follow-up actions. Include metrics like the percentage of successful responses to emails, phone calls, or LinkedIn messages.

Overdue Communication Trends- A trendline or heatmap showing the number of overdue communications over time, categorized by company.

Downloadable Reports- Allow users to export reports in PDF or CSV format for sharing or offline analysis. Real-Time Activity Log- A live feed displaying all communication activities performed, sortable by date, user, or company.

