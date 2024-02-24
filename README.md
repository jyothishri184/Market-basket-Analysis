# Market Basket Analysis Using Python Pyspark 🛒📊

## Table of Contents
1. [Market Basket Analysis Overview](#market-basket-analysis-overview)
2. [Python Libraries Used](#python-libraries-used)
3. [Quick Start](#quick-start)
4. [Results](#results)
5. [License](#license)
6. [Contact](#contact)
## Market Basket Analysis Overview

   ### To identify purchasing patterns !!

A simple example of market basket analysis is a grocery store analyzing its sales data to identify which products are frequently purchased together. 
   
   🎈Example: The store may find that customers who buy bread often purchase butter and jam.

![Screenshot (227)](https://github.com/jyothishri184/Market-basket-Analysis/assets/106957211/8ed4bdbd-c7f9-45e0-8168-db4b1a539ba4)


## FPGrowth algorithm

The FP Growth algorithm in data mining generates frequent itemsets efficiently by constructing an Trie data structure. Apriori algorithm is also an most used algorithm but FPGrowth uses an alternative way to find frequent itemsets without candidate generations which take a lot of memory and process time, this makes this algorithm performance is better than Apriori.

## Python Libraries Used

 🌟 Pandas
 
 🌟 Numpy
 
 🌟 Pyspark 
 
 🌟 Scikit-learn



## Quick Start
Follow these steps to get started with Market Basket Analysis:


```bash
# Clone the repository
git clone https://github.com//jyothishri184/Market-basket-Analysis.git

# Navigate to the project directory
cd Market-basket-Analysis

# Install dependencies
pip install -r requirements.txt
```


 ⚡Open and run the pre_processing_market_basket_analysis.py and Explore pre-processing.
   
 ⚡The local_output.csv file contains the preprocessed data, use it for further steps.
 
 ⚡Open and run the algorithm_market_basket_analysis.py and Explore the algorithm.

 
# Results 

 ## Data Visualisation using networkx and matplotlib:

1. When a customer buys "PAPER CHAIN KETO'S CHRISTMAS" they also tend to buy "BOX OF 6 MINI CRAKERS" , "JUMBO BAG 50'S CHRISTMAS" etc

![Screenshot (225)](https://github.com/jyothishri184/Market-basket-Analysis/assets/106957211/20b8325d-9437-49cf-ac84-b8f286ec7499)


2. When a customer buys "HAND WARMER UNION JACK" and "HAND WARMER RED POLKA DOT" together they also tend to buy "HAND WARMER BIRD DESIGN" 

![Screenshot (226)](https://github.com/jyothishri184/Market-basket-Analysis/assets/106957211/f7d944f5-4648-4414-b565-529d30a77cc6)



## License

This Market Basket Analysis project is licensed under the MIT License.

## Contact

For any inquiries or feedback regarding the project, feel free to reach out to the creator and maintainer:

**JYOTHI SHRI**
- Email: [shrijyothi184@gmail.com](mailto:shrijyothi184@gmail.com)

  
## Acknowledgments

Special thanks to the open-source community and contributors for inspiration and learning resources.

Happy Coding 🚀
