# Greenhouse_Plant_Growth Analysis Between IoT and Traditional Based Type.
Advanced IoT-Based Smart Greenhouse Dataset (Agriculture Growth Monitoring).

# About Dataset
This dataset contains physiological and morphological measurements of plants collected in an experimental study comparing IoT-based greenhouse systems with traditional greenhouses. It includes 30,000 samples with 14 columns representing growth metrics, chlorophyll levels, biomass data, and classification labels. The data was collected as part of a master’s thesis project at Tikrit University, aiming to analyze the effects of technology-driven agriculture.

# Aim Of The Project:
"The project aims to determine whether IoT-based or traditional greenhouses are more suitable for plant growth by analyzing growth patterns and environmental sensor data to assess yield productivity."

# Steps 1:
 **To Analysis:**
 - Average of chlorophyll in the plant for both IoT and Traditional green house
 - Average plant height rate for both IoT and Traditional green house
 - Average wet weight of the growth vegetative for both IoT and Traditional green house
 - To check for the correlation between ACHP	and some other variable like 'PHR', 'AWWGV', 'ADWV' 'ADWR', 'AWWR'. 
 # Step 2:  
  **Creation of Tableau Dashboard**:
 - To show and compare  the average of chlorophyll in the plant for both IoT and Traditional green house 
 - To show and compare average plant height rate for both IoT and Traditional green house
 - To show and compare average wet weight of the growth vegetative for both IoT and Traditional green house
 - To so check how do IoT-based setups impact key growth indicators compared to traditional ones?
   
# Features Inputs Will Be:
 - Random	Sample batch ID (e.g., R1, R2, R3):  An identifier for each record, likely indicating a random sample or batch (object type).
 - ACHP	Average chlorophyll content (photosynthetic pigment): The average chlorophyll content in the plant
 - PHR	Plant height growth rate: The rate of plant height growth
 - AWWGV	Average wet weight of vegetative growth: Total fresh weight of the above-ground parts.	
 - ALAP	Average leaf area per plant: Surface area of leaves which impacts photosynthesis.
 - ANPL	Average number of leaves per plant: Indicates plant maturity and foliage density.
 - ARD	Average root diameter	Float: Thickness of roots, relevant to nutrient uptake.
 - ADWR	Average dry weight of roots: Total root biomass after drying.
 - PDMVG	% dry matter in vegetative growth: Measures solid content in shoots.	
 - ARL	Average root length	Float: Indicates root development and depth.
 - AWWR	Average wet weight of roots: Total fresh root weight.
 - ADWV	Average dry weight of vegetative parts: Dried mass of above-ground plant parts.
 - PDMRG	% dry matter in root growth	Float: Solid content of the root system.
 - Class	Experimental group label (SA, SB, SC, TA, TB, TC): A categorical column indicating the class or category to which the plant record belongs.
   This could represent different groups or conditions under which the plants were studied or classified.
     - SA, SB, SC (Traditional Greenhouse),
     - TA, TB, TC (IoT-based Greenhouse).
   
# Technologies To Be Use:

 - Python 3.x
 - Jupyter Notebook
 - pandas
 - Seaborn
 - matplotlib
 - LabelEncoder, StandardScaler
   
 - # Note: 
 - There might be some changes as the reserach is ongoing.


