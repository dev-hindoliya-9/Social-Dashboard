# Social Media Dashboard

A modern, responsive social media dashboard built with React.js and Tailwind CSS. This comprehensive dashboard provides real-time analytics, engagement metrics, and insights across multiple social media platforms.

## Features

- 📊 **Real-time Analytics** - Track followers, engagement, reach, and comments
- 📈 **Interactive Charts** - Visualize engagement trends and audience growth
- 🔔 **Recent Activity Feed** - Stay updated with latest interactions
- 🎯 **Multi-Platform Support** - Manage Twitter, Facebook, Instagram, LinkedIn, and YouTube
- 📱 **Top Performing Posts** - Identify your best content
- 🎨 **Modern UI/UX** - Beautiful, responsive design with Tailwind CSS
- 📱 **Mobile Responsive** - Works seamlessly on all devices

## Tech Stack

- **React 18** - Modern React with hooks
- **Tailwind CSS** - Utility-first CSS framework
- **Recharts** - Responsive chart library
- **React Icons** - Beautiful icon set
- **Vite** - Fast build tool and dev server

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Open your browser and navigate to `http://localhost:5173`

### Build for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

### Preview Production Build

```bash
npm run preview
```

## Project Structure

```
social-media-dashboard/
├── src/
│   ├── components/
│   │   ├── Dashboard.jsx          # Main dashboard container
│   │   ├── Header.jsx             # Top navigation bar
│   │   ├── Sidebar.jsx            # Side navigation menu
│   │   ├── StatsOverview.jsx      # Overview statistics cards
│   │   ├── SocialPlatforms.jsx    # Platform widgets
│   │   ├── EngagementChart.jsx    # Engagement line chart
│   │   ├── AudienceGrowth.jsx     # Audience growth area chart
│   │   ├── TopPosts.jsx           # Top performing posts
│   │   └── RecentActivity.jsx     # Activity feed
│   ├── App.jsx                    # Main app component
│   ├── main.jsx                   # Entry point
│   └── index.css                  # Tailwind CSS imports
├── index.html                     # HTML entry point
├── package.json                   # Dependencies and scripts
├── tailwind.config.js             # Tailwind configuration
├── vite.config.js                 # Vite configuration
└── README.md                      # This file
```

## Components Overview

### Dashboard
Main container component that orchestrates all dashboard sections.

### StatsOverview
Displays key metrics cards:
- Total Followers
- Total Reach
- Engagement Rate
- Total Comments

### SocialPlatforms
Shows analytics for each connected platform with:
- Follower counts
- Engagement rates
- Post counts
- Growth percentages

### EngagementChart
Interactive line chart showing engagement and reach trends over time.

### AudienceGrowth
Area chart visualizing follower growth over the past months.

### TopPosts
List of best performing posts with engagement metrics.

### RecentActivity
Real-time feed of user interactions across platforms.

## Customization

### Colors

Edit `tailwind.config.js` to customize the color scheme:

```javascript
theme: {
  extend: {
    colors: {
      primary: {
        // Your custom colors
      }
    }
  }
}
```

### Data

Replace mock data in components with real API calls to your backend.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the MIT License.

## Contributing

Contributions, issues, and feature requests are welcome!

## Author

Built with ❤️ using React and Tailwind CSS


