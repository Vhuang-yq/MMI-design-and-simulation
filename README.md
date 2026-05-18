# 📡 MMI 多模干涉波导仿真（varFDTD）

本项目基于 Lumerical FDTD Solutions 中的 **varFDTD 求解器**，对 **多模干涉（MMI, Multimode Interference）波导结构**进行仿真分析，研究不同L_mmi下各输出端口的透射特性、电场分布。

---


### 📐 结构组成

该模型主要包括：

- 输入单模波导
- 多模干涉区（MMI区）
- 输出分支波导
- 多个监视器（monitor）用于数据采集

![Structure](./structure.png)

---

## ⚙️ 仿真设置

- **求解器**：varFDTD  
- **激励源**：模式光源（Mode Source）  
- **监视器（Monitors）**：
  - `T_up`：上输出端透射
  - `T_mid`：中输出端透射
  - `T_down`：下输出端透射  
- **扫描参数**：L_mmi

---

## 📊 仿真结果

### 🔼 上端输出透射（T_up）

![T_up](./T_up.png)

---

### 🔽 下端输出透射（T_down）

![T_down](./T_down.png)

---

### ⚡ 中间区域场分布（T_mid）

![T_mid](./T_mid.png)

---

### ⚡ 光场分布（E）

![光场](./E.png)

---
