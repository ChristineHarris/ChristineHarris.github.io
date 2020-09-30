## Portfolio

---

### Classification

[**NBA Player Position Classification**]()

Traditionally, there are five basketball positions: point guard (PG), shooting guard (SG), small forward (SF), power forward (PF), and center (C). When created, these labels differentiated players roles. Centers, for example, grabbed rebounds and blocked shots. Over time, rule changes and the rise of analytics have allowed the NBA to develop into a high speed game with emphasis on the 3-point shot. The lines dividing positions have become increasingly blurred. These changes have sparked debate about the validity of the five-position system. Some argue that the traditional labels are archaic and should be redefined; others argue that they should be abolished. In this report, we use classification techniques to weigh in on this debate. Specifically, we investigate how well the five-position system captures playing styles, both historically and today.

---

[**Wine Quality Classification from Physicochemical Properties**]()

In order to re-examine and build upon previous analyses of wine quality classification, this study will compare the predictive power of six different techniques: Logistic Regression (GLM), Support Vector Machines (SVM), Support Vector Machines with Radial Basis Function (SVM-RBF), Neural Networks (NNet), Neural Networks Average (AvgNN), and Random Forest (RF). These different classification methods will aid in the prediction of wine quality based solely on physicochemical data and therefore conquer the ability to understand human taste.

---

### Regression

[**Predicting “Floor” and “Ceiling” for NBA Draft Prospects**]()

The draft is arguable the most critical off-season event in the NBA. For small-market teams, acquiring superstar talent through the draft is their only viable strategy to compete for a championship. For all teams, however, the draft represents a fantastic opportunity to add young talent to their roster with little associated financial risk. Due to the rise of analytics in the NBA over the last decade or so, teams now have access to large quantities of data they can use to evaluate prospects. Working with front offices can be tricky, however, because general managers and team presidents still value the importance of not-yet quantifiable factors such as susceptibility to injury, mental and emotional state, and basketball IQ. The main objective for this study, then, is to assess the ability of various Quantile Regression (QR) models – such as Quantile Regression Forests (QRF) and Gradient Boosting Model (GBM) – to predict a NBA prospect’s “floor” and “ceiling” potential. These models likely suffer from survivorship bias, however, as the training and test sets include only players who actually entered the league. To mitigate this issue, a separate model is built to identify which prospects can actually be considered NBA-caliber. These models, when used in conjunction with one another, can serve as a useful draft support tool that acknowledges the risks involved in predicting NBA performance and the tradeoff between drafting for reliability or potential. 

---

### Clustering

[**Parallel K-Means Clustering**]()

In this report, we propose a parallel version of the K- means clustering algorithm and implement it using Python’s multiprocessing library. We then run a series of simulations to compare the runtime and speedup between the basic K- means clustering algorithm and our parallel version. We also explore the impact of incorporating more CPUs into our parallel algorithm. Our findings confirm what we intuitively thought would happen based on our understanding of parallel computing and the “embarrassingly parallel” nature of the K- means clustering algorithm. For datasets with fewer than 5,000 observations, the basic K- means clustering algorithm outperforms the parallel version. However, as the number of data points increases, our parallel K- means clustering algorithm significantly reduces overall time complexity. Added measures for speedup, scaleup and sizeup provide further evidence that our parallel K- means clustering algorithm is both robust and scalable.

---

### Deep Learning

[**Using Neural Networks to Make NBA Game Outcome Predictions**]()

In the following report, I attempt to predict the outcome of National Basketball Association (NBA) games with the use of neural networks. I collected the statistics for NBA games from the 2014-15 season to the 2017-18 season. I performed manual feature engineering on all match-related features to transform them into information that could have been known before each matchup. After performing feature selection and eliminating any highly-correlated features, I used the final dataset to train several different types of neural networks. These include feedforward neural networks (FNNs), radial basis function neural networks (RBFNs), and probabilistic neural networks (PNNs). The best network was only able to correctly predict the winning team 64.28% of the time. The results of this analysis go to show that predicting game outcomes over a number of seasons is a difficult task, as personnel changes each offseason can drastically alter a team's competitive value. As such, the incorporation of player-level (rather than team-level) data in future analyses may lead to significant improvements in model performance.

---

### Distributed Computing

[**A Spatial Analysis of NCAA Shooting Behaviors**](https://github.com/ChristineHarris/NCAA-Shooting-Behaviors)

In this report, I show that the BigQuery Storage API and the Spark-BigQuery connector can be used to load and analyze the high volume of shooting data available for NCAA Men's Basketball. By running SQL queries on this dataset, I both quantify and visualize general shooting behaviors in the NCAA, as well as shooting trends that have developed over a five-season period. Additionally, I use non-negative matrix factorization to delve deeper into the underlying structure of NCAA player shooting distributions. By analyzing the resulting spatial basis functions, I can draw conclusions about different shot type preferences in the NCAA. By using non-negative matrix factorization as a clustering technique, I categorize players with similar shooting behaviors. Lastly, applying non-negative matrix factorization over several seasons separately, I visualize how shooting preferences have changed over time. The results of this analysis are useful in understanding how NCAA Men’s Basketball has developed over the past decade. These results could also help teams make optimal lineup selections, ensuring that every player is occupying the area on the court where they prefer to shoot.

![](/images/ncaa_shooting_behaviors.png)
