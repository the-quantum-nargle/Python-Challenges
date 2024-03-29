# Weather API Python Wrapper

This directory contains the Python wrapper for the OpenWeatherMap API, which enables users to fetch and display weather information for specified locations.


## Dependencies

This project requires the following Python libraries:

- `requests`: Used to make HTTP requests to external APIs.
- `python-dotenv`: Used to load environment variables from a `.env` file.

To install these dependencies, run the following command:

```bash
pip install requests python-dotenv
```

## Setup

An `.env` file should already exist in this directory. You need to edit this file with your OpenWeatherMap API key.

1. Open the `.env` file located in this directory.
2. Add your API key to the file like this:

   ```env
   OPENWEATHER_API_KEY=your_api_key
   ```
Replace `your_api_key` with your personal API key from OpenWeatherMap.


## Usage

1. Ensure you've installed all dependencies and edited .env file. Run the Python script from the command line:
    ```bash
    python WeatherAPI.py
    ```

2. Follow the command line prompts to enter the city name.

    The script will print the weather data to the command line.


## Contributions

Contributions to this wrapper are welcome. Please ensure to follow the contribution guidelines outlined in the main project README.

## License

This wrapper is released under the MIT license. See the LICENSE file in the root directory for full details.

## Contact

If you have any questions or feedback regarding this wrapper, please file an issue in the main project repository.


