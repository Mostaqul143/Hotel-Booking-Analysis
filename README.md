# Hotel-Booking-Analysis


**Hotel Bookings Dataset :**

This dataset contains information about hotel bookings, including hotel types, booking dates, and customer demographics. The dataset includes 119,390 records and 32 features.



# Data Description :


The dataset contains the following features:

hotel: the type of hotel (City Hotel or Resort Hotel)
is_canceled: whether the booking was cancelled (1) or not (0)
lead_time: the number of days between the booking date and the arrival date
arrival_date_year: the year of arrival date
arrival_date_month: the month of arrival date
arrival_date_week_number: the week number of arrival date
arrival_date_day_of_month: the day of month of arrival date
stays_in_weekend_nights: number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
stays_in_week_nights: number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
adults: number of adults
children: number of children
babies: number of babies
meal: type of meal booked
country: country of origin of the guest
market_segment: market segment designation
distribution_channel: booking distribution channel
is_repeated_guest: whether the booking was made by a repeated guest (1) or not (0)
previous_cancellations: number of previous bookings that were cancelled by the customer prior to the current booking
previous_bookings_not_canceled: number of previous bookings that were not cancelled by the customer prior to the current booking
reserved_room_type: type of room reserved
assigned_room_type: type of room assigned to the customer
booking_changes: number of changes made to the booking
deposit_type: type of deposit made for the booking
agent: ID of the travel agency that made the booking
company: ID of the company/entity that made the booking or responsible for payment
days_in_waiting_list: number of days the booking was in the waiting list before it was confirmed to the customer
customer_type: type of booking (contract, group, transient, or transient-party)
adr: average daily rate, calculated by dividing the total booking revenue by the total number of stay days
required_car_parking_spaces: number of car parking spaces required by the customer
total_of_special_requests: number of special requests made by the customer
reservation_status: current status of the booking (cancelled, checked-in, or checked-out)
reservation_status_date: date at which the current status was set




Data Preprocessing:



The following preprocessing steps were performed on the dataset:

Missing values were imputed using the median for numerical columns and the mode for categorical columns

Outliers were removed from the 'adr' column using the IQR method

Categorical columns were one-hot encoded

Date columns were converted to datetime format




Exploratory Data Analysis:




The following visualizations were created to explore the data:

Bar chart showing the number of bookings per month

Box plot showing the average daily rate per hotel type

Scatter plot showing the relationship between the number of children and the total nights stayed

Stacked bar chart showing the reason for cancellation

Stacked bar chart showing the number of cancelled vs. non-cancelled
