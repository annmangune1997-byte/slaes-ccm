# Sales Performance Dashboard

A comprehensive web-based dashboard for analyzing and comparing self-delivery vs online web sales performance across multiple branches. The dashboard provides interactive visualizations, data management capabilities, and automated insights generation.

![Dashboard Screenshot](https://via.placeholder.com/800x400?text=Sales+Dashboard+Screenshot)

## Features

### 📊 Data Visualization
- **Trend Analysis**: Line charts showing sales and order trends over time
- **Channel Comparison**: Bar charts comparing Self Delivery vs Online Web performance
- **Branch Performance**: Visual comparison of sales across all branches
- **Monthly Trends**: Detailed monthly performance tracking
- **Year-over-Year Analysis**: Growth comparison between 2024 and 2025

### 🔍 Interactive Filtering
- Filter by branch (all branches or individual locations)
- Filter by channel (All, Self Delivery, or Online Web)
- Filter by metric (Sales or Orders)
- Search functionality for table data

### 📈 Performance Metrics
- **KPI Cards**: Total sales and orders for 2024 and 2025
- **Growth Calculations**: Automatic percentage growth calculations
- **Average Order Value (AOV)**: Comparison of AOV between years
- **Performance Scorecards**: Best performer, growth leader, and efficiency champion

### 💾 Data Management
- **Add New Data**: Form to add new monthly records
- **Edit Records**: Inline editing of existing data
- **Delete Records**: Remove unwanted entries with confirmation
- **Export Options**: CSV export (with placeholders for PDF and Excel)

### 🧠 Insights Generation
- Automated analysis of sales performance
- Channel dominance identification
- Branch performance insights
- Seasonality analysis
- Growth trend recommendations

### 📱 Responsive Design
- Mobile-friendly interface
- Adaptive layouts for different screen sizes
- Touch-friendly controls

## Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional installations required

### Installation
1. Download the `index.html` file
2. Open the file in your web browser
3. The dashboard will load with sample data

### Usage
1. **View Overall Performance**: The dashboard opens with all data displayed
2. **Filter Data**: Use the dropdown menus to filter by branch, channel, or metric
3. **Search Table**: Use the search box to find specific records in the table
4. **Add Data**: Scroll to the bottom and use the "Add New Data" form
5. **Edit/Delete**: Use the action buttons in the table to modify existing records
6. **Generate Insights**: Click the "Generate Insights" button for automated analysis
7. **Export Data**: Use the export buttons to download data in various formats

## Data Structure

The dashboard uses a simple data structure with the following fields for each record:

```javascript
{
  m: 1,              // Month number (1-12)
  month: 'Jan',      // Month name
  branch: 'Hamdan St', // Branch name
  channel: 'Self Delivery', // Sales channel
  s24: 130332,       // Sales for 2024
  s25: 119300,       // Sales for 2025
  o24: 2797,         // Orders for 2024
  o25: 2757          // Orders for 2025
}
