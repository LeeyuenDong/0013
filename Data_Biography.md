# Data Biography

### Declaration of Authorship

I, Liyuan Dong, confirm that the work presented in this assessment is my own. Where information has been derived from other sources, I confirm that this has been indicated in the work.

Liyuan

Date of signature: November 25th 2021 
Assessment due date: November 26th 2021 
Student Number: 21058831

_Please write your answer immediately below the level-3 headers and delete the guidance prior to submission._

---

### 1. Who collected the data?

#### The data were first collected by Murray Cox in 2014, and the detailed listings data for London was updated on 10 October 2021.

---

### 2. Why did they collect it?

#### The reason for collecting data is that in the early of the project, Murray was taught the youth of Central Brooklyn about gentrification in Bedford-Stuyvesant using mapping, data, and visualization. Therefore, he was inspired in 2014 to dispute Airbnb's claim that 87% of hosts would rent out the places they lived [1], scraping information from Airbnb's website, and then comparing that data with data the company had provided for New York City in December 2015. To detect the difference between these two sets of data and confirm the authenticity of the Airbnb official data.

---

### 3. How was it collected?

#### They use Python to scrape the information from the Airbnb website in 2014 initially for New York City. They expanded their data gradually and the website has provided data on 80 cities around the world, as of 2019 [2]. During the collection process, they only focused on the data they needed, like the host’s name and description. However, not all the data can be found on the website directly, they use some techniques to scrape the data hidden behind the website, like latitude and longitude of the property. Thus, the data set is filtered subjectively, and not all data on the websites are included, which has limitations on the structure and content of the data set. Meanwhile, it may cause structurally missing data and random missing data because they directly formed the data by capturing the variables they want, but some people might choose not to fill in or hide their information on the website, leading to data loss or deviation.

---

### 4. What useful information does it contain?

#### Generally, the data set of London Airbnb reveals 74 variables on the Inside Airbnb website [1]. The variables and data obtain different kinds of information and they can be divided into 9 main perspectives, basic information of the property, basic information of the host, the facilities provided in the property, the neighbourhood environment, the letting duration information, the reviewing situation, the review scores, the variety of calculation of the host’s property and some background for obtaining data information, such as last_scraped and scrape_id. Specifically, some data are in the text format like description and host_about. Some variables are denoted in the dummy variable form like has_availability and some of the data are the website and jpg address like listing_url and host_url. 
---

### 5. To what extent is the data 'complete'?

#### Although this dataset is relatively comprehensive and covers a large variety of information, there is still an incomplete problem. Firstly, there is a possibility of lag in the data set, meaning the data may not match the information on Airbnb currently and leading to the data incorrectly. This data source has some critical limitations: As with any online advertising, there is the potential for outdated or “bait and switch” listings (advertising of properties that upon investigation are not actually available) [3]. Secondly, the dataset itself contains incorrect data. The incorrect data issue pertains to reviews that were incorrectly added to listings in Inside Airbnb [1]. For example, the review of the property shown on the website, the reported location and the actual location cannot be matched in Los Angeles indicating the information in the dataset is incorrect. Furthermore, the number of listings with at least one incorrect review is 50 occupying 0.15% in all the samples in the dataset. Specifically, with the first 500 listings sample, the number of listings with at least one incorrect review is 31 occupying 6.2%. Thus, if this subset of data (the first 500 ids) is selected, the impact of the problems discovered can be severe [1]. Thirdly, some of the data are missing, because of the structurally missing data and random missing data, which may lead to bias in further study. Researchers should handle the missing data by filling them or deleting them, then explaining the missing data.

---

### 6. What kinds of analysis would this support?

#### Dataset from Inside Airbnb enabled researchers to study different kinds of relevant topics. Firstly, in the sharing economy perspective, some topics are relative to trust in the sharing economy, pricing issues and impacts of the sharing economy [4, 5]. Secondly, there is a heated discussion on the impact of the city’s real estate perspective, such as the potential relationship between Airbnb to rapid gentrification in different areas of the city [5, 6], Airbnb’s disruption of the housing structure and market [8] and impact on the hotel industry [9, 10]. Thirdly, this dataset contains geographic information, so it can be used in the analysis of its spatiotemporal dynamics and the Airbnb distribution in a city [6]. Finally, it also obtains a lot of review information, which can support to analyze of the social science perspective, such as using textual contents of reviews extracted from Airbnb [11], the trust investigation of guests in Airbnb [12, 13], and the guest’s satisfaction on Airbnb [14].

---

### 7. Which of the uses presented in Q.6 are _ethical_?

#### However, there is an inevitable problem, the ethical problem, when scholars use the data to conduct their studies and it covers several aspects. The privacy issue is the initial one because Inside Airbnb directly scraped the data from the Airbnb website. Although the information like host information, guest information, and reviewing information is published publicly on the website, they know that it's published for public reference so that people can understand the situation of the property, but they don't know that all their information is captured and assembled for research or even some commercial using. Therefore, the first principle of data ethics is that individuals own their personal information. Just as taking items that do not belong to you is considered theft, collecting personal data without someone's consent is illegal and unethical [15]. Secondly, the data subject has a right to know how you plan to collect, store, and use it, when collecting data, be transparent. Even though they agree to analyze the information, it doesn’t mean they want it publicly available or for other purposes. Moreover, the results of the analysis and algorithms may cause some bias, such as using machine learning to train the algorithms. Because algorithms are written by humans, biases can emerge intentionally or unintentionally. Biased algorithms can do serious harm to people [15]. Basic on Tingley’s view, no algorithm or team is perfect [15], so the existence of bias is normal and unavoidable. Finally, the outcomes of the analysis may impact others’ benefits. For example, affect the local hotel industry leading the customers to lose or affect some hosts make their houses difficult to rent, which is unfair in the economic market and disrupts the market order. In addition, someone may even use the data to make bias results subjectively. Use in a malicious way and generate favorable results for them, causing vicious competition in the market to break the balance and gain profits. Even worse, it could be devastating to the local real estate economy, which will lead to a serious ethical problem.

