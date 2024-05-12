# Graph Neural Networks for Disease Prediction within the Department of Energy

## Abstract
We present a graph neural network to predict employee-level instances of multiple myeloma at Department of Energy/National Nuclear Security Administration sites. Improved prediction of worker safety and health issues is important for preventative care, and a stated goal for the department as well. Our graph neural network model was trained on multiple myeloma data collected & aggregated from the study in Wing et al, 2000. The datasets in question were retrieved from the Department of Energy’s Comprehensive Epidemiological Data Resource and represented operational data from the Manhattan project through 1979. The data was wrangled into a graph dataset representing employees, buildings, chemical agents & hazardous materials, and sites within the Department of Energy and the interactions between these distinct entities. Our convolutional graph neural network was trained on these data, and retrieved a classification accuracy of 93%. 

## Links
- Link to [thesis paper](https://docs.google.com/document/d/1ykkNsB8uHsSuHsSlIGcACoHuX7Cu0kT-a-__kL0hpf0/edit?usp=sharing)
- [Primary Colab notebook](https://colab.research.google.com/drive/1ZVIQyoNe5XVlMrX6asHCDpUpBu2cTt0L#scrollTo=xRH1HNiOmTFD) (also included in this repository)
- Data was used from the [DOE's Comprehensive Epidemiological Data Resource (CEDR)](https://oriseapps.orau.gov/cedr/) and is available to users who have submitted an application to the CEDR ([see here](https://oriseapps.orau.gov/cedr/sign-up-web-form.aspx))
