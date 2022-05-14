<div id="top"></div>



<!-- PROJECT SHIELDS -->

[![MIT License][license-shield]][license-url]
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ning-yu-kao)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kaoningyupage/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kaoningyu@gmail.com)





<!-- PROJECT LOGO -->
<br />
<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1uh11jOUhul6ZCZjakydjvDK0eiwJqwrq" width="500" height="200">
  <h1 align="center">Tesla Stock Price Prediction using Rolling Regression and Prophet</h1>
  <p>Everybody knows that stock is extremely hard to predict, especially TESLA. (You know, Elon Musk somehow control the stock market...) Nevertheless, modern machine learning model had been built, with better architecture. Therefore, this method is conduct in order to follow up some new technology and pratice.</p>
</div>



<!-- TABLE OF CONTENTS -->
<details open>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#references">References</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

In this project, different methods were used to predict stock price of Tesla. We demonstrate models from the oldest polynomial regression model to the modern forecasting model, Prophet, published by Meta here. Furthermore, we can compare both models and dig into them.



### Built With

This is major frameworks/libraries used in this project.

* Python
* Jupyter

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Please follow the instruction below to set up your environment.

### Installation


1. Install packages

  * **Prophet**
   
    <img src="https://drive.google.com/uc?export=view&id=1AWWKKGCV3fqEv7yqqv7N7WK0-ZugDm7A" alt='https://facebook.github.io/prophet/' width="300" height="100">
    
    > Prophet is an open-source library developed by Facebook and designed for automatic forecasting of univariate time series data.
    
    You can just use `pip` to install Prophet. However, you should install `PyStan` first.
    
    ```bash
    pip install pystan==2.19.1.1
    pip install prophet
    ```
     
    For more installation detail, please check out [PROPHET](https://facebook.github.io/prophet/docs/installation.html#installation-in-python) official website.

<p align="right">(<a href="#top">back to top</a>)</p>

  * **Yahoo! Finance's API**
    
    > It's an open-source tool that uses Yahoo's publicly available APIs, and is intended for research and educational purposes.
    
    ```bash
    pip install yfinance
    ```
    
    Quick start to fatch stock data:
    
    ```python
    import yfinance as yf
    data = yf.download("SPY AAPL", start="2017-01-01", end="2017-04-30")
    ```



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>


## References
```bash
@article{prophet,
author = {Taylor SJ, Letham B.}
title = {Forecasting at scale},
journal = {PeerJ Preprints},
year = {2017},
doi = {https://doi.org/10.7287/peerj.preprints.3190v2},
}
```

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

These resources are which I would like to give credit to.
* [Time Series Forecasting With Prophet in Python](https://machinelearningmastery.com/time-series-forecasting-with-prophet-in-python/)
* [Free Stock Data for Python Using Yahoo Finance API](https://towardsdatascience.com/free-stock-data-for-python-using-yahoo-finance-api-9dafd96cad2e)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact
<div align="center">
  <h3>Please feel free to connect with me on social media</h3>
    <a href="https://github.com/ning-yu-kao">
        <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-github.png" width="3%"/>
    </a>
    <img width="3%" />
    <a href="https://www.linkedin.com/in/kaoningyupage">
        <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-linkedin.png" width="3%"/>
    </a>
    <img width="3%" />

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/ning-yu-kao/Med_scan_img_seg_unet/blob/main/LICENSE
