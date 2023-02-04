# Machine-learning-for-structural-damage-prediction
# 基于机器学习算法的结构破坏预测 #   
**[特别声明]** PEER柱数据库地址如下：
<div align="left"> 
<a href="https://nisee.berkeley.edu/spd/index.html"><img src="https://img.shields.io/badge/-PEER Dataset-F7931E?style=style=flat-square&logo=scikit-learn&logoColor=white" /></a>
</div> 

* ## 滞回曲线 ##
<div align=center>
<img width="1200" src="https://user-images.githubusercontent.com/98397090/216263827-ba5885f3-9fb4-41c8-becb-bd2c7efd11a8.png"/>
</div>

* ## 数据库结构 (PEER_Dataset) ##
选取PEER数据库中典型的13个可以影响柱力学性能指标的因素，如下表所示。
<div align=center>
<img width="1200" src="https://user-images.githubusercontent.com/98397090/216273407-0a884b95-58c6-4dfe-9fd5-f43090b62141.png"/>
<img width="1200" src="https://user-images.githubusercontent.com/98397090/216273426-310bd8cc-dea5-4938-83d6-c2529f9da75d.png"/>
<img width="1200" src="https://user-images.githubusercontent.com/98397090/216273423-bd582eb1-1f39-43f2-97f0-364b9bbd0707.png"/>  
<img width="1200" src="https://user-images.githubusercontent.com/98397090/216273443-588af748-ff0b-4a0e-9ae7-0944a829d907.png"/>  
</div>

* ## 特征分析 ##
基于梯度提升机合并多个决策树可以得到每个特征的重要性，梯度提升机通常使用深度很小的树(1~5之间)，预测速度很快。梯度提升的背后是合并多个简单的模型，比如深度较小的树，每棵树只能对部分数据进行准确预测，因此添加的树越来越多，可以不断提升迭代的性能。
<table align="center" border="0" style="border-collapse: collapse;">
  <tr>
    <td align=center><img width="600px" src="https://user-images.githubusercontent.com/98397090/216299296-804bb77a-4ea3-4967-9c60-f551cb0ce7ed.png"/></td>
    <td align=center><img width="600px" src="https://user-images.githubusercontent.com/98397090/216299903-d95c053c-6c42-4b09-bcbe-ae13bcbd7b28.png"/></td>
  </tr>
  <tr>
    <td align=center colspan="2"><img width="1200px" src="https://user-images.githubusercontent.com/98397090/216301540-2d63a6ff-cb1f-4664-8a2d-a407acfeb14c.png"/></td>
  </tr>
</table>

* ## XGBoost ##
模型优化前后对比
<table align="center" border="0" style="border-collapse: collapse;">
  <tr>
    <td align=center><img width="600px" src="https://user-images.githubusercontent.com/98397090/216739324-249843e6-a1b9-409b-9e78-01c052e7d22b.png"/></td>
    <td align=center><img width="600px" src="https://user-images.githubusercontent.com/98397090/216739326-9818755f-1bb8-413a-94b0-39ade7e82718.png"/></td>
  </tr>
  <tr>
    <td align=center colspan="2"><img width="1200px" src="https://user-images.githubusercontent.com/98397090/216739444-70259984-e04c-4d19-b41b-55ba8b9b6b49.png"/></td>
  </tr>
</table>
