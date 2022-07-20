# TODO:👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

# 1. 碳水耦合模型(ET & GPP)

- `hydroTools`：水文气象学函数库，https://github.com/CUG-hydro/hydroTools
- `rPML`: https://github.com/CUG-hydro/rPML, https://github.com/CUG-hydro/PML.jl
- `BEPS`: <https://github.com/JChen-UToronto/BEPS_hourly_site>, <https://github.com/CUG-hydro/BEPS.jl>
- `SCOPE`: https://github.com/Christiaanvandertol/SCOPE
- `Land.jl`: Land融合了气候模式、陆面模型最先进的理论，学会这一个，跨入国际领先。<https://github.com/CliMA/Land>，<https://github.com/Yujie-WANG/Published-Codes-Yujie-WANG>
- `Maestra`: <https://github.com/rafaqz/Photosynthesis.jl>, <https://github.com/rafaqz/DynamicEnergyBudgets.jl>, <https://github.com/rafaqz/DEBplant>, <https://github.com/rafaqz/Microclimate.jl>, <https://github.com/rafaqz/Maestra>

### 可解决的问题：

#### 1. 夏季撑伞与否对人体感知温度的影响
  
  > 可能用到的理论：
  > 1. **散射理论**
  > 2. **蒸发理论**：湿表面与空气的温差

#### 2. 地表温度与空气温度的转换

202206河南高温，空气温度40°，地表温度却可以到74°。通过Penman公式，你将能掌握背后的机理。

#### 3. 地表水文循环研究

# 2. 水文模型
- `MARRMoT`: 47种水文模型，Julia改写300倍提速，<https://github.com/CUG-hydro/MARRMoT>、<https://github.com/CUG-hydro/MARRMoT.jl>
- `XAJ`, `VIC5`: https://github.com/rpkgs/VIC5
- `VIC5tools`: https://github.com/CUG-hydro/VIC5tools
- `RunoffPredict`, https://github.com/CUG-hydro/RunoffPredict

### 可解决问题: 
#### 1. 洪涝模拟与预测
#### 2. 时间序列预测

# 3. 时间序列预测
- `kfold`, 多种方法的k-fold交叉验证，https://github.com/rpkgs/kfold
- `LSTM`: 时间序列预测，https://github.com/kongdd/LSTM
- `Flux.jl`机器学习，https://github.com/FluxML/Flux.jl、https://github.com/kongdd/model-zoo、https://github.com/kongdd/Eat_Flux.jl_in_30_days

# 热浪研究
- `SpatioTemporalCluster`: 3维时空热浪追踪，<https://github.com/CUG-hydro/SpatioTemporalCluster.jl>, <https://github.com/CUG-hydro/ChinaHW_cluster.jl>；同样可应用与干旱、暴雨

# 4. 气象成因分析
## 工具

- `metpy`: <https://github.com/Unidata/MetPy>, <https://unidata.github.io/MetPy/latest/examples/index.html>
- `metR`: <https://github.com/eliocamp/metR>
- 气象动力学：南京大学MOOC,https://github.com/CUG-hydro/nju-DynamicMeteorology

## 理论
- 位势高度场
- 水汽通量
- 锋生锋消
- Q矢量
- 涡度守恒

> _上述链接部分为private repository，加入我们你将拥有所有repository的访问权限；_   
> _代码版权归[kongdd](https://github.com/kongdd)所有，未经许可禁止传播。_

## Under going researches

- [ChinaHW_path](https://github.com/CUG-hydro/ChinaHW_path)
- [ChinaHW_cluster.R](https://github.com/CUG-hydro/ChinaHW_cluster.R), [ChinaHW_cluster.jl](https://github.com/CUG-hydro/ChinaHW_cluster.jl), [SpatioTemporalCluster.jl](https://github.com/CUG-hydro/SpatioTemporalCluster.jl)
- [ET_evaluation](https://github.com/CUG-hydro/ET_evaluation)
- <https://github.com/CUG-hydro/MARRMoT.jl>, <https://github.com/CUG-hydro/FloodEventDivision>

