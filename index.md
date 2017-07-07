## Gang Hu
Master<br>
<a href="www.bmc.uestc.edu.cn">Big Media Computing Centre</a><br>
School of Computer Science and Engineering<br>
University of Electronic Science and Technology of China 

## Contact
Address: Main Building B1-204, No. 2006 Xiyuan Ave., West High-tech Zone, Chengdu, 611731, China<br>
Email: hugang@std.uestc.edu.cn

## General Information 
I am a master student in School of Computer Science and Engineering, University of Electronic Science and Technology of China, supervised by Prof <a href="http://bmc.uestc.edu.cn/~shaojie/">Jie Shao</a>. I received a bachelor degree from University of Electronic Science and Technology of China in 2016.<br>

I joined the <a href="www.bmc.uestc.edu.cn">Big Media Computing Centre</a> in June 2014 supervised by Prof <a href="http://bmc.uestc.edu.cn/~shaojie/">Jie Shao</a>. Before that, I joined the <a href="www.wsc.uestc.edu.cn/">Web Sciences Center</a> in June 2013 supervised by Prof <a href="http://www.ccse.uestc.edu.cn:8080/teacher/view.html?id=159">Hu Xia</a>. My research focuses on spatial query processing, social media mining and multimedia databases. I have published 7 papers in MM, SIGIR, TKDE, ICDE, etc.

## Highlighted Work 
<ul>
<li>Map-matching</li>With the advance of various location-acquisition technologies, a myriad of GPS trajectories can be collected every day. However, the raw coordinate data captured by sensors often cannot reflect real positions due to many physical constraints and some rules of law. How to accurately match GPS trajectories to roads on a digital map is an important issue. The problem of map-matching is fundamental for many applications. Unfortunately, many existing methods still cannot meet stringent performance requirements in engineering. In particular, low/unstable sampling rate and noisy/lost data are usually big challenges. Information fusion of different data sources is becoming increasingly promising nowadays. As in practice, some other measurements such as speed and moving direction are collected together with the spatial locations acquired, we can make use of not only location coordinates but all data collected. We proposed a novel model using the related meta-information to describe a moving object, and present an algorithm called IF-Matching for map-matching. It can handle many ambiguous cases which cannot be correctly matched by existing methods. We ran our algorithm with taxi trajectory data on a city-wide road network. Compared with two state-of-the-art algorithms of ST-Matching and the winner of GIS Cup 2012, our approach achieves more accurate results.
<li>High-dimensional index</li>Locality sensitive hashing (LSH) and its variants are widely used for approximate kNN (k nearest neighbor) search in high-dimensional space. The success of these techniques largely depends on the ability of preserving kNN information. Unfortunately, LSH only provides a high probability that nearby points in the original space are projected into nearby region in a new space. This potentially makes many false positives and false negatives resulting from unrelated points. Numerous extensions of LSH aim to alleviate the above issue by improving the distance preserving ability. We abound improving LSH function but propose a novel idea to improve the performance of LSH for approximate kNN search by transforming the original data to a new space before applying LSH. Theoretical justification is given to prove that a preserving-ignoring transformation (PIT) satisfying some rigorous conditions can be used to convert original points to an interim space with strict distance preserving-ignoring capacity. Based on the property of distance preserving-ignoring, a linear order is utilized to build an efficient index structure in the interim space. Finally, LSH can be applied to candidate set searched by our index structure for final results. Our experiments are conducted with both simulation and real data sets, and the proposed PIT based index approach performs better than state-of-the-art methods SK-LSH, DSH and NSH in terms of both accuracy and efficiency.
<li>Travel route planning</li>Travel planning is an active problem for both research and industry, which aims to automatically mine user's attributes and recommend personalized routes. How to build interest model for users and understand their real intention brings great challenges. We proposed a travel route planning approach which mines the user interest model by multi-source social media (e.g., travelogues and check-in records), and understands the user’s real intention by active behavior (e.g., POI inputs). In order to unify heterogeneous data from dierent sources, a topical package is built as the measurement space. Based on the topical package, user topical package is modeled to nd user interest and route topical package is constructed to describe the attributes of each route. User’s active behavior can also be considered during route planning, where top ranked routes are nally recommended. The proposed multi-source topical package (MSTP) approach is evaluated on a real traveling dataset and compared with two state-of-the-art methods. The experimental result shows that MSTP performs better for providing a personalized POI visiting sequence.
</ul>

