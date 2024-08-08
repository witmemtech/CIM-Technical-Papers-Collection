#  存内计算 论文合集（Paper with links)

**ISSCC 2024 decisions are now available on OpenReview！**

注1：欢迎各位大佬提交issue，分享CIM 论文和开源项目！

有任何问题，欢迎在Discussion 发表讨论，第一时间分享最新最前沿的存内计算、存储介质，存内应用，深度学习等学起来！



## 目录

##### 【存内计算ISSCC 34系列】

##### 【存内计算基础概念】

##### 【存内计算忆阻器论文合集】

##### 【存内计算-向量乘矩阵】

##### 【存内计算-数字与模拟计算】

##### 【存内计算-机器学习领域】

##### 【存内计算- 加速器】

##### 【存内计算- 现有应用场景】

##### 【存内计算-研究进展】




## 存内计算 ISSCC 34系列：

ISSCC 34系列论文涵盖了多个前沿研究领域，其中包括当前最前沿的研究领域，存内计算技术，数字电路设计，模拟电路设计，混合信号设计，CMOS图像传感器，电容数字转换器等多个领域,此系列包含ISSCC 34系列的每节论文以及解析，共开发者学习以及讨论。



###### ISSCC.34.1 ——适用于高精度 AI 应用的 28nm 83.23TFLOPS/W POSIT 

