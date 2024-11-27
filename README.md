# Weather NoSQL Database

## Database Structure

### Document Database
```json
{
    Italy province capitals: {
        Weather informations
    }
    Users: {
        users information
    }
}
```
### Graph Database
```json
Entity == city; attributes: {
    name, 
    lat and long, 
    elevation, 
    extreme weather risk,
    population (only for pollution purposes),
    redundant: avg temp, avg rainfall...; 
}
Realations: {
    Distance (static),
    Similarity in weather: normalized CoV 0-1 (dynamic),
    More ideas: avg windflow direction and intensity,
}
```
### Apis to use

OpenMeteo historical data: https://open-meteo.com/en/docs/historical-weather-api
    OpenMeteo example: https://archive-api.open-meteo.com/v1/archive?latitude=40.7143&longitude=-74.006&start_date=2010-01-01&end_date=2020-01-01&hourly=temperature_2m,precipitation,rain,cloud_cover

#### Notes
Application in JAVA
Main aspect: Velocity/Variability, possibly also variant
