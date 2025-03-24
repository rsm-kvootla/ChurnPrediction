## S-mobile

Dataset used to investigate opportunities to decrease customer churn at S-mobile. The sample consists of three parts:

1. A training sample with 682,500 observations and a 2% churn rate ("training == 1")
2. A test sample with 292,500 observations and a 2% churn rate ("training == 0")
3. A representative sample with 30,000 observations and a churn rate of 2% ("representative == 1")

You can download the dataset from the link below:

<a href="https://www.dropbox.com/scl/fi/pxuvd588f66kdo99hl91t/s_mobile_1M.parquet?rlkey=1dybd2o9isi1ipcdzkuk3866t&dl=1" target="_blank">    "https://www.dropbox.com/scl/fi/pxuvd588f66kdo99hl91t/s_mobile_1M.parquet?rlkey=1dybd2o9isi1ipcdzkuk3866t&dl=1
</a>

## Variables

* customer: Customer ID
* churn: Did consumer churn in the last 30 days? (yes or no)
* changer: % change in revenue over the most recent 4 month period
* changem: % change in minutes of use over the most recent 4 month period
* revenue: Mean monthly revenue in SGD
* mou: Mean monthly minutes of use
* overage: Mean monthly overage minutes
* roam: Mean number of roaming calls
* conference: Mean number of conference calls
* months: # of months the customer has had service with S-Mobile
* uniqsubs: Number of individuals listed on the customer account
* custcare: Mean number of calls to customer care 
* retcalls: Number of calls by the customer to the retention team
* dropvce: Mean number of dropped voice calls 
* eqpdays: Number of days customer has owned current handset
* refurb: Handset is refurbished (no or yes)
* smartphone: Handset is a smartphone (no or yes)
* creditr: High credit rating as opposed to medium or low (no or yes)
* mcycle: Subscriber owns a motorcycle (no or yes)
* car: Subscriber owns a car (no or yes)
* travel: Subscriber has traveled internationally (no or yes)
* region: Regions delineated by the 5 Community Development Council Districts (e.g., CS is Central Singapore)
* occupation: Categorical variable with 4 occupation levels (professional, student, retired, or other)
* training: 1 for training sample, 0 for test sample, NA for representative sample
* representative: 1 for representative sample, 0 for training and test sample
