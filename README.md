# Big Data FC

The goal of the **Big Data FC** project is to **predict** how many **points** a **football team** belonging to the main European football leagues will end the season with, according to the **characteristics of its players**.

To reach the goal, data relative to the **football players** will first be loaded, in order to then compose the **football teams**.
After that, a second dataset will be used to gather seasonal **rankings**, for every football team.

The project as a whole is composed of:

* This **notebook**, containing all steps of:
  * Data loading.
  * Data cleaning and pre-processing
  * Data visualization.
  * Data analysis.
  * Learning and evaluation.
* A custom [**scraper**](https://github.com/Big-Data-FC/scraper), to gather further players data.
* A set of [**REST APIs**](https://github.com/Big-Data-FC/api) to query the loaded data and the prediction model.
* The collection of [scraped datasets](https://github.com/Big-Data-FC/datasets).

During the project, multiple approaches and techniques were explored and described in this notebook.

The notebook follows the thinking flow that happened during development stage:
1. Notebook **set-up** and **configuration**
2. Data **loading** and **pre-processing**
3. Preliminary data **exploration**
4. **Multiple** **learning** attempts:
   1. Naive
   2. Dimensionality reduction
   3. Learning-produced features (via Clustering)
   4. Prior-based approach (RP coefficient)
5. Final observations and **conclusion**

_By [Daniele Solombrino](https://github.com/dansolombrino) and [Davide Quaranta](https://github.com/davquar)._
