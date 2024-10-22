
# 5
# 5.1
1. Supported GPUs: NVIDIA Tesla P100, V100 and A100.
# 10
## 10.2
1. 并行分为周向模态并行和区域并行
2. 
# 14
1.![image](https://github.com/user-attachments/assets/60e489e7-a690-41b3-a38a-6468e3ed889d =100)
## 14.1 控制方程

1. 等熵LEE (5方程LEE)
2. 各向同性LEE(推导自等熵LEE)(4方程)
1. 方程空间离散阶次为1-16
2. 方程时间离散阶次为4阶或者更高的RK方法
3. 边界条件使用ghost element的方法
# 14.3 空间与时间离散
1. 2D下使用三角单元
2. 3D下使用4面体单元
3. 相邻单元也可以使用不同的单元阶次
4. 时间步长是全局的(缺点：可以使用局部时间步?)
### 14.1.1 Isentropic Linearized Euler Equations  等熵的LEE
1. 5个未知量，使用保守形式给出分别为：
   - 密度 $\rho^{a}$
   - 动量: $(\rho v_i)^a$ ,包含三个方向的速度
   - 总能量: $(\rho e_T)^a$
1. 而对于 $v_i^a$ 则可以由 $v_i^a=\frac{(\rho v_i)^a-\rho^a v_i^0}{\rho^0}$ 求得
2. 而对于声压 $p^a=-(\gamma-1)\frac{v_k^0v_k^0}{2}\rho^a-(\gamma-1)\rho^0v_k^0v_k^a+(\gamma-1)(\rho e_T)^a$
1. 方程形式为：![image](https://github.com/user-attachments/assets/52f54e44-b25f-4dd2-b019-659a4ea67894)
2. 此方程可以求解旋转流中的声传播，还可以求解超声速流下的声传播
### 14.1.2 Homentropic Linearized Euler Equations
1. 控制方程 ![image](https://github.com/user-attachments/assets/184de0c4-7686-48ff-ad0b-e9a223cb433b)

# 15 
# 15.3 Incident field of acoustic sources 入射声源 
1. 可以分为以下几类：
    -spherical source (point source)
    -cylindrical source (line source)
    -plane wave source.
1. 注意：入射声源外部必须由buffer zone包裹（或者由pml包裹）

# 16 气动声源
1. source remapping技术
## 16.3 AeroAcoustic Models in ActranDGM (关于声源的模型?)
1. 不同的方程采用了不同的声源
### 16.3.1 Bogey, Bailly & Juvé model
1. 此声源模型适用于LEE方程(16.2a-c) ![image](https://github.com/user-attachments/assets/147b6aa2-1a63-4f87-aa99-501b93743bcf)
2. 这些声源项是通过给定一个合适的**湍流模型**来求解非稳态NS方程得到的
3. 这些声源只在LEE方程的动量方程中出现 ![image](https://github.com/user-attachments/assets/c1ff5008-0743-43d5-92ae-6547f9e12797)
4. 在`VOLUME_SOURCE`数据块中存储，说明是体积源
5. 参考文献： Computation of flow noise using source terms in linearized euler’s equations
### 16.3.2 Turbulent Entropic model
1. 在动量方程和能量方程中都含有声源项
2. 能量方程的声源项依赖于温度场
3. 动量方程项与上面的Bailly的完全相同 ![image](https://github.com/user-attachments/assets/e4bc1bf4-edd4-42a9-b76e-f2071e49976e)

4. 参考文献：Acoustic source terms for the linearized euler equations in conservative form.
### 16.3.3 Stochastic Noise Generated Randomly (SNGR) model
1. ![image](https://github.com/user-attachments/assets/89dc8a16-5479-41d0-b402-7a8fa397ade5)
2. 与bailly比起来只有声源项不同，
3. 参考文献：
   - A stochastic approach to compute subsonic noise using linearized euler’s equations.
   - Stochastic approach to noise modelling for free turbulent flows.


   
