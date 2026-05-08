# Uber Rides Analytics Dashboard
A Power BI report providing an end-to-end overview of Uber ride operations — tracking bookings, revenue, distance, vehicle types, and location trends.

## 📈 Key Metrics (KPI Cards)
 
| Metric | Description |
|--------|-------------|
| **Completed Bookings** | Total number of successfully completed rides |
| **Lost Bookings** | Rides that were cancelled or unfulfilled |
| **Revenue** | Total revenue generated across all rides |
| **Total Distance** | Cumulative distance covered across all trips |
| **Top Pickup Location** | Most frequent ride pickup point |
| **Top Drop Location** | Most frequent ride drop-off point |

## 🔧 Data Model
 
The report draws from the following tables/fields:
 
- **Uber** — Core rides table (`Vehicle Type`, `Pickup Location`, `Drop Location`)
- **Calender** — Date table (`Month`) for time-intelligence
- **Date Axis** — Custom axis table for the date slicer
- **Img** — Vehicle type image mapping table
- **_Measure** — Calculated measures including:
  - `Completed_Bookings`
  - `Lost_Bookings`
  - `Revenue`
  - `Total Distance`
  - `Booking_Count`
  - `Bookings_Remove_Status_Filter`
 
  - ## 🖼️ Assets
 
The report includes the following embedded images:

- Uber logo
- Vehicle type icons (sedan, intercity/comfort)
- Custom KPI background graphics

- ## 📄 License
 
This project is for educational/portfolio purposes. Uber branding assets belong to [Uber Technologies, Inc.](https://uber.com)
