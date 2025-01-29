# Application of the Clustering Method as a Special Handling Strategy for Poverty in Jakarta
## Description
This project aims to apply the K-Means and Agglomerative Clustering algorithms to cluster regions in DKI Jakarta based on poverty levels. The data used includes factors such as the percentage of poor people, unemployment rate, per capita expenditure, average years of schooling (RLS), and Human Development Index (HDI) collected from the DKI Jakarta Central Bureau of Statistics (BPS) during the period 2011-2022.
By using clustering, this project helps the DKI Jakarta government to identify areas that need special handling based on the poverty patterns found in the data.

## Objective
- Analyzing poverty data in DKI Jakarta to identify regions that have similar poverty patterns.
- Apply a clustering algorithm to divide these regions into clusters based on poverty characteristics.
- Provide recommendations for poverty management strategies based on the clustering results.

## Dataset
The dataset used in this project is data from the Central Bureau of Statistics of DKI Jakarta Province with the following variables:
- Percentage of Poor Population (%) - Percentage of the population that has per capita expenditure below the poverty line.
- Unemployment Rate (%) - The percentage of the number of unemployed people to the total labor force.
- Average Years of Schooling (RLS) (years) - The number of years of education taken by the population.
- Per Capita Expenditure (thousand rupiah) - Average expenditure per capita per month, which is an indicator of purchasing power.
- Human Development Index (HDI) - An index that reflects the quality of life through education, health, and decent living standards.

## Methods
This project uses the following two clustering algorithms to analyze the data:
1. K-Means Clustering
K-Means is a clustering algorithm that divides data into a predetermined number of clusters. In this project, K-Means is used to identify poverty patterns based on the available data. The selection of the optimal number of clusters is done using the Elbow Method and Silhouette Score techniques.
2. Agglomerative Clustering
Agglomerative Clustering is a hierarchical clustering method that does not require a predetermined number of clusters. Dendrogram is used to determine the optimal number of clusters based on the distance between clusters.

## Implementation Steps
- Data Preprocessing:
  - Checking and cleaning the data from missing or duplicate values.
  - Standardizing the data so that all variables have the same scale, if required.
- Application of K-Means:
  - Determining the number of clusters using Elbow Method and Silhouette Score.
  - Apply the K-Means Clustering algorithm   and visualize the results.
- Application of Agglomerative Clustering:
  - Building a dendrogram to help select the optimal number of clusters.
  - Apply Agglomerative Clustering and visualize the results.
- Analysis and Handling:
After the areas are grouped into clusters, further analysis is conducted to provide recommendations for poverty reduction strategies for each cluster.

## Results
The clustering results are divided into several clusters, each of which has similar poverty characteristics. Based on the clustering results, the following are recommendations for handling poverty in DKI Jakarta:
### 1. “Very Poor” Cluster (Priority 1)
Handling Strategy:
- Improving Access to Education and Health:
Focus on strengthening basic education and health services in this area. Basic education and good health have a major influence on poverty alleviation efforts in the long run.
- Provision of Social Assistance:
Provide direct assistance to poor families to fulfill basic needs such as food, housing, and education.
- Skills Training Program:
Provides job skills training to improve the competitiveness of the population in the labor market.
- Health and Social Security Subsidization:
Provide more affordable health services, including health insurance, to reduce the financial burden on poor families.

Rationale:
Residents in this cluster exhibit very high poverty rates (e.g., more than 10%) and large unemployment rates. They require direct interventions to fulfill their basic needs and open up opportunities for economic improvement. (Source: World Bank, 2021; UNDP, 2020)

### 2. “Poor” Cluster (Priority 2)
Handling Strategy:
- Economic Infrastructure Development:
Improve basic infrastructure such as roads, electricity, and transportation to open up access to markets and more job opportunities.
- Local Economic Empowerment:
Develop micro, small and medium enterprises (MSMEs) and provide business capital to communities to encourage local entrepreneurship and employment.
- Skills and Further Education Program Development:
Improve the quality of job skills and further education to enable residents to adapt to the needs of the broader job market.
- Preventive Health Program:
Provide preventive health programs and nutrition counseling to reduce expenditures related to health problems that can exacerbate poverty.

Rationale:
The population in this cluster exhibits moderate poverty, but not extreme poverty. Therefore, this approach aims to improve their conditions by providing more access to economic and social opportunities. (Source: ADB, 2020; Bappenas, 2019)

### 3. “Vulnerable Poor” Cluster (Priority 3)
Handling Strategy:
- Strengthening Social and Economic Resilience:
Focus on improving economic resilience through diversification of income sources and job creation in emerging sectors, such as digital and technology.
- Social Protection and Insurance Programs:
Provide social protection, such as unemployment insurance or emergency funds, to reduce vulnerability to economic shocks.
- Financing and Business Credit Facilities:
Introduce more accessible financing schemes for small and medium-sized enterprises, as well as new entrepreneurs.
- Counseling on Financial Management and Investment:
Provide training on family financial management and long-term planning.

Rationale:
Although not identified as poor, residents in this cluster are vulnerable to economic downturns. They need more proactive strategies to maintain financial stability and prevent a slide into poverty. (Source: ILO, 2019; BPS, 2021)

Conclusion: Each cluster has different needs and challenges. Therefore, the treatment strategies offered are organized based on the priorities and conditions of each cluster, from direct intervention for the very poor, to increasing economic resilience for the vulnerable poor. These strategies aim to create better conditions and prevent deeper poverty for all community groups.

# Contact
For further questions or suggestions, contact me at anasafira579@gmail.com
