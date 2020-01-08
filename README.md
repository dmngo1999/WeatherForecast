# WeatherForecast

RNN-based model for weather prediction in cities using GRU network and crowd-sourced data

## Getting Started

Get weather data from your chosen city as well as four other nearby cities, in my case I chose Ho Chi Minh city, Hanoi, Danang, Haiphong, and Can tho. Then, parse the data into the correct format to be read as inputs (Parse function in hochiminh weather.ipynb). Use meteoblue.com for 2 week periods for free.

### Prerequisites

```
matplotlib.pyplot
tensorflow
numpy
pandas
os
MinMaxScaler from sklearn
Keras
```

## Running the tests

Change the name of the target_city variable to the city you want to forecast. Then change the shift_days to the number of days that you want predict the weather by.


### To see how accurate the model is, run the code to see comparisons between training and test files.



## Additional

You can play around with the model by changing the activation function, adding more layers, different inputs, etc...

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

