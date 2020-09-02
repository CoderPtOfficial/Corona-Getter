# Corona-Getter
This is a java corona virus library

## Usage
```
CovidGetter cov=new CovidGetter();
```

>Initialize object

```
List<String> country=cov.GetCountries();
```

>Returns all the countries listed

```
Boolean Exist=cov.GetCov("Spain");
```

>Checks if exist the country and get all the information. The information is stored in properties

```
cov.TotalConfirmed;
cov.NewConfirmed;
cov.TotalDeaths;
cov.NewDeaths;
cov.TotalRecovered;
cov.NewRecovered;
```

>This is the properties