## Bibliography


## Appendix 

Count:1150

Reference 

[1] A. Alsudais. (2021, February). “Incorrect data in the widely used Inside Airbnb dataset”. Decision Support Systems [Online]. Vol.141, p.113453. Available: https://www.sciencedirect.com/science/article/pii/S0167923620302086#bb0050

[2] P. Lo (2018, May). Practitioner Profile: Murray Cox [Online]. Available: https://morethancode.cc/2018/05/30/practitioner-profile-murray-cox.html

[3] G. Nicole, and P. Phibbs.(2017, January). “When Tourists Move In: How Should Urban Planners Respond to Airbnb?” Journal of the American Planning Association [Online]. Vol. 83, pp. 80–92. Available: https://www.tandfonline.com/doi/full/10.1080/01944363.2016.1249011

[4] L. Zhang, Q. Yan, and L. Zhang. (2018, November). "A Computational Framework for Understanding Antecedents of Guests' Perceived Trust towards Hosts on Airbnb". Decision Support Systems [Online]. Vol.115, pp. 105-116. Available: https://www.sciencedirect.com/science/article/pii/S0167923620302086#bb0055

[5] J. Chica-Olmo, J. Gabriel González-Morales, and J. L. Zafra-Gómez. (2020, April). "Effects of Location on Airbnb Apartment Pricing in Málaga". Tourism Management [Online]. Vol.77, p. 103981. Available: https://www.sciencedirect.com/science/article/abs/pii/S0261517719301797?via%3Dihub

[6] Z. Shabrina, Y. Zhang, E. Arcaute, and M. Batty. (2017, March). “Beyond Informality: The Rise of Peer-to-Peer (P2P) Renting.” CASA Working Paper 209. University College London. [Online]. Available: https://www.ucl.ac.uk/bartlett/casa/case-studies/2017/mar/casa-working-paper-209

[7] D. Wachsmuth, and A. Weisler. (2016, August). “Airbnb and the Rent Gap: Gentrification Through the Sharing Economy.” Environment and Planning A: Economy and Space [Online]. Vol.55, pp.62-7. Available: https://doi.org/10.1177/0308518X18778038

[8] Z. Shabrina, E. Arcaute, and M. Batty. (2019, May). “Airbnb’s Disruption of the Housing Structure in London.” ArXiv Prepring. University College London. [Online]. Available: 
https://arxiv.org/pdf/1903.11205.pdf

[9] J. Gutiérrez, J. C. Garcı́a-Palomares, G. Romanillos, and M. H. Salas-Olmedo. (2016, June). “The Eruption of Airbnb in Tourist Cities: Comparing Spatial Patterns of Hotels and Peer-to-Peer Accommodation in Barcelona.” Tourism Management [Online]. Vol.62, pp. 278–91. Available: https://www.sciencedirect.com/science/article/abs/pii/S0261517717301036?via%3Dihub

[10] D. Guttentag, and L. J. Stephen. (2017, July). “Assessing Airbnb as a Disruptive Innovation Relative to Hotels: Substitution and Comparative Performance Expectations.” International Journal of Hospitality Management [Online]. Vol.64, pp. 1–10. Available:  https://doi.org/10.1016/j.ijhm.2017.02.003

[11] M. Cheng, and J. Xin. (2019, January). “What Do Airbnb Users Care about? An Analysis of Online Review Comments”. International Journal of Hospitality Management [Online]. Vol.76, pp. 58-70. Available:
https://www.sciencedirect.com/science/article/abs/pii/S0278431917307491

[12] S. Erose, and P. Björk. (2019, July). “Sources of Distrust: Airbnb Guests’ Perspectives.” Tourism Management Perspectives [Online]. Vol.31, pp.245–53. Available: 
https://doi.org/https://doi.org/10.1016/j.tmp.2019.05.009

[13] Ert, E., A. Fleischer, and N. Magen. (2016, August). “Trust and Reputation in the Sharing Economy: The Role of Personal Photos in Airbnb.” Tourism Management [Online]. Vol. 55, pp. 62–63. Available: https://doi.org/10.1016/j.tourman.2016.01.013

[14] C.  Mohamed, O. Bencharef, M. Youssef Hadi, and Y. Chihab. (2021, February). "A Client-Centric Evaluation System to Evaluate Guest’s Satisfaction on Airbnb Using Machine Learning and NLP." Applied Computational Intelligence and Soft Computing [Online]. Vol.2021. Available: https://www.hindawi.com/journals/acisc/2021/6675790/

[15] C. Cote (2021, March). 5 PRINCIPLES OF DATA ETHICS FOR BUSINESS [Online]. Available: https://online.hbs.edu/blog/post/data-ethics
