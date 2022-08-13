# yelppy

Simple functionality to convert yelp search API to pandas dataframe. 

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install yelppy.

```bash
pip install yelppy
```

## Usage
Before using the package, please get the yelp api from [Yelp](https://www.yelp.com/developers/v3/manage_app)
```python
import yelppy

# returns 'pandas.dataframe'
df = yelppy.query_api('API_KEY','Search_term','Location')

```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)