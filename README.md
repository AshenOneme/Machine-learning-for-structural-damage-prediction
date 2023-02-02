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

* ## 数据库结构 ##

<table border="0" cellpadding="0" cellspacing="0" width="1484" style="border-collapse:
 collapse;table-layout:fixed;width:1115pt">
 <colgroup><col width="338" style="mso-width-source:userset;mso-width-alt:12032;width:254pt">
 <col width="66" style="mso-width-source:userset;mso-width-alt:2360;width:50pt">
 <col width="92" style="mso-width-source:userset;mso-width-alt:3271;width:69pt">
 <col width="110" style="mso-width-source:userset;mso-width-alt:3925;width:83pt">
 <col width="104" style="mso-width-source:userset;mso-width-alt:3697;width:78pt">
 <col width="48" style="mso-width-source:userset;mso-width-alt:1706;width:36pt">
 <col width="49" style="mso-width-source:userset;mso-width-alt:1735;width:37pt">
 <col width="110" style="mso-width-source:userset;mso-width-alt:3925;width:83pt">
 <col width="116" style="mso-width-source:userset;mso-width-alt:4124;width:87pt">
 <col width="41" style="mso-width-source:userset;mso-width-alt:1450;width:31pt">
 <col width="92" style="mso-width-source:userset;mso-width-alt:3271;width:69pt">
 <col width="99" style="mso-width-source:userset;mso-width-alt:3527;width:74pt">
 <col width="69" style="mso-width-source:userset;mso-width-alt:2446;width:52pt">
 <col width="47" style="mso-width-source:userset;mso-width-alt:1678;width:35pt">
 <col width="103" style="mso-width-source:userset;mso-width-alt:3669;width:77pt">
 </colgroup><tbody><tr height="55" style="height:41.4pt">
  <td height="55" class="xl65" width="338" style="height:41.4pt;width:254pt">Specimens</td>
  <td class="xl66" width="66" style="width:50pt">Concrete Strength (MPa)</td>
  <td class="xl66" width="92" style="width:69pt">Transversel_y (MPa)</td>
  <td class="xl66" width="110" style="width:83pt">Longitudinal_C_y (MPa)</td>
  <td class="xl66" width="104" style="width:78pt">Longitudinal_I_y (MPa)</td>
  <td class="xl66" width="48" style="width:36pt">Width (mm)</td>
  <td class="xl66" width="49" style="width:37pt">Depth (mm)</td>
  <td class="xl66" width="110" style="width:83pt">Length_Inflection (mm)</td>
  <td class="xl66" width="116" style="width:87pt">Length_Measured (mm)</td>
  <td class="xl66" width="41" style="width:31pt">Axial Load (kN)</td>
  <td class="xl66" width="92" style="width:69pt">Longitudinal reinforcement Ratio</td>
  <td class="xl66" width="99" style="width:74pt">Transverse reinforcement Ratio</td>
  <td class="xl66" width="69" style="width:52pt">Span-to-depth Ratio</td>
  <td class="xl66" width="47" style="width:35pt">Axial Load Ratio</td>
  <td class="xl65" width="103" style="width:77pt">Failure Type</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl65" style="height:13.8pt">Gill et al. 1979, No. 1</td>
  <td class="xl65">23.1</td>
  <td class="xl65">297</td>
  <td class="xl65">375</td>
  <td class="xl65">375</td>
  <td class="xl65">550</td>
  <td class="xl65">550</td>
  <td class="xl65">1200</td>
  <td class="xl65">1200</td>
  <td class="xl65">1815</td>
  <td class="xl65">0.0179</td>
  <td class="xl65">0.015</td>
  <td class="xl65">2.18</td>
  <td class="xl65">0.26</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Gill et al. 1979, No. 2</td>
  <td class="xl67">41.4</td>
  <td class="xl67">316</td>
  <td class="xl67">375</td>
  <td class="xl67">375</td>
  <td class="xl67">550</td>
  <td class="xl67">550</td>
  <td class="xl67">1200</td>
  <td class="xl67">1200</td>
  <td class="xl67">2680</td>
  <td class="xl67">0.0179</td>
  <td class="xl67">0.023</td>
  <td class="xl67">2.18</td>
  <td class="xl67">0.214</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Gill et al. 1979, No. 3</td>
  <td class="xl67">21.4</td>
  <td class="xl67">297</td>
  <td class="xl67">375</td>
  <td class="xl67">375</td>
  <td class="xl67">550</td>
  <td class="xl67">550</td>
  <td class="xl67">1200</td>
  <td class="xl67">1200</td>
  <td class="xl67">2719</td>
  <td class="xl67">0.0179</td>
  <td class="xl67">0.02</td>
  <td class="xl67">2.18</td>
  <td class="xl67">0.42</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Gill et al. 1979, No. 4</td>
  <td class="xl67">23.5</td>
  <td class="xl67">294</td>
  <td class="xl67">375</td>
  <td class="xl67">375</td>
  <td class="xl67">550</td>
  <td class="xl67">550</td>
  <td class="xl67">1200</td>
  <td class="xl67">1200</td>
  <td class="xl67">4265</td>
  <td class="xl67">0.0179</td>
  <td class="xl67">0.035</td>
  <td class="xl67">2.18</td>
  <td class="xl67">0.6</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Ang et al. 1981, No. 3</td>
  <td class="xl67">23.6</td>
  <td class="xl65">320</td>
  <td class="xl67">427</td>
  <td class="xl67">427</td>
  <td class="xl67">400</td>
  <td class="xl67">600</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">1435</td>
  <td class="xl67">0.0151</td>
  <td class="xl67">0.028</td>
  <td class="xl67">4</td>
  <td class="xl67">0.38</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Ang et al. 1981, No. 4</td>
  <td class="xl67">25</td>
  <td class="xl67">280</td>
  <td class="xl67">427</td>
  <td class="xl67">427</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">840</td>
  <td class="xl67">0.0151</td>
  <td class="xl67">0.022</td>
  <td class="xl67">4</td>
  <td class="xl67">0.21</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Soesianawati et al. 1986, No.
  1</td>
  <td class="xl67">46.5</td>
  <td class="xl67">364</td>
  <td class="xl67">446</td>
  <td class="xl67">446</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">744</td>
  <td class="xl67">0.0151</td>
  <td class="xl67">0.009</td>
  <td class="xl67">4</td>
  <td class="xl67">0.1</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Soesianawati et al. 1986, No.
  2</td>
  <td class="xl67">44</td>
  <td class="xl67">360</td>
  <td class="xl67">446</td>
  <td class="xl67">446</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">2112</td>
  <td class="xl67">0.0151</td>
  <td class="xl67">0.012</td>
  <td class="xl67">4</td>
  <td class="xl67">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Soesianawati et al. 1986, No.
  3</td>
  <td class="xl67">44</td>
  <td class="xl67">364</td>
  <td class="xl67">446</td>
  <td class="xl67">446</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">2112</td>
  <td class="xl67">0.0151</td>
  <td class="xl67">0.008</td>
  <td class="xl67">4</td>
  <td class="xl67">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Soesianawati et al. 1986, No.
  4</td>
  <td class="xl67">40</td>
  <td class="xl67">255</td>
  <td class="xl67">446</td>
  <td class="xl67">446</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">1920</td>
  <td class="xl67">0.0151</td>
  <td class="xl67">0.006</td>
  <td class="xl67">4</td>
  <td class="xl67">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Zahn et al. 1986, No. 7</td>
  <td class="xl67">28.3</td>
  <td class="xl67">466</td>
  <td class="xl67">440</td>
  <td class="xl67">440</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">1010</td>
  <td class="xl67">0.0151</td>
  <td class="xl67">0.016</td>
  <td class="xl67">4</td>
  <td class="xl67">0.223</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Zahn et al. 1986, No. 8</td>
  <td class="xl67">40.1</td>
  <td class="xl67">466</td>
  <td class="xl67">440</td>
  <td class="xl67">440</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">2502</td>
  <td class="xl67">0.0151</td>
  <td class="xl67">0.02</td>
  <td class="xl67">4</td>
  <td class="xl67">0.39</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Watson and Park 1989, No. 5</td>
  <td class="xl67">41</td>
  <td class="xl67">372</td>
  <td class="xl67">474</td>
  <td class="xl67">474</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">3280</td>
  <td class="xl67">0.0151</td>
  <td class="xl67">0.007</td>
  <td class="xl67">4</td>
  <td class="xl67">0.5</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Watson and Park 1989, No. 6</td>
  <td class="xl67">40</td>
  <td class="xl67">388</td>
  <td class="xl67">474</td>
  <td class="xl67">474</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">3200</td>
  <td class="xl67">0.0151</td>
  <td class="xl67">0.003</td>
  <td class="xl67">4</td>
  <td class="xl67">0.5</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Watson and Park 1989, No. 7</td>
  <td class="xl67">42</td>
  <td class="xl67">308</td>
  <td class="xl67">474</td>
  <td class="xl67">474</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">4704</td>
  <td class="xl67">0.0151</td>
  <td class="xl67">0.013</td>
  <td class="xl67">4</td>
  <td class="xl67">0.7</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Watson and Park 1989, No. 9</td>
  <td class="xl67">40</td>
  <td class="xl67">308</td>
  <td class="xl67">474</td>
  <td class="xl67">474</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">4480</td>
  <td class="xl67">0.0151</td>
  <td class="xl67">0.023</td>
  <td class="xl67">4</td>
  <td class="xl67">0.7</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Tanaka and Park 1990, No. 1</td>
  <td class="xl67">25.6</td>
  <td class="xl67">333</td>
  <td class="xl67">474</td>
  <td class="xl67">474</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">819</td>
  <td class="xl67">0.0157</td>
  <td class="xl67">0.025</td>
  <td class="xl67">4</td>
  <td class="xl67">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Tanaka and Park 1990, No. 2</td>
  <td class="xl67">25.6</td>
  <td class="xl67">333</td>
  <td class="xl67">474</td>
  <td class="xl67">474</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">819</td>
  <td class="xl67">0.0157</td>
  <td class="xl67">0.025</td>
  <td class="xl67">4</td>
  <td class="xl67">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Tanaka and Park 1990, No. 3</td>
  <td class="xl67">25.6</td>
  <td class="xl67">333</td>
  <td class="xl67">474</td>
  <td class="xl67">474</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">819</td>
  <td class="xl67">0.0157</td>
  <td class="xl67">0.025</td>
  <td class="xl67">4</td>
  <td class="xl67">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Tanaka and Park 1990, No. 4</td>
  <td class="xl67">25.6</td>
  <td class="xl67">333</td>
  <td class="xl67">474</td>
  <td class="xl67">474</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">819</td>
  <td class="xl67">0.0157</td>
  <td class="xl67">0.025</td>
  <td class="xl67">4</td>
  <td class="xl67">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Tanaka and Park 1990, No. 5</td>
  <td class="xl67">32</td>
  <td class="xl67">325</td>
  <td class="xl67">511</td>
  <td class="xl67">511</td>
  <td class="xl67">550</td>
  <td class="xl67">550</td>
  <td class="xl67">1650</td>
  <td class="xl67">1650</td>
  <td class="xl67">968</td>
  <td class="xl67">0.0125</td>
  <td class="xl67">0.017</td>
  <td class="xl67">3</td>
  <td class="xl67">0.1</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Tanaka and Park 1990, No. 6</td>
  <td class="xl67">32</td>
  <td class="xl67">325</td>
  <td class="xl67">511</td>
  <td class="xl67">511</td>
  <td class="xl67">550</td>
  <td class="xl67">550</td>
  <td class="xl67">1650</td>
  <td class="xl67">1650</td>
  <td class="xl67">968</td>
  <td class="xl67">0.0125</td>
  <td class="xl67">0.017</td>
  <td class="xl67">3</td>
  <td class="xl67">0.1</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Tanaka and Park 1990, No. 7</td>
  <td class="xl67">32.1</td>
  <td class="xl67">325</td>
  <td class="xl67">511</td>
  <td class="xl67">511</td>
  <td class="xl67">550</td>
  <td class="xl67">550</td>
  <td class="xl67">1650</td>
  <td class="xl67">1650</td>
  <td class="xl67">2913</td>
  <td class="xl67">0.0125</td>
  <td class="xl67">0.021</td>
  <td class="xl67">3</td>
  <td class="xl67">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Tanaka and Park 1990, No. 8</td>
  <td class="xl67">32.1</td>
  <td class="xl67">325</td>
  <td class="xl67">511</td>
  <td class="xl67">511</td>
  <td class="xl67">550</td>
  <td class="xl67">500</td>
  <td class="xl67">1650</td>
  <td class="xl67">1650</td>
  <td class="xl67">2913</td>
  <td class="xl67">0.0125</td>
  <td class="xl67">0.021</td>
  <td class="xl67">3</td>
  <td class="xl67">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Park and Paulay 1990, No. 9</td>
  <td class="xl67">26.9</td>
  <td class="xl67">305</td>
  <td class="xl67">432</td>
  <td class="xl67">432</td>
  <td class="xl67">400</td>
  <td class="xl67">600</td>
  <td class="xl67">1784</td>
  <td class="xl67">1784</td>
  <td class="xl67">646</td>
  <td class="xl67">0.0188</td>
  <td class="xl67">0.022</td>
  <td class="xl67">2.97</td>
  <td class="xl67">0.1</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Arakawa et al. 1982, No. 102</td>
  <td class="xl67">20.6</td>
  <td class="xl67">323</td>
  <td class="xl67">392.8</td>
  <td class="xl67">392.8</td>
  <td class="xl67">250</td>
  <td class="xl67">250</td>
  <td class="xl67">375</td>
  <td class="xl67">375</td>
  <td class="xl67">429</td>
  <td class="xl67">0.0068</td>
  <td class="xl67">0.012</td>
  <td class="xl67">1.5</td>
  <td class="xl67">0.333</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Nagasaka 1982, HPRC10-63</td>
  <td class="xl67">21.6</td>
  <td class="xl67">344</td>
  <td class="xl67">371</td>
  <td class="xl67">371</td>
  <td class="xl67">200</td>
  <td class="xl67">200</td>
  <td class="xl67">300</td>
  <td class="xl67">300</td>
  <td class="xl67">147</td>
  <td class="xl67">0.0127</td>
  <td class="xl67">0.008</td>
  <td class="xl67">1.5</td>
  <td class="xl67">0.17</td>
  <td class="xl65">Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Nagasaka 1982, HPRC19-32</td>
  <td class="xl67">21</td>
  <td class="xl67">344</td>
  <td class="xl67">371</td>
  <td class="xl67">371</td>
  <td class="xl67">200</td>
  <td class="xl67">200</td>
  <td class="xl67">300</td>
  <td class="xl67">300</td>
  <td class="xl67">294</td>
  <td class="xl67">0.0127</td>
  <td class="xl67">0.014</td>
  <td class="xl67">1.5</td>
  <td class="xl67">0.35</td>
  <td class="xl67">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Ohno and Nishioka 1984, L1</td>
  <td class="xl67">24.8</td>
  <td class="xl67">325</td>
  <td class="xl67">362</td>
  <td class="xl67">362</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">127</td>
  <td class="xl67">0.0142</td>
  <td class="xl67">0.003</td>
  <td class="xl67">4</td>
  <td class="xl67">0.032</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Ohno and Nishioka 1984, L2</td>
  <td class="xl67">24.8</td>
  <td class="xl67">325</td>
  <td class="xl67">362</td>
  <td class="xl67">362</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">127</td>
  <td class="xl67">0.0142</td>
  <td class="xl67">0.003</td>
  <td class="xl67">4</td>
  <td class="xl67">0.032</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Ohno and Nishioka 1984, L3</td>
  <td class="xl67">24.8</td>
  <td class="xl67">325</td>
  <td class="xl67">362</td>
  <td class="xl67">362</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">1600</td>
  <td class="xl67">1600</td>
  <td class="xl67">127</td>
  <td class="xl67">0.0142</td>
  <td class="xl67">0.003</td>
  <td class="xl67">4</td>
  <td class="xl67">0.032</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Ohue et al. 1985, 2D16RS</td>
  <td class="xl67">32</td>
  <td class="xl67">316</td>
  <td class="xl67">369</td>
  <td class="xl67">369</td>
  <td class="xl67">200</td>
  <td class="xl67">200</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">183</td>
  <td class="xl67">0.0201</td>
  <td class="xl67">0.006</td>
  <td class="xl67">2</td>
  <td class="xl67">0.143</td>
  <td class="xl67">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Ohue et al. 1985, 4D13RS</td>
  <td class="xl67">29.9</td>
  <td class="xl67">316</td>
  <td class="xl67">370</td>
  <td class="xl67">370</td>
  <td class="xl67">200</td>
  <td class="xl67">200</td>
  <td class="xl67">400</td>
  <td class="xl67">400</td>
  <td class="xl67">183</td>
  <td class="xl67">0.0265</td>
  <td class="xl67">0.006</td>
  <td class="xl67">2</td>
  <td class="xl67">0.153</td>
  <td class="xl67">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Zhou et al. 1985, No. 806</td>
  <td class="xl67">32.3</td>
  <td class="xl67">341</td>
  <td class="xl67">336</td>
  <td class="xl67">336</td>
  <td class="xl67">80</td>
  <td class="xl67">80</td>
  <td class="xl67">80</td>
  <td class="xl67">80</td>
  <td class="xl67">124</td>
  <td class="xl67">0.0177</td>
  <td class="xl67">0.005</td>
  <td class="xl67">1</td>
  <td class="xl67">0.6</td>
  <td class="xl67">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Zhou et al. 1985, No. 1007</td>
  <td class="xl67">34</td>
  <td class="xl67">341</td>
  <td class="xl67">336</td>
  <td class="xl67">336</td>
  <td class="xl67">80</td>
  <td class="xl67">80</td>
  <td class="xl67">80</td>
  <td class="xl67">80</td>
  <td class="xl67">152</td>
  <td class="xl67">0.0177</td>
  <td class="xl67">0.005</td>
  <td class="xl67">1</td>
  <td class="xl67">0.699</td>
  <td class="xl67">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Zhou et al. 1985, No. 1309</td>
  <td class="xl67">32.8</td>
  <td class="xl67">341</td>
  <td class="xl67">336</td>
  <td class="xl67">336</td>
  <td class="xl67">80</td>
  <td class="xl67">80</td>
  <td class="xl67">80</td>
  <td class="xl67">80</td>
  <td class="xl67">189</td>
  <td class="xl67">0.0177</td>
  <td class="xl67">0.005</td>
  <td class="xl67">1</td>
  <td class="xl67">0.9</td>
  <td class="xl67">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Imai and Yamamoto 1986, No. 1</td>
  <td class="xl67">27.1</td>
  <td class="xl67">336</td>
  <td class="xl67">318</td>
  <td class="xl67">318</td>
  <td class="xl67">400</td>
  <td class="xl67">500</td>
  <td class="xl67">825</td>
  <td class="xl67">825</td>
  <td class="xl67">392</td>
  <td class="xl67">0.0266</td>
  <td class="xl67">0.004</td>
  <td class="xl67">1.65</td>
  <td class="xl67">0.072</td>
  <td class="xl67">Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Zhou et al. 1987, No. 104-08</td>
  <td class="xl67">19.8</td>
  <td class="xl67">559</td>
  <td class="xl67">341</td>
  <td class="xl67">341</td>
  <td class="xl67">160</td>
  <td class="xl67">160</td>
  <td class="xl67">160</td>
  <td class="xl67">160</td>
  <td class="xl67">406</td>
  <td class="xl67">0.0222</td>
  <td class="xl67">0.007</td>
  <td class="xl67">1</td>
  <td class="xl67">0.801</td>
  <td class="xl67">Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Zhou et al. 1987, No. 114-08</td>
  <td class="xl65">19.8</td>
  <td class="xl65">559</td>
  <td class="xl65">341</td>
  <td class="xl65">341</td>
  <td class="xl65">160</td>
  <td class="xl65">160</td>
  <td class="xl65">160</td>
  <td class="xl65">160</td>
  <td class="xl65">406</td>
  <td class="xl65">0.0222</td>
  <td class="xl65">0.007</td>
  <td class="xl65">1</td>
  <td class="xl65">0.801</td>
  <td class="xl65">Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Zhou et al. 1987, No. 124-08</td>
  <td class="xl65">19.8</td>
  <td class="xl65">559</td>
  <td class="xl65">341</td>
  <td class="xl65">341</td>
  <td class="xl65">160</td>
  <td class="xl65">160</td>
  <td class="xl65">160</td>
  <td class="xl65">160</td>
  <td class="xl65">406</td>
  <td class="xl65">0.0222</td>
  <td class="xl65">0.018</td>
  <td class="xl65">1</td>
  <td class="xl65">0.801</td>
  <td class="xl65">Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Zhou et al. 1987, No. 204-08</td>
  <td class="xl65">21.1</td>
  <td class="xl65">559</td>
  <td class="xl65">341</td>
  <td class="xl65">341</td>
  <td class="xl65">160</td>
  <td class="xl65">160</td>
  <td class="xl65">320</td>
  <td class="xl65">320</td>
  <td class="xl65">432</td>
  <td class="xl65">0.0222</td>
  <td class="xl65">0.007</td>
  <td class="xl65">2</td>
  <td class="xl65">0.8</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Zhou et al. 1987, No. 214-08</td>
  <td class="xl65">21.1</td>
  <td class="xl65">559</td>
  <td class="xl65">341</td>
  <td class="xl65">341</td>
  <td class="xl65">160</td>
  <td class="xl65">160</td>
  <td class="xl65">320</td>
  <td class="xl65">320</td>
  <td class="xl65">432</td>
  <td class="xl65">0.0222</td>
  <td class="xl65">0.007</td>
  <td class="xl65">2</td>
  <td class="xl65">0.8</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Zhou et al. 1987, No. 223-09</td>
  <td class="xl65">21.1</td>
  <td class="xl65">559</td>
  <td class="xl65">341</td>
  <td class="xl65">341</td>
  <td class="xl65">160</td>
  <td class="xl65">160</td>
  <td class="xl65">320</td>
  <td class="xl65">320</td>
  <td class="xl65">486</td>
  <td class="xl65">0.0222</td>
  <td class="xl65">0.018</td>
  <td class="xl65">2</td>
  <td class="xl65">0.9</td>
  <td class="xl65"><span style="mso-spacerun:yes">&nbsp;</span>Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Zhou et al. 1987, No. 302-07</td>
  <td class="xl65">28.8</td>
  <td class="xl65">559</td>
  <td class="xl65">341</td>
  <td class="xl65">341</td>
  <td class="xl65">160</td>
  <td class="xl65">160</td>
  <td class="xl65">480</td>
  <td class="xl65">480</td>
  <td class="xl65">517</td>
  <td class="xl65">0.0222</td>
  <td class="xl65">0.007</td>
  <td class="xl65">2</td>
  <td class="xl65">0.701</td>
  <td class="xl65"><span style="mso-spacerun:yes">&nbsp;</span>Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Zhou et al. 1987, No. 312-07</td>
  <td class="xl65">28.8</td>
  <td class="xl65">559</td>
  <td class="xl65">341</td>
  <td class="xl65">341</td>
  <td class="xl65">160</td>
  <td class="xl65">160</td>
  <td class="xl65">480</td>
  <td class="xl65">480</td>
  <td class="xl65">517</td>
  <td class="xl65">0.0222</td>
  <td class="xl65">0.007</td>
  <td class="xl65">3</td>
  <td class="xl65">0.701</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Zhou et al. 1987, No. 322-07</td>
  <td class="xl65">28.8</td>
  <td class="xl65">559</td>
  <td class="xl65">341</td>
  <td class="xl65">341</td>
  <td class="xl65">160</td>
  <td class="xl65">160</td>
  <td class="xl65">480</td>
  <td class="xl65">480</td>
  <td class="xl65">517</td>
  <td class="xl65">0.0222</td>
  <td class="xl65">0.018</td>
  <td class="xl65">3</td>
  <td class="xl65">0.701</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Kanda et al. 1988, 85STC-1</td>
  <td class="xl65">27.9</td>
  <td class="xl65">506</td>
  <td class="xl65">374</td>
  <td class="xl65">374</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">750</td>
  <td class="xl65">750</td>
  <td class="xl65">184</td>
  <td class="xl65">0.0162</td>
  <td class="xl65">0.004</td>
  <td class="xl65">3</td>
  <td class="xl65">0.106</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Kanda et al. 1988, 85STC-2</td>
  <td class="xl65">27.9</td>
  <td class="xl65">506</td>
  <td class="xl65">374</td>
  <td class="xl65">374</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">750</td>
  <td class="xl65">750</td>
  <td class="xl65">184</td>
  <td class="xl65">0.0162</td>
  <td class="xl65">0.004</td>
  <td class="xl65">3</td>
  <td class="xl65">0.106</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Kanda et al. 1988, 85STC-3</td>
  <td class="xl65">27.9</td>
  <td class="xl65">506</td>
  <td class="xl65">374</td>
  <td class="xl65">374</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">750</td>
  <td class="xl65">750</td>
  <td class="xl65">184</td>
  <td class="xl65">0.0162</td>
  <td class="xl65">0.004</td>
  <td class="xl65">3</td>
  <td class="xl65">0.106</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Kanda et al. 1988, 85PDC-1</td>
  <td class="xl65">24.8</td>
  <td class="xl65">352</td>
  <td class="xl65">374</td>
  <td class="xl65">374</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">750</td>
  <td class="xl65">750</td>
  <td class="xl65">184</td>
  <td class="xl65">0.0162</td>
  <td class="xl65">0.004</td>
  <td class="xl65">3</td>
  <td class="xl65">0.119</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Kanda et al. 1988, 85PDC-2</td>
  <td class="xl65">27.9</td>
  <td class="xl65">506</td>
  <td class="xl65">374</td>
  <td class="xl65">374</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">750</td>
  <td class="xl65">750</td>
  <td class="xl65">184</td>
  <td class="xl65">0.0162</td>
  <td class="xl65">0.004</td>
  <td class="xl65">3</td>
  <td class="xl65">0.106</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Kanda et al. 1988, 85PDC-3</td>
  <td class="xl65">27.9</td>
  <td class="xl65">506</td>
  <td class="xl65">374</td>
  <td class="xl65">374</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">750</td>
  <td class="xl65">750</td>
  <td class="xl65">184</td>
  <td class="xl65">0.0162</td>
  <td class="xl65">0.004</td>
  <td class="xl65">3</td>
  <td class="xl65">0.106</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Arakawa et al. 1989, OA2</td>
  <td class="xl65">31.8</td>
  <td class="xl65">249</td>
  <td class="xl65">340</td>
  <td class="xl65">340</td>
  <td class="xl65">180</td>
  <td class="xl65">180</td>
  <td class="xl65">225</td>
  <td class="xl65">225</td>
  <td class="xl65">190</td>
  <td class="xl65">0.0313</td>
  <td class="xl65">0.002</td>
  <td class="xl65">1.23</td>
  <td class="xl65">0.184</td>
  <td class="xl65">Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Arakawa et al. 1989, OA5</td>
  <td class="xl65">33</td>
  <td class="xl65">249</td>
  <td class="xl65">340</td>
  <td class="xl65">340</td>
  <td class="xl65">180</td>
  <td class="xl65">180</td>
  <td class="xl65">225</td>
  <td class="xl65">225</td>
  <td class="xl65">476</td>
  <td class="xl65">0.0313</td>
  <td class="xl65">0.002</td>
  <td class="xl65">1.25</td>
  <td class="xl65">0.445</td>
  <td class="xl65">Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Muguruma et al. 1989, AL-1</td>
  <td class="xl65">85.7</td>
  <td class="xl65">328.4</td>
  <td class="xl65">399.6</td>
  <td class="xl65">399.6</td>
  <td class="xl65">200</td>
  <td class="xl65">200</td>
  <td class="xl65">500</td>
  <td class="xl65">500</td>
  <td class="xl65">1371</td>
  <td class="xl65">0.038</td>
  <td class="xl65">0.016</td>
  <td class="xl65">2.5</td>
  <td class="xl65">0.4</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Muguruma et al. 1989, AH-1</td>
  <td class="xl65">85.7</td>
  <td class="xl65">792.3</td>
  <td class="xl65">399.6</td>
  <td class="xl65">399.6</td>
  <td class="xl65">200</td>
  <td class="xl65">200</td>
  <td class="xl65">500</td>
  <td class="xl65">500</td>
  <td class="xl65">1371</td>
  <td class="xl65">0.038</td>
  <td class="xl65">0.016</td>
  <td class="xl65">2.5</td>
  <td class="xl65">0.4</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Muguruma et al. 1989, AL-2</td>
  <td class="xl65">85.7</td>
  <td class="xl65">328.4</td>
  <td class="xl65">399.6</td>
  <td class="xl65">399.6</td>
  <td class="xl65">200</td>
  <td class="xl65">200</td>
  <td class="xl65">500</td>
  <td class="xl65">500</td>
  <td class="xl65">2156</td>
  <td class="xl65">0.038</td>
  <td class="xl65">0.016</td>
  <td class="xl65">2.5</td>
  <td class="xl65">0.629</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Mugumura et al. 1989, AH-2</td>
  <td class="xl65">85.7</td>
  <td class="xl65">792.3</td>
  <td class="xl65">399.6</td>
  <td class="xl65">399.6</td>
  <td class="xl65">200</td>
  <td class="xl65">200</td>
  <td class="xl65">500</td>
  <td class="xl65">500</td>
  <td class="xl65">2156</td>
  <td class="xl65">0.038</td>
  <td class="xl65">0.016</td>
  <td class="xl65">2.5</td>
  <td class="xl65">0.629</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Muguruma et al. 1989, BL-1</td>
  <td class="xl65">115.8</td>
  <td class="xl65">328.4</td>
  <td class="xl65">399.6</td>
  <td class="xl65">399.6</td>
  <td class="xl65">200</td>
  <td class="xl65">200</td>
  <td class="xl65">500</td>
  <td class="xl65">500</td>
  <td class="xl65">1176</td>
  <td class="xl65">0.038</td>
  <td class="xl65">0.016</td>
  <td class="xl65">2.5</td>
  <td class="xl65">0.254</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Muguruma et al. 1989, BH-1</td>
  <td class="xl65">115.8</td>
  <td class="xl65">792.3</td>
  <td class="xl65">399.6</td>
  <td class="xl65">399.6</td>
  <td class="xl65">200</td>
  <td class="xl65">200</td>
  <td class="xl65">500</td>
  <td class="xl65">500</td>
  <td class="xl65">1176</td>
  <td class="xl65">0.038</td>
  <td class="xl65">0.016</td>
  <td class="xl65">2.5</td>
  <td class="xl65">0.254</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Muguruma et al. 1989, BL-2</td>
  <td class="xl65">115.8</td>
  <td class="xl65">328.4</td>
  <td class="xl65">399.6</td>
  <td class="xl65">399.6</td>
  <td class="xl65">200</td>
  <td class="xl65">200</td>
  <td class="xl65">500</td>
  <td class="xl65">500</td>
  <td class="xl65">1959</td>
  <td class="xl65">0.038</td>
  <td class="xl65">0.016</td>
  <td class="xl65">2.5</td>
  <td class="xl65">0.423</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Muguruma et al. 1989, BH-2</td>
  <td class="xl65">115.8</td>
  <td class="xl65">792.3</td>
  <td class="xl65">399.6</td>
  <td class="xl65">399.6</td>
  <td class="xl65">200</td>
  <td class="xl65">200</td>
  <td class="xl65">500</td>
  <td class="xl65">500</td>
  <td class="xl65">1959</td>
  <td class="xl65">0.038</td>
  <td class="xl65">0.016</td>
  <td class="xl65">2.5</td>
  <td class="xl65">0.423</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Ono et al. 1989, CA025C</td>
  <td class="xl65">25.8</td>
  <td class="xl65">426</td>
  <td class="xl65">361</td>
  <td class="xl65">361</td>
  <td class="xl65">200</td>
  <td class="xl65">200</td>
  <td class="xl65">300</td>
  <td class="xl65">300</td>
  <td class="xl65">265</td>
  <td class="xl65">0.0213</td>
  <td class="xl65">0.009</td>
  <td class="xl65">1.5</td>
  <td class="xl65">0.257</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Ono et al. 1989, CA060C</td>
  <td class="xl65">25.8</td>
  <td class="xl65">426</td>
  <td class="xl65">361</td>
  <td class="xl65">361</td>
  <td class="xl65">200</td>
  <td class="xl65">200</td>
  <td class="xl65">300</td>
  <td class="xl65">300</td>
  <td class="xl65">636</td>
  <td class="xl65">0.0213</td>
  <td class="xl65">0.009</td>
  <td class="xl65">1.5</td>
  <td class="xl65">0.616</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Sakai et al. 1990, B1</td>
  <td class="xl65">99.5</td>
  <td class="xl65">774</td>
  <td class="xl65">379</td>
  <td class="xl65">379</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">500</td>
  <td class="xl65">500</td>
  <td class="xl65">2176</td>
  <td class="xl65">0.0243</td>
  <td class="xl65">0.005</td>
  <td class="xl65">2</td>
  <td class="xl65">0.35</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Sakai et al. 1990, B2</td>
  <td class="xl65">99.5</td>
  <td class="xl65">774</td>
  <td class="xl65">379</td>
  <td class="xl65">379</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">500</td>
  <td class="xl65">500</td>
  <td class="xl65">2176</td>
  <td class="xl65">0.0243</td>
  <td class="xl65">0.007</td>
  <td class="xl65">2</td>
  <td class="xl65">0.35</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Sakai et al. 1990, B3</td>
  <td class="xl65">99.5</td>
  <td class="xl65">344</td>
  <td class="xl65">379</td>
  <td class="xl65">379</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">500</td>
  <td class="xl65">500</td>
  <td class="xl65">2176</td>
  <td class="xl65">0.0243</td>
  <td class="xl65">0.006</td>
  <td class="xl65">2</td>
  <td class="xl65">0.35</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Sakai et al. 1990, B4</td>
  <td class="xl65">99.5</td>
  <td class="xl65">1126</td>
  <td class="xl65">379</td>
  <td class="xl65">379</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">500</td>
  <td class="xl65">500</td>
  <td class="xl65">2176</td>
  <td class="xl65">0.0243</td>
  <td class="xl65">0.005</td>
  <td class="xl65">2</td>
  <td class="xl65">0.35</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Sakai et al. 1990, B5</td>
  <td class="xl65">99.5</td>
  <td class="xl65">774</td>
  <td class="xl65">379</td>
  <td class="xl65">379</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">500</td>
  <td class="xl65">500</td>
  <td class="xl65">2176</td>
  <td class="xl65">0.0243</td>
  <td class="xl65">0.005</td>
  <td class="xl65">2</td>
  <td class="xl65">0.35</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Sakai et al. 1990, B6</td>
  <td class="xl65">99.5</td>
  <td class="xl65">857</td>
  <td class="xl65">379</td>
  <td class="xl65">379</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">500</td>
  <td class="xl65">500</td>
  <td class="xl65">2176</td>
  <td class="xl65">0.0243</td>
  <td class="xl65">0.005</td>
  <td class="xl65">2</td>
  <td class="xl65">0.35</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Sakai et al. 1990, B7</td>
  <td class="xl65">99.5</td>
  <td class="xl65">774</td>
  <td class="xl65">339</td>
  <td class="xl65">339</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">500</td>
  <td class="xl65">500</td>
  <td class="xl65">2176</td>
  <td class="xl65">0.0181</td>
  <td class="xl65">0.005</td>
  <td class="xl65">2</td>
  <td class="xl65">0.35</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Amitsu et al. 1991, CB060C</td>
  <td class="xl65">46.3</td>
  <td class="xl65">414</td>
  <td class="xl65">441</td>
  <td class="xl65">441</td>
  <td class="xl65">278</td>
  <td class="xl65">278</td>
  <td class="xl65">323</td>
  <td class="xl65">323</td>
  <td class="xl65">2632</td>
  <td class="xl65">0.0412</td>
  <td class="xl65">0.009</td>
  <td class="xl65">1.16</td>
  <td class="xl65">0.736</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wight and Sozen 1973, No.
  40.033a(East)</td>
  <td class="xl65">34.7</td>
  <td class="xl65">345</td>
  <td class="xl65">496</td>
  <td class="xl65">496</td>
  <td class="xl65">152</td>
  <td class="xl65">305</td>
  <td class="xl65">876</td>
  <td class="xl65">876</td>
  <td class="xl65">189</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0.003</td>
  <td class="xl65">2.87</td>
  <td class="xl65">0.117</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wight and Sozen 1973, No.
  40.033a(West)</td>
  <td class="xl65">34.7</td>
  <td class="xl65">345</td>
  <td class="xl65">496</td>
  <td class="xl65">496</td>
  <td class="xl65">152</td>
  <td class="xl65">305</td>
  <td class="xl65">876</td>
  <td class="xl65">876</td>
  <td class="xl65">189</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0.003</td>
  <td class="xl65">2.87</td>
  <td class="xl65">0.117</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wight and Sozen 1973, No.
  40.048(East)</td>
  <td class="xl65">26.1</td>
  <td class="xl65">345</td>
  <td class="xl65">496</td>
  <td class="xl65">496</td>
  <td class="xl65">152</td>
  <td class="xl65">305</td>
  <td class="xl65">876</td>
  <td class="xl65">876</td>
  <td class="xl65">178</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0.005</td>
  <td class="xl65">2.87</td>
  <td class="xl65">0.147</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wight and Sozen 1973, No.
  40.048(West)</td>
  <td class="xl65">26.1</td>
  <td class="xl65">345</td>
  <td class="xl65">496</td>
  <td class="xl65">496</td>
  <td class="xl65">152</td>
  <td class="xl65">305</td>
  <td class="xl65">876</td>
  <td class="xl65">876</td>
  <td class="xl65">178</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0.005</td>
  <td class="xl65">2.87</td>
  <td class="xl65">0.147</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wight and Sozen 1973, No.
  40.033(East)</td>
  <td class="xl65">33.6</td>
  <td class="xl65">345</td>
  <td class="xl65">496</td>
  <td class="xl65">496</td>
  <td class="xl65">152</td>
  <td class="xl65">305</td>
  <td class="xl65">876</td>
  <td class="xl65">876</td>
  <td class="xl65">178</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0.003</td>
  <td class="xl65">2.87</td>
  <td class="xl65">0.147</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wight and Sozen 1973, No.
  40.033(West)</td>
  <td class="xl65">33.6</td>
  <td class="xl65">345</td>
  <td class="xl65">496</td>
  <td class="xl65">496</td>
  <td class="xl65">178</td>
  <td class="xl65">305</td>
  <td class="xl65">876</td>
  <td class="xl65">876</td>
  <td class="xl65">178</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0.003</td>
  <td class="xl65">2.87</td>
  <td class="xl65">0.147</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wight and Sozen 1973, No.
  25.033(East)</td>
  <td class="xl65">33.6</td>
  <td class="xl65">345</td>
  <td class="xl65">496</td>
  <td class="xl65">496</td>
  <td class="xl65">152</td>
  <td class="xl65">305</td>
  <td class="xl65">876</td>
  <td class="xl65">876</td>
  <td class="xl65">111</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0.003</td>
  <td class="xl65">2.87</td>
  <td class="xl65">0.071</td>
  <td class="xl65">Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wight and Sozen 1973, No.
  25.033(West)</td>
  <td class="xl65">33.6</td>
  <td class="xl65">345</td>
  <td class="xl65">496</td>
  <td class="xl65">496</td>
  <td class="xl65">152</td>
  <td class="xl65">305</td>
  <td class="xl65">876</td>
  <td class="xl65">876</td>
  <td class="xl65">111</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0.003</td>
  <td class="xl65">2.87</td>
  <td class="xl65">0.071</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wight and Sozen 1973, No.
  40.067(East)</td>
  <td class="xl65">33.4</td>
  <td class="xl65">345</td>
  <td class="xl65">496</td>
  <td class="xl65">496</td>
  <td class="xl65">152</td>
  <td class="xl65">305</td>
  <td class="xl65">876</td>
  <td class="xl65">876</td>
  <td class="xl65">178</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0.007</td>
  <td class="xl65">2.87</td>
  <td class="xl65">0.115</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wight and Sozen 1973, No.
  40.067(West)</td>
  <td class="xl65">33.4</td>
  <td class="xl65">345</td>
  <td class="xl65">496</td>
  <td class="xl65">496</td>
  <td class="xl65">152</td>
  <td class="xl65">305</td>
  <td class="xl65">876</td>
  <td class="xl65">876</td>
  <td class="xl65">178</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0.007</td>
  <td class="xl65">2.87</td>
  <td class="xl65">0.115</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wight and Sozen 1973, No.
  40.147(East)</td>
  <td class="xl65">33.5</td>
  <td class="xl65">317</td>
  <td class="xl65">496</td>
  <td class="xl65">496</td>
  <td class="xl65">152</td>
  <td class="xl65">305</td>
  <td class="xl65">876</td>
  <td class="xl65">876</td>
  <td class="xl65">178</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0.015</td>
  <td class="xl65">2.87</td>
  <td class="xl65">0.115</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wight and Sozen 1973, No.
  40.147(West)</td>
  <td class="xl65">33.5</td>
  <td class="xl65">317</td>
  <td class="xl65">496</td>
  <td class="xl65">496</td>
  <td class="xl65">152</td>
  <td class="xl65">305</td>
  <td class="xl65">876</td>
  <td class="xl65">876</td>
  <td class="xl65">178</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0.015</td>
  <td class="xl65">2.87</td>
  <td class="xl65">0.115</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wight and Sozen 1973, No.
  40.092(East)</td>
  <td class="xl65">33.5</td>
  <td class="xl65">317</td>
  <td class="xl65">496</td>
  <td class="xl65">496</td>
  <td class="xl65">152</td>
  <td class="xl65">305</td>
  <td class="xl65">876</td>
  <td class="xl65">876</td>
  <td class="xl65">178</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0.009</td>
  <td class="xl65">2.87</td>
  <td class="xl65">0.115</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wight and Sozen 1973, No.
  40.092(West)</td>
  <td class="xl65">33.5</td>
  <td class="xl65">317</td>
  <td class="xl65">496</td>
  <td class="xl65">496</td>
  <td class="xl65">152</td>
  <td class="xl65">305</td>
  <td class="xl65">876</td>
  <td class="xl65">876</td>
  <td class="xl65">178</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0.009</td>
  <td class="xl65">2.87</td>
  <td class="xl65">0.115</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Atalay and Penzien 1975, No.
  1S1</td>
  <td class="xl65">29.1</td>
  <td class="xl65">275</td>
  <td class="xl65">535</td>
  <td class="xl65">367</td>
  <td class="xl65">367</td>
  <td class="xl65">578</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">267</td>
  <td class="xl65">0.0163</td>
  <td class="xl65">0.015</td>
  <td class="xl65">5.5</td>
  <td class="xl65">0.099</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Atalay and Penzien 1975, No.
  2S1</td>
  <td class="xl65">30.7</td>
  <td class="xl65">275</td>
  <td class="xl65">535</td>
  <td class="xl65">367</td>
  <td class="xl65">367</td>
  <td class="xl65">578</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">267</td>
  <td class="xl65">0.0163</td>
  <td class="xl65">0.009</td>
  <td class="xl65">5.5</td>
  <td class="xl65">0.093</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Atalay and Penzien 1975, No.
  3S1</td>
  <td class="xl65">29.2</td>
  <td class="xl65">275</td>
  <td class="xl65">535</td>
  <td class="xl65">367</td>
  <td class="xl65">367</td>
  <td class="xl65">578</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">267</td>
  <td class="xl65">0.0163</td>
  <td class="xl65">0.015</td>
  <td class="xl65">5.5</td>
  <td class="xl65">0.098</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Atalay and Penzien 1975, No.
  4S1</td>
  <td class="xl65">27.6</td>
  <td class="xl65">275</td>
  <td class="xl65">535</td>
  <td class="xl65">429</td>
  <td class="xl65">429</td>
  <td class="xl65">657</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">267</td>
  <td class="xl65">0.0163</td>
  <td class="xl65">0.009</td>
  <td class="xl65">5.5</td>
  <td class="xl65">0.104</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Atalay and Penzien 1975, No.
  5S1</td>
  <td class="xl65">29.4</td>
  <td class="xl65">275</td>
  <td class="xl65">530</td>
  <td class="xl65">429</td>
  <td class="xl65">429</td>
  <td class="xl65">657</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">534</td>
  <td class="xl65">0.0163</td>
  <td class="xl65">0.015</td>
  <td class="xl65">5.5</td>
  <td class="xl65">0.195</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Atalay and Penzien 1975, No.
  6S1</td>
  <td class="xl65">31.8</td>
  <td class="xl65">275</td>
  <td class="xl65">530</td>
  <td class="xl65">429</td>
  <td class="xl65">429</td>
  <td class="xl65">657</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">534</td>
  <td class="xl65">0.0163</td>
  <td class="xl65">0.009</td>
  <td class="xl65">5.5</td>
  <td class="xl65">0.181</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Atalay and Penzien 1975, No. 9</td>
  <td class="xl65">33.3</td>
  <td class="xl65">275</td>
  <td class="xl65">530</td>
  <td class="xl65">363</td>
  <td class="xl65">363</td>
  <td class="xl65">563</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">801</td>
  <td class="xl65">0.0163</td>
  <td class="xl65">0.015</td>
  <td class="xl65">5.5</td>
  <td class="xl65">0.259</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Atalay and Penzien 1975, No.
  10</td>
  <td class="xl65">32.4</td>
  <td class="xl65">275</td>
  <td class="xl65">530</td>
  <td class="xl65">363</td>
  <td class="xl65">363</td>
  <td class="xl65">563</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">801</td>
  <td class="xl65">0.0163</td>
  <td class="xl65">0.009</td>
  <td class="xl65">5.5</td>
  <td class="xl65">0.266</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Atalay and Penzien 1975, No.
  11</td>
  <td class="xl65">31</td>
  <td class="xl65">275</td>
  <td class="xl65">492</td>
  <td class="xl65">363</td>
  <td class="xl65">363</td>
  <td class="xl65">563</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">801</td>
  <td class="xl65">0.0163</td>
  <td class="xl65">0.015</td>
  <td class="xl65">5.5</td>
  <td class="xl65">0.278</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Atalay and Penzien 1975, No.
  12</td>
  <td class="xl65">31.8</td>
  <td class="xl65">275</td>
  <td class="xl65">492</td>
  <td class="xl65">363</td>
  <td class="xl65">363</td>
  <td class="xl65">563</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">801</td>
  <td class="xl65">0.0163</td>
  <td class="xl65">0.009</td>
  <td class="xl65">5.5</td>
  <td class="xl65">0.271</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Umehara and Jirsa 1982, CUS</td>
  <td class="xl65">34.9</td>
  <td class="xl65">414</td>
  <td class="xl65">441</td>
  <td class="xl65">441</td>
  <td class="xl65">230</td>
  <td class="xl65">410</td>
  <td class="xl65">455</td>
  <td class="xl65">455</td>
  <td class="xl65">534</td>
  <td class="xl65">0.0301</td>
  <td class="xl65">0.003</td>
  <td class="xl65">1.11</td>
  <td class="xl65">0.162</td>
  <td class="xl65">Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Umehara and Jirsa 1982, CUW</td>
  <td class="xl65">34.9</td>
  <td class="xl65">414</td>
  <td class="xl65">441</td>
  <td class="xl65">441</td>
  <td class="xl65">410</td>
  <td class="xl65">230</td>
  <td class="xl65">455</td>
  <td class="xl65">455</td>
  <td class="xl65">534</td>
  <td class="xl65">0.0301</td>
  <td class="xl65">0.003</td>
  <td class="xl65">1.98</td>
  <td class="xl65">0.162</td>
  <td class="xl65">Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Umehara and Jirsa 1982, 2CUS</td>
  <td class="xl65">42</td>
  <td class="xl65">414</td>
  <td class="xl65">441</td>
  <td class="xl65">441</td>
  <td class="xl65">230</td>
  <td class="xl65">410</td>
  <td class="xl65">455</td>
  <td class="xl65">455</td>
  <td class="xl65">1068</td>
  <td class="xl65">0.0301</td>
  <td class="xl65">0.003</td>
  <td class="xl65">1.11</td>
  <td class="xl65">0.27</td>
  <td class="xl65">Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Bett et al. 1985 , No. 1-1</td>
  <td class="xl65">29.9</td>
  <td class="xl65">414</td>
  <td class="xl65">462</td>
  <td class="xl65">462</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">457</td>
  <td class="xl65">457</td>
  <td class="xl65">288</td>
  <td class="xl65">0.0244</td>
  <td class="xl65">0.003</td>
  <td class="xl65">1.5</td>
  <td class="xl65">0.104</td>
  <td class="xl65">Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Azizinamini et al. 1988, NC-2</td>
  <td class="xl65">39.3</td>
  <td class="xl65">454</td>
  <td class="xl65">439</td>
  <td class="xl65">439</td>
  <td class="xl65">457</td>
  <td class="xl65">457</td>
  <td class="xl65">1372</td>
  <td class="xl65">1372</td>
  <td class="xl65">1690</td>
  <td class="xl65">0.0194</td>
  <td class="xl65">0.022</td>
  <td class="xl65">3</td>
  <td class="xl65">0.206</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Azizinamini et al. 1988, NC-4</td>
  <td class="xl65">39.8</td>
  <td class="xl65">616</td>
  <td class="xl65">439</td>
  <td class="xl65">439</td>
  <td class="xl65">457</td>
  <td class="xl65">457</td>
  <td class="xl65">1372</td>
  <td class="xl65">1372</td>
  <td class="xl65">2580</td>
  <td class="xl65">0.0194</td>
  <td class="xl65">0.013</td>
  <td class="xl65">3</td>
  <td class="xl65">0.31</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Saatcioglu and Ozcebe 1989, U1</td>
  <td class="xl65">43.6</td>
  <td class="xl65">470</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">350</td>
  <td class="xl65">350</td>
  <td class="xl65">1000</td>
  <td class="xl65">1000</td>
  <td class="xl65">0</td>
  <td class="xl65">0.0321</td>
  <td class="xl65">0.009</td>
  <td class="xl65">2.86</td>
  <td class="xl65">0</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Saatcioglu and Ozcebe 1989, U3</td>
  <td class="xl65">34.8</td>
  <td class="xl65">470</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">350</td>
  <td class="xl65">350</td>
  <td class="xl65">1000</td>
  <td class="xl65">1000</td>
  <td class="xl65">600</td>
  <td class="xl65">0.0321</td>
  <td class="xl65">0.017</td>
  <td class="xl65">2.86</td>
  <td class="xl65">0.141</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Saatcioglu and Ozcebe 1989, U4</td>
  <td class="xl65">32</td>
  <td class="xl65">470</td>
  <td class="xl65">438</td>
  <td class="xl65">438</td>
  <td class="xl65">350</td>
  <td class="xl65">350</td>
  <td class="xl65">1000</td>
  <td class="xl65">1000</td>
  <td class="xl65">600</td>
  <td class="xl65">0.0321</td>
  <td class="xl65">0.025</td>
  <td class="xl65">2.86</td>
  <td class="xl65">0.153</td>
  <td class="xl65"><span style="mso-spacerun:yes">&nbsp;</span>Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Saatcioglu and Ozcebe 1989, U6</td>
  <td class="xl65">37.3</td>
  <td class="xl65">425</td>
  <td class="xl65">437</td>
  <td class="xl65">437</td>
  <td class="xl65">350</td>
  <td class="xl65">350</td>
  <td class="xl65">1000</td>
  <td class="xl65">1000</td>
  <td class="xl65">600</td>
  <td class="xl65">0.0321</td>
  <td class="xl65">0.02</td>
  <td class="xl65">2.86</td>
  <td class="xl65">0.131</td>
  <td class="xl65"><span style="mso-spacerun:yes">&nbsp;</span>Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Saatcioglu and Ozcebe 1989, U7</td>
  <td class="xl65">39</td>
  <td class="xl65">425</td>
  <td class="xl65">437</td>
  <td class="xl65">437</td>
  <td class="xl65">350</td>
  <td class="xl65">350</td>
  <td class="xl65">1000</td>
  <td class="xl65">1000</td>
  <td class="xl65">600</td>
  <td class="xl65">0.0321</td>
  <td class="xl65">0.02</td>
  <td class="xl65">2.86</td>
  <td class="xl65">0.126</td>
  <td class="xl65"><span style="mso-spacerun:yes">&nbsp;</span>Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, AA1</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1500</td>
  <td class="xl65">0.0151</td>
  <td class="xl65">0.012</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, AA2</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1500</td>
  <td class="xl65">0.0151</td>
  <td class="xl65">0.012</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.3</td>
  <td class="xl65"><span style="mso-spacerun:yes">&nbsp;</span>Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, AA3</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1000</td>
  <td class="xl65">0.0151</td>
  <td class="xl65">0.012</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, AA4</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1000</td>
  <td class="xl65">0.0151</td>
  <td class="xl65">0.012</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, BA1</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1000</td>
  <td class="xl65">0.0151</td>
  <td class="xl65">0.018</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, BA2</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1500</td>
  <td class="xl65">0.0151</td>
  <td class="xl65">0.018</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, BA3</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1500</td>
  <td class="xl65">0.0151</td>
  <td class="xl65">0.018</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, BA4</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1000</td>
  <td class="xl65">0.0151</td>
  <td class="xl65">0.018</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, CA1</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1000</td>
  <td class="xl65">0.0151</td>
  <td class="xl65">0.037</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, CA2</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1500</td>
  <td class="xl65">0.0151</td>
  <td class="xl65">0.037</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, CA3</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1000</td>
  <td class="xl65">0.0151</td>
  <td class="xl65">0.037</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, CA4</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1500</td>
  <td class="xl65">0.0151</td>
  <td class="xl65">0.037</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, AB1</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1000</td>
  <td class="xl65">0.0603</td>
  <td class="xl65">0.012</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, AB2</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1500</td>
  <td class="xl65">0.0603</td>
  <td class="xl65">0.012</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, AB3</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1500</td>
  <td class="xl65">0.0603</td>
  <td class="xl65">0.012</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, AB4</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1000</td>
  <td class="xl65">0.0603</td>
  <td class="xl65">0.012</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, BB</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1000</td>
  <td class="xl65">0.0603</td>
  <td class="xl65">0.018</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, BB1</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1000</td>
  <td class="xl65">0.0603</td>
  <td class="xl65">0.018</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, BB4</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1500</td>
  <td class="xl65">0.0603</td>
  <td class="xl65">0.018</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, BB4B</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1500</td>
  <td class="xl65">0.0603</td>
  <td class="xl65">0.018</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, CB1</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1000</td>
  <td class="xl65">0.0603</td>
  <td class="xl65">0.037</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, CB2</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1000</td>
  <td class="xl65">0.0603</td>
  <td class="xl65">0.037</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, CB3</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1500</td>
  <td class="xl65">0.0603</td>
  <td class="xl65">0.037</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Galeota et al. 1996, CB4</td>
  <td class="xl65">80</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">430</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">1140</td>
  <td class="xl65">1140</td>
  <td class="xl65">1500</td>
  <td class="xl65">0.0603</td>
  <td class="xl65">0.037</td>
  <td class="xl65">4.56</td>
  <td class="xl65">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wehbe et al. 1998, A1</td>
  <td class="xl65">27.2</td>
  <td class="xl65">428</td>
  <td class="xl65">448</td>
  <td class="xl65">448</td>
  <td class="xl65">380</td>
  <td class="xl65">610</td>
  <td class="xl65">2335</td>
  <td class="xl65">2335</td>
  <td class="xl65">615</td>
  <td class="xl65">0.0222</td>
  <td class="xl65">0.004</td>
  <td class="xl65">3.83</td>
  <td class="xl65">0.098</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wehbe et al. 1998, A2</td>
  <td class="xl65">27.2</td>
  <td class="xl65">428</td>
  <td class="xl65">448</td>
  <td class="xl65">448</td>
  <td class="xl65">380</td>
  <td class="xl65">610</td>
  <td class="xl65">2335</td>
  <td class="xl65">2335</td>
  <td class="xl65">1505</td>
  <td class="xl65">0.0222</td>
  <td class="xl65">0.004</td>
  <td class="xl65">3.83</td>
  <td class="xl65">0.239</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wehbe et al. 1998, B1</td>
  <td class="xl65">28.1</td>
  <td class="xl65">428</td>
  <td class="xl65">448</td>
  <td class="xl65">448</td>
  <td class="xl65">380</td>
  <td class="xl65">610</td>
  <td class="xl65">2335</td>
  <td class="xl65">2335</td>
  <td class="xl65">601</td>
  <td class="xl65">0.0222</td>
  <td class="xl65">0.005</td>
  <td class="xl65">3.83</td>
  <td class="xl65">0.092</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Wehbe et al. 1998, B2</td>
  <td class="xl65">28.1</td>
  <td class="xl65">428</td>
  <td class="xl65">448</td>
  <td class="xl65">448</td>
  <td class="xl65">380</td>
  <td class="xl65">610</td>
  <td class="xl65">2335</td>
  <td class="xl65">2335</td>
  <td class="xl65">1514</td>
  <td class="xl65">0.0222</td>
  <td class="xl65">0.005</td>
  <td class="xl65">3.83</td>
  <td class="xl65">0.232</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Lynn et al. 1998, 3CLH18</td>
  <td class="xl65">26.9</td>
  <td class="xl65">399.9</td>
  <td class="xl65">331</td>
  <td class="xl65">331</td>
  <td class="xl65">457.2</td>
  <td class="xl65">457.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">503</td>
  <td class="xl65">0.0303</td>
  <td class="xl65">0</td>
  <td class="xl65">3.22</td>
  <td class="xl65">0.089</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Lynn et al. 1998, 2CLH18</td>
  <td class="xl65">33.1</td>
  <td class="xl65">399.9</td>
  <td class="xl65">331</td>
  <td class="xl65">331</td>
  <td class="xl65">457.2</td>
  <td class="xl65">457.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">503</td>
  <td class="xl65">0.0194</td>
  <td class="xl65">0</td>
  <td class="xl65">3.22</td>
  <td class="xl65">0.073</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Lynn et al. 1998, 2CMH18</td>
  <td class="xl65">25.5</td>
  <td class="xl65">399.9</td>
  <td class="xl65">331</td>
  <td class="xl65">331</td>
  <td class="xl65">457.2</td>
  <td class="xl65">457.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">1512</td>
  <td class="xl65">0.0194</td>
  <td class="xl65">0</td>
  <td class="xl65">3.22</td>
  <td class="xl65">0.284</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Lynn et al. 1998, 3CMH18</td>
  <td class="xl65">27.6</td>
  <td class="xl65">399.9</td>
  <td class="xl65">331</td>
  <td class="xl65">331</td>
  <td class="xl65">457.2</td>
  <td class="xl65">457.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">1512</td>
  <td class="xl65">0.0303</td>
  <td class="xl65">0</td>
  <td class="xl65">3.22</td>
  <td class="xl65">0.262</td>
  <td class="xl65">Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Lynn et al. 1998, 3CMD12</td>
  <td class="xl65">27.6</td>
  <td class="xl65">399.9</td>
  <td class="xl65">331</td>
  <td class="xl65">331</td>
  <td class="xl65">457.2</td>
  <td class="xl65">457.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">1512</td>
  <td class="xl65">0.0303</td>
  <td class="xl65">0</td>
  <td class="xl65">3.22</td>
  <td class="xl65">0.262</td>
  <td class="xl65">Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Lynn et al. 1996, 3SLH18</td>
  <td class="xl65">26.9</td>
  <td class="xl65">399.9</td>
  <td class="xl65">331</td>
  <td class="xl65">331</td>
  <td class="xl65">457.2</td>
  <td class="xl65">457.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">503</td>
  <td class="xl65">0.0303</td>
  <td class="xl65">0</td>
  <td class="xl65">3.22</td>
  <td class="xl65">0.089</td>
  <td class="xl65">Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Lynn et al. 1996, 2SLH18</td>
  <td class="xl65">33.1</td>
  <td class="xl65">399.9</td>
  <td class="xl65">331</td>
  <td class="xl65">331</td>
  <td class="xl65">457.2</td>
  <td class="xl65">457.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">503</td>
  <td class="xl65">0.0194</td>
  <td class="xl65">0</td>
  <td class="xl65">3.22</td>
  <td class="xl65">0.073</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Lynn et al. 1996, 3SMD12</td>
  <td class="xl65">25.5</td>
  <td class="xl65">399.9</td>
  <td class="xl65">331</td>
  <td class="xl65">331</td>
  <td class="xl65">457.2</td>
  <td class="xl65">457.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">1512</td>
  <td class="xl65">0.0303</td>
  <td class="xl65">0</td>
  <td class="xl65">3.22</td>
  <td class="xl65">0.284</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Xiao and Martirossyan 1998,
  HC4-8L19-T10-0.1P</td>
  <td class="xl65">76</td>
  <td class="xl65">510</td>
  <td class="xl65">510</td>
  <td class="xl65">510</td>
  <td class="xl65">254</td>
  <td class="xl65">254</td>
  <td class="xl65">508</td>
  <td class="xl65">508</td>
  <td class="xl65">489</td>
  <td class="xl65">0.0355</td>
  <td class="xl65">0.037</td>
  <td class="xl65">2</td>
  <td class="xl65">0.1</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Xiao and Martirossyan 1998,
  HC4-8L19-T10-0.2P</td>
  <td class="xl65">76</td>
  <td class="xl65">510</td>
  <td class="xl65">510</td>
  <td class="xl65">510</td>
  <td class="xl65">254</td>
  <td class="xl65">254</td>
  <td class="xl65">508</td>
  <td class="xl65">508</td>
  <td class="xl65">979</td>
  <td class="xl65">0.0355</td>
  <td class="xl65">0.037</td>
  <td class="xl65">2</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Xiao and Martirossyan 1998,
  HC4-8L16-T10-0.1P</td>
  <td class="xl65">86</td>
  <td class="xl65">510</td>
  <td class="xl65">510</td>
  <td class="xl65">510</td>
  <td class="xl65">254</td>
  <td class="xl65">254</td>
  <td class="xl65">508</td>
  <td class="xl65">508</td>
  <td class="xl65">534</td>
  <td class="xl65">0.0246</td>
  <td class="xl65">0.037</td>
  <td class="xl65">2</td>
  <td class="xl65">0.096</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Xiao and Martirossyan 1998,
  HC4-8L16-T10-0.2P</td>
  <td class="xl65">86</td>
  <td class="xl65">510</td>
  <td class="xl65">510</td>
  <td class="xl65">510</td>
  <td class="xl65">254</td>
  <td class="xl65">254</td>
  <td class="xl65">508</td>
  <td class="xl65">508</td>
  <td class="xl65">1068</td>
  <td class="xl65">0.0246</td>
  <td class="xl65">0.037</td>
  <td class="xl65">2</td>
  <td class="xl65">0.192</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Xiao and Martirossyan 1998,
  HC4-8L16-T6-0.1P</td>
  <td class="xl65">86</td>
  <td class="xl65">449</td>
  <td class="xl65">510</td>
  <td class="xl65">510</td>
  <td class="xl65">254</td>
  <td class="xl65">254</td>
  <td class="xl65">508</td>
  <td class="xl65">508</td>
  <td class="xl65">534</td>
  <td class="xl65">0.0246</td>
  <td class="xl65">0.016</td>
  <td class="xl65">2</td>
  <td class="xl65">0.096</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Xiao and Martirossyan 1998,
  HC4-8L16-T6-0.2P</td>
  <td class="xl65">86</td>
  <td class="xl65">449</td>
  <td class="xl65">510</td>
  <td class="xl65">510</td>
  <td class="xl65">254</td>
  <td class="xl65">254</td>
  <td class="xl65">508</td>
  <td class="xl65">508</td>
  <td class="xl65">1068</td>
  <td class="xl65">0.0246</td>
  <td class="xl65">0.016</td>
  <td class="xl65">2</td>
  <td class="xl65">0.192</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Sugano 1996, UC10H</td>
  <td class="xl65">118</td>
  <td class="xl65">1415</td>
  <td class="xl65">393</td>
  <td class="xl65">393</td>
  <td class="xl65">225</td>
  <td class="xl65">225</td>
  <td class="xl65">450</td>
  <td class="xl65">450</td>
  <td class="xl65">3579</td>
  <td class="xl65">0.0186</td>
  <td class="xl65">0</td>
  <td class="xl65">2</td>
  <td class="xl65">0.599</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Sugano 1996, UC15H</td>
  <td class="xl65">118</td>
  <td class="xl65">1424</td>
  <td class="xl65">393</td>
  <td class="xl65">393</td>
  <td class="xl65">225</td>
  <td class="xl65">225</td>
  <td class="xl65">450</td>
  <td class="xl65">450</td>
  <td class="xl65">3579</td>
  <td class="xl65">0.0186</td>
  <td class="xl65">0</td>
  <td class="xl65">2</td>
  <td class="xl65">0.599</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Sugano 1996, UC20H</td>
  <td class="xl65">118</td>
  <td class="xl65">1424</td>
  <td class="xl65">393</td>
  <td class="xl65">393</td>
  <td class="xl65">225</td>
  <td class="xl65">225</td>
  <td class="xl65">450</td>
  <td class="xl65">450</td>
  <td class="xl65">3579</td>
  <td class="xl65">0.0186</td>
  <td class="xl65">0</td>
  <td class="xl65">2</td>
  <td class="xl65">0.599</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Sugano 1996, UC15L</td>
  <td class="xl65">118</td>
  <td class="xl65">1424</td>
  <td class="xl65">393</td>
  <td class="xl65">393</td>
  <td class="xl65">225</td>
  <td class="xl65">225</td>
  <td class="xl65">450</td>
  <td class="xl65">450</td>
  <td class="xl65">2089</td>
  <td class="xl65">0.0186</td>
  <td class="xl65">0</td>
  <td class="xl65">2</td>
  <td class="xl65">0.35</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Sugano 1996, UC20L</td>
  <td class="xl65">118</td>
  <td class="xl65">1424</td>
  <td class="xl65">393</td>
  <td class="xl65">393</td>
  <td class="xl65">225</td>
  <td class="xl65">225</td>
  <td class="xl65">450</td>
  <td class="xl65">450</td>
  <td class="xl65">2089</td>
  <td class="xl65">0.0186</td>
  <td class="xl65">0</td>
  <td class="xl65">2</td>
  <td class="xl65">0.35</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Nosho et al. 1996, No. 1</td>
  <td class="xl65">40.6</td>
  <td class="xl65">351</td>
  <td class="xl65">407</td>
  <td class="xl65">407</td>
  <td class="xl65">279.4</td>
  <td class="xl65">279.4</td>
  <td class="xl65">2134</td>
  <td class="xl65">2134</td>
  <td class="xl65">1076</td>
  <td class="xl65">0.0101</td>
  <td class="xl65">0</td>
  <td class="xl65">7.64</td>
  <td class="xl65">0.339</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Bayrak and Sheikh 1996, ES-1HT</td>
  <td class="xl65">72.1</td>
  <td class="xl65">463</td>
  <td class="xl65">454</td>
  <td class="xl65">454</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">1842</td>
  <td class="xl65">1473</td>
  <td class="xl65">3354</td>
  <td class="xl65">0.0258</td>
  <td class="xl65">0.032</td>
  <td class="xl65">6.04</td>
  <td class="xl65">0.5</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Bayrak and Sheikh 1996, AS-2HT</td>
  <td class="xl65">71.7</td>
  <td class="xl65">542</td>
  <td class="xl65">454</td>
  <td class="xl65">454</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">1842</td>
  <td class="xl65">1473</td>
  <td class="xl65">2401</td>
  <td class="xl65">0.0258</td>
  <td class="xl65">0.028</td>
  <td class="xl65">6.04</td>
  <td class="xl65">0.36</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Bayrak and Sheikh 1996, AS-3HT</td>
  <td class="xl65">71.8</td>
  <td class="xl65">542</td>
  <td class="xl65">454</td>
  <td class="xl65">454</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">1842</td>
  <td class="xl65">1473</td>
  <td class="xl65">3340</td>
  <td class="xl65">0.0258</td>
  <td class="xl65">0.028</td>
  <td class="xl65">6.04</td>
  <td class="xl65">0.5</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Bayrak and Sheikh 1996, AS-4HT</td>
  <td class="xl65">71.9</td>
  <td class="xl65">463</td>
  <td class="xl65">454</td>
  <td class="xl65">454</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">1842</td>
  <td class="xl65">1473</td>
  <td class="xl65">3344</td>
  <td class="xl65">0.0258</td>
  <td class="xl65">0.051</td>
  <td class="xl65">6.04</td>
  <td class="xl65">0.5</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Bayrak and Sheikh 1996, AS-5HT</td>
  <td class="xl65">101.8</td>
  <td class="xl65">463</td>
  <td class="xl65">454</td>
  <td class="xl65">454</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">1842</td>
  <td class="xl65">1473</td>
  <td class="xl65">4261</td>
  <td class="xl65">0.0258</td>
  <td class="xl65">0.04</td>
  <td class="xl65">6.04</td>
  <td class="xl65">0.5</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Bayrak and Sheikh 1996, AS-6HT</td>
  <td class="xl65">101.9</td>
  <td class="xl65">463</td>
  <td class="xl65">454</td>
  <td class="xl65">454</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">1842</td>
  <td class="xl65">1473</td>
  <td class="xl65">4360</td>
  <td class="xl65">0.0258</td>
  <td class="xl65">0.067</td>
  <td class="xl65">6.04</td>
  <td class="xl65">0.46</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Bayrak and Sheikh 1996, AS-7HT</td>
  <td class="xl65">102</td>
  <td class="xl65">542</td>
  <td class="xl65">454</td>
  <td class="xl65">454</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">1842</td>
  <td class="xl65">1473</td>
  <td class="xl65">4270</td>
  <td class="xl65">0.0258</td>
  <td class="xl65">0.027</td>
  <td class="xl65">6.04</td>
  <td class="xl65">0.45</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Bayrak and Sheikh 1996, ES-8HT</td>
  <td class="xl65">102.2</td>
  <td class="xl65">463</td>
  <td class="xl65">454</td>
  <td class="xl65">454</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">1842</td>
  <td class="xl65">1473</td>
  <td class="xl65">4468</td>
  <td class="xl65">0.0258</td>
  <td class="xl65">0.043</td>
  <td class="xl65">6.04</td>
  <td class="xl65">0.47</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Saatcioglu and Grira 1999,
  BG-1</td>
  <td class="xl65">34</td>
  <td class="xl65">570</td>
  <td class="xl65">455.6</td>
  <td class="xl65">455.6</td>
  <td class="xl65">350</td>
  <td class="xl65">350</td>
  <td class="xl65">1645</td>
  <td class="xl65">1645</td>
  <td class="xl65">1782</td>
  <td class="xl65">0.0195</td>
  <td class="xl65">0.01</td>
  <td class="xl65">4.7</td>
  <td class="xl65">0.428</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Saatcioglu and Grira 1999,
  BG-2</td>
  <td class="xl65">34</td>
  <td class="xl65">570</td>
  <td class="xl65">455.6</td>
  <td class="xl65">455.6</td>
  <td class="xl65">350</td>
  <td class="xl65">350</td>
  <td class="xl65">1645</td>
  <td class="xl65">1645</td>
  <td class="xl65">1782</td>
  <td class="xl65">0.0195</td>
  <td class="xl65">0.02</td>
  <td class="xl65">4.7</td>
  <td class="xl65">0.428</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Saatcioglu and Grira 1999,
  BG-3</td>
  <td class="xl65">34</td>
  <td class="xl65">570</td>
  <td class="xl65">455.6</td>
  <td class="xl65">455.6</td>
  <td class="xl65">350</td>
  <td class="xl65">350</td>
  <td class="xl65">1645</td>
  <td class="xl65">1645</td>
  <td class="xl65">831</td>
  <td class="xl65">0.0195</td>
  <td class="xl65">0.02</td>
  <td class="xl65">4.7</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Saatcioglu and Grira 1999,
  BG-4</td>
  <td class="xl65">34</td>
  <td class="xl65">570</td>
  <td class="xl65">455.6</td>
  <td class="xl65">455.6</td>
  <td class="xl65">350</td>
  <td class="xl65">350</td>
  <td class="xl65">1645</td>
  <td class="xl65">1645</td>
  <td class="xl65">1923</td>
  <td class="xl65">0.0293</td>
  <td class="xl65">0.013</td>
  <td class="xl65">4.7</td>
  <td class="xl65">0.462</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Saatcioglu and Grira 1999,
  BG-5</td>
  <td class="xl65">34</td>
  <td class="xl65">570</td>
  <td class="xl65">455.6</td>
  <td class="xl65">455.6</td>
  <td class="xl65">350</td>
  <td class="xl65">350</td>
  <td class="xl65">1645</td>
  <td class="xl65">1645</td>
  <td class="xl65">1923</td>
  <td class="xl65">0.0293</td>
  <td class="xl65">0.027</td>
  <td class="xl65">4.7</td>
  <td class="xl65">0.462</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Saatcioglu and Grira 1999,
  BG-6</td>
  <td class="xl65">34</td>
  <td class="xl65">570</td>
  <td class="xl65">477.8</td>
  <td class="xl65">477.8</td>
  <td class="xl65">350</td>
  <td class="xl65">350</td>
  <td class="xl65">1645</td>
  <td class="xl65">1645</td>
  <td class="xl65">1900</td>
  <td class="xl65">0.0229</td>
  <td class="xl65">0.027</td>
  <td class="xl65">4.7</td>
  <td class="xl65">0.456</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Saatcioglu and Grira 1999,
  BG-7</td>
  <td class="xl65">34</td>
  <td class="xl65">580</td>
  <td class="xl65">455.6</td>
  <td class="xl65">455.6</td>
  <td class="xl65">350</td>
  <td class="xl65">350</td>
  <td class="xl65">1645</td>
  <td class="xl65">1645</td>
  <td class="xl65">1923</td>
  <td class="xl65">0.0293</td>
  <td class="xl65">0.013</td>
  <td class="xl65">4.7</td>
  <td class="xl65">0.462</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Saatcioglu and Grira 1999,
  BG-8</td>
  <td class="xl65">34</td>
  <td class="xl65">580</td>
  <td class="xl65">455.6</td>
  <td class="xl65">455.6</td>
  <td class="xl65">350</td>
  <td class="xl65">350</td>
  <td class="xl65">1645</td>
  <td class="xl65">1645</td>
  <td class="xl65">961</td>
  <td class="xl65">0.0293</td>
  <td class="xl65">0.013</td>
  <td class="xl65">4.7</td>
  <td class="xl65">0.231</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Saatcioglu and Grira 1999,
  BG-9</td>
  <td class="xl65">34</td>
  <td class="xl65">580</td>
  <td class="xl65">427.8</td>
  <td class="xl65">427.8</td>
  <td class="xl65">350</td>
  <td class="xl65">350</td>
  <td class="xl65">1645</td>
  <td class="xl65">1645</td>
  <td class="xl65">1923</td>
  <td class="xl65">0.0328</td>
  <td class="xl65">0.013</td>
  <td class="xl65">4.7</td>
  <td class="xl65">0.462</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Saatcioglu and Grira 1999,
  BG-10</td>
  <td class="xl65">34</td>
  <td class="xl65">570</td>
  <td class="xl65">427.8</td>
  <td class="xl65">427.8</td>
  <td class="xl65">350</td>
  <td class="xl65">350</td>
  <td class="xl65">1645</td>
  <td class="xl65">1645</td>
  <td class="xl65">1923</td>
  <td class="xl65">0.0328</td>
  <td class="xl65">0.027</td>
  <td class="xl65">4.7</td>
  <td class="xl65">0.462</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Matamoros et al. 1999,C10-05N</td>
  <td class="xl65">69.6</td>
  <td class="xl65">406.8</td>
  <td class="xl65">586.1</td>
  <td class="xl65">586.1</td>
  <td class="xl65">203</td>
  <td class="xl65">203</td>
  <td class="xl65">610</td>
  <td class="xl65">610</td>
  <td class="xl65">142</td>
  <td class="xl65">0.0193</td>
  <td class="xl65">0.01</td>
  <td class="xl65">3</td>
  <td class="xl65">0.05</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Matamoros et al. 1999,C10-05S</td>
  <td class="xl65">69.6</td>
  <td class="xl65">406.8</td>
  <td class="xl65">586.1</td>
  <td class="xl65">586.1</td>
  <td class="xl65">203</td>
  <td class="xl65">203</td>
  <td class="xl65">610</td>
  <td class="xl65">610</td>
  <td class="xl65">142</td>
  <td class="xl65">0.0193</td>
  <td class="xl65">0.01</td>
  <td class="xl65">3</td>
  <td class="xl65">0.055</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Matamoros et al. 1999,C10-10N</td>
  <td class="xl65">67.8</td>
  <td class="xl65">513.7</td>
  <td class="xl65">572.3</td>
  <td class="xl65">572.3</td>
  <td class="xl65">203</td>
  <td class="xl65">203</td>
  <td class="xl65">610</td>
  <td class="xl65">610</td>
  <td class="xl65">285</td>
  <td class="xl65">0.0193</td>
  <td class="xl65">0.01</td>
  <td class="xl65">3</td>
  <td class="xl65">0.102</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Matamoros et al. 1999,C10-10S</td>
  <td class="xl65">67.8</td>
  <td class="xl65">514.7</td>
  <td class="xl65">573.3</td>
  <td class="xl65">573.3</td>
  <td class="xl65">203</td>
  <td class="xl65">203</td>
  <td class="xl65">610</td>
  <td class="xl65">610</td>
  <td class="xl65">285</td>
  <td class="xl65">0.0193</td>
  <td class="xl65">0.01</td>
  <td class="xl65">3</td>
  <td class="xl65">0.102</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Matamoros et al. 1999,C10-20N</td>
  <td class="xl65">65.5</td>
  <td class="xl65">513.7</td>
  <td class="xl65">572.3</td>
  <td class="xl65">572.3</td>
  <td class="xl65">203</td>
  <td class="xl65">203</td>
  <td class="xl65">610</td>
  <td class="xl65">610</td>
  <td class="xl65">569</td>
  <td class="xl65">0.0193</td>
  <td class="xl65">0.01</td>
  <td class="xl65">3</td>
  <td class="xl65">0.211</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Matamoros et al. 1999,C10-20S</td>
  <td class="xl65">65.5</td>
  <td class="xl65">514.7</td>
  <td class="xl65">573.3</td>
  <td class="xl65">573.3</td>
  <td class="xl65">203</td>
  <td class="xl65">203</td>
  <td class="xl65">610</td>
  <td class="xl65">610</td>
  <td class="xl65">569</td>
  <td class="xl65">0.0193</td>
  <td class="xl65">0.01</td>
  <td class="xl65">3</td>
  <td class="xl65">0.211</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Matamoros et al. 1999,C5-00N</td>
  <td class="xl65">37.9</td>
  <td class="xl65">513.7</td>
  <td class="xl65">572.3</td>
  <td class="xl65">572.3</td>
  <td class="xl65">203</td>
  <td class="xl65">203</td>
  <td class="xl65">610</td>
  <td class="xl65">610</td>
  <td class="xl65">0</td>
  <td class="xl65">0.0193</td>
  <td class="xl65">0.01</td>
  <td class="xl65">3</td>
  <td class="xl65">0</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Matamoros et al. 1999,C5-00S</td>
  <td class="xl65">37.9</td>
  <td class="xl65">514.7</td>
  <td class="xl65">573.3</td>
  <td class="xl65">573.3</td>
  <td class="xl65">203</td>
  <td class="xl65">203</td>
  <td class="xl65">610</td>
  <td class="xl65">610</td>
  <td class="xl65">0</td>
  <td class="xl65">0.0193</td>
  <td class="xl65">0.01</td>
  <td class="xl65">3</td>
  <td class="xl65">0</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Matamoros et al. 1999,C5-20N</td>
  <td class="xl65">48.3</td>
  <td class="xl65">406.8</td>
  <td class="xl65">586.1</td>
  <td class="xl65">586.1</td>
  <td class="xl65">203</td>
  <td class="xl65">203</td>
  <td class="xl65">610</td>
  <td class="xl65">610</td>
  <td class="xl65">285</td>
  <td class="xl65">0.0193</td>
  <td class="xl65">0.01</td>
  <td class="xl65">3</td>
  <td class="xl65">0.143</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Matamoros et al. 1999,C5-20S</td>
  <td class="xl65">48.3</td>
  <td class="xl65">407.8</td>
  <td class="xl65">587.1</td>
  <td class="xl65">587.1</td>
  <td class="xl65">203</td>
  <td class="xl65">203</td>
  <td class="xl65">610</td>
  <td class="xl65">610</td>
  <td class="xl65">285</td>
  <td class="xl65">0.0193</td>
  <td class="xl65">0.01</td>
  <td class="xl65">3</td>
  <td class="xl65">0.143</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Matamoros et al. 1999,C5-40N</td>
  <td class="xl65">38.1</td>
  <td class="xl65">513.7</td>
  <td class="xl65">572.3</td>
  <td class="xl65">572.3</td>
  <td class="xl65">203</td>
  <td class="xl65">203</td>
  <td class="xl65">610</td>
  <td class="xl65">610</td>
  <td class="xl65">569</td>
  <td class="xl65">0.0193</td>
  <td class="xl65">0.01</td>
  <td class="xl65">3</td>
  <td class="xl65">0.362</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Matamoros et al. 1999,C5-40S</td>
  <td class="xl65">38.1</td>
  <td class="xl65">514.7</td>
  <td class="xl65">573.3</td>
  <td class="xl65">573.3</td>
  <td class="xl65">203</td>
  <td class="xl65">203</td>
  <td class="xl65">610</td>
  <td class="xl65">610</td>
  <td class="xl65">569</td>
  <td class="xl65">0.0193</td>
  <td class="xl65">0.01</td>
  <td class="xl65">3</td>
  <td class="xl65">0.362</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Mo and Wang 2000,C1-1</td>
  <td class="xl65">24.9</td>
  <td class="xl65">459.5</td>
  <td class="xl65">497</td>
  <td class="xl65">497</td>
  <td class="xl65">400</td>
  <td class="xl65">400</td>
  <td class="xl65">1400</td>
  <td class="xl65">1400</td>
  <td class="xl65">450</td>
  <td class="xl65">0.0214</td>
  <td class="xl65">0</td>
  <td class="xl65">3.5</td>
  <td class="xl65">0.113</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Mo and Wang 2000,C1-2</td>
  <td class="xl65">26.7</td>
  <td class="xl65">459.5</td>
  <td class="xl65">497</td>
  <td class="xl65">497</td>
  <td class="xl65">400</td>
  <td class="xl65">400</td>
  <td class="xl65">1400</td>
  <td class="xl65">1400</td>
  <td class="xl65">675</td>
  <td class="xl65">0.0214</td>
  <td class="xl65">0</td>
  <td class="xl65">3.5</td>
  <td class="xl65">0.158</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Mo and Wang 2000,C1-3</td>
  <td class="xl65">26.1</td>
  <td class="xl65">459.5</td>
  <td class="xl65">497</td>
  <td class="xl65">497</td>
  <td class="xl65">400</td>
  <td class="xl65">400</td>
  <td class="xl65">1400</td>
  <td class="xl65">1400</td>
  <td class="xl65">900</td>
  <td class="xl65">0.0214</td>
  <td class="xl65">0</td>
  <td class="xl65">3.5</td>
  <td class="xl65">0.216</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Mo and Wang 2000,C2-1</td>
  <td class="xl65">25.3</td>
  <td class="xl65">459.5</td>
  <td class="xl65">497</td>
  <td class="xl65">497</td>
  <td class="xl65">400</td>
  <td class="xl65">400</td>
  <td class="xl65">1400</td>
  <td class="xl65">1400</td>
  <td class="xl65">450</td>
  <td class="xl65">0.0214</td>
  <td class="xl65">0</td>
  <td class="xl65">3.5</td>
  <td class="xl65">0.111</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Mo and Wang 2000,C2-2</td>
  <td class="xl65">27.1</td>
  <td class="xl65">459.5</td>
  <td class="xl65">497</td>
  <td class="xl65">497</td>
  <td class="xl65">400</td>
  <td class="xl65">400</td>
  <td class="xl65">1400</td>
  <td class="xl65">1400</td>
  <td class="xl65">675</td>
  <td class="xl65">0.0214</td>
  <td class="xl65">0</td>
  <td class="xl65">3.5</td>
  <td class="xl65">0.156</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Mo and Wang 2000,C2-3</td>
  <td class="xl65">26.8</td>
  <td class="xl65">459.5</td>
  <td class="xl65">497</td>
  <td class="xl65">497</td>
  <td class="xl65">400</td>
  <td class="xl65">400</td>
  <td class="xl65">1400</td>
  <td class="xl65">1400</td>
  <td class="xl65">900</td>
  <td class="xl65">0.0214</td>
  <td class="xl65">0</td>
  <td class="xl65">3.5</td>
  <td class="xl65">0.21</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Mo and Wang 2000,C3-1</td>
  <td class="xl65">26.4</td>
  <td class="xl65">459.5</td>
  <td class="xl65">497</td>
  <td class="xl65">497</td>
  <td class="xl65">400</td>
  <td class="xl65">400</td>
  <td class="xl65">1400</td>
  <td class="xl65">1400</td>
  <td class="xl65">450</td>
  <td class="xl65">0.0214</td>
  <td class="xl65">0</td>
  <td class="xl65">3.5</td>
  <td class="xl65">0.107</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Mo and Wang 2000,C3-2</td>
  <td class="xl65">27.5</td>
  <td class="xl65">459.5</td>
  <td class="xl65">497</td>
  <td class="xl65">497</td>
  <td class="xl65">400</td>
  <td class="xl65">400</td>
  <td class="xl65">1400</td>
  <td class="xl65">1400</td>
  <td class="xl65">675</td>
  <td class="xl65">0.0214</td>
  <td class="xl65">0</td>
  <td class="xl65">3.5</td>
  <td class="xl65">0.154</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Mo and Wang 2000,C3-3</td>
  <td class="xl65">26.9</td>
  <td class="xl65">459.5</td>
  <td class="xl65">497</td>
  <td class="xl65">497</td>
  <td class="xl65">400</td>
  <td class="xl65">400</td>
  <td class="xl65">1400</td>
  <td class="xl65">1400</td>
  <td class="xl65">900</td>
  <td class="xl65">0.0214</td>
  <td class="xl65">0</td>
  <td class="xl65">3.5</td>
  <td class="xl65">0.209</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Aboutaha et al. 1999, SC3</td>
  <td class="xl65">21.9</td>
  <td class="xl65">400</td>
  <td class="xl65">434</td>
  <td class="xl65">434</td>
  <td class="xl65">914.4</td>
  <td class="xl65">457.2</td>
  <td class="xl65">1219.2</td>
  <td class="xl65">1219.2</td>
  <td class="xl65">0</td>
  <td class="xl65">0.0188</td>
  <td class="xl65">0</td>
  <td class="xl65">2.67</td>
  <td class="xl65">0</td>
  <td class="xl65">Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Aboutaha et al. 1999, SC9</td>
  <td class="xl65">16</td>
  <td class="xl65">400</td>
  <td class="xl65">434</td>
  <td class="xl65">434</td>
  <td class="xl65">457.2</td>
  <td class="xl65">914.4</td>
  <td class="xl65">1219.2</td>
  <td class="xl65">1219.2</td>
  <td class="xl65">0</td>
  <td class="xl65">0.0188</td>
  <td class="xl65">0</td>
  <td class="xl65">1.33</td>
  <td class="xl65">0</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Thomsen and Wallace 1994, A1</td>
  <td class="xl65">102.7</td>
  <td class="xl65">793</td>
  <td class="xl65">517.1</td>
  <td class="xl65">517.1</td>
  <td class="xl65">152.4</td>
  <td class="xl65">152.4</td>
  <td class="xl65">596.9</td>
  <td class="xl65">596.9</td>
  <td class="xl65">0</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">3.92</td>
  <td class="xl65">0</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Thomsen and Wallace 1994, A3</td>
  <td class="xl65">86.3</td>
  <td class="xl65">793</td>
  <td class="xl65">517.1</td>
  <td class="xl65">517.1</td>
  <td class="xl65">152.4</td>
  <td class="xl65">152.4</td>
  <td class="xl65">593.9</td>
  <td class="xl65">596.9</td>
  <td class="xl65">401</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">3.92</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Thomsen and Wallace 1994, B1</td>
  <td class="xl65">87.5</td>
  <td class="xl65">793</td>
  <td class="xl65">455.1</td>
  <td class="xl65">455.1</td>
  <td class="xl65">152.4</td>
  <td class="xl65">152.4</td>
  <td class="xl65">596.9</td>
  <td class="xl65">596.9</td>
  <td class="xl65">0</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">3.92</td>
  <td class="xl65">0</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Thomsen and Wallace 1994, B2</td>
  <td class="xl65">83.4</td>
  <td class="xl65">793</td>
  <td class="xl65">455.1</td>
  <td class="xl65">455.1</td>
  <td class="xl65">152.4</td>
  <td class="xl65">152.4</td>
  <td class="xl65">596.9</td>
  <td class="xl65">596.9</td>
  <td class="xl65">194</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">3.92</td>
  <td class="xl65">0.1</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Thomsen and Wallace 1994, B3</td>
  <td class="xl65">90</td>
  <td class="xl65">793</td>
  <td class="xl65">455.1</td>
  <td class="xl65">455.1</td>
  <td class="xl65">152.4</td>
  <td class="xl65">152.4</td>
  <td class="xl65">596.9</td>
  <td class="xl65">596.9</td>
  <td class="xl65">418</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">3.92</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Thomsen and Wallace 1994, C1</td>
  <td class="xl65">67.5</td>
  <td class="xl65">1262</td>
  <td class="xl65">475.8</td>
  <td class="xl65">475.8</td>
  <td class="xl65">152.4</td>
  <td class="xl65">152.4</td>
  <td class="xl65">596.9</td>
  <td class="xl65">596.9</td>
  <td class="xl65">0</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">3.92</td>
  <td class="xl65">0</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Thomsen and Wallace 1994, C2</td>
  <td class="xl65">74.6</td>
  <td class="xl65">1262</td>
  <td class="xl65">475.8</td>
  <td class="xl65">475.8</td>
  <td class="xl65">152.4</td>
  <td class="xl65">152.4</td>
  <td class="xl65">596.9</td>
  <td class="xl65">596.9</td>
  <td class="xl65">173</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">3.92</td>
  <td class="xl65">0.1</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Thomsen and Wallace 1994, C3</td>
  <td class="xl65">81.8</td>
  <td class="xl65">1262</td>
  <td class="xl65">475.8</td>
  <td class="xl65">475.8</td>
  <td class="xl65">152.4</td>
  <td class="xl65">152.4</td>
  <td class="xl65">596.9</td>
  <td class="xl65">596.9</td>
  <td class="xl65">380</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">3.92</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Thomsen and Wallace 1994, D1</td>
  <td class="xl65">75.8</td>
  <td class="xl65">1262</td>
  <td class="xl65">475.8</td>
  <td class="xl65">475.8</td>
  <td class="xl65">152.4</td>
  <td class="xl65">152.4</td>
  <td class="xl65">596.9</td>
  <td class="xl65">596.9</td>
  <td class="xl65">352</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">3.92</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Thomsen and Wallace 1994, D2</td>
  <td class="xl65">87</td>
  <td class="xl65">1262</td>
  <td class="xl65">475.8</td>
  <td class="xl65">475.8</td>
  <td class="xl65">152.4</td>
  <td class="xl65">152.4</td>
  <td class="xl65">596.9</td>
  <td class="xl65">596.9</td>
  <td class="xl65">404</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">3.92</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Thomsen and Wallace 1994, D3</td>
  <td class="xl65">71.2</td>
  <td class="xl65">1262</td>
  <td class="xl65">475.8</td>
  <td class="xl65">475.8</td>
  <td class="xl65">152.4</td>
  <td class="xl65">152.4</td>
  <td class="xl65">596.9</td>
  <td class="xl65">596.9</td>
  <td class="xl65">331</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">3.92</td>
  <td class="xl65">0.2</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Sezen and Moehle No. 1</td>
  <td class="xl65">21.1</td>
  <td class="xl65">476</td>
  <td class="xl65">434.4</td>
  <td class="xl65">434.4</td>
  <td class="xl65">457.2</td>
  <td class="xl65">457.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">667</td>
  <td class="xl65">0.0247</td>
  <td class="xl65">0.002</td>
  <td class="xl65">3.22</td>
  <td class="xl65">0.151</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Sezen and Moehle No. 2</td>
  <td class="xl65">21.1</td>
  <td class="xl65">476</td>
  <td class="xl65">434.4</td>
  <td class="xl65">434.4</td>
  <td class="xl65">457.2</td>
  <td class="xl65">457.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">2669</td>
  <td class="xl65">0.0247</td>
  <td class="xl65">0.002</td>
  <td class="xl65">3.22</td>
  <td class="xl65">0.605</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Sezen and Moehle No. 4</td>
  <td class="xl65">21.8</td>
  <td class="xl65">476</td>
  <td class="xl65">434.4</td>
  <td class="xl65">434.4</td>
  <td class="xl65">457.2</td>
  <td class="xl65">457.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">1473.2</td>
  <td class="xl65">667</td>
  <td class="xl65">0.0247</td>
  <td class="xl65">0.002</td>
  <td class="xl65">3.22</td>
  <td class="xl65">0.146</td>
  <td class="xl65">Flexure-Shear</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Paultre and Legeron, 2000, No.
  1006015</td>
  <td class="xl65">92.4</td>
  <td class="xl65">391</td>
  <td class="xl65">451</td>
  <td class="xl65">494</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">2000</td>
  <td class="xl65">2000</td>
  <td class="xl65">1200</td>
  <td class="xl65">0.0215</td>
  <td class="xl65">0.002</td>
  <td class="xl65">6.56</td>
  <td class="xl65">0.14</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Paultre and Legeron, 2000, No.
  1006025</td>
  <td class="xl65">93.3</td>
  <td class="xl65">391</td>
  <td class="xl65">430</td>
  <td class="xl65">494</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">2000</td>
  <td class="xl65">2000</td>
  <td class="xl65">2400</td>
  <td class="xl65">0.0215</td>
  <td class="xl65">0.002</td>
  <td class="xl65">6.56</td>
  <td class="xl65">0.277</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Paultre and Legeron, 2000, No.
  1006040</td>
  <td class="xl65">98.2</td>
  <td class="xl65">418</td>
  <td class="xl65">451</td>
  <td class="xl65">467</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">2000</td>
  <td class="xl65">2000</td>
  <td class="xl65">3600</td>
  <td class="xl65">0.0215</td>
  <td class="xl65">0.002</td>
  <td class="xl65">6.56</td>
  <td class="xl65">0.394</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Paultre and Legeron, 2000, No.
  10013015</td>
  <td class="xl65">94.8</td>
  <td class="xl65">391</td>
  <td class="xl65">451</td>
  <td class="xl65">494</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">2000</td>
  <td class="xl65">2000</td>
  <td class="xl65">1200</td>
  <td class="xl65">0.0215</td>
  <td class="xl65">0.002</td>
  <td class="xl65">6.56</td>
  <td class="xl65">0.136</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Paultre and Legeron, 2000, No.
  10013025</td>
  <td class="xl65">97.7</td>
  <td class="xl65">391</td>
  <td class="xl65">451</td>
  <td class="xl65">494</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">2000</td>
  <td class="xl65">2000</td>
  <td class="xl65">2400</td>
  <td class="xl65">0.0215</td>
  <td class="xl65">0.002</td>
  <td class="xl65">6.56</td>
  <td class="xl65">0.264</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Paultre and Legeron, 2000, No.
  10013040</td>
  <td class="xl65">104.3</td>
  <td class="xl65">418</td>
  <td class="xl65">451</td>
  <td class="xl65">467</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">2000</td>
  <td class="xl65">2000</td>
  <td class="xl65">3600</td>
  <td class="xl65">0.0215</td>
  <td class="xl65">0.002</td>
  <td class="xl65">6.56</td>
  <td class="xl65">0.371</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Paultre et al., 2001, No.
  806040</td>
  <td class="xl65">78.7</td>
  <td class="xl65">438</td>
  <td class="xl65">446</td>
  <td class="xl65">499</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">2000</td>
  <td class="xl65">2000</td>
  <td class="xl65">2900</td>
  <td class="xl65">0.0215</td>
  <td class="xl65">0.002</td>
  <td class="xl65">6.56</td>
  <td class="xl65">0.396</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Paultre et al., 2001, No.
  1206040</td>
  <td class="xl65">109.2</td>
  <td class="xl65">438</td>
  <td class="xl65">446</td>
  <td class="xl65">499</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">2000</td>
  <td class="xl65">2000</td>
  <td class="xl65">4200</td>
  <td class="xl65">0.0215</td>
  <td class="xl65">0.002</td>
  <td class="xl65">6.56</td>
  <td class="xl65">0.413</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Paultre et al., 2001, No.
  1005540</td>
  <td class="xl65">109.5</td>
  <td class="xl65">825</td>
  <td class="xl65">446</td>
  <td class="xl65">499</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">2000</td>
  <td class="xl65">2000</td>
  <td class="xl65">4200</td>
  <td class="xl65">0.0215</td>
  <td class="xl65">0.002</td>
  <td class="xl65">6.56</td>
  <td class="xl65">0.412</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Paultre et al., 2001, No.
  1008040</td>
  <td class="xl65">104.2</td>
  <td class="xl65">825</td>
  <td class="xl65">446</td>
  <td class="xl65">499</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">2000</td>
  <td class="xl65">2000</td>
  <td class="xl65">3600</td>
  <td class="xl65">0.0215</td>
  <td class="xl65">0.002</td>
  <td class="xl65">6.56</td>
  <td class="xl65">0.371</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Paultre et al., 2001, No.
  1005552</td>
  <td class="xl65">104.5</td>
  <td class="xl65">744</td>
  <td class="xl65">446</td>
  <td class="xl65">533</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">2000</td>
  <td class="xl65">2000</td>
  <td class="xl65">5150</td>
  <td class="xl65">0.0215</td>
  <td class="xl65">0.002</td>
  <td class="xl65">6.56</td>
  <td class="xl65">0.53</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Paultre et al., 2001, No.
  1006052</td>
  <td class="xl65">109.4</td>
  <td class="xl65">492</td>
  <td class="xl65">446</td>
  <td class="xl65">533</td>
  <td class="xl65">305</td>
  <td class="xl65">305</td>
  <td class="xl65">2000</td>
  <td class="xl65">2000</td>
  <td class="xl65">5150</td>
  <td class="xl65">0.0215</td>
  <td class="xl65">0.002</td>
  <td class="xl65">6.56</td>
  <td class="xl65">0.506</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Pujol 2002, No. 10-2-3N</td>
  <td class="xl65">33.7</td>
  <td class="xl65">410.9</td>
  <td class="xl65">453</td>
  <td class="xl65">453</td>
  <td class="xl65">152.4</td>
  <td class="xl65">304.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">133</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0.006</td>
  <td class="xl65">2.25</td>
  <td class="xl65">0.085</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Pujol 2002, No. 10-2-3S</td>
  <td class="xl65">33.7</td>
  <td class="xl65">410.9</td>
  <td class="xl65">453</td>
  <td class="xl65">453</td>
  <td class="xl65">152.4</td>
  <td class="xl65">304.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">133</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0.006</td>
  <td class="xl65">2.25</td>
  <td class="xl65">0.085</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Pujol 2002, No. 10-3-1.5N</td>
  <td class="xl65">32.1</td>
  <td class="xl65">410.9</td>
  <td class="xl65">453</td>
  <td class="xl65">453</td>
  <td class="xl65">152.4</td>
  <td class="xl65">304.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">133</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">2.25</td>
  <td class="xl65">0.089</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Pujol 2002, No. 10-3-1.5S</td>
  <td class="xl65">32.1</td>
  <td class="xl65">410.9</td>
  <td class="xl65">453</td>
  <td class="xl65">453</td>
  <td class="xl65">152.4</td>
  <td class="xl65">304.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">133</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">2.25</td>
  <td class="xl65">0.089</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Pujol 2002, No. 10-3-3N</td>
  <td class="xl65">29.9</td>
  <td class="xl65">410.9</td>
  <td class="xl65">453</td>
  <td class="xl65">453</td>
  <td class="xl65">152.4</td>
  <td class="xl65">304.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">133</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">2.25</td>
  <td class="xl65">0.096</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Pujol 2002, No. 10-3-3S</td>
  <td class="xl65">29.9</td>
  <td class="xl65">410.9</td>
  <td class="xl65">453</td>
  <td class="xl65">453</td>
  <td class="xl65">152.4</td>
  <td class="xl65">304.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">133</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">2.25</td>
  <td class="xl65">0.096</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Pujol 2002, No. 10-3-2.25N</td>
  <td class="xl65">27.4</td>
  <td class="xl65">410.9</td>
  <td class="xl65">453</td>
  <td class="xl65">453</td>
  <td class="xl65">152.4</td>
  <td class="xl65">304.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">133</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">2.25</td>
  <td class="xl65">0.104</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Pujol 2002, No. 10-3-2.25S</td>
  <td class="xl65">27.4</td>
  <td class="xl65">410.9</td>
  <td class="xl65">453</td>
  <td class="xl65">453</td>
  <td class="xl65">152.4</td>
  <td class="xl65">304.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">133</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">2.25</td>
  <td class="xl65">0.104</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Pujol 2002, No. 20-3-1.5N</td>
  <td class="xl65">27.4</td>
  <td class="xl65">410.9</td>
  <td class="xl65">453</td>
  <td class="xl65">453</td>
  <td class="xl65">152.4</td>
  <td class="xl65">304.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">267</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">2.25</td>
  <td class="xl65">0.21</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Pujol 2002, No. 20-3-1.5S</td>
  <td class="xl65">27.4</td>
  <td class="xl65">410.9</td>
  <td class="xl65">453</td>
  <td class="xl65">453</td>
  <td class="xl65">152.4</td>
  <td class="xl65">304.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">267</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">2.25</td>
  <td class="xl65">0.21</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Pujol 2002, No. 20-3-3N</td>
  <td class="xl65">36.4</td>
  <td class="xl65">410.9</td>
  <td class="xl65">453</td>
  <td class="xl65">453</td>
  <td class="xl65">152.4</td>
  <td class="xl65">304.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">267</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">2.25</td>
  <td class="xl65">0.158</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Pujol 2002, No. 20-3-3S</td>
  <td class="xl65">36.4</td>
  <td class="xl65">410.9</td>
  <td class="xl65">453</td>
  <td class="xl65">453</td>
  <td class="xl65">152.4</td>
  <td class="xl65">304.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">267</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">2.25</td>
  <td class="xl65">0.158</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Pujol 2002, No. 10-2-2.25N</td>
  <td class="xl65">34.9</td>
  <td class="xl65">410.9</td>
  <td class="xl65">453</td>
  <td class="xl65">453</td>
  <td class="xl65">152.4</td>
  <td class="xl65">304.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">133</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">2.25</td>
  <td class="xl65">0.082</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Pujol 2002, No. 10-2-2.25S</td>
  <td class="xl65">34.9</td>
  <td class="xl65">410.9</td>
  <td class="xl65">453</td>
  <td class="xl65">453</td>
  <td class="xl65">152.4</td>
  <td class="xl65">304.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">133</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">2.25</td>
  <td class="xl65">0.082</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Pujol 2002, No. 10-1-2.25N</td>
  <td class="xl65">36.5</td>
  <td class="xl65">410.9</td>
  <td class="xl65">453</td>
  <td class="xl65">453</td>
  <td class="xl65">152.4</td>
  <td class="xl65">304.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">133</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">2.25</td>
  <td class="xl65">0.078</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Pujol 2002, No. 10-1-2.25S</td>
  <td class="xl65">36.5</td>
  <td class="xl65">410.9</td>
  <td class="xl65">453</td>
  <td class="xl65">453</td>
  <td class="xl65">152.4</td>
  <td class="xl65">304.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">685.8</td>
  <td class="xl65">133</td>
  <td class="xl65">0.0245</td>
  <td class="xl65">0</td>
  <td class="xl65">2.25</td>
  <td class="xl65">0.078</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Bechtoula, Kono, Arai and
  Watanabe, 2002, D1N30</td>
  <td class="xl65">37.6</td>
  <td class="xl65">485</td>
  <td class="xl65">461</td>
  <td class="xl65">461</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">625</td>
  <td class="xl65">625</td>
  <td class="xl65">705</td>
  <td class="xl65">0.0243</td>
  <td class="xl65">0</td>
  <td class="xl65">2.5</td>
  <td class="xl65">0.3</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Bechtoula, Kono, Arai and
  Watanabe, 2002, D1N60</td>
  <td class="xl65">37.6</td>
  <td class="xl65">485</td>
  <td class="xl65">461</td>
  <td class="xl65">461</td>
  <td class="xl65">250</td>
  <td class="xl65">250</td>
  <td class="xl65">625</td>
  <td class="xl65">625</td>
  <td class="xl65">1410</td>
  <td class="xl65">0.0243</td>
  <td class="xl65">0</td>
  <td class="xl65">2.5</td>
  <td class="xl65">0.6</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Bechtoula, Kono, Arai and
  Watanabe, 2002, L1D60</td>
  <td class="xl65">39.2</td>
  <td class="xl65">524</td>
  <td class="xl65">388</td>
  <td class="xl65">388</td>
  <td class="xl65">600</td>
  <td class="xl65">600</td>
  <td class="xl65">1200</td>
  <td class="xl65">1200</td>
  <td class="xl65">8000</td>
  <td class="xl65">0.0169</td>
  <td class="xl65">0</td>
  <td class="xl65">2</td>
  <td class="xl65">0.567</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Bechtoula, Kono, Arai and
  Watanabe, 2002, L1N60</td>
  <td class="xl65">39.2</td>
  <td class="xl65">524</td>
  <td class="xl65">388</td>
  <td class="xl65">388</td>
  <td class="xl65">600</td>
  <td class="xl65">600</td>
  <td class="xl65">1200</td>
  <td class="xl65">1200</td>
  <td class="xl65">8000</td>
  <td class="xl65">0.0169</td>
  <td class="xl65">0</td>
  <td class="xl65">2</td>
  <td class="xl65">0.567</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Bechtoula, Kono, Arai and
  Watanabe, 2002, L1N6B</td>
  <td class="xl65">32.2</td>
  <td class="xl65">524</td>
  <td class="xl65">388</td>
  <td class="xl65">388</td>
  <td class="xl65">560</td>
  <td class="xl65">560</td>
  <td class="xl65">1200</td>
  <td class="xl65">1200</td>
  <td class="xl65">6000</td>
  <td class="xl65">0.0194</td>
  <td class="xl65">0</td>
  <td class="xl65">2.14</td>
  <td class="xl65">0.594</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Takemura and Kawashima, 1997,
  Test 1 (JSCE-4)</td>
  <td class="xl65">35.9</td>
  <td class="xl65">368</td>
  <td class="xl65">363</td>
  <td class="xl65">363</td>
  <td class="xl65">400</td>
  <td class="xl65">400</td>
  <td class="xl65">1245</td>
  <td class="xl65">1245</td>
  <td class="xl65">157</td>
  <td class="xl65">0.0158</td>
  <td class="xl65">0</td>
  <td class="xl65">3.11</td>
  <td class="xl65">0.027</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Takemura and Kawashima, 1997,
  Test 2 (JSCE-5)</td>
  <td class="xl65">35.7</td>
  <td class="xl65">368</td>
  <td class="xl65">363</td>
  <td class="xl65">363</td>
  <td class="xl65">400</td>
  <td class="xl65">400</td>
  <td class="xl65">1245</td>
  <td class="xl65">1245</td>
  <td class="xl65">157</td>
  <td class="xl65">0.0158</td>
  <td class="xl65">0</td>
  <td class="xl65">3.11</td>
  <td class="xl65">0.027</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Takemura and Kawashima, 1997,
  Test 3 (JSCE-6)</td>
  <td class="xl65">34.3</td>
  <td class="xl65">368</td>
  <td class="xl65">363</td>
  <td class="xl65">363</td>
  <td class="xl65">400</td>
  <td class="xl65">400</td>
  <td class="xl65">1245</td>
  <td class="xl65">1245</td>
  <td class="xl65">157</td>
  <td class="xl65">0.0158</td>
  <td class="xl65">0</td>
  <td class="xl65">3.11</td>
  <td class="xl65">0.029</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Takemura and Kawashima, 1997,
  Test 4 (JSCE-7)</td>
  <td class="xl65">33.2</td>
  <td class="xl65">368</td>
  <td class="xl65">363</td>
  <td class="xl65">363</td>
  <td class="xl65">400</td>
  <td class="xl65">400</td>
  <td class="xl65">1245</td>
  <td class="xl65">1245</td>
  <td class="xl65">157</td>
  <td class="xl65">0.0158</td>
  <td class="xl65">0</td>
  <td class="xl65">3.11</td>
  <td class="xl65">0.03</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Takemura and Kawashima, 1997,
  Test 5 (JSCE-8)</td>
  <td class="xl65">36.8</td>
  <td class="xl65">368</td>
  <td class="xl65">363</td>
  <td class="xl65">363</td>
  <td class="xl65">400</td>
  <td class="xl65">400</td>
  <td class="xl65">1245</td>
  <td class="xl65">1245</td>
  <td class="xl65">157</td>
  <td class="xl65">0.0158</td>
  <td class="xl65">0</td>
  <td class="xl65">3.11</td>
  <td class="xl65">0.027</td>
  <td class="xl65">Flexure</td>
 </tr>
 <tr height="18" style="height:13.8pt">
  <td height="18" class="xl67" style="height:13.8pt">Takemura and Kawashima, 1997,
  Test 6 (JSCE-9)</td>
  <td class="xl65">35.9</td>
  <td class="xl65">368</td>
  <td class="xl65">363</td>
  <td class="xl65">363</td>
  <td class="xl65">400</td>
  <td class="xl65">400</td>
  <td class="xl65">1245</td>
  <td class="xl65">1245</td>
  <td class="xl65">157</td>
  <td class="xl65">0.0158</td>
  <td class="xl65">0</td>
  <td class="xl65">3.11</td>
  <td class="xl65">0.027</td>
  <td class="xl65">Flexure</td>
 </tr>
 <!--[if supportMisalignedColumns]-->
 <tr height="0" style="display:none">
  <td width="338" style="width:254pt"></td>
  <td width="66" style="width:50pt"></td>
  <td width="92" style="width:69pt"></td>
  <td width="110" style="width:83pt"></td>
  <td width="104" style="width:78pt"></td>
  <td width="48" style="width:36pt"></td>
  <td width="49" style="width:37pt"></td>
  <td width="110" style="width:83pt"></td>
  <td width="116" style="width:87pt"></td>
  <td width="41" style="width:31pt"></td>
  <td width="92" style="width:69pt"></td>
  <td width="99" style="width:74pt"></td>
  <td width="69" style="width:52pt"></td>
  <td width="47" style="width:35pt"></td>
  <td width="103" style="width:77pt"></td>
 </tr>
 <!--[endif]-->
</tbody></table>



