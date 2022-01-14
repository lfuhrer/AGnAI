Notes on data organization and labels from original data sent by Luke.  

# 2019  
Total fields in 2019: 2    

---

## *1. Field: Big Shy a.k.a. Shy North (Keith Bowen/Colquitt)  
Status: need to find boundary file AND check on correct quality layer.  

  - **Boundary: could not find file.** 
  - Yield/elevation:  
    - path: ~/Worsley/2019/Shy North_export (1)/doc/Keith Bowen-Colquitt-Shy North-Cotton.shp  
    - n: 142,944
  - Quality:    
    - path: ~/Worsley/2019/Big Shy all data.csv  
    - n: 90  
    OR
    - path: ~/Worsley/2019/HIDC_CFF_KEITH BOWEN_COLQUITT_SHY NORTH.csv  
    - n: 91  


---
        
## *2. Field:  Big Half (Keith Bowen/Colquitt)  
Status: need to find quality layer.  

- Boundary:
    - path: ~/Worsley/2019/BigHalfUGAIrrigation/boundaries/boundaries.shp  
    
- Yield/elevation: 
    - path: ~/Worsley/2019/BigHalfUGAIrrigation/doc/Keith Bowen_Colquitt_Big Half_Harvest_2019-12-02_00.shp  
    - n: 29,790  
    
- **Quality: could not find file.**  NOT RECORDED!  

---

# 2020  
Total fields in 2020: 3  

---

## 3. Field: Big Half (Keith Bowen/Colquitt)   
Status: checked, conformed  

- Boundary:  
    - path: ~/Worsley/2020/Big_Half_2020/boundaries/boundaries.shp  
    
- Yield:  
    - path: ~/Worsley/2020/Big_Half_2020/doc/Keith Bowen_Colquitt_Big Half_Harvest_2020-11-23_00.shp  
    - n: 30,603  
    
- Quality:  
    - path: ~/Worsley/2020/Big_Half_2020/bighalf_all_data.csv  
    - n: 45  
    
--- 

## 4. Field: Fire Tower (Russ Worsley/Fire Tower Farms)   
Status: checked, conformed   

  - Boundary:  
    - path: ~/Worsley/2020/Fire_Tower_2020/boundaries/Keith Bowen_Colquitt_Fire Tower.shp  
    
  - Yield/elevation:  
    - path: ~/Worsley/2020/Fire_Tower_2020/doc/Keith Bowen_Colquitt_Fire Tower_Harvest_2020-11-23_00.shp  
    - n: 20,593  
    
  - Quality:  
    - path: ~/Worsley/2020/Fire_Tower_2020/firetower_all_data.csv  
    - n: 26  
    
  - **Other**: has an application shapefile. Need to ask what is it.

---

## 5. Hog House (Keith Bowen/Colquitt)    
Status: checked, conformed   

- Boundary:  
    - path: ~/Worsley/2020/Hog_House_2020/boundaries/Keith Bowen_Colquitt_Hog House.shp  
    
- Yield/elevation:  
    - path: ~/Worsley/2020/Hog_House_2020/doc/Keith Bowen_Colquitt_Hog House_Harvest_2020-11-25_00.shp  
    - n: 20,450  
    
- Quality:  
    - path: ~/Worsley/2020/Hog_House_2020/hoghouse_all_data.csv  
    - n: 31  

---
    
# 2021  
Total fields in 2021: 3  

---

## *6. John Weaver South (Keith Bowen/Colquitt)    
Status: need to find boundary file  

- Boundary:  
    - path: ~/Worsley/2021/John Weaver/Boundary.shp  
    
- Yield/elevation: 
    - path: ~/Worsley/2021/John Weaver South/JWS_2021_Harvest/doc/Keith Bowen_Colquitt_john weaver _Harvest_2021-11-03_00.shp  (ON A DIFFERENT ROOT FOLDER!)
    - n: 12,244
- **Quality: could not find file.** 

---
  
## *7. John Weaver North (Keith Bowen/Colquitt)  
Status: need to find quality layer.  

- Boundary:  
    - path: ~/Worsley/2021/John Weaver South/Planting/Boundary2.shp  
    
- Yield/elevation:  
    - path: ~/Worsley/2021/John Weaver/JW_2021_Harvest/doc/Keith Bowen_Colquitt_John Weaver_Harvest_2021-11-03_00.shp  
    - n: 10,336  
    
  - **Quality: could not find file.**  

---

## *8. Shy North (Keith Bowen/Colquitt)  
Status: need to find boundary file AND quality file.  

  - **Boundary: could not find file.**  
  - Yield/elevation:  
    - path: ~/Worsley/2021/Shy North/Shy_North_2021/doc/Keith Bowen_Colquitt_Shy North_Harvest_2021-11-23_00.shp  
    - n: 18,526  
    
  - **Quality: could not find file.**  
  

# Questions  
## Yield layers  
I am assuming that the yield layers are the ones with the column "VRYILDBAL". Is that right? If so, what is this column and what is its measurement unit, and how is it used to calculate yield?  

Has yield data been cleaned? If not, what is common practice for cleaning cotton yield data (Yield Editor from USDA, other?).  


## Quality layers  
As of now, quality layers are point shapefile. Do we have a polygon shapefile to identify them?  

What is the complete name of the quality column headers? What units are they in?  

# Notes from Meeting Jan 14th  

Shy North 2019 and 2021 have treatments.  
John Weaver 2021 is skp-row, but does not appear on files.  
For 2021 season, Luke just got fiber quality yesterday,  

bales/ac or lbs/ac. 
1 module made up of seed cotton (fiber, seed, trash), pre-gin.  
lbs/ac is seed cotton. 
bales/ac is derived from seed cotton (40% of lbs/ac is actually lint that then expressed as bales/ac), lint/gin turnout.  

irrigated ~ 2 bales/ac   
micronaire has a quadratic response with loan, depending on whether it is under or over mature.  



