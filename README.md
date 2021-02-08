# Camp DB


## About The Project

This is a project to keep track of free camp sites that are stumbled upon and not necessarily listed anywhere else on the internet.  This will focus more on dispersed and primative campsites but anywhere you can sleep in a tent is fine. 


### Built With

* Python
* Django
* PostgreSQL

## Getting Started

This section tells you about getting started in working in this project.

### Prerequisites

* Python 3.8

### Installation

1. Clone the repo
    ``` sh
    git clone https://github.com/sbunnewith/camp-db.git
    ```
1. Change to the directory
    ``` sh
    cd camp-db
    ```
1. Setup a virtual environment
    ``` sh
    python3 -m venv venv
    ```
1. Activate the virtual environment
    ``` sh
    source venv/bin/activate
    ```



## Usage

## Design

### Objects

* Campsite
    * Location
    * Fee
    * Pictures
    * Name
    * ID
    * Date Entered
    * Last Updated
    * Description
    * Amenities
* Users
    * Name
    * ID
    * Picture
    * Email
    * Location

### Services

* Search
    * By Location
        * Radius
    * By User ID
    * By Campsite Name
    * By Fee
    * By Amenities

## License