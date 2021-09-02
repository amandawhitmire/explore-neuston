# Exploring neuston observations in historical oceanographic field logs
The plan s to create a Jupyter Notebook to explore mentions of oceanic neuston in historical Stanford research cruise logs, then launch it in a [Binder](https://mybinder.org/) for collaborators to interact with.

# Repo organization
      
      ├── code               
            ├── neuston-ner.ipynb      # Runs the Python code
      ├── data
            ├──                        # Text files that are corrected OCR from scanned cruise logs
      ├── docs
            ├── helm.jsonl             # Contains the custom entities for the spaCy NER pipeline
            └── dataset-summary.xlsx   # Describes dates of cruises, text files, and other descriptive info
      ├── LICENSE             
      └── README
      
## Background

From 1961-1969, the ship Te Vega, a 135-foot two-masted, steel-hulled schooner capable of sustained operations at sea provided the base for graduate training in biological oceanography. The ship carried a scientific party of 15 and was outfitted as a floating laboratory for observation, collection, experimentation, and teaching. Deep sea trawling and hydrographic winches permitted sampling at depths of up to 6,000 meters. In addition to a variety of gear for physical measurement, chemical analysis, and the collection, examination and maintenance of living organisms, the ship carried a small reference library which was changed to suit the needs of each cruise. Several skiffs and a launch for inshore work were carried on deck. Each year the vessel conducted four cruises, each cruise lasting for one academic quarter. The Te Vega was donated to Hopkins Marine Station by Harold Miller (who also donated money for the Harold A. Miller Library).  Professor Rolf Bolin (1934-1968) was the program director for the Te Vega until he retired in 1967. He also served as chief scientist on 8 of its 12 cruises.

