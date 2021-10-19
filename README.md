# python-api-challenge
Repository for Python API Homework

This repository contains three folders:

    Weather: This folder contains the jupyter notebook WeatherPy.ipynb
                This notebook should be executed first as its output is used by the next notebook

    Vacation: This folder contains the jupyter notebook VacationPy.ipynb
                This notebook reads in the output file from the first notebook

    output_data: This folder contains the output csv from WeatherPy.ipynb that is then read in by
                    VacationPy.ipynb

Important note: A keys file named api_keys.py must be created in the repository root since it used by 
                    both notebooks using relative path file importing.
                This file should contain entries for weather_api_key (an open weather API key)
                and g_key (A google maps API key)
