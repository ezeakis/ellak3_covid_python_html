# ellak3_covid_1

Το πρόγραμμα έχει τη δυνατότητα να λαμβάνει υπόψη του μία σειρά από δεδομένα για ένα άτομο και να εξάγει την πιθανότητα να έχει κορωνοϊό.

Χρησιμοποιήθηκαν Machine Learning packages της Python για την επεξεργασία των δεδομένων και HTML/CSS για την απεικόνιση

Δεν προκύπτει κόστος υλοποίησης.

Το αρχικό dataset ήταν [αυτό](https://github.com/ezeakis/ellak3_covid_python_html/blob/main/Covid%20Dataset.csv) το οποίο εντοπίσαμε [εδώ](https://www.kaggle.com/hemanthhari/symptoms-and-covid-presence)

Για τις ανάγκες του python κώδικα το μετατρέψαμε σε [αυτό](https://github.com/ezeakis/ellak3_covid_python_html/blob/main/Covid-Dataset-with-numbers.csv)

Κατά την τελική εκδοχή όμως περιορίσαμε τα συμπτώματα/πληροφορίες στα

Fever

Headache

Contact with COVID Patient

Family working in Public Exposed Places

Dry Cough

Breathing Problem

Wearing Masks 

και το dataset μας ήταν [αυτό](https://github.com/ezeakis/ellak3_covid_python_html/blob/main/Covid-Dataset-with-numbers-and-restricted-columns.csv)

Στον φάκελο final_flask_code βρίσκεται ο τελικός κώδικας ο οποίος μπορεί να χρησιμοποιηθεί για να σηκωθεί το flask service με την εντολή

python covid.py

Ο χρήστης μετά μπαίνει στη σελίδα

http://<host_ip_address>:81

και συμπληρώνει τα συμπτώματα
