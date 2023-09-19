# Hotel-Booking-Analysis-capstone-project

The project contains the real world data record of hotel bookings of a city and a resort hotel containing details like bookings, cancellations, guest details etc. from 2015 to 2017. In this project we are going to analyze Hotel Booking Data in order to find out valuable insights and give suggestions to increase revenue of hotels.

Programming Language : Python

Libraries used : Pandas, Numpy, Matplotlib, Seaborn

NoteBook : Google Colab

Dataset Source : Provided by Almabetter themself.

# Objective
We are provided with a hotel bookings dataset.

The main purpose of this study is to perform EDA on the given dataset and draw useful conclusions about the trends in hotel bookings and how factors that control hotel bookings influence each other.

# Dataset
We are given a hotel bookings dataset. This dataset contains booking information for a city hotel and a resort hotel. It contains the following features.

- hotel: Name of hotel ( City or Resort)
- is_canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)
- lead_time: time (in days) between booking transaction and actual arrival.
- arrival_date_year: Year of arrival
- arrival_date_month: month of arrival
- arrival_date_week_number: week number of arrival date.
- arrival_date_day_of_month: Day of month of arrival date
- stays_in_weekend_nights: No. of weekend nights spent in a hotel
- stays_in_week_nights: No. of weeknights spent in a hotel
- adults: No. of adults in single booking record.
- children: No. of children in single booking record.
- babies: No. of babies in single booking record. 
- meal: Type of meal chosen 
- country: Country of origin of customers (as mentioned by them)
- market_segment: What segment via booking was made and for what purpose.
- distribution_channel: Via which medium booking was made.
- is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for Yes)
- previous_cancellations: No. of previous canceled bookings.
- previous_bookings_not_canceled: No. of previous non-canceled bookings.
- reserved_room_type: Room type reserved by a customer.
- assigned_room_type: Room type assigned to the customer.
- booking_changes: No. of booking changes done by customers
- deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
- agent: Id of agent for booking
- company: Id of the company making a booking
- days_in_waiting_list: No. of days on waiting list.
- customer_type: Type of customer(Transient, Group, etc.)
- adr: Average Daily rate.
- required_car_parking_spaces: No. of car parking asked in booking
- total_of_special_requests: total no. of special request.
- reservation_status: Whether a customer has checked out or canceled,or not showed 
- reservation_status_date: Date of making reservation status.

-. Total number of rows in data: 119390
-.Total number of columns: 32

# Data Cleaning and Feature Engineering
i have dropped duplicates from data set children agent company dtype is float will convert to int using astype for total people stayed in the hotel i added adults children and babies to get total days of stay i had added weekday nights and weekend nights in adr column the min is in negative so drop from particular column

# conclusion
(1) 61% bookings are for City hotel and 39% bookings are for Resort hotel, therefore City Hotel is busier than Resort hotel. Also the overall average daily rate of City hotel is slightly higher than Resort hotel.
(2) Mostly guests stay for less than 5 days in hotel and for longer stays Resort hotel is preferred.
(3) Most of the guests came from european countries, with most of guests coming from Portugal.
(4) It's clearly seen that the most people preferred room is Type A, . Also, the average daily rate of type A rooms seems to be less. But, those whose average daily rate is higher i.e.(Type C,G,F,H) it's seen that preference is also less, hotel need to improve on this.
(5) Retention rate of both the hotel is very low need to think on that too.
(6) We should also target months between May to Aug. Those are peak month for Hotel revenue generation. 
(7) Within a month, average daily rate gradually increases as month ends, with small sudden rise on weekends.
(8) Couples are the most common guests for hotels, hence hotels can plan services according to couples needs to increase revenue.
(9) For customers, generally the longer stays (more than 15 days) can result in better deals in terms of low average daily rate.
(10) November, December, January and February are the months which has least bookings so in this periods you can get rooms with less average daily rate.
And many more conclusion
