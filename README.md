## Monthly Campaign Reporting ETL

# Overview

Using Python in Jupyter Notebook UI with pandas and numpy modules a monthly campaign report ETL process was generated. The end product was defined as a [Summary Table CSV File](https://github.com/Trevor-Jackson94/movio_monthly_campaign_report_etl/blob/main/monthly_campaigns_summary.csv) with the following columns created:
- campaign_id (int)
- campaign_description (string)
- campaign_date (date)
- campaign_target_count (int)
- campaign_control_count (int)
- campaign_has_control_group (bool)
- campaign_unique_email_opens (int)
- campaign_unique_link_clicks (int)
- campaign_target_total_spend (float)
- campaign_target_total_admissions (int)
- campaign_target_box_office_spend (float)
- campaign_target_concession_spend (float)
- campaign_control_total_spend (float)
- campaign_control_total_admissions (int)
- campaign_target_spend_per_moviegoer (float)
- campaign_control_spend_per_moviegoer (float)
- campaign_spend_uplift_per_moviegoer (float)

The following metadata tables were used to produce the final summary table:
- campaigns.csv
- email_interactions.csv
- target_profiles.csv
- targeted_moviegoers.csv
- transaction_lines.csv

The final ETL code can be found in a Jupyter Notebook file [here.](https://github.com/Trevor-Jackson94/movio_monthly_campaign_report_etl/blob/main/Monthly_Campaign_Report.ipynb)

Thank you Bryan Smith and the Movio team for putting the project and allowing me to work with their data.
