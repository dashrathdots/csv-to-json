# csv-to-json
Convert Csv to Json


### Project checkout flow
Clone the entire repository on your local machine using the command
```
git clone https://github.com/dashrathdots/csv-to-json.git

git checkout -b Beginner

git pull origin Beginner
```
Say the above is cloned out in a folder say `csv-to-json`.
Execute the following command to go in the checked out project folder
```
cd csv-to-json
```

After the above, open the `csv-to-json` folder in any IDE of your choice (preferable to use Visual Studio Code).
It has one folder
- csv-to-json: Holds the complete code
  - csvtojson: The django based project. This project will read the csv file and create new json file according to nested data.


## Create virtual environment
Create virtual environment and install requirements.txt
```
https://docs.python.org/3/library/venv.html
```
### Install new pip module and runserver

pip install -r requirements.txt

python manage.py runserver
- Hit the below url and upload the csv file to convert nested json .
  ```
    http://127.0.0.1:8000/upload/csv


## Run Unit Test Case inside the docker
  python manage.py test csvapp.tests.ConvertCsvToJsonTestCase.create_tree








