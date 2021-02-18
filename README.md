# Kajabi
Data analyst project


75 rows of account found to be duplicates
 research why they are being duplicated
 
 assumed if trial activity mins was empty then it would be 0
 
 logins for 5 accts were outliers
 
 Assumed if NULL then no for columns created_offer_durring_trial and uploaded_video_durring_trial

Canceled dates filtered < jan 2021. An account is not considered churned until canceled date = now() because there is time to win back the customer.
