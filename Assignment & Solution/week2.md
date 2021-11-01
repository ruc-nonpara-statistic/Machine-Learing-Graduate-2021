##### 第二周作业

**一、证明：多元正态分布的边缘分布也是正态分布：**

$$
X=\left[\begin{array}{l}
X_{1} \\
X_{2}
\end{array}\right], \quad \mu=\left[\begin{array}{l}
\mu_{1} \\
\mu_{2}
\end{array}\right], \quad
\Sigma=\left[\begin{array}{ll}
\Sigma_{11} & \Sigma_{12} \\
\Sigma_{21} & \Sigma_{22}
\end{array}\right]
$$

若$X \sim N(\mu, \Sigma)$ ，证明$X_{1} \sim N\left(\mu_{1}, \Sigma_{11}\right), X_{2} \sim N\left(\mu_{2}, \Sigma_{22}\right)$

**二、证明：实对称矩阵一定正交相似于对角矩阵**（Slide P16）

**三、**

3.1 将$8\times8$维的数据文件读入(见adj_8times8.csv)，记为A矩阵。

3.2 对矩阵A求特征根和特征向量，记最大的特征根为$\lambda_{1}$，对应的特征向量记为$\xi_{1}$，第二大特征根及特征向量为$\lambda_{2},\xi_{2}$，依此类推。

3.3 计算$\frac{\xi_{2}}{\xi_{1}}, \frac{\xi_{3}}{\xi_{1}}$,即对应元素相除，得到两个向量，按列合并为矩阵$B_{8\times2}$。

3.4 可以将矩阵$B$看作8个点的坐标，使用k-means方法进行聚类，并分析聚类的效果。聚类方法也可以选择其他类型，允许自由发挥（提示：也可以结合A矩阵，分析聚类结果是否合理，其中A矩阵中元素可以看作8个点之间是否有连接，取0表示不相连，取1表示相连）。

**四、**
4.1 给出矩阵A和向量b，计算回归方程Ax=b中的x（参见cs229-linalg.pdf第27页）。矩阵A以及向量b的数据见 LeastSq.csv。

4.2 计算矩阵$X^TA^TAX$对$X$的一阶导数。

4.3 计算矩阵$X^TA^TAX$对$X$的二阶导数。
