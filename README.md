# Weather-app
A CLI weather application with python.

View weather and temperature information for different cities around the world right inside your CLI:

## requirements
1. To run this CLI app, you need a modern installation of Python
2. An api-key from (https://openweathermap.org)



## usage
clone the project repo to your local machine
  ```bash
  git clone https://github.com/SneezyG/Weather-app
  ```
  
move to the repo root dir
  ```bash
  cd weather-app
  ```

create .env file in repo root dir with this content:
  ```bash
  api_key = "your api key"
  ```
  
install program dependencies in requirements.txt
  ```bash
  pip install -r requirements.txt
  ```
  
  
## usage example
Once you're set up, you can call the weather CLI by running:

```bash
$ python3 weather.py <CITY_NAME> [-i]
```

For example, to get the current weather in lagos, Nigeria, you can run the following command:

```bash
$ python3 weather.py lagos
```
```bash
$ python3 weather.py lagos -i
```


