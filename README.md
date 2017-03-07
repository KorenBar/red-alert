# Features

* Get red-alerts in real-time from "Pikud ha-oref" public API

* Fetch location data from alerts codes (coordinates, city names, time to run for shelters)

* Generate random coordinates within a city for virtualizing flying rocket

* Count number of alerts currently there is

# FAQ

### Q) Why is this even helpful?

*    The Class I made is helpful for developers and makers as one
     Who are willing to develop platforms / apps based on Israeli "Pikud ha-oref" system.
     The class provides the necessary functions and tools to get the latest information
     About the Israeli missiles status and when Israel is under attack.

### Q) Isn't the enemy can use it against Israel?

*    No. All the information in the Class is public and available,
     All I did is to organize it at one place for easy access.
     I also scraped and organized the cities names with their area codes for easy reading.

### Q) Is it possible to predict or to know where exactly the missile will land?

*    No, at least not for the developers. the military may have such capabilities.
     The prediction is not possible due to many parameters such as:
     Where the rocket came from, how many fuel inside the rocket, what speed the rocket flying it,
     Directions of the rocket and weather conditions - something which make it impossible for any
     non-military individual, even with technology such as machine learning and prediction algorithms.

### Q) Can I take the code and make a product of my own using your Class?

*    Absolutely. The code and everything inside the repository is open-sourced.
     The Code is under MIT license - please make sure to understand the meaning.
     The Code provided AS IS WITHOUT ANY WARRANTY.

### Q) How can I virtualize how much time the rocket have till it will hit the city?

*    Use the milliseconds calculated from how much time left for people to run to shelters,
     Then virtualize using that seconds of long the rocket has to fly till it will hit the city.

# Requirements

* Python requests library
```sh
$ sudo pip install python-requests
```