## Invited Journal Reviewer
<ul>
<li>IEEE Transactions on Knowledge and Data Engineering</li>
</ul>

## Awards
<ul>
<li>First Class Academic Scholarship, University of Electronic Science and Technology of China, China, 2016.09</li>
<li>National Postgraduate Scholarship, University of Electronic Science and Technology of China, China, 2016.09</li>
<li>Outstanding Undergraduate Dissertation, University of Electronic Science and Technology of China, China, 2016.06</li>
<li>Third Class Academic Scholarship, University of Electronic Science and Technology of China, China, 2015.09</li>
<li>Third Class Academic Scholarship, University of Electronic Science and Technology of China, China, 2014.09</li>
<li>National Encouragement scholarship, University of Electronic Science and Technology of China, China, 2013.09</li>
</ul>

## Main Projects
<ul>
<li>Big Media Content Analysis and Retrieval in Mobile Interactive Environment, Key Project funded by National Nature Science Foundation of China (No. 61632007), 2017-2021. Principal Investigator.</li>
<li>Research on Travel Trajectory Semantic Enhancement, Mining and Recommendation in Social Media, General Project funded by National Nature Science Foundation of China (No. 61672133), 2017-2020. Main Researcher.</li>
<li>Key Technologies and Applications in Context Aware Mobile Video Retrieval, Fundamental Research Funds for
the Central Universities of China under Grants (No.ZYGX2014Z007), 2015-2018. Principal Investigator.</li>
</ul>

## Publications 
<ul>
<li>Gang Hu, Jie Shao, Fumin Shen, Zi Huang, and Heng Tao Shen, <a href="http://dx.doi.org/10.1145/3077136.3080672">Unifying Multi-Source Social Media Data for Personalized Travel Route Planning</a>, <i>In Proceedings of the 40th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR)</i>, August 7-11, 2017, Tokyo, Japan.</li>
<li>Gang Hu, Jie Shao, Dongxiang Zhang, Yang Yang, and Heng Tao Shen, <a href="http://dx.doi.org/10.1109/ICDE.2017.47">Preserving-Ignoring Transformation based Index for Approximate k Nearest Neighbor Search</a>, <i>In Proceedings of the 33rd IEEE International Conference on Data Engineering (ICDE)</i>, April 19-22, 2017, San Diego, CA, USA.</li>
<li>Gang Hu, Jie Shao, Dongxiang Zhang, Yang Yang, and Heng Tao Shen, <a href="http://dx.doi.org/10.1109/ICDE.2017.11">IF-Matching: Towards Accurate Map-Matching with Information Fusion (Extended Abstract)</a>, <i>In Proceedings of the 33rd IEEE International Conference on Data Engineering (ICDE)</i>, April 19-22, 2017, San Diego, CA, USA.</li>
<li>Gang Hu, Jie Shao, Fenglin Liu, Yuan Wang, and Heng Tao Shen, <a href="http://dx.doi.org/10.1109/TKDE.2016.2617326">IF-Matching: Towards Accurate Map-Matching with Information Fusion</a>, <i>IEEE Transactions on Knowledge and Data Engineering (TKDE)</i>, 29(1): 114-127, 2017.</li>
<li>Bo Wang, Jie Shao, Chengkun He, and Gang Hu, <a href="http://dx.doi.org/10.1007/978-3-319-51814-5_30">Spatial Verification via Compact Words for Mobile Instance Search</a>, <i>In Proceedings of the 23rd International Conference on Multimedia Modelling (MMM)</i>, pages 356-367, January 4-6, 2017, Reykjavik, Iceland.</li>
<li>Jie Chen, Chengkun He, Gang Hu, and Jie Shao, <a href="http://dx.doi.org/10.1007/978-3-319-27674-8_10">SELSH: A Hashing Scheme for Approximate Similarity Search with Early Stop Condition</a>, <i>In Proceedings of the 22nd International Conference on Multimedia Modelling (MMM)</i>, pages 104-115, January 4-6, 2016, Miami, FL, USA.</li>
<li>Gang Hu, Jie Shao, Lianli Gao, and Yang Yang, <a href="http://doi.acm.org/10.1145/2733373.2806344">Exploring Viewable Angle Information in Georeferenced Video Search,</a>, <i>In Proceedings of the 23rd ACM International Conference on Multimedia (ACM MM)</i>, pages 839-842, October 26-30, 2015, Brisbane, Australia.</li>
</ul>
