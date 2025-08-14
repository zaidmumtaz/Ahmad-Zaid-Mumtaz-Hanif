# Ahmad-Zaid-Mumtaz-Hanif
Data Analyst - Technical Test - Zaid

Tahapan dalam mengakses query SQL :

📍 Custom Query di BigQuery:
	1.	Masuk BigQuery Console:
[https://console.cloud.google.com/bigquery](https://console.cloud.google.com/bigquery?inv=1&invt=Ab5afA&authuser=4&project=technical-test-data-analyst&supportedpurview=project&ws=!1m20!1m4!4m3!1stechnical-test-data-analyst!2scards_data!3scards_data!1m4!4m3!1stechnical-test-data-analyst!2scards_data!3susers_data!1m4!4m3!1stechnical-test-data-analyst!2scards_data!3stransactions_data!1m4!1m3!1stechnical-test-data-analyst!2sbquxjob_5b3ccce6_198a2c1c955!3sasia-southeast2)
	2.	Masukkan syntax query SQL seperti berikut:

SELECT * FROM `technical-test-data-analyst.cards_data.users_data`
join `technical-test-data-analyst.cards_data.cards_data`
on `technical-test-data-analyst.cards_data.users_data`.id = `technical-test-data-analyst.cards_data.cards_data`.client_id
join `technical-test-data-analyst.cards_data.transactions_data`
on `technical-test-data-analyst.cards_data.users_data`.id = `technical-test-data-analyst.cards_data.transactions_data`.client_id
