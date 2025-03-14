# Naas Templates [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
(aka the "awesome-notebooks") 


## What is Naas ?

Naas is an all-in-one data platform that enable anyone with minimal technical knowledge to turn <a href="https://jupyter.org" target="_blank">Jupyter Notebooks</a> into powerful automation, analytical and AI data products thanks to <a href="https://docs.naas.ai/" target="_blank">low-code formulas</a> and microservices.<br>

The platform is based on 3 low-code layers:<br>
- **😎 Templates**: enable anyone to use data engines on all kind of subjects in minutes.
- **🏎 Drivers**: connectors to facilitate access to tools, and complex libraries (database, API, ML algorithm...)
- **🪐 Features**: production microservices on top of Jupyter like scheduling, asset sharing, notifications and more.<br>

Naas Cloud is free to use with 100 credits/month.<br>
<a href="https://www.naas.ai/free-forever" target="_blank">Open your account</a><br>

[>> More information](https://docs.naas.ai/)


## What is the objective of this repository ?

The objective of this repository is to create the largest catalog of production-ready Jupyter Notebooks templates. With those templates, it becomes easy to create data products (analytical dashboards, automation/AI engines and more). Check out the [data-product-template](https://github.com/jupyter-naas/data-product-template) repository to learn more.<br>
The repository is organized by source/tools for easy discovery. You can also use our ["Google-like" search](http://search.live.kn.naas.ai/) to find templates by keywords<br>

To ensure the quality of the templates, we have defined a framework. Each notebook shall be organized with the following sections:  
- **Naas logo**
- **# Title**: "Tool - Action of the notebook", as h1 (an "Open in Naas" button will be automatically added by the CI/CD when a notebook is merged to the master branch)
- **Tags**: hastags of the topics the notebook is about, as text
- **Author**: name and social profile link of the author(s), as text
- **Description**: a one-liner explaining the benefits of the notebooks for the user, as text
- **## Input**: list of all the variables, credentials, that needs to be setup, as h2
- **## Model**: list the functions applied to the data, as h2
- **## Output**: list the assets to be used by the user and its distribution channels if any, as h2


## How to contribute ?

### Pre-requisites:
- Open free account on [Naas Cloud](https://www.naas.ai/free-forever) so we can test the templates in a similar environment 
- Register to the [Contributor Program](https://form.typeform.com/to/jdls9qZf?typeform-source=www.naas.ai) so we can add you to team of contributors in the Naas GitHub organization 
- Join our [Slack Community](https://join.slack.com/t/naas-club/shared_invite/zt-1970s5rie-dXXkigAdEJYc~LPdQIEaLA) so you can present yourself and #chat with us

### Step by step process:

- **Step 1**: Find or propose an issue you want to work on
  - The Backlog of the [Product Roadmap](https://github.com/orgs/jupyter-naas/projects/10) is where we put all the priorities
  - The [Issues](https://github.com/jupyter-naas/awesome-notebooks/issues) section is where we gather all the needs 
- **Step 2**: Prepare the issue before you start working on it
  - Make sure the description is clear
  - Tag yourself in Assignees section
  - Change the status to 'In Progress' in Projects section/Community Roadmap
  - Create a branch in Development section 
- **Step 3**: Clone the awesome-notebooks repository on your Naas Cloud account and switch to the branch you created
- **Step 4**: Create folder named with the source tool (if it's not already created)
- **Step 5**: Copy/Paste template.ipynb at the root of the folder inside the folder you are working on, and start working on your notebook
- **Step 6**: Once you are happy with the result, commit to the branch by using Git extension or command line (make sure you use a GitHub personal access token and not password, otherwise it wont work)
- **Step 7**: Open a Pull Request and add a member of the core team as Reviewer ([Florent](https://github.com/FlorentLvr),[Maxime](https://github.com/Dr0p42) or [Jeremy](https://github.com/jravenel))
- **Step 8**: Change status of this Issue to “Review” in Projects section and comment the Pull Request with a brief on what you have done
- **Step 9**: Expect a feedback and merge in the next 48h-72h
- **Step 10**: Once merged, promote your work on LinkedIn, Twitter and other social media channels! (Optional, but people need to know you are awesome 😉)

[>> More information](https://docs.naas.ai/contributing-to-naas)


## Support on social media
We are committed to sharing templates and giving shout outs to the contributors on our social media platforms, you can support us on:
- [Twitter](https://twitter.com/JupyterNaas) for fast updates<br>
- [LinkedIn](https://www.linkedin.com/company/naas-ai/) for more elaborated posts and articles<br>
- [Youtube](https://www.youtube.com/channel/UCKKG5hzjXXU_rRdHHWQ8JHQ/videos) for demos and tutorials<br>

# Template analytics

![Templates_monthly](https://public.naas.ai/bWV0cmljcy00MG5hYXMtMkVhaQ==/asset/09d0bd9ed8ac2479a2a4f05e60c74d101d140ffdfacd9b0ac7bbb4e53966.png)

# Templates list


## AWS
* [Daily biling notification to slack](https://github.com/jupyter-naas/awesome-notebooks/blob/master/AWS/AWS_Daily_biling_notification_to_slack.ipynb)
* [Get files from S3 bucket](https://github.com/jupyter-naas/awesome-notebooks/blob/master/AWS/AWS_Get_files_from_S3_bucket.ipynb)
* [Read dataframe from S3](https://github.com/jupyter-naas/awesome-notebooks/blob/master/AWS/AWS_Read_dataframe_from_S3.ipynb)
* [Send dataframe to S3](https://github.com/jupyter-naas/awesome-notebooks/blob/master/AWS/AWS_Send_dataframe_to_S3.ipynb)
* [Upload file to S3 bucket](https://github.com/jupyter-naas/awesome-notebooks/blob/master/AWS/AWS_Upload_file_to_S3_bucket.ipynb)

## Abstract API
* [Check Email Validation](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Abstract%20API/Abstract_API_Check_Email_Validation.ipynb)
* [Get IP Geolocation](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Abstract%20API/Abstract_API_Get_IP_Geolocation.ipynb)

## Advertools
* [Analyze website content using XML sitemap](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Advertools/Advertools_Analyze_website_content_using_XML_sitemap.ipynb)
* [Audit robots txt and xml sitemap issues](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Advertools/Advertools_Audit_robots_txt_and_xml_sitemap_issues.ipynb)
* [Check status code and Send report by email](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Advertools/Advertools_Check_status_code_and_Send_notifications.ipynb)
* [Check status code in bulk](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Advertools/Advertools_Check_status_code_in_bulk.ipynb)
* [Crawling a website](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Advertools/Advertools_Crawl_a_website.ipynb)
* [Visualize status codes OK and KO](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Advertools/Advertools_Visualize_status_codes_OK_KO.ipynb)
* [Visualize status codes count](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Advertools/Advertools_Visualize_status_codes_count.ipynb)

## Affinity
* [Sync with Notion database](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Affinity/Affinity_Sync_with_Notion_database.ipynb)

## Agicap
* [Export treasury plan](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Agicap/Agicap_Export_treasury_plan.ipynb)
* [Export treasury plan by account](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Agicap/Agicap_Export_treasury_plan_by_account.ipynb)
* [Get banks accounts from company](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Agicap/Agicap_Get_banks_accounts_from_company.ipynb)
* [Get inflow categories from company](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Agicap/Agicap_Get_inflow_categories_from_company.ipynb)
* [Get outflow categories from company](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Agicap/Agicap_Get_outflow_categories_from_company.ipynb)
* [List companies](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Agicap/Agicap_List_companies.ipynb)

## Airtable
* [Delete data](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Airtable/Airtable_Delete_data.ipynb)
* [Get data](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Airtable/Airtable_Get_data.ipynb)
* [Insert data](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Airtable/Airtable_Insert_data.ipynb)
* [Search data](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Airtable/Airtable_Search_data.ipynb)

## Algolia
* [Add or Replace all attributes in existing records](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Algolia/Algolia_Add_or_Replace_all_attributes_in_existing_records.ipynb)
* [Add or Replace all attributes in a single record](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Algolia/Algolia_Add_or_Replace_all_attributes_in_single_record.ipynb)
* [Delete multiples objects](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Algolia/Algolia_Delete_multiples_objects.ipynb)
* [Delete a single object](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Algolia/Algolia_Delete_single_object.ipynb)
* [Get all records from an index](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Algolia/Algolia_Get_all_records_from_an_index.ipynb)
* [List indices](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Algolia/Algolia_List%20indices.ipynb)

## AlphaVantage
* [Get balance sheet](https://github.com/jupyter-naas/awesome-notebooks/blob/master/AlphaVantage/AlphaVantage_Get_balance_sheet.ipynb)
* [Get cashflow statement](https://github.com/jupyter-naas/awesome-notebooks/blob/master/AlphaVantage/AlphaVantage_Get_cashflow_statement.ipynb)
* [Get company overview](https://github.com/jupyter-naas/awesome-notebooks/blob/master/AlphaVantage/AlphaVantage_Get_company_overview.ipynb)
* [Get income statement](https://github.com/jupyter-naas/awesome-notebooks/blob/master/AlphaVantage/AlphaVantage_Get_income_statement.ipynb)

## Azure Blob Storage
* [List blobs](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Azure%20Blob%20Storage/Azure_Blob_Storage_List_blobs.ipynb)
* [Upload files](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Azure%20Blob%20Storage/Azure_Blob_Storage_Upload_files.ipynb)

## Azure Machine Learning
* [Univariate Timeseries Inference](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Azure%20Machine%20Learning/Azure_Machine_Learning_Univariate_Timeseries_Inference.ipynb)

## Bazimo
* [Get export Actifs](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Bazimo/Bazimo_Get_export_Actifs.ipynb)
* [Get export Baux](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Bazimo/Bazimo_Get_export_Baux.ipynb)
* [Get export Factures](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Bazimo/Bazimo_Get_export_Factures.ipynb)
* [Get export Locataires](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Bazimo/Bazimo_Get_export_Locataires.ipynb)
* [Get export Lots](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Bazimo/Bazimo_Get_export_Lots.ipynb)

## BeautifulSoup
* [List social network links from website](https://github.com/jupyter-naas/awesome-notebooks/blob/master/BeautifulSoup/BeautifulSoup_List_social_network_links_from_website.ipynb)
* [Scrape emails from URL](https://github.com/jupyter-naas/awesome-notebooks/blob/master/BeautifulSoup/BeautifulSoup_Scrape_emails_from_URL.ipynb)

## BigQuery
* [Create table from csv](https://github.com/jupyter-naas/awesome-notebooks/blob/master/BigQuery/BigQuery_Create_table_from_csv.ipynb)
* [Read Table](https://github.com/jupyter-naas/awesome-notebooks/blob/master/BigQuery/BigQuery_Read_Table.ipynb)

## Bitly
* [Create Links](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Bitly/Bitly_Create_Links.ipynb)
* [Delete a Bitlink](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Bitly/Bitly_Delete_a_Bitlink.ipynb)
* [Get Clicks for a Bitlink](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Bitly/Bitly_Get_Clicks_for_a_Bitlink.ipynb)
* [Get Metrics for a Bitlink by City](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Bitly/Bitly_Get_Metrics_for_a_Bitlink_by_City.ipynb)
* [Get Metrics for a Bitlink by Country](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Bitly/Bitly_Get_Metrics_for_a_Bitlink_by_Country.ipynb)
* [Get Metrics for a Bitlink by Devices](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Bitly/Bitly_Get_Metrics_for_a_Bitlink_by_Devices.ipynb)
* [Get Metrics for a Bitlink by Referrers](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Bitly/Bitly_Get_Metrics_for_a_Bitlink_by_Referrers.ipynb)
* [Get a Clicks Summary for a Bitlink](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Bitly/Bitly_Get_a_Clicks_Summary_for_a_Bitlink.ipynb)
* [Retrieve Bitlink](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Bitly/Bitly_Retrieve_Bitlink.ipynb)
* [Update a Bitlink](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Bitly/Bitly_Update_a_Bitlink.ipynb)

## Boursorama
* [Get CDS](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Boursorama/Boursorama_Get_CDS.ipynb)
* [Get EURIBOR 3 MOIS](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Boursorama/Boursorama_Get_EURIBOR_3_MOIS.ipynb)

## Bubble
* [Send data](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Bubble/Bubble_Send_data.ipynb)

## CCXT
* [Calculate Support and Resistance](https://github.com/jupyter-naas/awesome-notebooks/blob/master/CCXT/CCXT_Calculate_Support_and_Resistance.ipynb)
* [Predict Bitcoin from Binance](https://github.com/jupyter-naas/awesome-notebooks/blob/master/CCXT/CCXT_Predict_Bitcoin_from_Binance.ipynb)

## Canny
* [Create](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Canny/Canny_Create.ipynb)
* [Github issue update](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Canny/Canny_Github_issue_update.ipynb)
* [Read](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Canny/Canny_Read.ipynb)

## Celestrak
* [Satellites over time](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Celestrak/Celestrak_Satellites_over_time.ipynb)

## Cityfalcon
* [Get data from API](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Cityfalcon/Cityfalcon_Get_data_from_API.ipynb)

## Clockify
* [Add a new client](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Clockify/Clockify_Add_a_new_client.ipynb)
* [Add a new project](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Clockify/Clockify_Add_a_new_project.ipynb)
* [Create time entries database on a workspace](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Clockify/Clockify_Create_time_entries_database_on_workspace.ipynb)
* [Delete client](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Clockify/Clockify_Delete_client.ipynb)
* [Delete project](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Clockify/Clockify_Delete_project.ipynb)
* [Find all users on workspace](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Clockify/Clockify_Find_all_users_on_workspace.ipynb)
* [Find clients on workspace](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Clockify/Clockify_Find_clients_on_workspace.ipynb)
* [Find tasks on project](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Clockify/Clockify_Find_tasks_on_project.ipynb)
* [Get all my workspaces](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Clockify/Clockify_Get_all_my_workspaces.ipynb)
* [Get all projects on workspace](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Clockify/Clockify_Get_all_projects_on_workspace.ipynb)
* [Get client by ID](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Clockify/Clockify_Get_client_by_ID.ipynb)
* [Get project by ID](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Clockify/Clockify_Get_project_by_ID.ipynb)
* [Get time entries for a user on workspace](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Clockify/Clockify_Get_time_entries_for_a_user_on_workspace.ipynb)
* [Remove user from workspace](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Clockify/Clockify_Remove_user_from_workspace.ipynb)
* [Update client](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Clockify/Clockify_Update_client.ipynb)
* [Update project](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Clockify/Clockify_Update_project.ipynb)

## Cloud Mercato
* [Compare VM pricing](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Cloud%20Mercato/Cloud_Mercato_Compare_VM_pricing.ipynb)

## Creditsafe
* [Get Company Credit Report](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Creditsafe/Creditsafe_Get_Company_Credit_Report.ipynb)

## D-Tale
* [Visualize dataframe](https://github.com/jupyter-naas/awesome-notebooks/blob/master/D-Tale/D-Tale_Visualize_dataframe.ipynb)

## Dash
* [Add a customisable sidebar](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_Add_a_customisable_sidebar.ipynb)
* [Create Datatable With Dropdown](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_Create_Datatable_With_Dropdown.ipynb)
* [Create Dropdown Callback](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_Create_Dropdown_Callback.ipynb)
* [Create Dropdown with multiples output callbacks](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_Create_Dropdown_with_multiples_output_callbacks.ipynb)
* [Create Interactive Plot](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_Create_Interactive_Plot.ipynb)
* [Create Navbar](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_Create_Navbar.ipynb)
* [Create Navbar board](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_Create_Navbar_Dashboard.ipynb)
* [Create Navbar Search](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_Create_Navbar_Search.ipynb)
* [Create button to refresh page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_Create_button_to_refresh_page.ipynb)
* [Create conditional formatting on HTML element](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_Create_conditional_formatting_on_HTML_element.ipynb)
* [Create conditional formatting on number value](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_Create_conditional_formatting_on_number_value.ipynb)
* [Create download button](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_Create_download_button.ipynb)
* [Create loading button](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_Create_loading_button.ipynb)
* [Create spinner button](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_Create_spinner_button.ipynb)
* [Deploy app in Naas](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_Deploy_app_in_Naas.ipynb)
* [LinkedIn posts metrics dashboard](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_LinkedIn_posts_metrics_dashboard.ipynb)
* [Plotly Dynamic Link](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_Plotly_Dynamic_Link.ipynb)
* [Upload mutiples CSV Excel](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dash/Dash_Upload_mutiples_CSV_Excel.ipynb)

## Dask
* [Parallelize operations on multiple csvs](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Dask/Dask_parallelize_operations_on_multiple_csvs.ipynb)

## Data.gouv.fr
* [COVID19 -  FR - Entrées et sorties par région pour 1 million d'hab.](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Data.gouv.fr/COVID19%20-%20%20FR%20-%20Entr%C3%A9es%20et%20sorties%20par%20r%C3%A9gion%20pour%201%20million%20d%27hab..ipynb)
* [Récupération données légales entreprise](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Data.gouv.fr/Data.gouv.fr_R%C3%A9cup%C3%A9ration_donn%C3%A9es_l%C3%A9gales_entreprise.ipynb)

## Datetime
* [Calculate relative time delta between two dates](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Datetime/Datetime_Calculate_relative_time_delta_between_two_dates.ipynb)
* [Calculate time delta between two dates](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Datetime/Datetime_Calculate_time_delta_between_two_dates.ipynb)
* [Convert datetime object to a formatted date string](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Datetime/Datetime_Convert_datetime_object_to_string_date.ipynb)
* [Convert  with Timezone to ISO 8601 date string](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Datetime/Datetime_Convert_datetime_with_timezone_to_ISO_8601_date_string.ipynb)
* [Convert relative time delta to months](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Datetime/Datetime_Convert_relative_time_delta_to_months.ipynb)
* [Convert a string date to a datetime object](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Datetime/Datetime_Convert_string_to_datetime_object.ipynb)
* [Convert timestamp to a datetime object](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Datetime/Datetime_Convert_timestamp_to_a_datetime_object.ipynb)

## Deepl
* [Translated string to txt](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Deepl/Deepl_Translated_string_to_txt.ipynb)

## Draft Kings
* [Get MLB Moneylines](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Draft%20Kings/Draft_Kings_Get_MLB_Moneylines.ipynb)
* [Get NBA Moneylines](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Draft%20Kings/Draft_Kings_Get_NBA_Moneylines.ipynb)

## EM-DAT
* [Natural disasters](https://github.com/jupyter-naas/awesome-notebooks/blob/master/EM-DAT/EM-DAT_natural_disasters.ipynb)

## Elasticsearch
* [Connect to server](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Elasticsearch/Elasticsearch_Connect_to_server.ipynb)

## Excel
* [Apply Custom Styles](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Excel/Excel_Apply_Custom_Styles.ipynb)
* [Consolidate files](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Excel/Excel_Consolidate_files.ipynb)
* [Get dynamic active range](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Excel/Excel_Get_dynamic_active_range.ipynb)
* [List sheets in workbook](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Excel/Excel_List_sheets_in_workbook.ipynb)
* [Read file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Excel/Excel_Read_file.ipynb)
* [Save file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Excel/Excel_Save_file.ipynb)

## FAO
* [Consumer price indice](https://github.com/jupyter-naas/awesome-notebooks/blob/master/FAO/FAO_Consumer_price_indice.ipynb)

## FEC
* [Creer un dashboard PowerBI](https://github.com/jupyter-naas/awesome-notebooks/blob/master/FEC/FEC_Creer_un_dashboard_PowerBI.ipynb)
* [Lecture des fichiers](https://github.com/jupyter-naas/awesome-notebooks/blob/master/FEC/FEC_Lecture_des_fichiers.ipynb)
* [Visualiser Bilan Treemap](https://github.com/jupyter-naas/awesome-notebooks/blob/master/FEC/FEC_Visualiser_Bilan_Treemap.ipynb)
* [Visualiser Charges Horizontal Barchart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/FEC/FEC_Visualiser_Charges_Horizontal_Barchart.ipynb)
* [Visualiser Comparer Ventes Line Chart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/FEC/FEC_Visualiser_Comparer_Ventes_Line_Chart.ipynb)
* [Visualiser Trésorerie Barline Chart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/FEC/FEC_Visualiser_Tr%C3%A9sorerie_Barline_Chart.ipynb)

## FED
* [Visualize Inflation Rate](https://github.com/jupyter-naas/awesome-notebooks/blob/master/FED/FED_Visualize_Inflation_Rate.ipynb)

## FTP
* [S Connect](https://github.com/jupyter-naas/awesome-notebooks/blob/master/FTP/FTPS_Connect.ipynb)
* [Connect](https://github.com/jupyter-naas/awesome-notebooks/blob/master/FTP/FTP_Connect.ipynb)
* [Get file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/FTP/FTP_Get_file.ipynb)
* [Send file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/FTP/FTP_Send_file.ipynb)

## Faker
* [Anonymize Address from dataframe](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Faker/Faker_Anonymize_Address_from_dataframe.ipynb)
* [Anonymize Personal Names from dataframe](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Faker/Faker_Anonymize_Personal_Names_from_dataframe.ipynb)

## Formant
* [Query Device Network](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Formant/Formant_Query_Device_Network.ipynb)

## GitHub
* [Add new issues as page in Notion database](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Add_new_issues_as_page_in_Notion_database.ipynb)
* [Add new member to team](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Add_new_member_to_team.ipynb)
* [Add or update team membership for a user](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Add_or_update_team_membership_for_a_user.ipynb)
* [Clone open branches from repository on my local](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Clone_open_branches_from_repository_on_my_local.ipynb)
* [Clone repository](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Clone_repository.ipynb)
* [Clone repository and switch branch](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Clone_repository_and_switch_branch.ipynb)
* [Close issue](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Close_issue.ipynb)
* [Create Repo](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Create_Repo.ipynb)
* [Create an issue comment](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Create_an_issue_comment.ipynb)
* [Create issue](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Create_issue.ipynb)
* [Create leaderboard of contributors](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Create_leaderboard_of_contributors.ipynb)
* [Create newsletter based on repository activity](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Create_newsletter_based_on_repository_activity.ipynb)
* [Create pull request](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Create_pull_request.ipynb)
* [Create repository on personal account](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Create_repository_on_personal_account.ipynb)
* [Delete an issue comment](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Delete_an_issue_comment.ipynb)
* [Download Excel file from URL](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Download_Excel_file_from_URL.ipynb)
* [Download file from url](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Download_file_from_url.ipynb)
* [Download repository from URL](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Download_repository_from_URL.ipynb)
* [Follow stargazers trend](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Follow_stargazers_trend.ipynb)
* [Get DataFrame with issue estimate from project view](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Get_DataFrame_with_issue_estimate_from_project_view.ipynb)
* [Get Traffic Clones on repository](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Get_Traffic_Clones_on_repository.ipynb)
* [Get Traffic Views on repository](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Get_Traffic_Views_on_repository.ipynb)
* [Get a repository](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Get_a_repository.ipynb)
* [Get active projects](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Get_active_projects.ipynb)
* [Get commits from repository](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Get_commits_from_repository.ipynb)
* [List commits history from file path](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Get_commits_history_from_file_path.ipynb)
* [Get commits ranking from repository](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Get_commits_ranking_from_repository.ipynb)
* [Get files added on pull request](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Get_files_added_on_pull_request.ipynb)
* [Get files changed on pull request](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Get_files_changed_on_pull_request.ipynb)
* [Get issues from repo](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Get_issues_from_repo.ipynb)
* [Get most starred repos](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Get_most_starred_repos.ipynb)
* [Get open pull requests](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Get_open_pull_requests.ipynb)
* [Get profile from user](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Get_profile_from_user.ipynb)
* [Get profiles from teams](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Get_profiles_from_teams.ipynb)
* [Get team membership for a user](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Get_team_membership_for_a_user.ipynb)
* [Get weekly commits from repository](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Get_weekly_commits_from_repository.ipynb)
* [List all pull requests](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_List_all_pull_requests.ipynb)
* [List branches](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_List_branches.ipynb)
* [List branches with open PR](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_List_branches_with_open_PR.ipynb)
* [List closed pull requests](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_List_closed_pull_requests.ipynb)
* [List issue comments](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_List_issue_comments.ipynb)
* [List open pull requests](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_List_open_pull_requests.ipynb)
* [List organization repositories](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_List_organization_repositories.ipynb)
* [List pending team invitations](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_List_pending_team_invitations.ipynb)
* [List stargazers from repository](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_List_stargazers_from_repository.ipynb)
* [List team members](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_List_team_members.ipynb)
* [Peform basic actions](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Peform_basic_actions.ipynb)
* [Read issue](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Read_issue.ipynb)
* [Remove directories with branches closed on my local](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Remove_directories_with_branches_closed_on_my_local.ipynb)
* [Remove member from team](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Remove_member_from_team.ipynb)
* [Remove team membership for a user](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Remove_team_membership_for_a_user.ipynb)
* [Reopen issue](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Reopen_issue.ipynb)
* [Send contributor activity on slack](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Send_contributor_activity_on_slack.ipynb)
* [Send stargazers to Google Sheets](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Send_stargazers_to_Google_Sheets.ipynb)
* [Send templates created on a notebooks to Slack channel](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Send_templates_created_on_a_notebooks_to_Slack_channel.ipynb)
* [Track issues on projects](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Track_issues_on_projects.ipynb)
* [Track notebooks created over time](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Track_notebooks_created_over_time.ipynb)
* [Update issue](https://github.com/jupyter-naas/awesome-notebooks/blob/master/GitHub/GitHub_Update_issue.ipynb)

## Gmail
* [Automate response from keywords in mailbox](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Gmail/Gmail_Automate_response_from_keywords_in_mailbox.ipynb)
* [Clean mailbox](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Gmail/Gmail_Clean_mailbox.ipynb)
* [Create GitHub issue on specific email](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Gmail/Gmail_Create_GitHub_issue_on_specific_email.ipynb)
* [Create draft email](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Gmail/Gmail_Create_draft_email.ipynb)
* [Delete email from mailbox](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Gmail/Gmail_Delete_email_from_mailbox.ipynb)
* [Get emails by date](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Gmail/Gmail_Get_emails_by_date.ipynb)
* [Get emails stats by sender](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Gmail/Gmail_Get_emails_stats_by_sender.ipynb)
* [Get most common senders](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Gmail/Gmail_Get_most_common_senders.ipynb)
* [Get most important unseen emails](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Gmail/Gmail_Get_most_important_unseen_emails.ipynb)
* [Get seen emails](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Gmail/Gmail_Get_seen_emails.ipynb)
* [Get unseen emails](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Gmail/Gmail_Get_unseen_emails.ipynb)
* [Mark emails as seen by dates](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Gmail/Gmail_Mark_emails_as_seen_by_dates.ipynb)
* [Read mailbox](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Gmail/Gmail_Read_mailbox.ipynb)
* [Send email](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Gmail/Gmail_Send_email.ipynb)
* [Update email flag](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Gmail/Gmail_Update_email_flag.ipynb)

## Google Analytics
* [Follow average session duration daily](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Follow_average_session_duration_daily.ipynb)
* [Follow number of new visitors daily](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Follow_number_of_new_visitors_daily.ipynb)
* [Follow number of new visitors hourly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Follow_number_of_new_visitors_hourly.ipynb)
* [Follow number of new visitors monthly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Follow_number_of_new_visitors_monthly.ipynb)
* [Follow number of new visitors weekly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Follow_number_of_new_visitors_weekly.ipynb)
* [Follow number of sessions daily](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Follow_number_of_sessions_daily.ipynb)
* [Follow number of sessions hourly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Follow_number_of_sessions_hourly.ipynb)
* [Follow number of sessions monthly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Follow_number_of_sessions_monthly.ipynb)
* [Follow number of sessions weekly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Follow_number_of_sessions_weekly.ipynb)
* [Follow number of visitors daily](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Follow_number_of_visitors_daily.ipynb)
* [Follow number of visitors hourly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Follow_number_of_visitors_hourly.ipynb)
* [Follow number of visitors monthly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Follow_number_of_visitors_monthly.ipynb)
* [Follow number of visitors weekly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Follow_number_of_visitors_weekly.ipynb)
* [Get bounce rate](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Get_bounce_rate.ipynb)
* [Get pageview ranking](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Get_pageview_ranking.ipynb)
* [Get stats per country](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Get_stats_per_country.ipynb)
* [Get time on landing page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Get_time_on_landing_page.ipynb)
* [Get unique visitors](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Get_unique_visitors.ipynb)
* [Get unique visitors by country](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Get_unique_visitors_by_country.ipynb)
* [Send visitors traffic graph and trends prediction to Slack channel](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Analytics/Google_Analytics_Send_visitors_traffic_graph_and_trends_prediction_to_Slack_channel.ipynb)

## Google Calendar
* [Get calendar](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Calendar/Google_Calendar_Get_calendar.ipynb)
* [List calendars](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Calendar/Google_Calendar_List_calendars.ipynb)
* [List events from calendar](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Calendar/Google_Calendar_List_events_from_calendar.ipynb)

## Google Drive
* [Download file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Drive/Google_Drive_Download_file.ipynb)

## Google Maps
* [Calculate travel costs between two addresses](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Maps/Google_Maps_Calculate_travel_costs_between_two_addresses.ipynb)
* [Connect to Routes API](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Maps/Google_Maps_Connect_to_Routes_API.ipynb)
* [Get coordinates from address](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Maps/Google_Maps_Get_coordinates_from_address.ipynb)

## Google Search
* [Get LinkedIn company url from name](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Search/Google_Search_Get_LinkedIn_company_url_from_name.ipynb)
* [Get LinkedIn profile url from name](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Search/Google_Search_Get_LinkedIn_profile_url_from_name.ipynb)
* [Perform search](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Search/Google_Search_Perform_search.ipynb)

## Google Sheets
* [Add items to Notion databases from new rows in](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Sheets/Google_Sheets_Add_items_to_Notion_databases_from_new_rows_in_Google_Sheets.ipynb)
* [Add new github member to team from spreadsheet](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Sheets/Google_Sheets_Add_new_github_member_to_team_from_spreadsheet.ipynb)
* [Calculate distance and price](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Sheets/Google_Sheets_Calculate_Distance_and_Price.ipynb)
* [Get data](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Sheets/Google_Sheets_Get_data.ipynb)
* [Send LinkedIn invitations from spreadsheet](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Sheets/Google_Sheets_Send_LinkedIn_invitations_from_spreadsheet.ipynb)
* [Send data](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Sheets/Google_Sheets_Send_data.ipynb)
* [Send data to MongoDB](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Sheets/Google_Sheets_Send_data_to_MongoDB.ipynb)
* [Send emails from sheet](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Sheets/Google_Sheets_Send_emails_from_sheet.ipynb)

## Google Slides
* [Create a Slide](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Slides/Google_Slides_Create_a_Slide.ipynb)
* [Create a blank presentation](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Slides/Google_Slides_Create_a_blank_presentation.ipynb)
* [Duplicate slide](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Slides/Google_Slides_Duplicate_slide.ipynb)
* [List slides in presentation](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Slides/Google_Slides_List_slides_in_presentation.ipynb)
* [Replace text within a shape](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Google%20Slides/Google_Slides_Replace_text_within_a_shape.ipynb)

## HTML
* [Create a website](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HTML/HTML_Create_a_website.ipynb)

## Harvest
* [List all clients](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Harvest/Harvest_List_all_clients.ipynb)
* [List all time entries](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Harvest/Harvest_List_all_time_entries.ipynb)

## Healthchecks
* [Perfom basic actions](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Healthchecks/Healthchecks_Perfom_basic_actions.ipynb)

## HubSpot
* [Associate contact to deal](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Associate_contact_to_deal.ipynb)
* [Create Task](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Create_Task.ipynb)
* [Create contact](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Create_contact.ipynb)
* [Create contact from LinkedIn profile](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Create_contact_from_LinkedIn_profile.ipynb)
* [Create contacts from linkedin post likes](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Create_contacts_from_linkedin_post_likes.ipynb)
* [Create deal](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Create_deal.ipynb)
* [Create note](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Create_note.ipynb)
* [Delete Task](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Delete_Task.ipynb)
* [Delete contact](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Delete_contact.ipynb)
* [Delete deal](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Delete_deal.ipynb)
* [Delete note](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Delete_note.ipynb)
* [Get Task](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Get_Task.ipynb)
* [Get all contacts](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Get_all_contacts.ipynb)
* [Get all deals](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Get_all_deals.ipynb)
* [Get all pipelines and dealstages](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Get_all_pipelines_and_dealstages.ipynb)
* [Get contact from URL](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Get_contact_from_URL.ipynb)
* [Get contact from email](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Get_contact_from_email.ipynb)
* [Get contact from id](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Get_contact_from_id.ipynb)
* [Get contacts associated to deal](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Get_contacts_associated_to_deal.ipynb)
* [Get deal](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Get_deal.ipynb)
* [Get notes from contact](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Get_notes_from_contact.ipynb)
* [Send LinkedIn invitations from contacts](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Send_LinkedIn_invitations_from_contacts.ipynb)
* [Send closed deals weekly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Send_closed_deals_weekly.ipynb)
* [Send contacts to gsheet](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Send_contacts_to_gsheet.ipynb)
* [Send deals to gsheet](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Send_deals_to_gsheet.ipynb)
* [Send new deals created weekly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Send_new_deals_created_weekly.ipynb)
* [Send sales brief](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Send_sales_brief.ipynb)
* [Send sales pipeline to Notion](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Send_sales_pipeline_to_Notion.ipynb)
* [Update Task](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Update_Task.ipynb)
* [Update contact](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Update_contact.ipynb)
* [Update deal](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Update_deal.ipynb)
* [Update followers from linkedin](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Update_followers_from_linkedin.ipynb)
* [Update jobtitle country industry from linkedin](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Update_jobtitle_country_industry_from_linkedin.ipynb)
* [Update linkedinbio from google](https://github.com/jupyter-naas/awesome-notebooks/blob/master/HubSpot/HubSpot_Update_linkedinbio_from_google.ipynb)

## Hugging Face
* [Ask boolean question to T5](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Hugging%20Face/Hugging_Face_Ask_boolean_question_to_T5.ipynb)
* [Naas drivers integration](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Hugging%20Face/Hugging_Face_Naas_drivers_integration.ipynb)
* [Question Answering from PDF](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Hugging%20Face/Hugging_Face_Question_Answering_from_PDF.ipynb)

## IFTTT
* [Post on Twitter](https://github.com/jupyter-naas/awesome-notebooks/blob/master/IFTTT/IFTTT_Post_on_Twitter.ipynb)
* [Trigger workflow](https://github.com/jupyter-naas/awesome-notebooks/blob/master/IFTTT/IFTTT_Trigger_workflow.ipynb)

## IMDB
* [Top  Movie](https://github.com/jupyter-naas/awesome-notebooks/blob/master/IMDB/Top_IMDB_Movie.ipynb)

## INPI
* [Download PDF recap](https://github.com/jupyter-naas/awesome-notebooks/blob/master/INPI/INPI_Download_PDF_recap.ipynb)

## IPyWidgets
* [Create button](https://github.com/jupyter-naas/awesome-notebooks/blob/master/IPyWidgets/IPyWidgets_Create_button.ipynb)
* [Create input text and submit button](https://github.com/jupyter-naas/awesome-notebooks/blob/master/IPyWidgets/IPyWidgets_Create_input_text_and_submit_button.ipynb)
* [Setup naas secret](https://github.com/jupyter-naas/awesome-notebooks/blob/master/IPyWidgets/IPyWidgets_Setup_naas_secret.ipynb)

## IUCN
* [Extinct species](https://github.com/jupyter-naas/awesome-notebooks/blob/master/IUCN/IUCN_Extinct_species.ipynb)

## Insee
* [Download PDF recap](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Insee/Insee_Download_PDF_recap.ipynb)

## Instagram
* [Get stats from posts](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Instagram/Instagram_Get_stats_from_posts.ipynb)
* [Post image and caption](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Instagram/Instagram_Post_image_and_caption.ipynb)

## Integromat
* [Trigger workflow](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Integromat/Integromat_Trigger_workflow.ipynb)

## Johns Hopkins
* [Covid19 Active Cases](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Johns%20Hopkins/Johns_Hopkins_Covid19_Active_Cases.ipynb)
* [Get Covid19 data](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Johns%20Hopkins/Johns_Hopkins_Get_Covid19_data.ipynb)

## Jupyter Notebooks
* [Add cells in notebook json](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Jupyter%20Notebooks/Jupyter_Notebooks_Add_cells_in_notebook_json.ipynb)
* [Add tags in cells](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Jupyter%20Notebooks/Jupyter_Notebooks_Add_tags_in_cells.ipynb)
* [Apply black on notebook file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Jupyter%20Notebooks/Jupyter_Notebooks_Apply_black_on_notebook_file.ipynb)
* [Count code characters](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Jupyter%20Notebooks/Jupyter_Notebooks_Count_code_characters.ipynb)
* [Count code lines](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Jupyter%20Notebooks/Jupyter_Notebooks_Count_code_lines.ipynb)
* [Get installs](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Jupyter%20Notebooks/Jupyter_Notebooks_Get_installs.ipynb)
* [Get libraries](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Jupyter%20Notebooks/Jupyter_Notebooks_Get_libraries.ipynb)
* [Read file json](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Jupyter%20Notebooks/Jupyter_Notebooks_Read_file_json.ipynb)
* [Save file ipynb](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Jupyter%20Notebooks/Jupyter_Notebooks_Save_file_ipynb.ipynb)

## Jupyter
* [Get server uptime](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Jupyter/Jupyter_Get_server_uptime.ipynb)
* [Get user information](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Jupyter/Jupyter_Get_user_information.ipynb)
* [Get user session](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Jupyter/Jupyter_Get_user_session.ipynb)
* [Get user terminal](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Jupyter/Jupyter_Get_user_terminal.ipynb)
* [Restart server](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Jupyter/Jupyter_Restart_server.ipynb)

## Kaggle
* [Download Data](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Kaggle/Kaggle_Download_Data.ipynb)

## Knative
* [Create command file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Knative/Knative_Create_command_file.ipynb)

## LangChain
* [CSV Agent](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LangChain/LangChain_CSV_Agent.ipynb)
* [Gmail Toolkit](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LangChain/LangChain_Gmail_Toolkit.ipynb)
* [JSON Agent](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LangChain/LangChain_JSON_Agent.ipynb)
* [Pandas Dataframe Agent](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LangChain/LangChain_Pandas_Dataframe_Agent.ipynb)

## LeFigaro
* [House Price analysis](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LeFigaro/LeFigaro_House_Price_analysis.ipynb)

## LinkedIn Sales Navigator
* [Extract Leads List from URL](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn%20Sales%20Navigator/LinkedIn_Sales_Navigator_Extract_Leads_List_from_URL.ipynb)
* [Send Leads to Spreadsheet](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn%20Sales%20Navigator/LinkedIn_Sales_Navigator_Send_Leads_to_Spreadsheet.ipynb)

## LinkedIn
* [Accept all invitations and send first message](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Accept_all_invitations_and_send_first_message.ipynb)
* [Accept invitation received](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Accept_invitation_received.ipynb)
* [Chat about my latest profile posts](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Chat_about_my_latest_profile_posts.ipynb)
* [Create Post](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Create_Post.ipynb)
* [Create posts metrics dashboard](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Create_posts_metrics_dashboard.ipynb)
* [Extract content world cloud](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Extract_content_world_cloud.ipynb)
* [Follow company followers](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Follow_company_followers.ipynb)
* [Follow connections from profile](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Follow_connections_from_profile.ipynb)
* [Follow content comments monthly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Follow_content_comments_monthly.ipynb)
* [Follow content comments weekly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Follow_content_comments_weekly.ipynb)
* [Follow content engagements monthly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Follow_content_engagements_monthly.ipynb)
* [Follow content engagements weekly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Follow_content_engagements_weekly.ipynb)
* [Follow content frequency](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Follow_content_frequency.ipynb)
* [Follow content likes monthly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Follow_content_likes_monthly.ipynb)
* [Follow content likes weekly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Follow_content_likes_weekly.ipynb)
* [Follow content published by weekdays by months](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Follow_content_published_by_weekdays_by_months.ipynb)
* [Follow content published monthly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Follow_content_published_monthly.ipynb)
* [Follow content published weekly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Follow_content_published_weekly.ipynb)
* [Follow content views by weekdays by hours](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Follow_content_views_by_weekdays_by_hours.ipynb)
* [Follow content views monthly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Follow_content_views_monthly.ipynb)
* [Follow content views weekly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Follow_content_views_weekly.ipynb)
* [Follow number of connections monthly](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Follow_number_of_connections_monthly.ipynb)
* [Generate leads from posts](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Generate_leads_from_posts.ipynb)
* [Get age and gender from profile picture](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_age_and_gender_from_profile_picture.ipynb)
* [Get comments from post](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_comments_from_post.ipynb)
* [Get company followers](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_company_followers.ipynb)
* [Get company posts stats](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_company_posts_stats.ipynb)
* [Get connections from network](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_connections_from_network.ipynb)
* [Get contact from profile](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_contact_from_profile.ipynb)
* [Get conversations](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_conversations.ipynb)
* [Get followers from network](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_followers_from_network.ipynb)
* [Get guests from event](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_guests_from_event.ipynb)
* [Get identity from profile](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_identity_from_profile.ipynb)
* [Get info from company](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_info_from_company.ipynb)
* [Get invitations received](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_invitations_received.ipynb)
* [Get invitations sent](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_invitations_sent.ipynb)
* [Get likes from post](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_likes_from_post.ipynb)
* [Get messages from profile](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_messages_from_profile.ipynb)
* [Get network from profile](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_network_from_profile.ipynb)
* [Get polls from post](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_polls_from_post.ipynb)
* [Get posts engagements](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_posts_engagements.ipynb)
* [Get profile information](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_profile_information.ipynb)
* [Get profile posts stats](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_profile_posts_stats.ipynb)
* [Get resume from profile](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_resume_from_profile.ipynb)
* [Get sentiment emotion irony offensiveness from comments](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_sentiment_emotion_irony_offensiveness_from_comments.ipynb)
* [Get stats from post](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Get_stats_from_post.ipynb)
* [Ignore invitation received](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Ignore_invitation_received.ipynb)
* [Send comments from post to gsheet](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Send_comments_from_post_to_gsheet.ipynb)
* [Send company followers to Google Sheets](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Send_company_followers_to_Google_Sheets.ipynb)
* [Send connections from network to gsheet](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Send_connections_from_network_to_gsheet.ipynb)
* [Send event invitations post engagements](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Send_event_invitations_post_engagements.ipynb)
* [Send followers demographic data to a Google Sheets spreadsheet](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Send_followers_demographic_data_to_a_Google_Sheets_spreadsheet.ipynb)
* [Send invitation to company followers](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Send_invitation_to_company_followers.ipynb)
* [Send invitation to profile](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Send_invitation_to_profile.ipynb)
* [Send invitation to profile from post likes](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Send_invitation_to_profile_from_post_likes.ipynb)
* [Send invitations to post commenters](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Send_invitations_to_post_commenters.ipynb)
* [Send likes from post to gsheet](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Send_likes_from_post_to_gsheet.ipynb)
* [Send message to new connections](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Send_message_to_new_connections.ipynb)
* [Send message to profile](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Send_message_to_profile.ipynb)
* [Send message to profile from post likes](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Send_message_to_profile_from_post_likes.ipynb)
* [Send posts feed to gsheet](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Send_posts_feed_to_gsheet.ipynb)
* [Send profile followers by email](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Send_profile_followers_by_email.ipynb)
* [Send weekly post engagement metrics by email](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Send_weekly_post_engagement_metrics_by_email.ipynb)
* [Update metrics from company posts in Notion content calendar](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Update_metrics_from_company_posts_in_Notion_content_calendar.ipynb)
* [Update metrics from posts in Notion content calendar](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Update_metrics_from_posts_in_Notion_content_calendar.ipynb)
* [Withdraw pending profile invitations](https://github.com/jupyter-naas/awesome-notebooks/blob/master/LinkedIn/LinkedIn_Withdraw_pending_profile_invitations.ipynb)

## Matplotlib
* [Create Barchart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Matplotlib/Matplotlib_Create_Barchart.ipynb)
* [Create Horizontal Barchart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Matplotlib/Matplotlib_Create_Horizontal_barchart.ipynb)
* [Create Stacked Barchart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Matplotlib/Matplotlib_Create_Stacked_barchart.ipynb)
* [Create Stackplots](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Matplotlib/Matplotlib_Create_Stackplot.ipynb)
* [Create Step Demo](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Matplotlib/Matplotlib_Create_Step_Demo.ipynb)
* [Create Streamgraphs](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Matplotlib/Matplotlib_Create_Streamgraphs.ipynb)
* [Create Waterfall chart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Matplotlib/Matplotlib_Create_Waterfall_chart.ipynb)
* [Creating a timeline with lines, dates, and text](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Matplotlib/Matplotlib_Create_timeline%20_with_lines_dates_and_text.ipynb)
* [Errorbar Limit Selection](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Matplotlib/Matplotlib_Errorbar_limit_selection.ipynb)
* [Mapping marker properties to multivariate data](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Matplotlib/Matplotlib_Map_marker_properties_to_plot_multivariate_data.ipynb)
* [Plotting the Coherence of two signals](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Matplotlib/Matplotlib_Plotting_the_coherence_of_two_signals.ipynb)

## Metrics Store
* [Content creation Track connections](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Metrics%20Store/Content_creation_Track_connections.ipynb)

## Microsoft Teams
* [Send message](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Microsoft%20Teams/Microsoft_Teams_Send_message.ipynb)

## Microsoft Word
* [Convert to HMTL](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Microsoft%20Word/Microsoft_Word_Convert_to_HMTL.ipynb)

## Mixpanel
* [Get Profile Event Activity](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Mixpanel/Mixpanel_Get_Profile_Event_Activity.ipynb)

## MongoDB
* [Get data](https://github.com/jupyter-naas/awesome-notebooks/blob/master/MongoDB/MongoDB_Get_data.ipynb)
* [Send data](https://github.com/jupyter-naas/awesome-notebooks/blob/master/MongoDB/MongoDB_Send_data.ipynb)
* [Send data to Google Sheets](https://github.com/jupyter-naas/awesome-notebooks/blob/master/MongoDB/MongoDB_Send_data_to_Google_Sheets.ipynb)

## MoviePy
* [Convert audio file M4A to MP3](https://github.com/jupyter-naas/awesome-notebooks/blob/master/MoviePy/MoviePy_Convert_audio_file_M4A_to_MP3.ipynb)

## MySQL
* [Query database](https://github.com/jupyter-naas/awesome-notebooks/blob/master/MySQL/MySQL_Query_database.ipynb)

## NASA
* [Artic sea ice](https://github.com/jupyter-naas/awesome-notebooks/blob/master/NASA/NASA_Artic_sea_ice.ipynb)
* [Display Exoplanet by Light Curves](https://github.com/jupyter-naas/awesome-notebooks/blob/master/NASA/NASA_Classify_Exoplanet_by_light_curves.ipynb)
* [Global temperature](https://github.com/jupyter-naas/awesome-notebooks/blob/master/NASA/NASA_Global_temperature.ipynb)
* [Sea level](https://github.com/jupyter-naas/awesome-notebooks/blob/master/NASA/NASA_Sea_level.ipynb)

## Naas Auth
* [Bearer validate](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas%20Auth/Naas_Auth_bearer_validate.ipynb)
* [Connect](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas%20Auth/Naas_Auth_connect.ipynb)
* [Users me](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas%20Auth/Naas_Auth_users_me.ipynb)

## Naas Dashboard
* [Financial Consolidation](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas%20Dashboard/Naas_Dashboard_Financial_Consolidation.ipynb)
* [Revenue Cogs by Segment](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas%20Dashboard/Naas_Dashboard_Revenue_Cogs_by_Segment.ipynb)
* [Social Media KPIs ScoreCard](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas%20Dashboard/Naas_Dashboard_Social_Media_KPIs_ScoreCard.ipynb)

## Naas
* [Add or Update Asset](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Add_or_Update_Asset.ipynb)
* [Add or Update Dependency](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Add_or_Update_Dependency.ipynb)
* [Add or Update Scheduler](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Add_or_Update_Scheduler.ipynb)
* [Add or Update Secret](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Add_or_Update_Secret.ipynb)
* [Add or Update Webhook](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Add_or_Update_Webhook.ipynb)
* [Asset demo](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Asset_demo.ipynb)
* [Automate GitHub Auth](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Automate_GitHub_Auth.ipynb)
* [Configure Github with ssh](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Configure_Github_with_ssh.ipynb)
* [Create Kernel](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Create_Kernel.ipynb)
* [Create Pipeline](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Create_Pipeline.ipynb)
* [Create onboarding plugin using OpenAI](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Create_onboarding_plugin_using_OpenAI.ipynb)
* [Credits Get Balance](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Credits_Get_Balance.ipynb)
* [Delete Asset](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Delete_Asset.ipynb)
* [Delete Dependency](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Delete_Dependency.ipynb)
* [Delete Scheduler](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Delete_Scheduler.ipynb)
* [Delete Secret](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Delete_Secret.ipynb)
* [Delete Webhook](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Delete_Webhook.ipynb)
* [Dependency demo](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Dependency_demo.ipynb)
* [Doc demo](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Doc_demo.ipynb)
* [Download Content Engine](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Download_Content_Engine.ipynb)
* [Emailbuilder demo](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Emailbuilder_demo.ipynb)
* [Find Asset link from path](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Find_Asset_link_from_path.ipynb)
* [Get Transactions](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Get_Transactions.ipynb)
* [Get help](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Get_help.ipynb)
* [Get number of downloads naas drivers package](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Get_number_of_downloads_naas_drivers_package.ipynb)
* [Get number of downloads naas package](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Get_number_of_downloads_naas_package.ipynb)
* [Get total downloads naas libraries](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Get_total_downloads_naas_libraries.ipynb)
* [List Assets](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_List_Assets.ipynb)
* [List Dependencies](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_List_Dependencies.ipynb)
* [List Schedulers](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_List_Schedulers.ipynb)
* [List Schedulers with all executions](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_List_Schedulers_with_all_executions.ipynb)
* [List Schedulers with last execution](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_List_Schedulers_with_last_execution.ipynb)
* [List Secrets](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_List_Secrets.ipynb)
* [List Webhooks](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_List_Webhooks.ipynb)
* [Manage Pipeline Errors](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Manage_Pipeline_Errors.ipynb)
* [NLP Examples](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_NLP_Examples.ipynb)
* [Notification demo](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Notification_demo.ipynb)
* [Remove Pipeline Executions Outputs](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Remove_Pipeline_Executions_Outputs.ipynb)
* [Remove Scheduler Outputs](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Remove_Scheduler_Outputs.ipynb)
* [Reset Instance](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Reset_Instance.ipynb)
* [Scheduler demo](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Scheduler_demo.ipynb)
* [Secret demo](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Secret_demo.ipynb)
* [Send Asset image to Notion page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Send_Asset_image_to_Notion_page.ipynb)
* [Send notifications from Google Sheets](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Send_notifications_from_Google_Sheets.ipynb)
* [Set timezone](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Set_timezone.ipynb)
* [Start data product](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Start_data_product.ipynb)
* [Use SSH tunnel to reach network protected resources](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Use_SSH_tunnel_to_reach_network_protected_resources.ipynb)
* [Webhook demo](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Naas/Naas_Webhook_demo.ipynb)

## Neo
* [Get currencies live prices](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Neo/Neo_Get_currencies_live_prices.ipynb)

## Newsapi
* [Get data](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Newsapi/Newsapi_Get_data.ipynb)
* [Run sentiment analysis](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Newsapi/Newsapi_Run_sentiment_analysis.ipynb)
* [Send emails briefs](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Newsapi/Newsapi_Send_emails_briefs.ipynb)

## Notion
* [Add bulleted list in page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Add_bulleted_list_in_page.ipynb)
* [Add code block in page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Add_code_block_in_page.ipynb)
* [Add cover image to page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Add_cover_image_to_page.ipynb)
* [Add equation in page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Add_equation_in_page.ipynb)
* [Add heading in page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Add_heading_in_page.ipynb)
* [Add icon image to page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Add_icon_image_to_page.ipynb)
* [Add new github member to team from database](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Add_new_github_member_to_team_from_database.ipynb)
* [Add numbered list in page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Add_numbered_list_in_page.ipynb)
* [Add paragraph with link in page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Add_paragraph_with_link_in_page.ipynb)
* [Add to do list in page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Add_to_do_list_in_page.ipynb)
* [Automate transcript generation from recording link in page property](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Automate_transcript_generation_from_recording_link_in_page_property.ipynb)
* [Create page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Create_page.ipynb)
* [Create pages in database from dataframe](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Create_pages_in_database_from_dataframe.ipynb)
* [Delete all pages from database](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Delete_all_pages_from_database.ipynb)
* [Delete blocks from page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Delete_blocks_from_page.ipynb)
* [Delete page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Delete_page.ipynb)
* [Duplicate page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Duplicate_page.ipynb)
* [Explore API](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Explore_API.ipynb)
* [Generate Google Sheets rows for new items in  database](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Generate_Google_Sheets_rows_for_new_items_in_Notion_database.ipynb)
* [Get blocks from page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Get_blocks_from_page.ipynb)
* [Get database](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Get_database.ipynb)
* [Get page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Get_page.ipynb)
* [Get users](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Get_users.ipynb)
* [Send LinkedIn invitations from database](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Send_LinkedIn_invitations_from_database.ipynb)
* [Send Slack Messages For New  Database Items](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Send_Slack_Messages_For_New_Notion_Database_Items.ipynb)
* [Sent Gmail On New Item](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Sent_Gmail_On_New_Item.ipynb)
* [Update database with GitHub repositories info](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Update_database_with_GitHub_repositories_info.ipynb)
* [Update database with LinkedIn company info](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Update_database_with_LinkedIn_company_info.ipynb)
* [Update database with LinkedIn profile info](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Update_database_with_LinkedIn_profile_info.ipynb)
* [Update page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Update_page.ipynb)
* [Update page relation](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Update_page_relation.ipynb)
* [Update pages from database](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Update_pages_from_database.ipynb)
* [Upload PDF in page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Upload_PDF_in_page.ipynb)
* [Upload image in page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Upload_image_in_page.ipynb)
* [Upload video in page](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Notion/Notion_Upload_video_in_page.ipynb)

## OS
* [Access environment variable](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OS/OS_Access_environment_variable.ipynb)
* [Add new environment variable](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OS/OS_Add_new_environment_variable.ipynb)
* [Check path exist](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OS/OS_Check_path_exist.ipynb)
* [Create directory](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OS/OS_Create_directory.ipynb)
* [Get access of environment variables](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OS/OS_Get_access_of_environment_variables.ipynb)
* [Get current working directory](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OS/OS_Get_current_working_directory.ipynb)
* [Get folder stats](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OS/OS_Get_folder_stats.ipynb)
* [List entries in directory](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OS/OS_List_entries_in_directory.ipynb)
* [Remove file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OS/OS_Remove_file.ipynb)
* [Rename file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OS/OS_Rename_file.ipynb)

## OWID
* [Visualize GDP per capita through the years](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OWID/OWID_Visualize_GDP_per_capita_through_the_years.ipynb)
* [Visualize oil consumption throughout the years](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OWID/OWID_Visualize_Oil_Consumption_through_the_Years.ipynb)
* [Visualize Population of Different Age Groups](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OWID/OWID_Visualize_Population_of_Different_Age_Groups.ipynb)

## OpenAI
* [Act as a AI enthusiast](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_AI_enthusiast.ipynb)
* [Act as a Business Analyst](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_Business_Analyst.ipynb)
* [Act as a CEO](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_CEO.ipynb)
* [Act as a COO](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_COO.ipynb)
* [Act as a CTO](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_CTO.ipynb)
* [Act as a Creative Writer or Artist](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_Creative_Writer_or_Artist.ipynb)
* [Act as a Data Analyst](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_Data_Analyst.ipynb)
* [Act as a Data Scientist](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_Data_Scientist.ipynb)
* [Act as a Educator or student](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_Educator_or_student.ipynb)
* [Act as a Hobbyist](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_Hobbyist.ipynb)
* [Act as a Homeowner](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_Homeowner.ipynb)
* [Act as a IT Professional](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_IT_Professional.ipynb)
* [Act as a Lifelong learner](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_Lifelong_learner.ipynb)
* [Act as a Marketer](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_Marketer.ipynb)
* [Act as a Parent or Child](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_Parent_or_Child.ipynb)
* [Act as a Product Manager](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_Product_Manager.ipynb)
* [Act as a Project Manager](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_Project_Manager.ipynb)
* [Act as a Retiree](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_Retiree.ipynb)
* [Act as a Sales Professional](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_Sales_Professional.ipynb)
* [Act as a Software Developer](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_Software_Developer.ipynb)
* [Act as a Software Engineer](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_Software_Engineer.ipynb)
* [Act as a chef](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Act_as_a_chef.ipynb)
* [Brainstorm ideas](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Brainstorm_ideas.ipynb)
* [Count tokens with tiktoken](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Count_tokens_with_tiktoken.ipynb)
* [Create Completion](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Create_Completion.ipynb)
* [Create chat completion](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Create_chat_completion.ipynb)
* [Create chatbot](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Create_chatbot.ipynb)
* [Generate_Act_as_a_x_notebook](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Generate_Act_as_a_x_notebook.ipynb)
* [Generate Dialogue](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Generate_Dialogue.ipynb)
* [Generate Q&A](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Generate_Q%26A.ipynb)
* [Generate README for GitHub repository](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Generate_README_for_GitHub_repository.ipynb)
* [Generate Text to Speech](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Generate_Text_to_Speech.ipynb)
* [Generate image from text](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Generate_image_from_text.ipynb)
* [Generate language translations](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Generate_language_translations.ipynb)
* [Generate text based prediction](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Generate_text_based_prediction.ipynb)
* [Generate text replacements](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Generate_text_replacements.ipynb)
* [Generate text summaries](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Generate_text_summaries.ipynb)
* [Write a blog post](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Write_a_blog_post.ipynb)
* [Write a job description](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Write_a_job_description.ipynb)
* [Write a press release](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Write_a_press_release.ipynb)
* [Write a social media post](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Write_a_social_media_post.ipynb)
* [Write an outline](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAI/OpenAI_Write_an_outline.ipynb)

## OpenAlex
* [Get lists of authors](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAlex/OpenAlex_Get_lists_of_authors.ipynb)
* [Get lists of concepts](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAlex/OpenAlex_Get_lists_of_concepts.ipynb)
* [Get lists of funders](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAlex/OpenAlex_Get_lists_of_funders.ipynb)
* [Get lists of institutions](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAlex/OpenAlex_Get_lists_of_institutions.ipynb)
* [Get lists of publishers](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAlex/OpenAlex_Get_lists_of_publishers.ipynb)
* [Get lists of sources](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAlex/OpenAlex_Get_lists_of_sources.ipynb)
* [Get lists of works](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenAlex/OpenAlex_Get_lists_of_works.ipynb)

## OpenBB
* [Create an  kernel on Naas](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenBB/OpenBB_Create_an_OpenBB_kernel_on_Naas.ipynb)

## OpenPIV
* [Openpiv-python-template](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenPIV/openpiv-python-template.ipynb)

## OpenWeatherMap
* [Get City Weather](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenWeatherMap/OpenWeatherMap_Get_City_Weather.ipynb)
* [Get City temperature weather-type wind-speed](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenWeatherMap/OpenWeatherMap_Get_City_temperature_weather-type_wind-speed.ipynb)
* [Send daily email with predictions](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OpenWeatherMap/OpenWeatherMap_Send_daily_email_with_predictions.ipynb)

## OwnCloud
* [Download file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OwnCloud/OwnCloud_Download_file.ipynb)
* [Upload file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/OwnCloud/OwnCloud_Upload_file.ipynb)

## PDF
* [Extract Text from](https://github.com/jupyter-naas/awesome-notebooks/blob/master/PDF/PDF_Extract_Text_from_PDF.ipynb)
* [Merge multiple  documents](https://github.com/jupyter-naas/awesome-notebooks/blob/master/PDF/PDF_Merge_multiple_PDF_documents.ipynb)
* [Transform to MP3](https://github.com/jupyter-naas/awesome-notebooks/blob/master/PDF/PDF_Transform_to_MP3.ipynb)

## Pandas
* [Apply custom styles on column](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Apply_custom_styles_on_column.ipynb)
* [Check Columns type](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Check_Columns_type.ipynb)
* [Check if column is in date format](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Check_if_column_is_in_date_format.ipynb)
* [Concatenate dataframes](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Concatenate_dataframes.ipynb)
* [Convert datetime series](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Convert_datetime_series.ipynb)
* [Create Pivot Table](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Create_Pivot_Table.ipynb)
* [Create conditional column enrichment using DataFrame.loc](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Create_conditional_column_enrichment_using_DataFrame.loc.ipynb)
* [Create dataframe from dict](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Create_dataframe_from_dict.ipynb)
* [Drop Columns By Index](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Drop_Columns_By_Index.ipynb)
* [Drop First column](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Drop_First_column.ipynb)
* [Drop columns](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Drop_columns.ipynb)
* [Drop duplicates](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Drop_duplicates.ipynb)
* [Enforce data types to columns](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Enforce_data_types_to_columns.ipynb)
* [Fill emtpy values](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Fill_emtpy_values.ipynb)
* [Filter DataFrame](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Filter_DataFrame.ipynb)
* [Flatten MultiIndex Columns](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Flatten_MultiIndex_Columns.ipynb)
* [Format URL as clickable link on column](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Format_URL_as_clickable_link_on_column.ipynb)
* [Format number to string](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Format_number_to_string.ipynb)
* [Get n largest](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Get_n_largest.ipynb)
* [Get n smallest](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Get_n_smallest.ipynb)
* [Groupby and Aggregate](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Groupby_and_Aggregate.ipynb)
* [ISO Date Conversion](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_ISO_Date_Conversion.ipynb)
* [Insert column](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Insert_column.ipynb)
* [Iterate over DataFrame rows](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Iterate_over_DataFrame_rows.ipynb)
* [Iterate over DataFrame rows as namedtuples](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Iterate_over_DataFrame_rows_as_namedtuples.ipynb)
* [Keep columns](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Keep_columns.ipynb)
* [Looping Over Dataframe](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Looping_Over_Dataframe.ipynb)
* [Map column with values in dict](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Map_column_with_values_in_dict.ipynb)
* [Merge Dataframes](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Merge_Dataframes.ipynb)
* [Pivot rows to columns](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Pivot_rows_to_columns.ipynb)
* [Read CSV](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Read_CSV.ipynb)
* [Read Excel](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Read_Excel.ipynb)
* [Rename columns](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Rename_columns.ipynb)
* [Save dataframe to CSV](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Save_dataframe_to_CSV.ipynb)
* [Save dataframe to Excel](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Save_dataframe_to_Excel.ipynb)
* [Sort values by multiples columns](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Sort_values_by_multiples_columns.ipynb)
* [Transform DataFrame to json file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Transform_DataFrame_to_json_file.ipynb)
* [Transform Dataframe to dict](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandas/Pandas_Transform_Dataframe_to_dict.ipynb)

## Pandasql
* [Query CSV Using SQL](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandasql/Pandasql_Query_CSV_Using_SQL.ipynb)
* [Query Excel Using SQL](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandasql/Pandasql_Query_Excel_Using_SQL.ipynb)
* [Query Parquet Using SQL](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pandasql/Pandasql_Query_Parquet_Using_SQL.ipynb)

## Panel
* [Create a  kernel on Naas](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Panel/Panel_Create_a_Panel_kernel_on_Naas.ipynb)

## Pillow
* [Add data to image](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pillow/Pillow_Add_data_to_image.ipynb)
* [Create indicator](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pillow/Pillow_Create_indicator.ipynb)
* [Create new image](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pillow/Pillow_Create_new_image.ipynb)
* [Generate A Certificate Template](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pillow/Pillow_Generate_A_Certificate_Template.ipynb)

## Pipedrive
* [Get contact](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pipedrive/Pipedrive_Get_contact.ipynb)

## Plaid
* [Get accounts](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plaid/Plaid_Get_accounts.ipynb)
* [Get transactions](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plaid/Plaid_Get_transactions.ipynb)

## Plotly
* [Create Balance Sheet Treemaps](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Balance_Sheet_Treemaps.ipynb)
* [Create Barline chart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Barline_chart.ipynb)
* [Create Bubblechart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Bubblechart.ipynb)
* [Create Bubblemap by City](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Bubblemap_by_City.ipynb)
* [Create Candlestick](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Candlestick.ipynb)
* [Create Gantt chart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Gantt_chart.ipynb)
* [Create Heatmap](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Heatmap.ipynb)
* [Create Horizontal Barchart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Horizontal_Barchart.ipynb)
* [Create Leaderboard](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Leaderboard.ipynb)
* [Create Leaderboard stacked](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Leaderboard_stacked.ipynb)
* [Create Linechart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Linechart.ipynb)
* [Create Mapchart world](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Mapchart_world.ipynb)
* [Create Treemaps with plotly.express](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Treemaps_with_plotly.express.ipynb)
* [Create Treemaps with plotly.graph objects](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Treemaps_with_plotly.graph_objects.ipynb)
* [Create Vertical Barchart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Vertical_Barchart.ipynb)
* [Create Vertical Barchart group](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Vertical_Barchart_group.ipynb)
* [Create Vertical Barchart stacked](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Vertical_Barchart_stacked.ipynb)
* [Create Waterfall chart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Plotly/Plotly_Create_Waterfall_chart.ipynb)

## Polars
* [Concatenate DataFrames](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Polars/Polars_Concatenate_DataFrames.ipynb)
* [Create DataFrame](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Polars/Polars_Create_DataFrame.ipynb)
* [Read CSV](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Polars/Polars_Read_CSV.ipynb)
* [Select columns](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Polars/Polars_Select_Columns.ipynb)
* [Select rows](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Polars/Polars_Select_Rows.ipynb)
* [Select both rows and columns](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Polars/Polars_Select_Rows_and_Columns.ipynb)

## PostgresSQL
* [Get data from database](https://github.com/jupyter-naas/awesome-notebooks/blob/master/PostgresSQL/PostgresSQL_Get_data_from_database.ipynb)

## PowerPoint
* [Add Slide With Image](https://github.com/jupyter-naas/awesome-notebooks/blob/master/PowerPoint/PowerPoint_Add_Slide_With_Image.ipynb)
* [Add Slide With Textbox](https://github.com/jupyter-naas/awesome-notebooks/blob/master/PowerPoint/PowerPoint_Add_Slide_With_Textbox.ipynb)
* [Add Slide With Title Subtitle](https://github.com/jupyter-naas/awesome-notebooks/blob/master/PowerPoint/PowerPoint_Add_Slide_With_Title_Subtitle.ipynb)
* [Add title + line in presentation](https://github.com/jupyter-naas/awesome-notebooks/blob/master/PowerPoint/PowerPoint_Add_title_%2B_line_in_presentation.ipynb)
* [Create Presentation](https://github.com/jupyter-naas/awesome-notebooks/blob/master/PowerPoint/PowerPoint_Create_Presentation.ipynb)
* [Set portrait format](https://github.com/jupyter-naas/awesome-notebooks/blob/master/PowerPoint/PowerPoint_Set_portrait_format.ipynb)

## PyCaret
* [Automl classification](https://github.com/jupyter-naas/awesome-notebooks/blob/master/PyCaret/PyCaret_automl_classification.ipynb)
* [Automl regression](https://github.com/jupyter-naas/awesome-notebooks/blob/master/PyCaret/PyCaret_automl_regression.ipynb)

## PyGWalker
* [Analyze Pandas dataframe](https://github.com/jupyter-naas/awesome-notebooks/blob/master/PyGWalker/PyGWalker_Analyze_Pandas_dataframe.ipynb)

## PyPI
* [- Get number of downloads any package](https://github.com/jupyter-naas/awesome-notebooks/blob/master/PyPI/PyPI_Get_number_of_downloads_any_package.ipynb)

## Python
* [Check if string is number](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Check_if_string_is_number.ipynb)
* [Clean your download folder](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Clean_your_download_folder.ipynb)
* [Compress images](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Compress_images.ipynb)
* [Consolidate Excel files](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Consolidate_Excel_files.ipynb)
* [Convert CSV to Excel](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Convert_CSV_to_Excel.ipynb)
* [Convert PNG Images To JPG](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Convert_PNG_Images_To_JPG.ipynb)
* [Convert URL to string](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Convert_URL_to_string.ipynb)
* [Convert audiofile from wav to mp3](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Convert_audiofile_from_wav_to_mp3.ipynb)
* [Convert currency](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Convert_currency.ipynb)
* [Convert length](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Convert_length.ipynb)
* [Convert speed](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Convert_speed.ipynb)
* [Convert string boolean to boolean](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Convert_string_boolean_to_boolean.ipynb)
* [Convert string to URL](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Convert_string_to_URL.ipynb)
* [Convert temperature](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Convert_temperature.ipynb)
* [Convert time](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Convert_time.ipynb)
* [Convert time delta to months](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Convert_time_delta_to_months.ipynb)
* [Convert units](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Convert_units.ipynb)
* [Convert volume](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Convert_volume.ipynb)
* [Convert weight](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Convert_weight.ipynb)
* [Copy files and subdir from directory to another directory](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Copy_files_and_subdir_from_directory_to_another_directory.ipynb.ipynb)
* [Create Email Combination with Firstname Lastname Domain address](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Create_Email_Combination_with_Firstname_Lastname_Domain_address.ipynb)
* [Create Strong Random Password](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Create_Strong_Random_Password.ipynb)
* [Create dataframe from lists](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Create_dataframe_from_lists.ipynb)
* [Create dict from lists](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Create_dict_from_lists.ipynb)
* [Delete entire directory tree](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Delete_entire_directory_tree.ipynb)
* [Download Image from URL](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Download_Image_from_URL.ipynb)
* [Download PDF from URL](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Download_PDF_from_URL.ipynb)
* [Download ZIP from URL](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Download_ZIP_from_URL.ipynb)
* [Download audio file from URL](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Download_audio_file_from_URL.ipynb)
* [Explore Dataset with Pivot Table](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Explore_Dataset_with_Pivot_Table.ipynb)
* [Extract characters from string](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Extract_characters_from_string.ipynb)
* [Find Phone Number in string](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Find_Phone_Number_in_string.ipynb)
* [Find differences between strings](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Find_differences_between_strings.ipynb)
* [Flatten nested dict](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Flatten_nested_dict.ipynb)
* [Get Word Definition and Translation](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Get_Word_Definition_and_Translation.ipynb)
* [Get all files from directory](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Get_all_files_from_directory.ipynb)
* [Get coordinates from address](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Get_coordinates_from_address.ipynb)
* [Get last file modified from directy](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Get_last_file_modified_from_directy.ipynb)
* [Get next occurrences of a cron job](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Get_next_occurrences_of_a_cron_job.ipynb)
* [Get random number](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Get_random_number.ipynb)
* [Get a random word](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Get_random_word.ipynb)
* [List specific files from directory and subdirectories](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_List_specific_files_from_directory_and_subdirectories.ipynb)
* [Locate address on map](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Locate_address_on_map.ipynb)
* [Locate city on map](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Locate_city_on_map.ipynb)
* [Locate coordinates](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Locate_coordinates.ipynb)
* [Looping Over Dataframe](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Looping_Over_Dataframe.ipynb)
* [Manage code error with try except](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Manage_exception_with_try_except.ipynb)
* [Organize Directories based on file types](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Organize_Directories_based_on_file_types.ipynb)
* [Pseudonym generator](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Pseudonym_generator.ipynb)
* [Read json file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Read_json_file.ipynb)
* [Read pickle file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Read_pickle_file.ipynb)
* [Remove all spaces on string](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Remove_all_spaces_on_string.ipynb)
* [Save dict to pickle](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Save_dict_to_pickle.ipynb)
* [Save json file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Save_json_file.ipynb)
* [Split string](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Split_string.ipynb)
* [Transform String to Secure Hash Algorithm](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Transform_string_to_Secure_Hash_Algorithm.ipynb)
* [Validate email and phone numbers](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Python/Python_Validate_email_and_phone_numbers.ipynb)

## Pyvis
* [Create a network visualization](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Pyvis/Pyvis_Create_a_network_visualization.ipynb)

## Qonto
* [Get cash position trend](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Qonto/Qonto_Get_cash_position_trend.ipynb)
* [Get organizations](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Qonto/Qonto_Get_organizations.ipynb)
* [Get positions](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Qonto/Qonto_Get_positions.ipynb)
* [Get statement](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Qonto/Qonto_Get_statement.ipynb)
* [Get statement barline](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Qonto/Qonto_Get_statement_barline.ipynb)
* [Get statement ranking by category](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Qonto/Qonto_Get_statement_ranking_by_category.ipynb)
* [Get statement summary by operation type](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Qonto/Qonto_Get_statement_summary_by_operation_type.ipynb)
* [Get transactions](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Qonto/Qonto_Get_transactions.ipynb)
* [Releve de compte augmente](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Qonto/Qonto_Releve_de_compte_augmente.ipynb)

## Quandl
* [Get data from API](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Quandl/Quandl_Get_data_from_API.ipynb)
* [Get data from CSV](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Quandl/Quandl_Get_data_from_CSV.ipynb)

## Reddit
* [Get Hot Posts From Subreddit](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Reddit/Reddit_Get_Hot_Posts_From_Subreddit.ipynb)

## Redshift
* [Connect with SQL Magic and IAM Credentials](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Redshift/Redshift_Connect_with_SQL_Magic_and_IAM_Credentials.ipynb)

## RegEx
* [Check email validity](https://github.com/jupyter-naas/awesome-notebooks/blob/master/RegEx/RegEx_Check_email_validity.ipynb)
* [Match pattern](https://github.com/jupyter-naas/awesome-notebooks/blob/master/RegEx/RegEx_Match_pattern.ipynb)
* [Replace value in text in a specific paragraph](https://github.com/jupyter-naas/awesome-notebooks/blob/master/RegEx/RegEx_Replace_value_in_text_in_a_specific_paragraph.ipynb)

## Remoteok
* [Get jobs from categories](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Remoteok/Remoteok_Get_jobs_from_categories.ipynb)
* [Post daily jobs on slack](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Remoteok/Remoteok_Post_daily_jobs_on_slack.ipynb)

## Remotive
* [Get categories from job](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Remotive/Remotive_Get_categories_from_job.ipynb)
* [Get jobs from categories](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Remotive/Remotive_Get_jobs_from_categories.ipynb)
* [Post daily jobs on slack](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Remotive/Remotive_Post_daily_jobs_on_slack.ipynb)
* [Send jobs to gsheet](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Remotive/Remotive_Send_jobs_to_gsheet.ipynb)

## Request
* [Basic HTTP GET](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Request/Request_Basic_HTTP_GET_Request.ipynb)
* [Handling Errors and Exceptions](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Request/Request_Handling_Errors_and_Exceptions.ipynb)
* [Sending POST s with Data](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Request/Request_Sending_POST_Requests_with_Data.ipynb)

## SAP-HANA
* [Query data](https://github.com/jupyter-naas/awesome-notebooks/blob/master/SAP-HANA/SAP-HANA_Query_data.ipynb)

## SEON
* [Get email info](https://github.com/jupyter-naas/awesome-notebooks/blob/master/SEON/SEON_Get_email_info.ipynb)

## SQLite
* [Create Database file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/SQLite/SQLite_Create_Database_file.ipynb)
* [Create Table in Database](https://github.com/jupyter-naas/awesome-notebooks/blob/master/SQLite/SQLite_Create_Table_in_Database.ipynb)
* [Insert data in Table](https://github.com/jupyter-naas/awesome-notebooks/blob/master/SQLite/SQLite_Insert_data_in_Table.ipynb)
* [List Tables in Database](https://github.com/jupyter-naas/awesome-notebooks/blob/master/SQLite/SQLite_List_Tables_in_Database.ipynb)
* [Read data in Table](https://github.com/jupyter-naas/awesome-notebooks/blob/master/SQLite/SQLite_Read_data_in_Table.ipynb)

## SWIFT
* [Create MT940 XML file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/SWIFT/SWIFT_Create_MT940_XML_file.ipynb)

## SendGrid
* [Get all messages](https://github.com/jupyter-naas/awesome-notebooks/blob/master/SendGrid/SendGrid_Get_all_messages.ipynb)
* [Send message](https://github.com/jupyter-naas/awesome-notebooks/blob/master/SendGrid/SendGrid_Send_message.ipynb)

## Sendinblue
* [Get no of emails opened](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Sendinblue/Sendinblue_Get_no_of_emails_opened.ipynb)
* [Get no of emails sent](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Sendinblue/Sendinblue_Get_no_of_emails_sent.ipynb)
* [Get no of spam reports](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Sendinblue/Sendinblue_Get_no_of_spam_reports.ipynb)
* [Get no of undelivered emails](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Sendinblue/Sendinblue_Get_no_of_undelivered_emails.ipynb)

## SharePoint
* [Get file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/SharePoint/SharePoint_Get_file.ipynb)
* [List folder](https://github.com/jupyter-naas/awesome-notebooks/blob/master/SharePoint/SharePoint_List_folder.ipynb)
* [Upload file](https://github.com/jupyter-naas/awesome-notebooks/blob/master/SharePoint/SharePoint_Upload_file.ipynb)

## Shutterstock
* [Search for images](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Shutterstock/Shutterstock_Search_for_images.ipynb)

## Slack
* [Add new user to Google Sheets](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Slack/Slack_Add_new_user_to_Google_Sheets.ipynb)
* [Follow number of users in workspace](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Slack/Slack_Follow_number_of_users_in_workspace.ipynb)
* [Send blocks to channel](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Slack/Slack_Send_blocks_to_channel.ipynb)
* [Send message](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Slack/Slack_Send_message_to_channel.ipynb)

## Snowflake
* [Basics and data querying](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Snowflake/Snowflake_Basics_and_data_querying.ipynb)
* [Ingest csv data from local stage](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Snowflake/Snowflake_Ingest_csv_data_from_local_stage.ipynb)
* [Ingest data from AWS external stages](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Snowflake/Snowflake_Ingest_data_from_AWS_external_stages.ipynb)
* [Ingest json data from local stage](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Snowflake/Snowflake_Ingest_json_data_from_local_stage.ipynb)

## Societe.com
* [Get company details](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Societe.com/Societe.com_Get_company_details.ipynb)
* [Get verif.com](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Societe.com/Societe.com_Get_verif.com.ipynb)

## Spotify
* [Create Radar Chart to analyze Playlist](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Spotify/Spotify_Create_Radar_Chart_to_analyze_Playlist.ipynb)

## Stabilty AI
* [Generate Image from text](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Stabilty%20AI/Stabilty_AI_Generate_Image_from_text.ipynb)

## Stable Diffusion
* [Generate image from text](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Stable%20Diffusion/Stable_Diffusion_Generate_image_from_text.ipynb)

## Streamlit
* [Create prediction app](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Streamlit/Streamlit_Create_prediction_app.ipynb)

## Stripe
* [Create a customer](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Stripe/Stripe_Create_a_customer.ipynb)
* [Delete a customer](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Stripe/Stripe_Delete_a_customer.ipynb)
* [Get balances](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Stripe/Stripe_Get_balances.ipynb)
* [Get charges](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Stripe/Stripe_Get_charges.ipynb)
* [List all customers](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Stripe/Stripe_List_all_customers.ipynb)
* [Retrieve a customer](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Stripe/Stripe_Retrieve_a_customer.ipynb)
* [Update a customer](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Stripe/Stripe_Update_a_customer.ipynb)

## Supabase
* [Email Auth](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Supabase/Supabase_Email_Auth.ipynb)

## Telegram
* [Create crypto sentiment bot](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Telegram/Telegram_Create_crypto_sentiment_bot.ipynb)

## Text
* [Reformat  Without Spaces](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Text/Text_Reformat_Text_Without_Spaces.ipynb)

## Thinkific
* [Get users](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Thinkific/Thinkific_Get_users.ipynb)
* [Send users](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Thinkific/Thinkific_Send_users.ipynb)

## TikTok
* [Get user stats](https://github.com/jupyter-naas/awesome-notebooks/blob/master/TikTok/TikTok_Get_user_stats.ipynb)
* [Get videos stats](https://github.com/jupyter-naas/awesome-notebooks/blob/master/TikTok/TikTok_Get_videos_stats.ipynb)

## Trello
* [Create Card](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Trello/Trello_Create_Card.ipynb)
* [Get Cards on a Board](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Trello/Trello_Get_Cards_on_a_Board.ipynb)
* [Get Lists on a Board](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Trello/Trello_Get_Lists_on_a_Board.ipynb)
* [Get board data](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Trello/Trello_Get_board_data.ipynb)
* [List Boards](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Trello/Trello_List_Boards.ipynb)

## Twilio
* [Add SMS to Google Sheets spreadsheet](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Twilio/Twilio_Add_SMS_to_Google_Sheets_spreadsheet.ipynb)
* [Make Call](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Twilio/Twilio_Make_Call.ipynb)
* [Send SMS](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Twilio/Twilio_Send_SMS.ipynb)
* [Send  SMS messages for Google Calendar Events](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Twilio/Twilio_Send_SMS_Google_Calendar_Events.ipynb)

## Twitter
* [Add member to list](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Twitter/Twitter_Add_member_to_list.ipynb)
* [Get followers list](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Twitter/Twitter_Get_followers_list.ipynb)
* [Get members of list](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Twitter/Twitter_Get_members_of%20list.ipynb)
* [Get posts stats](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Twitter/Twitter_Get_posts_stats.ipynb)
* [Get tweets from search](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Twitter/Twitter_Get_tweets_from_search.ipynb)
* [Get tweets stats from profile](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Twitter/Twitter_Get_tweets_stats_from_profile.ipynb)
* [Get user data](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Twitter/Twitter_Get_user_data.ipynb)
* [Post text and image](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Twitter/Twitter_Post_text_and_image.ipynb)
* [Remove member from list](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Twitter/Twitter_Remove_member_from_list.ipynb)
* [Schedule posts](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Twitter/Twitter_Schedule_posts.ipynb)
* [Send posts stats to Notion](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Twitter/Twitter_Send_posts_stats_to_Notion.ipynb)

## Typeform
* [Log New  Entries In Notion Databases](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Typeform/Typeform_Log_New_Typeform_Entries_In_Notion_Databases.ipynb)

## US Bureau of Labor Statistics
* [Follow CPI](https://github.com/jupyter-naas/awesome-notebooks/blob/master/US%20Bureau%20of%20Labor%20Statistics/US_Bureau_of_Labor_Statistics_Follow_CPI.ipynb)

## Vizzu
* [Create Animated Bar Chart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Vizzu/Vizzu_Create_Animated_Bar_Chart.ipynb)
* [Create Animated Pie Chart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Vizzu/Vizzu_Create_Animated_Pie_Chart.ipynb)
* [Create Column Chart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Vizzu/Vizzu_Create_Column_Chart.ipynb)
* [Create Grouped Column Chart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Vizzu/Vizzu_Create_Grouped_Column_Chart.ipynb)
* [Create Line Chart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Vizzu/Vizzu_Create_Line_Chart.ipynb)
* [Create Stacked Column Chart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Vizzu/Vizzu_Create_Stacked_Column_Chart.ipynb)
* [Create Waterfall Chart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Vizzu/Vizzu_Create_Waterfall_Chart.ipynb)

## WAQI
* [Display AQI on worldmap](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WAQI/WAQI_Display_AQI_on_worldmap.ipynb)
* [Get daily air quality data by coordinates](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WAQI/WAQI_Get_daily_air_quality_data_by_coordinates.ipynb)
* [Get daily air quality data for a city](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WAQI/WAQI_Get_daily_air_quality_data_for_a_city.ipynb)
* [Get stations by coordinates](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WAQI/WAQI_Get_stations_by_coordinates.ipynb)
* [Search station by name](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WAQI/WAQI_Search_station_by_name.ipynb)

## WSR
* [WHI Create indicator](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WSR/WHI_Create_indicator.ipynb)
* [Get daily Covid19 active cases trend JHU](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WSR/WSR_Get_daily_Covid19_active_cases_trend_JHU.ipynb)
* [Get daily Covid19 active cases worldmap JHU](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WSR/WSR_Get_daily_Covid19_active_cases_worldmap_JHU.ipynb)

## WhatsApp
* [Create heatmap of activities](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WhatsApp/WhatsApp_Create_heatmap_of_activities.ipynb)
* [Transform chat txt to dataframe](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WhatsApp/WhatsApp_Transform_chat_txt_to_dataframe.ipynb)

## Wikipedia
* [List largest cities in the world](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Wikipedia/Wikipedia_List_largest_cities_in_the_world.ipynb)

## WindsorAI
* [Create Dash app to query AP](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WindsorAI/WindsorAI_Create_Dash_app_to_query_AP.ipynb)

## WorldBank
* [GDP contributors](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WorldBank/WorldBank_GDP_contributors.ipynb)
* [GDP per capita and growth](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WorldBank/WorldBank_GDP_per_capita_and_growth.ipynb)
* [GDP per country and evolution](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WorldBank/WorldBank_GDP_per_country_and_evolution.ipynb)
* [Gini index](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WorldBank/WorldBank_Gini_index.ipynb)
* [Most populated countries](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WorldBank/WorldBank_Most_populated_countries.ipynb)
* [Richest countries top10](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WorldBank/WorldBank_Richest_countries_top10.ipynb)
* [World employment by sector](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WorldBank/WorldBank_World_employment_by_sector.ipynb)
* [World population and density](https://github.com/jupyter-naas/awesome-notebooks/blob/master/WorldBank/WorldBank_World_population_and_density.ipynb)

## Worldometer
* [World population evolution and projections](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Worldometer/Worldometer_World_population_evolution_and_projections.ipynb)

## XGBoost
* [Binary classification example with hyper-parameters optimization](https://github.com/jupyter-naas/awesome-notebooks/blob/master/XGBoost/XGBoost_Binary_classification_example_with_hyper-parameters_optimization.ipynb)

## XML
* [Transform sitemap to dataframe](https://github.com/jupyter-naas/awesome-notebooks/blob/master/XML/XML_Transform_sitemap_to_dataframe.ipynb)

## YahooFinance
* [Candlestick chart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YahooFinance/YahooFinance_Candlestick_chart.ipynb)
* [Cryptocurrencies heatmap correlation graph](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YahooFinance/YahooFinance_Cryptocurrencies_heatmap_correlation_graph.ipynb)
* [Display chart from ticker](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YahooFinance/YahooFinance_Display_chart_from_ticker.ipynb)
* [Find the stock with closest performance using KNN](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YahooFinance/YahooFinance_Find_the_stock_with_closest_performance_using_KNN.ipynb)
* [Get Brent Crude Oil trend and predictions](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YahooFinance/YahooFinance_Get_Brent_Crude_Oil_trend_and_predictions.ipynb)
* [Get Stock Update](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YahooFinance/YahooFinance_Get_Stock_Update.ipynb)
* [Get USDEUR data and chart](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YahooFinance/YahooFinance_Get_USDEUR_data_and_chart.ipynb)
* [Get data from ticker](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YahooFinance/YahooFinance_Get_data_from_ticker.ipynb)
* [Send daily prediction to Email](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YahooFinance/YahooFinance_Send_daily_prediction_to_Email.ipynb)
* [Send daily prediction to Notion](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YahooFinance/YahooFinance_Send_daily_prediction_to_Notion.ipynb)
* [Send daily prediction to Slack](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YahooFinance/YahooFinance_Send_daily_prediction_to_Slack.ipynb)

## YouTube
* [Download video](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YouTube/YouTube_Download_video.ipynb)
* [Extract and summarize transcript](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YouTube/YouTube_Extract_and_summarize_transcript.ipynb)
* [Extract transcript from video](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YouTube/YouTube_Extract_transcript_from_video.ipynb)
* [Get statistics from channel](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YouTube/YouTube_Get_statistics_from_channel.ipynb)
* [Get statistics from video](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YouTube/YouTube_Get_statistics_from_video.ipynb)
* [Get uploads from channel](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YouTube/YouTube_Get_uploads_from_channel.ipynb)
* [Send track to Spotify](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YouTube/YouTube_Send_track_to_Spotify.ipynb)
* [Send video stats to Notion](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YouTube/YouTube_Send_video_stats_to_Notion.ipynb)
* [Summarize video](https://github.com/jupyter-naas/awesome-notebooks/blob/master/YouTube/YouTube_Summarize_video.ipynb)

## ZIP
* [Extract files](https://github.com/jupyter-naas/awesome-notebooks/blob/master/ZIP/ZIP_Extract_files.ipynb)

## Zapier
* [Trigger workflow](https://github.com/jupyter-naas/awesome-notebooks/blob/master/Zapier/Zapier_Trigger_workflow.ipynb)

## ZeroBounce
* [Validate Single Email](https://github.com/jupyter-naas/awesome-notebooks/blob/master/ZeroBounce/ZeroBounce_Validate_Single_Email.ipynb)

## gTTS
* [Save Text to Speech to MP3](https://github.com/jupyter-naas/awesome-notebooks/blob/master/gTTS/gTTS_Save_Text_to_Speech_to_MP3.ipynb)

## spaCy
* [SpaCy Build a sentiment analysis model using Twitter](https://github.com/jupyter-naas/awesome-notebooks/blob/master/spaCy/SpaCy_Build_a_sentiment_analysis_model_using_Twitter.ipynb)



<br/>
Contact us on support@naas.ai if you need any help or join our [Slack community](https://join.slack.com/t/naas-club/shared_invite/zt-1970s5rie-dXXkigAdEJYc~LPdQIEaLA)
