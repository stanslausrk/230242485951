QUESTION:
During today's lecture, we saw data mining as one step in the knowledge discovery process. However, in industry, in media, and in the research environment, the term data mining is often used to describe the entire knowledge discovery process. Why is this the case?
What are the differences between data wrangling, scanning, and filtering in data mining?

ANSWER:
The term data mining is frequently used interchangeably with the full knowledge discovery in databases (KDD) process in industry, media, and even some research contexts due to several key factors. Primarily, data mining represents the central, analytical core of KDD where algorithms are applied to extract patterns, insights, and models from prepared data, making it the most important phase. This step is often highlighted because it directly leads to actionable knowledge, while the surrounding steps (like data selection, preprocessing, transformation, and evaluation) are seen as supportive or preparatory. In practical applications, the boundaries between steps blur, leading to simplified communication where the entire workflow is labelled as data mining for brevity, especially in non-academic settings where precision matters less than results.

Data wrangling, scanning, and filtering are distinct concepts within data mining, often appearing in the preprocessing or pattern-discovery phases, though their scope and application differ:

Data wrangling: This is a broad process (also called data munging or preparation) that involves transforming raw, messy data into a structured, analysis-ready format. It encompasses tasks like cleaning (handling missing values or errors), integrating multiple sources, restructuring (e.g., pivoting tables or normalizing formats), enriching (adding derived features), and overall optimization for downstream modeling or mining. 

Scanning: In data mining, this typically refers to the systematic reading or passing over a dataset (often a database) to compute frequencies, statistics, or initial patterns. It's commonly associated with algorithms like Apriori for association rule mining, where multiple scans of the data are performed to count itemset support and generate candidates. Scanning is more algorithmic and efficiency focused, emphasizing traversal to identify frequent items or anomalies without major alterations to the data itself. It can also broadly mean initial exploratory review in preprocessing, but it's narrower than wrangling and often tied to specific mining techniques.

Filtering: This is a targeted technique for refining data by selecting subsets based on criteria or removing unwanted elements. It includes noise reduction (e.g., smoothing outliers), feature selection (e.g., using statistical tests to keep relevant attributes), or row-level exclusion (e.g., dropping records below a threshold). Filtering is a subset of wrangling, focused on reduction and relevance to improve quality or efficiency, but it doesn't involve broad transformations like restructuring.

In summary, data wrangling is the broad preparation phase that cleans and reshapes raw data; filtering is a specific refinement step within it that removes unwanted rows/columns; scanning is a later mining step that reads through data to count patterns or frequencies. In practice, they often overlap.

