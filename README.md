# Kajabi
Data analyst project

Changed table name data_analyst_challenge to member_a

75 rows duplicated
 --research why they are being duplicated
 
Assumed if trial activity mins was NULL then it would be 0
 
 
 Assumed if NULL then no for columns created_offer_durring_trial and uploaded_video_durring_trial

Canceled dates filtered > jan 2021. An account is not considered churned until canceled date = now() because there is time to win back the customer.

Accounts canceled 4+ months and not activated. Data seems off.

5 accounts with logins way beyond outlier.