Paper: [10.1109/ISSCC49657.2024.10454567](http://dx.doi.org/10.1109/ISSCC49657.2024.10454567)

###### 解析： https://blog.csdn.net/m0_58966968/article/details/139472261?utm_source=bbs_include



###### ISSCC 34.2——双端口设计实现高面积利用的浮点/整数存算

Paper: [10.1109/ISSCC49657.2024.10454447](https://doi.org/10.1109/ISSCC49657.2024.10454447)

解析：https://blog.csdn.net/m0_58966968/article/details/139983166?spm=1001.2014.3001.5502



###### ISSCC 34.3——“闪电”数模混合存内计算，适应transformer和CNNs架构

Paper: [10.1109/ISSCC19947.2020.9062931](https://doi.org/10.1109/ISSCC19947.2020.9062931)

解析：https://blog.csdn.net/m0_58966968/article/details/138122847?spm=1001.2014.3001.5502



###### ISSCC 34.4—— 采用台积电3nm工艺制作的数字存算一体芯片

Paper: [10.1109/ISSCC49657.2024.10454556](https://doi.org/10.1109/ISSCC49657.2024.10454556)

解析：https://bbs.csdn.net/topics/618245914



###### ISSCC 34.5——用于统一加速CNN和Transformers的818-4094 TOPS/W电容可重构CIM宏单元

Paper: [10.1109/ISSCC49657.2024.10454489](https://doi.org/10.1109/ISSCC49657.2024.10454489)

解析：https://bbs.csdn.net/topics/619197013



## 存内计算-基础概念：

存内计算（Computing in Memory）是指将计算单元直接嵌入到存储器中，顾名思义就是把计算单元嵌入到内存当中，通常计算机运行的冯·诺依曼体系包括存储单元和计算单元两部分。在本质上消除不必要的数据搬移的延迟和功耗，从而消除了传统的冯·诺依曼架构的瓶颈，打破存储墙。据悉，存内计算特别适用于需要大数据处理的领域，比如云计算、人工智能等领域，最重要的一点是存内计算是基于存储介质的计算架构，而且存内计算是一种新型存储架构且轻松打破传统存储架构的瓶颈。



###### **1.In-Memory Computing: A Game Changer for Enterprise Applications**

Paper:  https://www.usenix.org/conference/atc19/presentation/lee



###### 2.In-Memory Computing with Phase-Change Memory: Opportunities and Challenges

Links: https://www.sciencedirect.com/science/article/abs/pii/S0165562520301085



###### 3.Towards End-to-End In-Memory Computing Systems

Links: https://link.springer.com/article/10.1007/s13389-020-00308-5



## 存内计算-忆阻器论文合集：

存内计算忆阻器是一种前沿技术，它利用忆阻器的电阻可变特性，在存储单元中直接完成计算操作，避免了数据在内存和处理器之间的频繁传输，提高了计算效率和能效比。忆阻器作为存内计算的重要器件候选，可以支持各种模拟计算应用，包括人工神经网络（ANN）、机器学习、科学计算和数字图像处理等。下面论文包括几种存内计算领域热门关注的忆阻器SRAM，MRAM，Nor Flash, DRAM 。



#### SRAM: 

###### 1.In-Memory Computing with Emerging Non-Volatile Memory: A Machine Learning Perspective

Paper: https://www.nature.com/articles/s41729-021-00100-5



###### 2. A 137.5 TOPS/W SRAM Compute-in-Memory Macro with 9-b Memory Cell-Embedded ADCs and Signal Margin Enhancement Techniques for AI Edge Applications

Paper:https://arxiv.org/abs/2307.05944



###### 3.A Charge Domain P-8T SRAM Compute-In-Memory with Low-Cost DAC/ADC Operation for 4-bit Input Processing

Paper: https://arxiv.org/abs/2211.16008



#### MRAM：

###### 1.MRAM-based Analog Sigmoid Function for In-memory Computing

Paper ：https://arxiv.org/abs/2204.09918



###### 2.A noise-tolerant, resource-saving probabilistic binary neural network implemented by the SOT-MRAM compute-in-memory system

Paper: https://arxiv.org/abs/2403.19374



#### Nor Flash: 

###### 1.Collaborative Training for Compensation of Inference Errors in NOR Flash Computing in memory Chips

Paper: [10.1109/CSCWD61410.2024.10580459](https://doi.org/10.1109/CSCWD61410.2024.10580459)



###### 2.A 40nm 1Mb 35.6 TOPS/W MLC NOR-Flash Based Computation-in-Memory Structure for Machine Learning

Paper:[10.1109/ISCAS51556.2021.9401600](https://doi.org/10.1109/ISCAS51556.2021.9401600)



###### 3.Multibit Content Addressable Memory Design and Optimization Based on 3-D nand-Compatible IGZO Flash

Paper: https://xplorestaging.ieee.org/document/10521670



###### 4.Design-Technology Co-Optimizations (DTCO) for General-Purpose Computing In-Memory Based on 55nm NOR Flash Technology

Paper:  [10.1109/IEDM19574.2021.9720625](https://doi.org/10.1109/IEDM19574.2021.9720625)



#### DRAM：

###### 1.Computing-In-Memory Using 1T1C Embedded DRAM Cell with Micro Sense Amplifier for Enhancing Throughput

Paper:[10.1109/ICCE-Asia57006.2022.9954870](https://doi.org/10.1109/ICCE-Asia57006.2022.9954870)



###### 2.IGZO CIM: Enabling In-Memory Computations Using Multilevel Capacitorless Indium–Gallium–Zinc–Oxide-Based Embedded DRAM Technology

Paper:  [10.1109/JXCDC.2022.3188366](https://doi.org/10.1109/JXCDC.2022.3188366)



###### 3.A Novel Transpose 2T-DRAM based Computing-in-Memory Architecture for On-chip DNN Training and Inference

Paper: [10.1109/AICAS57966.2023.10168641](https://doi.org/10.1109/AICAS57966.2023.10168641)



## 存内计算-向量乘矩阵：

所有存内计算操作中, 最普遍的是利用基尔霍夫定律 (Kirchoff’s Law) 进行向量乘矩阵操作. 原因在于: （1）它能够高效地将计算和存储紧密结合; (2) 它的计算效率高 (即, 在一个读操作延迟内能 完成一次向量乘矩阵); (3) 目前流行的数据密集型应用中, 如机器学习应用和图计算应用, 向量乘矩阵的计算占了总计算量的 90% 以上 。











## 存内计算-数字与模拟计算：

数字存内计算与模拟存内计算各有优劣，都是存算一体发展进程中的重点发展路径，数字存内计算由于其高速、高精度、抗噪性强、工艺技术成熟、能效比高等特点，更适用于大算力、云计算、边缘计算等应用场景；模拟存内计算由于其非易失性、高密度、低成本、功耗低等特点，更适用于小算力、端侧、需长时待机等的应用场景。在如今可穿戴设备、智能家具、玩具机器人等应用走进千家万户的背景下，模拟存内计算的高能效、小面积、低成本等市场优势逐渐凸显，比如前面所提到的知存科技WTM2101已率先进入市场规模化应用，在商业化进程中处于领先地位，且更高算力WTM-8系列即将量产，在端侧AI市场具有极大的应用潜力。





## 存内计算-机器学习领域：

基于阻变存储器阵列的存内计算技术，实现了一步训练传统的机器学习算法，包括线性回归、逻辑回归。这一技术可以进一步用于训练多项式回归、神经网络等其它机器学习算法。



## 存内计算-加速器：



## 存内计算- 现有应用场景：

存内计算技术正迅速成为人工智能和其他数据密集型应用的关键驱动力。它通过将计算任务直接嵌入到存储单元中，显著减少了数据在处理器和存储器之间传输的需要，从而降低了延迟和能耗。存内计算在深度学习，图计算，智能传感器以及物联网设备中都有较多应用。



###### 1.A Survey on In-Memory Computing Architectures for Big Data Applications

Paper: https://ieeexplore.ieee.org/document/9150090



###### 2.A Comparative Study of In-Memory Computing Technologies for Data-Intensive Applications

Paper: https://www.sciencedirect.com/science/article/pii/S0167739X21000286



###### 3.In-Memory Computing with Phase-Change Memory: Opportunities and Challenges

Paper: https://www.sciencedirect.com/science/article/abs/pii/S0165562520301085


## 存内计算- 研究进展：


