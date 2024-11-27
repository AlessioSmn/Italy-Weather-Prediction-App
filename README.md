# Weather NoSQL Database

## Database Structure

### Document Database
{
    Italy province capitals: {
        Weather informations
    }
    Users: {
        users information
    }
}

### Graph Database
Entity == city; attributes: {
    name, 
    lat and long, 
    elevation, 
    extreme weather risk,
    population (only for pollution purposes),
    redundant: avg temp, avg rainfall...; 
}

### Apis to use

OpenMeteo historical data: https://open-meteo.com/en/docs/historical-weather-api
    OpenMeteo example: https://archive-api.open-meteo.com/v1/archive?latitude=40.7143&longitude=-74.006&start_date=2010-01-01&end_date=2020-01-01&hourly=temperature_2m,precipitation,rain,cloud_cover

#### Notes
Application in JAVA
Main aspect: Velocity/Variability, possibly also variant
