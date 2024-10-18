
# actrandgm版本更新变化
|  2024.2 | 2024.1  |   |   |   |   |   |   |
|---|---|---|---|---|---|---|---|
|   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |

# 2024.2
1. https://simcompanion.hexagon.com/customers/s/article/What-s-New-in-Actran-2024-2
2. ![image](https://github.com/user-attachments/assets/ed31c69b-4a11-4fca-8ce4-41edbf6ffbf4)

# 2024.1
1. https://www.bilibili.com/video/BV1BCvbefEru?t=1060.8
2. ![image](https://github.com/user-attachments/assets/90164cfe-058f-49ba-8c05-94379a667c4e)

# 2023.2
1. 官网介绍 https://simcompanion.hexagon.com/customers/s/article/Whats-New-Actran-2023-2
2. b站 https://www.bilibili.com/video/BV1xs421N7zB?t=46.5
3. ![image](https://github.com/user-attachments/assets/c56c9e87-defc-4ed5-8241-bffbb63d8fdb)
4. 没有关于dgm的？

# 2023.1
1. 官网 https://simcompanion.hexagon.com/customers/s/article/Whats-New-Actran-2023-1
2. b站 https://www.bilibili.com/video/BV17g4y1r7y2?t=25.1
3. dgm旋转部件 https://www.bilibili.com/video/BV17g4y1r7y2?t=1452.6
4. ![image](https://github.com/user-attachments/assets/4f17069b-37fc-4958-a3c0-dcada9d7eefe)

# 2023
1. 官网https://simcompanion.hexagon.com/customers/s/article/Whats-New-Actran-2023 没有dgm的
2. 没看到介绍的
3. 
# 2022.1
1. 官网 https://simcompanion.hexagon.com/customers/s/article/Whats-New-Actran-2022-1
2. 没看到相关介绍
# 2022
1. 官网 https://simcompanion.hexagon.com/customers/s/article/Whats-New-in-Actran-2022 没有
2. b站 https://www.bilibili.com/video/BV1ZS4y1Y7E4?t=1472.2
3. 时域内求解宽频带噪声源 ![image](https://github.com/user-attachments/assets/50fb07a3-a459-4bb2-adb6-40d39b20f3e9)
4. 时域声衬计算https://www.bilibili.com/video/BV1ZS4y1Y7E4?t=1574.7 ![image](https://github.com/user-attachments/assets/37eacdeb-3856-4bd5-a0d3-82782833d6cb)
5. 增加了涡波控制 ![image](https://github.com/user-attachments/assets/d746441b-609e-4e3b-810f-2224a41c8693) https://www.bilibili.com/video/BV1ZS4y1Y7E4?t=1645.7
6. 相当于增加了新的求解方程？

# 2021.1
1. 官网 https://simcompanion.hexagon.com/customers/s/article/Whats-New-Actran-20211
2. 没有更新dgm相关的？

# 2021
1. 官网 https://simcompanion.hexagon.com/customers/s/article/What-s-New-in-Actran-2021
2. 没有相关更新
3. b站https://www.bilibili.com/video/BV1rU4y147Mo?t=31.0

# 2020
1. 官网 没有信息
2. b站 https://www.bilibili.com/video/BV1mE411E7CW?t=60.0
3. ![image](https://github.com/user-attachments/assets/230f2c06-ef8c-4f3a-baf3-d2f3f314e3cf)
4. 没有dgm相关信息
5. 
# 2017 

# 2016 
1. 支持gpu https://audioxpress.com/news/New-Actran-16-Release-Delivers-New-Advances-for-Acoustic-Response-in-Bigger-Domains-and-for-Higher-Frequencies
2. 


# user guide的章节信息
## 13.0
1. ![image](https://github.com/user-attachments/assets/1804c75f-af61-493c-a269-b21f9c969f46)
2. 这个theory章为37页

## 15.0
1. ![image](https://github.com/user-attachments/assets/b207accb-1103-4f73-991c-2dad44a991b3)
2. 多了一章`Boundary Conditions`
3. 19章多了一节`19.3 Rotating and non-rotating modes . . . . . . . . . . . . . . . . . . . 271`
1. 这个theory章为57页
5. 
## 17.0
1. ![image](https://github.com/user-attachments/assets/53c1e68a-ee94-475d-97df-753f302e1db8)
2. 这个theory章为33页，少了很多

## 20.0
1. ![image](https://github.com/user-attachments/assets/8fd1e12c-7932-4966-b00f-9403211288cb)
2. 这个theory章为47页
   
## 24.1
1. ![image](https://github.com/user-attachments/assets/8e1d62bf-61ff-4272-bb49-d704d72f0901)
2. 这个theory章为70页


# userguide 中对新功能的介绍 Major new features of Actran DGM Release xxx
## 总览
|  2024.2 | 2024.1  | 2020  |  2017 |  15.0 | 13.0  |   |   |
|---|---|---|---|---|---|---|---|
|1. Reflection coefficient boundary condition
2. Adding numerical viscosity to control instabilities
3. Green analysis with flow   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |
## 24.1
1. Reflection coefficient boundary condition
2. Adding numerical viscosity to control instabilities
3. Green analysis with flow
### Reflection coefficient boundary condition
A ctran 2024.1 introduces a new REFLECTION_COEFFICIENT boundary condition that can be used to model absorbing materials in Actran DGM  ̇ Like ADMITTANCE and IMPEDANCE boundary conditions, it can be used for multi-frequency simulations with the Extended Multi-Pole BroadBand (XMPBB) model.
Actran 2024.1在Actran DGM ̇ Like ADMITTANCE和IMPEDANCE边界条件中引入了一种新的可用于建模吸波材料的REFLECTION _ COEFFICIENT边界条件，可用于扩展多极宽带( Extended Multi-Pole Broad Band，XMPBB )模型的多频仿真。
### Adding numerical viscosity to control instabilities
A new datablock has been added to this release, the LIMITER, to help correcting instabilities in Actran DGM computations. It can be used to add numerical viscosity in the Euler equations in zones that were the cause of instabilities, without impacting the simulation results if it’s correctly setup.
该版本增加了一个新的数据集，即LIMITER，以帮助纠正Actran DGM计算中的不稳定性。它可以在导致不稳定的区域在欧拉方程中加入数值粘性，只要设置正确，不影响模拟结果。
### Green analysis with flow
A ctran 2024.1 introduces Green analysis within Actran DGM  ̇ This anlsysis first computes the Green transfer functions by inverting the sources and the microphones in the radiation sequence, and then can reconstruct the solution for any source amplitude in the solution step. This Green approach in Actran DGM can be very useful for computations with many loadcases, as the radiation sequence (longer one) only needs to be run once.
Actran 2024.1在Actran DGM ̇中引入了Green分析。该分析首先通过反演辐射序列中的声源和麦克风来计算Green传递函数，然后在求解步骤中可以对任意声源幅度重建解决方案。Actran DGM中的这种Green方法对于具有多个工况的计算非常有用，因为辐射序列(较长的序列)只需要运行一次。

## 2020
1. Multifrequential power evaluation
2. New definition of mean flow and inclusion of multiple mean flows
3. Extended GPU acceleration
4. Various other improvements
### Multifrequential power evaluation
The current revision of Actran DGM includes improvements in the power evaluation, both for MODAL and BUFFER components. Frequency powers are now evaluated based on frequential data, which heavily improves the accuracy of the provided results. As a result, multifrequential power evaluations are also available.
Actran DGM目前的修订包括对MODAL和BUFFER组件的功耗评估的改进。频率功率现在是基于频率数据进行评估的，这大大提高了提供结果的准确性。因此，多频功率评估也是可用的。
### New definition of mean flow and inclusion of multiple mean flows
The current version of Actran DGM includes a new syntax for setting the mean flow of the components and of the analysis. For the components, it is now possible to select an Isentropic or Homentropic formulation independently of the flow definition. Moreover, beside the main mean flow file defined by the user, additional mean flow definition for specific components can be defined as well.
当前版本的Actran DGM包含了一种新的语法，用于设置组件和分析的平均流程。对于部件，现在可以独立于流动定义选择等熵或等熵形式。此外，在用户定义的主平均流文件之外，还可以定义针对特定部件的附加平均流定义。
### Extended GPU acceleration
The current revision of Actran DGM extends the support of GPU acceleration for the mean flow integration on acoustic elements, and for quadratic and curved geometries.
Actran DGM目前的修订扩展了GPU加速对声学单元平均流积分的支持，以及对二次和曲面几何的支持。
## 2017
1. Integrated Thompson Boundary condition
2. Zonal Thompson Boundary condition
1. Integrated BC_MESH Boundary condition
2. Support of dipoles and quadrupoles
### Integrated Thompson Boundary condition
The current revision of Actran DGM supports the INTEGRATION keyword for the THOMPSON boundary condition. This latest can be activated within the iCFD input file and allows to capture complex patterns on higher order surface elements. This improves the computational performance of the computation as well as the physical representation of the excitation.
积分Thompson边界条件Actran DGM目前的修订支持THOMPSON边界条件的INTEGRATION关键字。这个最新版本可以在i CFD输入文件中激活，并允许在更高阶的表面元素上捕获复杂的模式。这提高了计算的计算性能，也改善了激励的物理表征。
### Zonal Thompson Boundary condition
A new component is available in the current release, the so-called characteristic buffer component. This component can be used as a buffer component to selectively damp incoming waves. This allows to be used backing a THOMPSON boundary condition, insuring the reflected waves are not directly damped, and thus improving the non reflective behavior at the back of the THOMPSON boundary condition.
在当前的发布中，有一种新的组件是可用的，即所谓的特征缓冲组件。该元件可作为缓冲元件，对入射波进行选择性阻尼。这允许使用THOMPSON边界条件的背面，确保反射波不被直接衰减，从而改善THOMPSON边界条件背面的非反射行为。
### Integrated BC_MESH Boundary condition
The current revision of Actran DGM supports the INTEGRATION keyword for the BC_MESH boundary condition. The integration order on the acoustic elements is automatically selected by Actran DGM, or can be user-defined. The usage of the INTEGRATION keyword allows to use higher order elements, thus improving the computational performance and numerical accuracy.
Actran DGM目前的修订版支持BC _ MESH边界条件的INTEGRATION关键字。声学元件上的积分顺序可由Actran DGM自动选择，也可由用户自定义。INTEGRATION关键字的使用允许使用更高阶的单元，从而提高了计算性能和数值精度。
### Support of dipoles and quadrupoles
This version of Actran DGM supports dipole and quadrupole sources within the near field domain. This completes the already existing support of spherical, cylindrical and planar sources. The specification of the dipole and quadrupole sources can be provided through respective amplitude and directions, or directly through their tensor. Moreover, the usage of multiple dipole and quadrupole sources can be performed using the CLOUD_SOURCE data block.
这个版本的Actran DGM支持近场范围内的偶极子和四极子源。这就完成了对已经存在的球形、圆柱形和平面源的支持。偶极子源和四极子源的规格可以通过各自的振幅和方向给出，也可以直接通过它们的张量给出。此外，可以使用CLOUD _ SOURCE数据块进行多个偶极子和四极子源的使用。
## 2015
1. Performance improvements
2. Loadcase and domain multi-parallelism
3. New admittance formulation
4. Convergence check
5. Integrated FWH computation
6. Transient excitations
7. Element order selection
### Performance improvements
This new revision of Actran DGM includes a new kernel which avoids the domain decomposition following the element order. This induces a faster model building and less interfaces to handle during parallel communication. The time required for model assembly and outputs is thus reduced with respect to previous revisions.
Actran DGM的这一新修订包含了一个新的内核，避免了遵循元素阶次的区域分解。这使得并行通信过程中模型建立更快，需要处理的接口更少。因此，模型组装和输出所需的时间相对于之前的修订有所减少。

### Loadcase and domain multi-parallelism
A new type of multiparallelism, combining Loadcase parallelism with Domain parallelism is made available for multiple loadcase computations. It allows to partition the loadcases in an efficient way while using less domain partitions to optimize the efficiency of the computation. More information on running parallel computations can be found in Section 10.2.
将Loadcase并行与Domain并行相结合，提出了一种新的多机并行算法，可用于多机并行处理。它允许以有效的方式划分负载情况，同时使用较少的域划分来优化计算的效率。关于运行并行计算的更多信息可参见第10.2节。
### New admittance formulation
The current revision of Actran DGM has a new formulation for the ADMITTANCE boundary condition. This latest replaces the previous formulation, which was based on an impedance formulation. This modification has different consequences. The new formulation is now stable for admittances between 0and 1 ρ∗c , which represents usual admittance values. Moreover, the transfer admittance values specified within a TRANSFER_PP material can now be symmetric.
目前Actran DGM的修订对ADMITTANCE边界条件有了新的表述。这个最新的公式取代了以前基于阻抗公式的公式。这种修改具有不同的后果。新的公式现在对于0到$\frac{1}{\rho c}$之间的导纳是稳定的，这代表了通常的导纳值。此外，在TRANSFER _ PP材料中规定的传递导纳值现在可以是对称的。
### Convergence check
The current revision of Actran DGM allows to perform the convergence check operation on a user defined surface. By default, this check is performed on the surface located between the PHYSICAL and BUFFER components. The CONVERGENCE_CHECK data block allows to specify the surface on which to perform the convergence check and the associated parameters. Using the CONVERGENCE_CHECK or the default FWH surface, the convergence can now be checked on either the density, or on a particular characteristic quantity. The relative error can also be exported into an external file or image to follow the convergence of the computation.
当前`Actran DGM`的修订允许在用户定义的曲面上执行收敛性检查操作。默认情况下，这种检查是在位于`PHYSICAL`和`BUFFER`组件之间的表面上进行的。`CONVERGENCE_CHECK`数据块允许指定执行收敛性检查的表面和相关参数。使用`CONVERGENCE_CHECK`或默认的FWH表面，现在可以在密度上或在特定的特征量上检查收敛性。相对误差也可以输出到外部文件或图像中，以跟随计算的收敛。
### Integrated FWH computation
The evaluation of the far field pressure for field points or field meshes is now performed during the Actran DGM computation. If a field point is located outside the PHYSICAL components, it is automatically assigned to all BUFFER components. Alternatively, it can also be forced to a particular BUFFER component. This allows to avoid using the FWH utility and thus to reduces the number of input files.
对于场点或场网格的远场压力的评估现在是在Actran DGM计算过程中进行的。如果一个场点位于PHYSICAL组件之外，则自动分配给所有的BUFFER组件。或者，它也可以强制到一个特定的BUFFER组件。这样可以避免使用FWH实用工具，从而减少输入文件的数量。
### Transient excitations
The current release of Actran DGM allows to impose transient or multiple frequential inputs for sources, velocity or Thompson excitations. This allows to impose realistic excitations, impulses to excite all frequencies, or different frequencies using the same computation.
目前发布的Actran DGM允许对震源、速度或Thompson激发施加瞬态或多次频繁输入。这允许施加实际的激励，脉冲来激励所有的频率，或者使用相同的计算来激励不同的频率。
### Element order selection
The element orders are selected to insure a particular dissipation error, using a logarithm law based on the number of element per wavelength. The current revision of Actran DGM allows to manually specify the dissipation error, in order to improve precision of computational performance. This selection can be made using the ELEMENT_ORDER_DISSIPATION within the PARAMETER data block.
单元阶数的选择是为了保证特定的耗散误差，采用基于每个波长单元数的对数律。目前对Actran DGM的修订允许手动指定耗散误差，以提高计算性能的精度。这种选择可以使用`PARAMETER`数据块中的`ELEMENT_ORDER _DISSIPATION`进行。
## 2013
1. Velocity boundary condition
2. Thompson boundary condition
3. Transfer admittance
4. Multi-parallelism
5. Selection of output requests
### Velocity boundary condition
This new release includes a velocity boundary condition in Actran DGM. This natural boundary condition should be applied to free faces of a physical component, and can be used to simulate the noise of a body with a prescribed rigid motion in the surrounding acoustic fluid. Further details can be found in Section 8.40.
这个新的发布版在Actran DGM中包含了一个速度边界条件。这种**自然边界条件**适用于物理部件的自由面，并且可以用来模拟周围声流体中具有规定刚性运动的物体的噪声。进一步的细节可参见第8.40节
### Thompson boundary condition
The current revision of Actran DGM includes a Thompson boundary condition. This boundary condition corresponds to a velocity boundary condition with a non reflective condition for incident waves. It can be used to simulate an excitation from a neighboring acoustic component to take into account installation effects on the acoustic radiation by coupling an Actran/TM computation of the near free field with an Actran DGM computation of the installed far field. Further details can be found in Section 8.41.
目前对Actran DGM的修正包含了Thompson边界条件。该边界条件对应于入射波具有非反射条件的速度边界条件。通过近自由场的Actran / TM计算和远场的Actran DGM计算的耦合，可以用来模拟来自邻近声学部件的激励，以考虑安装对声辐射的影响。进一步的细节可参见第8.41节。
### Transfer admittance
This new release includes the specification of transfer admittance between different physical components. Typically, it is used to model the acoustic transmission between two fluid domains, for example perforated sheets or filters, for modelling expansion chambers or non localized treatments. It takes into account the influence of a grazing flow on both faces of the component. Further details can be found in Section 21.4.
这个新的发布版包含了不同物理部件之间的传输导纳的确定方法。通常，它用于模拟两个流体域之间的声波传输，例如穿孔板或过滤器，用于模拟膨胀腔或非局域声学处理部分。它考虑了一个grazing流对部件两个面的影响。更进一步的细节可以在第21.4节中找到。
### Multi-parallelism
In addition to the standard parallel solutions, a dual parallelism is now supported for Actran DGM. It is now possible to combine the azimuthal and domain parallelisms together. More information on how to run a parallel job can be found in Section 12.2.
除了标准的并行解决方案，Actran DGM现在还支持双重并行。现在可以将周向并行和域并行结合在一起。关于如何运行一个并行作业的更多信息可以在第12.2节中找到。
### Selection of output requests
The specification of output request is now available in the current revision of A ctran DGM. This specification allows reducing the size of output files by reducing the number of outputs.
Actran DGM的当前修订版中提供了输出请求的规范。该规范允许通过减少输出的数量来减少输出文件的大小。


