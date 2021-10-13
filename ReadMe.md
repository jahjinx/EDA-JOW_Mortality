# Japanese Oak Wilt Mortality Analysis


## About the Dataset

The data used in this project was obtained from [Mendeley Data](https://data.mendeley.com/datasets/xwj98nb39r/1), with additional information available on [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S2352340915001730?via%3Dihub). The data in full is available as four CSV files. However, for this project we will only use data.csv and gps_points.csv.

This data was collected in 2009, from June to early July and "provides field-observed viability status of 1935 trees and surrounding stand conditions." (Oguro et al., 2015) The focus area is in the mountain forests near Tsuruoka City, Yamagata Prefecture, Japan. This particular area was chosen "to cover the variation in land-use types and vegetation, and because of their accessibility." (Oguro et al., 2015) Michio Oguro and her team collected the source data in order to track Japanese Oak Wilt, a disease that causes mass mortality among _fagaceous_ trees in Japan.

The accuracy of the data is sound, as all trees and vegetation were identified and documented by experienced researchers. GPS coordinates were gathered using dedicated GPS devices. The data is highly usable as-is, requiring minimal preparation for our use cases.

Before describing the data in detail, it is helpful to understand a few terms in greater depth.

## Project Aim and Objectives
The overall goal of this project is to explore the relationships between the various features collected in this dataset and the mortality of Q. serrata and Q. crispula trees—or even disease occurrence. From the standpoint of a hopeful conservationist, one may hope to identify, for example, a nativie species of foliage that acts as a deterrent to our vector, the Flying Ambrosia Beetle. More realistically, we expect to track the effect oak mortality may have on the surroundings and possibly formulate recommendations for a point at which to intervene.

In order to best understand the context and environment from which the data was collected, we can leverage the GPS data to map each point identified in gps_points.csv. We can then add further value to the visualization with the addition of details such as the number of trees at each point and the percentage that remain alive. Optimistically, we may also hope to identify a spatial pattern of mortality among the observed trees.

With a better understanding of the geography of our data, we can then explore in further detail the relationships between mortality and the two individual species at hand. Are Q. serrata and Q. crispula represented equally? Are both affected at similar rates?

Finally, we will aim to explore the direct relationship each collected feature has with the mortality of Q. serrata and Q. crispula through correlation analysis.

Specific Objectives
*   **Objective 1:** Map dataset locations and explore spatial patterns
*   **Objective 2:** Visualize mortality by species
*   **Objective 3:** Explore possible correlations between dataset features and mortality of trees as a result of Japanese Oak Wilt
