# ISYE_7406_GROUP_PROJECT
ISYE 7406 Group Project Repo

##Abstract

The shift toward online grocery shopping, accelerated by pandemic-induced lockdowns, has highlighted the need for retailers to adapt swiftly to changing consumer preferences and expectations. The increased reliance on platforms like Instacart for grocery delivery services has underscored the importance of using predictive analytics to anticipate and fulfill customer needs effectively.
In response to this demand, our project delves into the realm of data analytics with the Instacart Market Basket Analysis. Through this endeavor, we aim to deliver actionable insights that can potentially help retailers (both physical and online) offer more personalized shopping experiences and streamline operations, thereby increasing customer satisfaction and business efficiency.

##Introduction
###Background

In the digital commerce era, online marketplaces like Amazon, eBay, Alibaba, and JD.com, and many others have emerged as dominant players, collectively responsible for over one-third of global online shopping transactions. According to a survey conducted by Statista 2023, 15 percent of digital shoppers allocated their spending to e-grocers and supermarkets, reflecting a notable preference for online grocery shopping. As a result, understanding customer purchasing behavior emerges as a pivotal challenge, with transaction analysis serving as a key technique to glean actionable insights.

###Problem Statement

Transaction analysis holds profound implications for businesses across various sectors, especially in the retail domain, where comprehension of customer purchasing patterns is instrumental in driving sales. Despite the availability of robust datasets like Instacart's, many retailers struggle to efficiently utilize such data to gain actionable insights. Traditional analysis methods can be time-consuming and may not effectively handle the volume and complexity of the data. Advanced algorithms such as A-Priori, FP-Growth, and ECLAT offer solutions to these challenges, yet their comparative effectiveness in real-world scenarios is not well-documented, especially in the context of grocery shopping data.

###Objectives

The primary objective of this project is to employ common association rules embedded within the historical transactions recorded in the Instacart dataset. Leveraging the A-Priori, FP-Growth, and ECLAT algorithms - known for their efficacy in frequent itemset mining - we aim to extract actionable insights from the dataset. Each algorithm boasts unique strengths and strategies, offering versatile approaches to association rule mining tailored to diverse datasets and mining scenarios. Unlike probabilistic ensemble methods, which necessitate extensive feature engineering and may yield suboptimal results due to inherent biases, our chosen algorithms offer a more direct and interpretable approach to uncovering important association rules between products. Moreover, given the sparsity of the dataset, we endeavor to explore association rules not only between individual products but also between departments and aisles. By leveraging department and aisle associations, retailers (both online and physical) can potentially enhance marketing strategies, optimize product placements, and improve inventory management.

 
In the subsequent sections of this report, we detail our exploratory data analysis and the methodology for association rule mining (including the comparison of these algorithms in terms of efficiency, scalability, and practical applicability), present our findings, and offer insights garnered from the application of these methodologies.
