这个项目是我在爱丁堡大学读硕士期间的毕业论文项目，主要目的是针对Multi-Period Service Territory Design Problem的Schedule部分提出一种启发式算法来求解。

根据业务需要，我们将客户分为若干组，同时考虑组内成员的距离以及组与组之间工作量的平衡，在此思路上建模，并为这个模型的解题提出了一种全新的启发式算法。这个算法包括initialize部分和improve部分。在improve部分中，我们又分别测试了relaxing和adjusting两种方法。结果表明，相比于直接对问题进行求解，使用启发式算法和其中的relaxing方法改善时，可以在有效减少计算时间的同时,将与最优值的gap缩小到5%以下。具体的介绍、内容、数学模型和结果见**A Heuristic Solution for MPSTDP-S.pdf**。

文件说明：
1. Data文件夹：包含所有数据，
2. MPSTDP-S.ipynb：项目运行所需要的所有代码，
3. upgrade pass method(Py xpress).pdf: 将xpress软件专业版通行证导入python xpress包方法（通行证需自行购买），
4. A Heuristic Solution for MPSTDP-S.pdf：毕业论文，
5. Result文件夹：MPSTDP-S.jpynb运行后的结果，可复现。


This project is my dissertation project during my master's degree in the University of Edinburgh. The main purpose of this project is to eliminate a heuristic algorithm to solve the Schedule part of the Multi-Period Service Territory Design Problem.

According to the business needs, we divide customers into several groups, and consider the distance of members in the group and the balance of workload between groups. Then we build a model based on this idea, and propose a new heuristic algorithm for solving the problem of this model. The algorithm includes initialize part and improve part. In the improve section, we test both relaxing and adjusting methods, respectively. The results show that compared with solving the problem directly, using the heuristic algorithm and the relaxing method therein can effectively reduce the calculation time while reducing the gap from the optimal value to less than 5%. See **A Heuristic Solution for MPSTDP-S.DF ** for specific introduction, contents, mathematical models and results.

Description:
1. Data folder: contains all data files,
2. Mpstdp-s.ipnb: All the code needed to run the project,
3. upgrade pass method(Py xpress).pdf: Import the xpress Professional pass to the python xpress package.
4. A Heuristic Solution for MPSTDP-S.DF: Graduation thesis,
5. Result folder: mpstdp-s.pynb after running the result, can be repeated.
