# Exploring neuston observations in historical oceanographic field logs
A Jupyter Notebook to explore mentions of oceanic neuston in historical Stanford research cruise logs.

# Repo organization
      
      ├── code               
            ├── neuston-ner.ipynb      # Runs the Python code
      ├── data
            ├──                        # Text files that are corrected OCR from scanned cruise logs
      ├── docs
            ├── helm.jsonl             # Contains the custom entities for the spaCy NER pipeline
            └── dataset-summary.xlsx   # Describes dates of cruises and other descriptiove info
      ├── LICENSE             
      └── README
      
## Background

From 1961-1969, the ship Te Vega, a 135-foot two-masted, steel-hulled schooner capable of sustained operations at sea provided the base for graduate training in biological oceanography. The ship carried a scientific party of 15 and was outfitted as a floating laboratory for observation, collection, experimentation, and teaching. Deep sea trawling and hydrographic winches permitted sampling at depths of up to 6,000 meters. In addition to a variety of gear for physical measurement, chemical analysis, and the collection, examination and maintenance of living organisms, the ship carried a small reference library which was changed to suit the needs of each cruise. Several skiffs and a launch for inshore work were carried on deck. Each year the vessel conducted four cruises, each cruise lasting for one academic quarter. The Te Vega was donated to Hopkins Marine Station by Harold Miller (who also donated money for the Harold A. Miller Library).  Professor Rolf Bolin (1934-1968) was the program director for the Te Vega until he retired in 1967. He also served as chief scientist on 8 of its 12 cruises.


## Cruises

1. Cruise #1:  July-September 1963
    * Ports of Call: San Diego—Honolulu—Pago Pago—Suva—Tikopia—Kieta—Rabaul—Kotabaru—Halmahera—Zamboanga—Singapore
2. Cruise #2: October-December, 1963 
    * Ports of Call: Singapore (Malaysia)—Port Swettenham (Malaysia)—Rhuket (West Thailand)—Penang (Malaysia)—Kotardja (Indonesia)—Padang (Indonesia)—Colombo (Ceylon)
3. Cruise #3: February-June, 1964 
    * Ports of Call: Colombo (Ceylon)—Maldive Islands—Cochin (India)—Chagos Archipelago—Port Louis (Mauritius) —Port Victoria (Mahe Island Seychelles Islands)---Tamatave (Madagascar)
4. Cruise #4: July-September, 1964
    * Ports of Call:  Majunga (Madagascar) --Mombosa (Kenya)
5. Cruise #5: October-December, 1964 
    * Ports of Call:  Mombosa (Kenya)—Seychelles Islands—Gan (Maldive)—Penang (Malaysia)—Bhuket (Thailand)—Singapore (Malaysia)
6. Cruise #6: January-March, 1965
    * Ports of Call:  Singapore (Malaysia) –Zamboanga (Philippine Islands)-Rabaul (New Britain) –Honiara (Guadalcanal)-Suva (Fiji) 
7. Cruise #7: April-June, 1965 
    * Ports of Call:  Honiara (British Soloman Islands)—Suva (Fiji Islands)—Nukualofa (Tonga)—Rarotonga (Cook Islands)--Pago Pago (American Samoa)
8. Cruise #8: July-September, 1965 
    * Ports of Call:  Pago Pago (American Samoa) –Honolulu --Monterey
9. Cruise #9: 1965
    * NO CRUISE - SHIP DRY-DOCKED
10. Cruise #10: April-June, 1966 
    * Ports of Call:  Monterey—San Pedro--Monterey
11. Cruise #11: July-September, 1966
    * Ports of Call:  Monterey—Magdelena Bay—Monterey
12. Cruise #12: September-December, 1966
    * Ports of Call:  Monterey—Santa Barbara Channel Islands—San Diego—Santa Barbara--Monterey
13. Cruise #13: January-March, 1967
    * Ports of Call:  Monterey—San Diego—Ensenada—La Paz—Acapulco—Galapagos Islands—Panama
14. Cruise #14: March-June, 1967
    * Ports of Call:  Acapulco—Mazatlan—Cabo San Lucas—Guadalupe Island--Mazatlan—Long Beach--Monterey
15. Cruise #15: June-September, 1967
    * Ports of Call:  Monterey to Mazatlan (via San Diego, Cabo San Lucas, Guaymas, Tiburon Islands)
16. Cruise #16: September-December, 1967
    * Ports of Call:  Mazatlan—Guayamus—La Paz—Long Beach--Monterey
17. Cruise #17:  January-March, 1968
    * Ports of Call:  Monterey—San Diego—Acapulco (Mexico)—100 degrees West meridian toward position south of the equator—3 degrees and 4 degrees south –(26 days out of sight of land)--Isabella Island (Galapagos)—Guayaquil (Ecuador)—Around Galapagos Islands—Guyaquil (Ecuador)
18. Cruise #18:  April-June, 1968
    * Ports of Call: Ecuador—Peru—Columbia—Panama—El Salvador—Mexico--
19. Cruise #19: June-September, 1968
    * Ports of Call:  Monterey—San Diego—Cabo San Lucas—Acapulco—Guayaquil—Isla Isabella—Salinas--Guayaquil
20. Cruise #20: September-December 1968
    * Ports of Call:  Guayaquil—Galapagos—Buenaventura—Cocos Islands—El Salvadore—Acapulco—Cabo San Lucas—San Diego

## Text Files

* Cruise-01-Installment-01-Narrative.txt
* Cruise-01-Installment-02-Narrative.txt
* Cruise-01-Installment-03-Narrative.txt
* Cruise-01-Installment-04-Narrative.txt
* Cruise-01-Installment-05-Narrative.txt
* Cruise-02-Additional-Post-Cruise-Narrative.txt
* Cruise-02-Installment-06-Narrative.txt
* Cruise-02-Installment-07-Narrative.txt
* Cruise-02-Installment-08-Narrative.txt
* Cruise-02-Installment-09-Narrative.txt
* Cruise-03-Installment-10-Narrative.txt
* Cruise-04-Installment-11-Narrative.txt
* Cruise-04-Installment-12-Narrative.txt
* Cruise-04-Installment-13-Narrative.txt
* Cruise-05-Abbott-Letter.txt
* Cruise-06-Installment-14-Narrative.txt
* Cruise-06-Installment-15-Narrative.txt
* Cruise-06-Installment-16-Narrative.txt
* Cruise-07-Installment-17-Narrative.txt
* Cruise-07-Installment-18-Narrative.txt
* Cruise-07-Installment-19-Narrative.txt
* Cruise-07-Installment-20-Narrative.txt
* Cruise-08-Installment-21-Narrative.txt
* Cruise-08-Installment-22-Narrative.txt
* Cruise-08-Installment-23-Narrative.txt
* Cruise-08-Installment-24-Narrative.txt
* Cruise-10-Installment-Narrative.txt
* Cruise-11-Installment-Narrative.txt
* Cruise-12-Installment-Narrative.txt
* Cruise-13-Installment-Narrative.txt
* Cruise-14-Installment-Narrative.txt
* Cruise-17-Installment-Narrative.txt
* Cruise-18-Installment-Narrative.txt
* Cruise-19-Installment-Narrative.txt
* Cruise-20-Installment-Narrative.txt

