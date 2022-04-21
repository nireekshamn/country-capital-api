# Country Capital API
<hr>
This is the project were it returns the name of the country when the capital city is provided.

## Prerequisites
* Install the virtual environment package<br>
  ```$ pip install virtualenv```

* Create a virtual environment<br> 
  ```$ virtualenv <Virtual Environment name>```

* Activate your virtual environment with the command<br>
  ```$ <Virtual Environment name>\Scripts\activate```

* With the virtual environment properly activated, install the plugins available at the **requirements.txt** file through the command<br>
  ```$ pip install -r requirements.txt```

* Config for flask<br>
  ```$ export FLASK_APP=app.py```<br>
  ```$ export FLASk_ENV=development```


## Deployment
```$ flask run```<br>
```$ uvicorn main.py```

## API endpoints 
* Microservice endpoint for API is available in this url<br>
```https://example.com/country-capital/<query-params>```
