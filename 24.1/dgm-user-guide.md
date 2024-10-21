
# 5
# 5.1
1. Supported GPUs: NVIDIA Tesla P100, V100 and A100.
# 10
## 10.2
1. 并行分为周向模态并行和区域并行
2. 
# 14
1.![image](https://github.com/user-attachments/assets/60e489e7-a690-41b3-a38a-6468e3ed889d)
## 14.1
1. 等熵LEE (5方程LEE)
2. 各向同性LEE(推导自等熵LEE)(4方程)
1. 方程空间离散阶次为1-16
2. 方程时间离散阶次为4阶或者更高的RK方法
3. 边界条件使用ghost element的方法
# 14.3 空间与时间离散
1. 2D下使用三角剖分
2. 3D下使用4面体剖分
3. 相邻单元也可以使用不同的单元阶次
4. 时间离散步是全局的(缺点：可以使用局部时间步?)
5. 

