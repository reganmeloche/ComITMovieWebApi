Steps to re-create:
- Command: dotnet new webapi
- Copy the WeatherForecastController and rename it to MovieController
- Rename all the references in it from WeatherForecastController to MovieController
- Remove some of the unnecessary code (logger, static member, ...)
- Build out the endpoints in the MovieController (GET, POST, PUT, DELETE)
- Create the Movie class in a new file
- Inject a List<Movie> into the controller from the Startup class (services.AddSingleton())
- Read and write from this movieList when doing your GETs and POSTs
