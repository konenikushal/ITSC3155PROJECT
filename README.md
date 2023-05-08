# Online Store Template

## Description

We've created a simple checking and booking system for flights between various cities across the United States. A user is able to add a flight after searching to their cart and then manage those existing flights.

## How to Use

To run this project, you simply need to have Python 3.10 installed on your machine. You can download Python 3.10 from the [official website](<https://www.python.org/downloads/release/python-3108>).

### Setup Script (Recommended)

A script titled `setup.sh` is included at the root of this repository, which will automatically install the required dependencies and set up the database. To run this script, execute the following command:

```bash
bash setup.sh
```

If you instead prefer to manually install the python module dependencies, run the following command:

```bash
pip install -r requirements.txt # or pip3 install -r requirements.txt if pip is not set to use Python 3
```

### Running the Server

Another script titled `run.sh` is also included at the root of this repository, which will automatically run the application. Execution of this script is recommended but not required. If you would like to manually run the server, run the following command:

```bash
./run.sh # or bash run.sh if permissions are not set
```

## Documentation Style

Across all files, classes and functions are documented using docstrings, which are formatted according to the [Google Python Style Guide](<https://google.github.io/styleguide/pyguide.html#38-comments-and-docstrings>).

Additionally, `authentication`, `core`, `database`, `static` `templates`, and `tests` each contain their own `README.md` file, where the contents of each directory are described in more detail.

## Testing

The unit tests are kept across various files in the `testing` directory. From the root of the repository, you can run the `test.py` script to check all unit tests, which will generate a report in the `testing/reports` directory.
