
# Ola Data Analytics — Bengaluru (Oct 2025) (Synthetic)

**One-line:** Synthetic Ola-like trips dataset for Bengaluru — 100k rows for analytics, SQL practice, and Power BI dashboards.

## Overview
This project contains a synthetic dataset that models Ola ride-bookings in Bengaluru for October 2025 (31 days). Useful for exploratory data analysis, SQL practice, Power BI visualizations and demo portfolio.

## Dataset
- Filename: `ola Project csv File 1000`
- Rows: 100,000
- Columns: Date, Time, Booking_ID, Booking_Status, Customer_ID, Vehicle_Type, Pickup_Location, Drop_Location, V_TAT, C_TAT, Cancelled_Rides_by_Customer, Reason_for_cancelling_by_Customer, Cancelled_Rides_by_Driver, Cancelled_Rides_by_Driver_Reason, Incomplete_Rides, Incomplete_Rides_Reason, Booking_Value, Payment_Method, Ride_Distance, Driver_Ratings, Customer_Rating
- Month: October 2025 (match days boosted: Oct 9, Oct 19)
- License: CC-BY-NC (or select whichever you prefer) — document in LICENSE.

## Key constraints enforced
- Overall Success rate: **62%**
- Cancel by customer ≤ **7%**
- Cancel by driver ≤ **18%**
- Incomplete < **6%**
- Weekend & match-day order volume increased
- Booking_ID pattern: `CNR##########` (10 digits after CNR)
- Booking values distribution: ≤500 (70%), 501–1000 (28%), >1000 (2%)

## Quick usage
Clone repo, create venv & install:
```bash
git clone git@github.com:<your-username>/<repo>.git
cd <repo>
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
