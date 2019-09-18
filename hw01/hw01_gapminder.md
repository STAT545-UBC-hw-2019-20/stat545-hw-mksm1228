---
title: "**Gapminder Exploration**"
output: 
  html_document:
    theme: cerulean
    toc: true
    keep_md: true
---
### **Introduction**

-----------------------

##### I performed an exploratory data analysis on the Gapminder data set using the functions I learned from class meetings 2 and 3. I also set echo = FALSE for all the code chunks to prevent the code, but not the results from appearing in the finished file. 



--------------------------------------------------------------------------

### **How many rows and variables does this data set contain?**

```
## [1] "This dataset has 1704 rows and 6 variables."
```
### **What are the names of the variables?**

```
## [1] "country"   "continent" "year"      "lifeExp"   "pop"       "gdpPercap"
```
### **Which countries does this data set contain?**

```
##   [1] Afghanistan              Albania                 
##   [3] Algeria                  Angola                  
##   [5] Argentina                Australia               
##   [7] Austria                  Bahrain                 
##   [9] Bangladesh               Belgium                 
##  [11] Benin                    Bolivia                 
##  [13] Bosnia and Herzegovina   Botswana                
##  [15] Brazil                   Bulgaria                
##  [17] Burkina Faso             Burundi                 
##  [19] Cambodia                 Cameroon                
##  [21] Canada                   Central African Republic
##  [23] Chad                     Chile                   
##  [25] China                    Colombia                
##  [27] Comoros                  Congo, Dem. Rep.        
##  [29] Congo, Rep.              Costa Rica              
##  [31] Cote d'Ivoire            Croatia                 
##  [33] Cuba                     Czech Republic          
##  [35] Denmark                  Djibouti                
##  [37] Dominican Republic       Ecuador                 
##  [39] Egypt                    El Salvador             
##  [41] Equatorial Guinea        Eritrea                 
##  [43] Ethiopia                 Finland                 
##  [45] France                   Gabon                   
##  [47] Gambia                   Germany                 
##  [49] Ghana                    Greece                  
##  [51] Guatemala                Guinea                  
##  [53] Guinea-Bissau            Haiti                   
##  [55] Honduras                 Hong Kong, China        
##  [57] Hungary                  Iceland                 
##  [59] India                    Indonesia               
##  [61] Iran                     Iraq                    
##  [63] Ireland                  Israel                  
##  [65] Italy                    Jamaica                 
##  [67] Japan                    Jordan                  
##  [69] Kenya                    Korea, Dem. Rep.        
##  [71] Korea, Rep.              Kuwait                  
##  [73] Lebanon                  Lesotho                 
##  [75] Liberia                  Libya                   
##  [77] Madagascar               Malawi                  
##  [79] Malaysia                 Mali                    
##  [81] Mauritania               Mauritius               
##  [83] Mexico                   Mongolia                
##  [85] Montenegro               Morocco                 
##  [87] Mozambique               Myanmar                 
##  [89] Namibia                  Nepal                   
##  [91] Netherlands              New Zealand             
##  [93] Nicaragua                Niger                   
##  [95] Nigeria                  Norway                  
##  [97] Oman                     Pakistan                
##  [99] Panama                   Paraguay                
## [101] Peru                     Philippines             
## [103] Poland                   Portugal                
## [105] Puerto Rico              Reunion                 
## [107] Romania                  Rwanda                  
## [109] Sao Tome and Principe    Saudi Arabia            
## [111] Senegal                  Serbia                  
## [113] Sierra Leone             Singapore               
## [115] Slovak Republic          Slovenia                
## [117] Somalia                  South Africa            
## [119] Spain                    Sri Lanka               
## [121] Sudan                    Swaziland               
## [123] Sweden                   Switzerland             
## [125] Syria                    Taiwan                  
## [127] Tanzania                 Thailand                
## [129] Togo                     Trinidad and Tobago     
## [131] Tunisia                  Turkey                  
## [133] Uganda                   United Kingdom          
## [135] United States            Uruguay                 
## [137] Venezuela                Vietnam                 
## [139] West Bank and Gaza       Yemen, Rep.             
## [141] Zambia                   Zimbabwe                
## 142 Levels: Afghanistan Albania Algeria Angola Argentina ... Zimbabwe
```

### **Which continents does this data set contain?**

```
## [1] Asia     Europe   Africa   Americas Oceania 
## Levels: Africa Americas Asia Europe Oceania
```


### **What is the smallest and largest year this data set contains? What is the mean and median?**

```
## [1] "The smallest year is 1952 and the largest year is 2007 . The mean is 1979.5 and the median is 1979.5 ."
```


### **What is the lowest and highest life expectancy? What is the mean and median?**

```
## [1] "The lowest life expectancy is 23.599 and the highest life expectancy is 82.603 years. The mean is 59.4744393661972 and the median is 60.7125 ."
```

### **What is the smallest and largest population? What is the mean and median?**

```
## [1] "The smallest population is 60011 and the largest population is 1318683096 . The mean is 29601212.3245305 and the median is 7023595.5 ."
```


### **What is the lowest and highest GDP per capita? What is the mean and median?**

```
## [1] "The lowest GDP per capita is 241.1658765 and the highest GDP per capita is 113523.1329 . The mean is 7215.32708121215 and the median is 3531.8469885 ."
```

### **Summary of the Gapminder data set**

```
##         country        continent        year         lifeExp     
##  Afghanistan:  12   Africa  :624   Min.   :1952   Min.   :23.60  
##  Albania    :  12   Americas:300   1st Qu.:1966   1st Qu.:48.20  
##  Algeria    :  12   Asia    :396   Median :1980   Median :60.71  
##  Angola     :  12   Europe  :360   Mean   :1980   Mean   :59.47  
##  Argentina  :  12   Oceania : 24   3rd Qu.:1993   3rd Qu.:70.85  
##  Australia  :  12                  Max.   :2007   Max.   :82.60  
##  (Other)    :1632                                                
##       pop              gdpPercap       
##  Min.   :6.001e+04   Min.   :   241.2  
##  1st Qu.:2.794e+06   1st Qu.:  1202.1  
##  Median :7.024e+06   Median :  3531.8  
##  Mean   :2.960e+07   Mean   :  7215.3  
##  3rd Qu.:1.959e+07   3rd Qu.:  9325.5  
##  Max.   :1.319e+09   Max.   :113523.1  
## 
```

### **Ending Remarks**
This concludes my exploratory data analysis of the Gapminder data set.

