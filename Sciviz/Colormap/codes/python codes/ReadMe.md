### **Codes in this folder:**

* animation.py  
* get\_day.py  
* global\_max\_min.py  
* plot\_colorscale.py  
* plot\_sampled\_days.py  
* plot\_seq\_div.py  
* get\_data.py  
* vs\_2005.nc  
* pr\_2005.nc


  

## **Description of each file:**

\- animation.py \- Creates Animation GIFs for sampled days.  
\- get\_day.py \- Used to return dates of the day index.  
\- get\_data.py \- loads data from the dataset.  
\- global\_max\_min.py-  Returns Global min max for variables of  sampled days  
\- plot\_colorscale.py \- Plots colormap using discrete , continuous and logarithmic scales.   
\- plot\_sampled\_days.py \- Plots colormap for sampled days using chosen colorscale (continuous) and colormap(viridis \- sequential)  
\- Plot\_seq\_div.py \- experiments with different colormaps using different divergent and sequential  colormaps  
\- vs\_2005.nc \= dataset for wind-speed variable  
\- pr\_2005.nc \= dataset for precipitation amount variable

## **Dependencies to install beforehand :**

* pip install numpy  
* pip install matplotlib  
* pip install netCDF4  
* pip install scipy  
* Download the entire “python codes” folder into a **single directory**.  
* This folder contains the datasets used in code as well as all the .py codes..  
* IIf one is unable to download dataset  ,please download **pr\_2005.nc** and **vs\_2005.nc** files from the dataset folder (or this [link](https://www.northwestknowledge.net/metdata/data/) ) into  the same directory.

**Details on how to run :**

To get Animated GIFs

- The code to generate animated GIFs is in animation.py. After installing and downloading everything that is mentioned in the previous point , save and run the animation.py code using command  **python animation.py**  
- “finalprecipitation\_animation.gif”  and “finalwind\_animation.gif”  files will be created after running animation.py , and prints saved on console.  It will take a few seconds to create files.  
- Animation GIF for sampled days for both precipitation and wind speed variables can be seen. We can experiment by changing the colormaps and colorscales in the code. 

To tryout  different colorscales:

- The code to run to generate different colorscales is **plot\_colorscale.py**. Running this file after following all the downloads and installation instructions should generate plots for discrete,continuous and logarithmic scales. Run using command **python plot\_colorscale.py.** The plot wil pop up.

To try out different colormaps:

- The code to run to generate different colormaps is **plot\_seq\_div.py**. Running this file after following all the downloads and installation instructions should generate plots for discrete,continuous and logarithmic scales. Run using command **python plot\_seq\_div.py.** The plot wil pop up.


  
To get colormaps for all the sampled days for wind speed and precipitation variable:

- The code to run to generate colormaps for all the sampled days for wind speed and precipitation variable is **plot\_sampled\_days.py.**  Running this file after following all the downloads and installation instructions should generate plots for discrete,continuous and logarithmic scales. Run using the command **python plot\_sampled\_days.py.** This will take a few time to generate all the plots one by one.The plots wil pop up one by one.

  
