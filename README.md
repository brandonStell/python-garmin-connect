# Garmin
Python API wrapper for Garmin Connect

See https://connect.garmin.com/

## Usage
Create a new connection by supplying your user credentials
```
import garmin

data = garmin.Garmin(YOUR_EMAIL, YOUR_PASSWORD)
```

Fetch your Garmin Connect activities data
```
print(data.fetch_stats('YYYY-mm-dd'))
```


Fetch your Garmin Connect heart rate data

```
print(data.fetch_heart_rates('YYYY-mm-dd'))
```