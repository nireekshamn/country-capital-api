# Country Capital API
<hr>
This is the project were it returns the name of the country when the capital city is provided.

## Prerequisites
* Install the virtual environment package
  ```$ pip install virtualenv```

* Create a virtual environment 
  ```$ virtualenv <Virtual Environment name>```

* Activate your virtual environment with the command:
  ```$ <Virtual Environment name>\Scripts\activate```

* With the virtual environment properly activated, install the plugins available at the **requirements.txt** file through the command:
  ```$ pip install -r requirements.txt```

* Config for flask
  ```$ export FLASK_APP=app.py```
  ```$ export FLASk_ENV=development```


## Deployment
```$ flask run```
```$ uvicorn main.py```

## API endpoints 
* Microservice endpoint for API is available in this url
```https://example.com/country-capital/<query-params>```
