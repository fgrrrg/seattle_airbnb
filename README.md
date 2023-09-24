# The intricacies of Seattle’s Airbnb scene
A short analysis of airbnb in seattle based on kaggle dataset from 2016.

Files in the repository:
* seattle.ipynb: Jupyter notebook with the code
* listings.csv: dataset containing the listed residences on Airbnb in Seattle in 2016.

  Source of the data: https://www.kaggle.com/datasets/airbnb/seattle

Necessary libraries:
* Pandas
* Numpy
* Matplotlib
* Seaborn

### Business understanding:

Looking for answers for the following questions:

 * How the review scores influence the booking frequency?
 * Is it beneficial to choose or become a “superhost”?
 * Should you manage your Airbnb apartment yourself, or is it more advantageous to use the services of a professional Airbnb apartment manager?
  

### Data understanding:
The dataset contains 3818 accommodations in Seattle with a lot of details about both the host and the residence itself.

### Data preparation:

  There a few columns with significant amount of null values, or only one unique values.
  
  Added a few new columns like price per bed/accommodate
  
### Model data:

  Statistical analysis regarding the mentioned questions
  
### Results:

  Overall, the data showed us among the many excellent Airbnb hosts in Seattle, the Superhosts stood out, providing even higher quality service, while the “professional” hosts although offering cost effective residences, manage lower amount of reservations and a bit lower quality service.
The analysis was published here: https://medium.com/@fgergo/the-intricacies-of-seattles-airbnb-scene-a97d7a88de27

### Acknowledgements:
  The dataset is publicly available here: https://www.kaggle.com/datasets/airbnb/seattle
