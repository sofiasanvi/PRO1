# PRO1 - Eukaryotic plankton diversity in the sunlit ocean
Sofia Klangby & Nubaid Khan

<img src="data/Diatoms_through_the_microscope.jpg" width="600">
source:wikipedia
Our approach: 
We identified that from the data that we found in our article we could set the random variable to the number of planktion species in the sample. With this approach we could plot the data into a histogram and see the distribution. We later due to some observations on the data, it came from different oceans and had a variance much larger than the mean, we concluded that we should use a negative bionomial model to fit to our data. Using the mean and the variance from our data we could calculate the n and p parameters in our model. 

[
X \sim \text{NegativeBinomial}(n,p)
]

where (X) represents the number of different OTUs in one sample, with the unit OTUs per sample.
n – a shape/dispersion parameter with no physical unit. A larger value gives less relative variation, while a smaller value allows more variation between samples.

p – a probability parameter between 0 and 1 and has no unit. For a fixed value of (n), a lower (p) gives a higher expected number of OTUs and a larger variance.


How to run the code:
The code in the form of a jupyter notebook which can be opened in google Colab and runned pressing the run bottom. To do so you need to dowload the data that can be accessed in the data folder. The data is stored in a zip file which can easily be unzipped and you get the tsv-file which is used in this project. 
