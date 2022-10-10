# Air_Quality_Analysis
1- IDENTIFICATION AN ANALYSIS OF THE PROBLEM
        
 - The dataset contains 9358 instances of hourly averaged responses from an array of 5 metal oxide chemical sensors embedded in an Air Quality Chemical Multisensor Device. 
 
 - The device was located on the field in a significantly polluted area, at road level,within an Italian city. 
 
 - Data were recorded from March 2004 to February 2005 (one year)representing the longest freely available recordings of on field deployed air quality chemical sensor devices responses. 
 
 - Ground Truth hourly averaged concentrations for CO, Non Metanic Hydrocarbons, Benzene, Total Nitrogen Oxides (NOx) and Nitrogen Dioxide (NO2) and were provided by a co-located reference certified analyzer. 
 
 - Evidences of cross-sensitivities as well as both concept and sensor drifts are present as described in De Vito et al., Sens. And Act. B, Vol. 129,2,2008 (citation required) eventually affecting sensors concentration estimation capabilities. 
 
- Missing values are tagged with -200 value.

        FEATURES:
        1 - Date (DD/MM/YYYY)

        2 - Time (HH.MM.SS)

        3 - True hourly averaged concentration CO in mg/m^3 (reference analyzer) / mg/m^3 cinsinden gerçek saatlik ortalama CO konsantrasyonu (referans analizörü)

            Carbon monoxide(CO) is harmful because it binds to hemoglobin in the blood, reducing the ability of blood to carry oxygen. This interferes with oxygen delivery to the body's organs. The most common effects of CO exposure are fatigue, headaches, confusion, and dizziness due to inadequate oxygen delivery to the brain.

            Resource: https://ww2.arb.ca.gov/resources/carbon-monoxide-and-health

        4 - PT08.S1 (tin oxide) hourly averaged sensor response (nominally CO targeted) / PT08.S1 (kalay oksit) saatlik ortalama sensör yanıtı (nominal olarak CO hedefli)

            Tin oxide is still the most important material used for the detection of atmospheric pollution gases.

            Resource: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6468801/#:~:text=Tin%20oxide%20is%20still%20the,low%20temperatures%20and%20low%20cost.

        5 - True hourly averaged overall Non Metanic HydroCarbons concentration in microg/m^3 (reference analyzer) / Mikrog/m^3 cinsinden gerçek saatlik ortalama genel Metanik Olmayan Hidrokarbon konsantrasyonu (referans analiz cihazı)
             
             NMHCs are trace atmospheric components that provide a sink for hydroxyl radicals and control ozone concentration. Exmples of NMHCs are ethane, ethene, propane, propene, and isoprene. Methane is excluded in air-pollution contexts because it is not harmful.

             Resource: https://www.gas-sensing.com/information/nmhc
            
        6 - True hourly averaged Benzene concentration in microg/m^3 (reference analyzer) / Mikrog/m^3 cinsinden gerçek saatlik ortalama Benzen konsantrasyonu (referans analizörü)

             Benzene exposure affects the central nervous system and can affect the immune system. Chromosomal abnormalities of bone marrow cells and circulating lymphocytes have been observed in people exposed to benzene. Fatal anaemia has also been reported. It has been seen that ambient exposure to benzene increases risk of contracting cancers such as leukaemia. Several reports relate benzene exposure to a variety of lymphatic tumours. Chronic exposure to toluene during pregnancy can lead to disorders of the central nervous system, attention deficits and hyperactivity, mental delay and limb abnormalities in foetuses.

             Resource: https://www.downtoearth.org.in/news/benzene-in-the-air-22111

        7 - PT08.S2 (titania) hourly averaged sensor response (nominally NMHC targeted) / PT08.S2 (titania) saatlik ortalama sensör yanıtı (nominal olarak NMHC hedefli)

        8 - True hourly averaged NOx concentration in ppb (reference analyzer) / ppb cinsinden gerçek saatlik ortalama NOx konsantrasyonu (referans analizörü)

            Nitrogen oxides (NOx), mainly a mixture of nitric oxide (NO) and nitrogen dioxide (NO2), are formed by the reaction of nitrogen and oxygen compounds in the air as a result of combustion processes and traffic. Both deposit into leaves via stomata, which on the one hand benefits air quality and on the other hand provides an additional source of nitrogen for plants.

            Resource: https://www.frontiersin.org/articles/10.3389/fpls.2020.549913/full

            Nitrous oxide is 300 times more potent than carbon dioxide, and it also depletes the ozone layer. Since it also has a shorter life span, reducing it could have a faster, significant impact on global warming.
            But the largest source of nitrous oxide is agriculture, particularly fertilized soil and animal waste, and that makes it harder to rein in.

            Resoruce: https://insideclimatenews.org/news/11092019/nitrous-oxide-climate-pollutant-explainer-greenhouse-gas-agriculture-livestock/

        9 - PT08.S3 (tungsten oxide) hourly averaged sensor response (nominally NOx targeted) / PT08.S3 (tungsten oksit) saatlik ortalama sensör yanıtı (nominal olarak NOx hedefli)

        10 - True hourly averaged NO2 concentration in microg/m^3 (reference analyzer) / Mikrog/m^3 cinsinden gerçek saatlik ortalama NO2 konsantrasyonu (referans analizörü)

        11 - PT08.S4 (tungsten oxide) hourly averaged sensor response (nominally NO2 targeted) / PT08.S4 (tungsten oksit) saatlik ortalama sensör yanıtı (nominal olarak NO2 hedefli)

        12 - PT08.S5 (indium oxide) hourly averaged sensor response (nominally O3 targeted) / PT08.S5 (indiyum oksit) saatlik ortalama sensör yanıtı (nominal olarak O3 hedefli)

             After repeated inhalation, In2O3 particles accumulate in the lungs. Their mobilization can cause significant systemic exposure over long periods of time.

             Resource: https://pubmed.ncbi.nlm.nih.gov/29448164/#:~:text=After%20repeated%20inhalation%2C%20In2,over%20long%20periods%20of%20time

        
        13 - Temperature in Â°C / Sıcaklık
        14 - Relative Humidity (%) / Bağıl Nem
        15 - AH Absolute Humidity / Mutlak Nem



High humidity increases the rate of harmful or toxic chemicals in the air. 
Low humidity also causes airborne germs.
humidity increases the negative effects of harmful air pollutants like smog.
Humidity is a significant cause of the drastic temperature changes in our immediate environment. It plays a crucial role in directing our daily weather and climate conditions.

Low humidity causes domestic ailments from dry skin to chapped lips. High humidity increases the birth rate of disease-causing microorganisms. On the other hand, relative humidity determines the amount of water in the air relative to the temperature.

Relative humidity affects the rate of transpiration in plants and determines their quantity and quality of
nutrients.
--------------------
