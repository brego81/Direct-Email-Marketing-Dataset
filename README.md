# Direct Email Marketing optimisation with a Random Forest based approach 
*Giulia De Poli, Maria Angélica Lobo Paulino, Stefania Tola, Manuela Bazzarelli, Leone De Marco and Matteo Bregonzio* 
**ICDSST 2020, Zaragoza, Spain**

This dataset sample has been used in our ICDSST 2020 publication and contains the pre-processed data relevant to the class upgrade campaign for a single company. 
The dataset contains a set of features used to profile the user and another set to describe the campaign. The former is an aggregation of all user’s data collected just before sending the class upgrade marketing email. The second contains the characteristics of the marketing email itself. The challenge consists of predicting whether a user will actually purchase the class upgrade after receiving a marketing email. In the dataset the target variable is called 'success'. Please note that each row represents a single user however the user ID has been omitted since irrelevant for this task. Here follows a brief description dataset features.

* **Previous purchase and general user information from CRM:** 
	* age:  The user age
	* n_purchase: Amount of purchase done from the user 
	* discount_purchase: Amount of purchase using a promo code 
	* n_reward: Amount of purchase using loyalty reward points 
	* n_environmet: Number of trips done in the given environment 
	* avg_npassengers: Average amount of passengers per trip 
	* avg_price: Average tickets price 
	* sdt_dev_price: Standart deviation from the tickets price 
	* avg_distance: Average travel distance 
	* sdt_dev_distance: Standart deviation from the travel 
	* since_last_purchase: Amount of days since the last purchase 
* **Email interaction information:** 
	* n_sent_campaign: Amount of sent emails from the given campaign 
	* n_open_campaign: Amount of open emails from the given campaign 
	* avg_opens_campaign: Average amount of times the user opens the campaign email 
	* n_click_campaign: Amount of emails from campaign “Reminder” that had its link clicked 
	* avg_clicks_reminder: Average amount of times the user clicks the link in the campaign email 
* **Web navigation collected from Analytics:** 
	* n_sessions: Total amount of sessions 
	* n_bounces: Total amount of bounces 
	* n_hits: Total amount of hits given by the user 
	* avg_hits: Average amount of hits per session 
	* total_session_duration 
	* avg_session_duration: Average sessions duration 
	* total_revenue: Total revenue gotten by the user 
	* avg_revenue: Average revenue per session 
	* conversions: Total number of conversions done by the user 
	* avg_conversion: Average conversions per session 
	* n_search: Number of different researches done by the user 
	* n_path: Number of different paths searched by the user 
* **Description of the current trip to upgrade:** 
	* price: Original ticket price 
	* is_second_class: Boolean value to inform if the ticket were initially second class 
	* distance: Linear distance between origin and destination 
	* days_2_trip: days between sending the email and the trip 
