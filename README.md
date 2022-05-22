Parsed results of Global Data Barometer (https://globaldatabarometer.org/) in nice [JSONL](https://jsonlines.org/) format, one county by line, or as per-country JSON.

Originally, data was only available as CSV or bunch of badly structured JSONs.

Global Data Barometer did not specified data license, so use at your own risk.

## Data format
* country_info
* indicators[]
    * score - *int score used in rating*
    * justification
    * evidence[]
        * link - *optional*
        * title
    * indicator_id
    * indicator_name
    * responses[]
        * response_id - *int*
        * varname - *starts with indicator_id*
        * subquestion_id - *int*
        * response_text
        * subquestion_text