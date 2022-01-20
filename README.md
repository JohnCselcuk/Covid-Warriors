# Covid Warriors
## Project Outline
### Pre-processing
After deciding on a dataset from the CDC, we were able to do some data cleaning in Pandas:
* Filtered the dataset to show North Carolina cases only
* Remove and rows that contained null or unknown values
* Dropped columns with unnecessary data for our project

Once cleaned, we exported the DataFrame to a csv file to get ready for some exploritory analysis. 

### Exploritory Analysis
We plan to use matplotlib and numpy to begin visualizing how we might begin to use the dataset to answer possible questions:
* How do demographic factors impact the sevarity of COVID illness?
* Can we predict the rate of hospitalizations and deaths using machine learning based on those facotrs?