# AIMD_extxyz_sampling
将从AIMD获取的数据进行向量化，随后使用降维算法将向量化后的表格进行降维，随后使用聚类算法，从每个簇中随机采样，随后再给他转换回来，使用一些评估指标（能量分布/每一个时间步长的晶格结构mae等去衡量采样的有效性）
Vectomize the data obtained from AIMD, then use the dimensionality reduction algorithm to reduce the dimensionality of the vectomized table, then use the clustering algorithm to randomly sample from each cluster, and then convert it back to it, and use some evaluation indicators (energy distribution/lattice structure of each time step length mae, etc., to measure the validity of sampling).
