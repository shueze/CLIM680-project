

## <font face="Times New Roman" >  Who's secretly compromising your health: an Introduction to Particulate Matter (PM) in the US </font>

[Proposal](https://shueze.github.io/CLIM680-project/proposal)   

### **<font face="Times New Roman" >  Introduction </font>**  

<font face="Times New Roman" >  
Particulate Matter (PM), also known as particle pollution, is a mixture of solid particles and liquid droplets in the atmosphere. The most famous PM are PM10 (with diameter generally 10mm and smaller) and PM2.5 (with diameters generally 2.5mm and smaller). Exposure to PM can pose great risk to our health, causing respiratory and cardiovascular deseases. In this study, we briefly investigate the characteristics of PM distribution and discuss its seasonal and diurnal evolution . 
</font>  

### **<font face="Times New Roman" >  Data </font>**  

<font face="Times New Roman" >  
CMAQ (Community Multiscale Air Quality Modeling System) output data. CMAQ ingests emissions and meteorology to predict spatial and temporal variations of chemical components such as PM2.5, O3, NO2, and their precursors (Byun and Schere, 2006; Luecken et al., 2019). The model has a 12 km horizontal resolution over the Continental United States (CONUS) region and its surrounding areas. The dimension of this dataset is 24 timesteps x 35 layers x 265 rows x 442 columns.  
</font>

### **<font face="Times New Roman" >  Environment </font>**  

<font face="Times New Roman" >  
The environment settings used in this project have been provided in the new_clim_data.yml file.
</font>

### **<font face="Times New Roman" >  Results  </font>**  

#### <font face="Times New Roman" >  Monthly Mean (July and January) </font>  

<font face="Times New Roman" > 
By comparison betwwen PM10 levels, we can see that the PM10 in July is generally higher than the level in January. While the maximum level in July is over 30ug/m3, the level remains below 20ug/m3 in January. Also, in July, the midwest region has the highest level, while in January, high PM10 locate around midwest to southest region, and the west region's PM10 level is rather low.  
  
Acoording to EPA, the annual healthy standard is 50ug/m3. Areas with values higher than 50 is hatched with dots.
</font>  

![Screen Shot 2022-11-26 at 15 22 22](https://user-images.githubusercontent.com/49365141/204107710-fdac5f4a-4aad-4c52-930f-06ee9b57898f.png){:height="48%" width="48%"}
![Screen Shot 2022-11-26 at 15 22 41](https://user-images.githubusercontent.com/49365141/204107713-da3b3bec-3947-47ff-8335-380d49cbb112.png){:height="48%" width="48%"}

<font face="Times New Roman" > 
PM2.5 levels have similar patterns with PM10 levels, with about half of PM10 values. This is in line with previous work of Wanger and Ganor (1999).  
</font>    

<font face="Times New Roman" > 
Acoording to EPA, the annual healthy standard is 15ug/m3. Areas with values higher than 15 is hatched with dots.
</font>  



![Screen Shot 2022-11-26 at 15 24 34](https://user-images.githubusercontent.com/49365141/204107779-333bdc82-dcf6-4bae-9ba4-dad6091dd3d4.png){:height="48%" width="48%"}
![Screen Shot 2022-11-26 at 15 24 49](https://user-images.githubusercontent.com/49365141/204107780-76c523f2-1fe2-4003-9b6a-b79646910f07.png){:height="48%" width="48%"}  

<font face="Times New Roman" > 
The ratio between PM2.5 and PM10 shows whether the PM is from local sources or transmitted from other places. That's because heavier particals (like PM10) get subsidized during tranmission. So when the dust is transmitted from other areas, it's characterized with high value of PM2.5/PM10 ratio.  
  
As is shown in the figures, areas at the edge of the US have higher PM2.5/PM10 ratio than the center region. That implies transmission of PM affect the edges of the US more than the center region, which makes sense physically.  For the reason why the ratio is higher in January than in July, it might be related to the seasonal variation of surface wind speed.  
</font>  

![Screen Shot 2022-11-27 at 21 04 32](https://user-images.githubusercontent.com/49365141/204176997-06a49def-68e8-42e3-a10d-d9b42e22c284.png){:height="48%" width="48%"}
![Screen Shot 2022-11-28 at 10 14 47](https://user-images.githubusercontent.com/49365141/204313477-80844b88-0a91-4995-b014-62cea2152bb3.png){:height="48%" width="48%"}

#### <font face="Times New Roman" >  Monthly Correlation (July and January) </font>  
<font face="Times New Roman" > 
The correlation between PM10 and PM2.5 implies whether they are from the same sources. PM10 and PM2.5 with higher correlation are more likely from the same sources. As is shown, most of their correlation coefficient in the US is above 0.9.  
</font>  

![Screen Shot 2022-11-27 at 20 30 13](https://user-images.githubusercontent.com/49365141/204314834-3f80fb5f-7705-416d-bdaf-835270267d71.png){:height="48%" width="48%"}
![Screen Shot 2022-11-27 at 20 36 18](https://user-images.githubusercontent.com/49365141/204314858-5439f2a1-2cf8-485f-b5fc-eb3cb70cf997.png){:height="48%" width="48%"}



#### <font face="Times New Roman" >  Monthly Diurnal Mean  </font>

<font face="Times New Roman" > 
EST time zone offset is UTC-05.   
So the first row: evening (5pm to 2am est);   
the second row: morning   (3am to 10am est);   
the third row: afternoon  (11am to 18pm est).   
</font>  

****
<font face="Times New Roman" > 
From the plots, we can see that the maximum PM10 level in July is reached at around 5~6 PM in the middle region of the US, the minimum is at arund 5~6 AM. 
The PM10 level seems to vary less in January than in July, to varify that, I plot the area mean of PM10 (which is also the "Climate Index" I will use to do the composites later in this project). 
We can see that the area mean varies from 7 to 11 ug/m3 in July, whereas it's from 8 to 9 in January. Also, their diurnal maximum and minimum time have differences.  
</font>  

![Screen Shot 2022-11-14 at 16 29 16](https://user-images.githubusercontent.com/49365141/201769533-1c47b1dd-18d0-4998-9eca-8289ae314da7.png){:height="48%" width="48%"}
![Screen Shot 2022-11-14 at 16 31 26](https://user-images.githubusercontent.com/49365141/201769987-50c6377c-0cfc-4636-b3b5-c85f55cd8fb0.png){:height="48%" width="48%"}

![Screen Shot 2022-11-29 at 11 20 31](https://user-images.githubusercontent.com/49365141/204584695-3056cc33-f276-4112-a68f-80697388df30.png)

#### <font face="Times New Roman" >  PM10 Composite of different diurnal PM10 level phases in July  </font>  

<font face="Times New Roman" > 
From the plotting, we can see that the PM10 level at the eastern coast is above 20ug/m3 even in Low level composite. Generally, the middle to eastern part of the US and the western coast have higher PM10 levels. With the area mean increasing, PM10 level increases quickly in the middle part of the US up to above 80ug/m3. While in the other areas, the level increases a little or remains on the same level. 
</font>  

![download](https://user-images.githubusercontent.com/49365141/204108887-9515b442-7be5-43e8-aaac-fc0e7246a335.png)


### **<font face="Times New Roman" >  Summary  </font>**  

<font face="Times New Roman" > 
In this study, we learnt that Particulate Matter in the United States is in general under healthy level, but in some regions especaily the central part, PM level should have more attention from people. Also, PM level varies on different temporal scales, whether seasonally or diurnally. PM transmission affect the edges of the US more than the central region. And Surface winds have impact on the PM level. All in all, don't do cardio outdoors at 5~6 PM in the central region of the US during summer.
</font>  

### **<font face="Times New Roman" >  Codes  </font>**  

[Climatology](https://github.com/shueze/CLIM680-project/blob/main/Project.ipynb)   
[Correlation](https://github.com/shueze/CLIM680-project/blob/main/Correlation.ipynb)   
[Composites](https://github.com/shueze/clim680/blob/master/Composites.ipynb)   

### **<font face="Times New Roman" >  References  </font>**  

<font face="Times New Roman" > 
Byun, D. W., & Schere, K. L. (2006). Review of the governing equations, computational algorithms, and other components of the models-3 community multiscale air quality (CMAQ) modeling system. Applied Mechanics Reviews, 59, 51-77. http://dx.doi.org/10.1115/1.2128636. 
</font>  

****  

<font face="Times New Roman" > 
Ganor, E., Stupp, A. & Alpert, P. A method to determine the effect of mineral dust aerosols on air quality. Atmospheric Environment 43, 5463–5468 (2009).
</font>  

****  

<font face="Times New Roman" > 
Luecken DJ, Yarwood G, Hutzell WT. Multipollutant modeling of ozone, reactive nitrogen and HAPs across the continental US with CMAQ-CB6. Atmos Environ (1994). 2019 Mar 15;201:62-72. doi: 10.1016/j.atmosenv.2018.11.060. PMID: 33981178; PMCID: PMC8112378.  
</font>  
