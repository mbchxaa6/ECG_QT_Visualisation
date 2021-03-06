# The Impact of Pseudo-Colour and Coordinate System on ECG Interpretation

We conducted a resaerch showing that visualising an electrocardiograph (ECG) on Cartesian/Polar coordinates, and applying pseudo-colouring under the area of ECG signal, significantly helps lay-people to detect increases in the QT-interval at low normal heart rate (60bpm), when compared with a normal ECG baseline. Here is the link for the research paper: https://dl.acm.org/citation.cfm?id=3300353

## Getting Started

This repository will give you a copy of the R-scripts used to create the visualisations and the raw ECG signals on your local machine for development and testing purposes. 

### Prerequisites

You need to install R and RStudio software to run the scripts.

```
https://www.rstudio.com/products/rstudio/download/
```

You need also to install some R packages including  

```
(pracma)
(readr)
(tibble)
(signal)
(readxl)
(dplyr)
(tidyr)
(ggplot2)
(ggcyto)
```

### Images folder

The images folder containes full size image (PNG type) showing visualisation examples of normal
(QT < 430), borderline (QT > 440 and QT < 470), prolonged (QT > 470 and QT < 500) and very prolonged (QT > 500) QT-intervals. 
The image name are coded as the value of QT-interval in millisconds and the type of the visualisation technique, where 'C' indicates Cartesian, 'CC' indicates Cartesian with Colour, 'P' indicates Polar and 'PC' indicates Polar with Colour.

## R-scripts folder

The R-scripts used to create the visualisation techniques are provided for each QT exmaple, along with the excels files of the raw ECG signals. 

## Built With
RStudio software version 1.1.447.

## Authors

**Alaa Alahmadi** - **Caroline Jay** 




