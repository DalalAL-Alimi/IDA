# IDA: Improving Distribution Analysis for Reducing Data Complexity and Dimensionality in Hyperspectral Images

This is the main code of the paper, which is [here](https://doi.org/10.1016/j.patcog.2022.109096)

## Abstract
Hyperspectral images (HSIs) are known for their high dimensionality and wide spectral bands that increase redundant information and complicate classification. Outliers and mixed data are common problems in HSIs. Thus, preprocessing methods are essential in enhancing and reducing data complexity, redundant information, and the number of bands. This study introduces a novel feature reduction method (FRM) called improving distribution analysis (IDA). IDA works to increase the correlation between related data, decrease the distance between big and small data, and correct each value's location to be inside its group range. In IDA, the input data passes through three stages. Getting rid of outliers and improving data correlation is the first step. The second stage involves increasing the variance. The third is to simplify the data and normalize the distribution. IDA is compared with four popular FRMs in four available HSIs. It is also tested and evaluated in various classification models, including spatial, spectral, and spectral-spatial models. The experimental results demonstrate that IDA performs admirably in enhancing data distribution, reducing complexity, and accelerating performance.

### The requested packages:
 
  
> - Tensorfolow 2.6.0 
> - keras 2.10.0 
> - matplotlib 3.53 
> - numpy 1.23.2 
> - pandas 1.4.4 
> - plotly 5.10.0 
> - scikite-image 0.19.3 
> - seaborn 0.12.0 
> - sklearn 
> - spectral 0.22.4 


## Citation
### We would appreciate a citation to the original paper if you use this code in your research works.
```
{
  @article{ALALIMI2022109096,
  title = {IDA: Improving Distribution Analysis for Reducing Data Complexity and Dimensionality in Hyperspectral Images},
  journal = {Pattern Recognition},
  pages = {109096},
  year = {2022},
  issn = {0031-3203},
  doi = {https://doi.org/10.1016/j.patcog.2022.109096},
  url = {https://www.sciencedirect.com/science/article/pii/S0031320322005763},
  author = {Dalal AL-Alimi and Mohammed A.A. Al-qaness and Zhihua Cai and Eman Ahmed Alawamy},
  }
}
```
