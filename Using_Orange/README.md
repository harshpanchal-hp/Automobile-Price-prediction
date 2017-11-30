<div id="2076747255240" class="normal" onclick="pybridge._select_item(this.id)">

<section class="section">

# File <span class="timestamp">Thu Nov 30 17, 17:49:19</span>

<div class="content">

## File

**File name:**

**Format:**

## Data

**Data instances:**

**Features:**

</div>

</section>

<div class="textwrapper"><textarea placeholder="Write a comment..." oninput="this.innerHTML = this.value;pybridge._add_comment(this.parentNode.parentNode.id, this.value);">Train Data</textarea></div>

</div>

<div id="2076835422856" class="normal" onclick="pybridge._select_item(this.id)">

<section class="section">

# Preprocess <span class="timestamp">Thu Nov 30 17, 17:49:48</span>

<div class="content">

## Settings

**Impute Missing Values:**

</div>

</section>

<div class="textwrapper"><textarea placeholder="Write a comment..." oninput="this.innerHTML = this.value;pybridge._add_comment(this.parentNode.parentNode.id, this.value);"></textarea></div>

</div>

<div id="2076935770472" class="normal" onclick="pybridge._select_item(this.id)">

<section class="section">

# SVM <span class="timestamp">Thu Nov 30 17, 18:51:10</span>

<div class="content">

**Name:**

## Model parameters

**SVM type:**

**Kernel:**

<sup>8.0</sup>

**Numerical tolerance:**

**Iteration limt:**

## Data

**Data instances:**

**Features:**

**Target:**

</div>

</section>

<div class="textwrapper"><textarea placeholder="Write a comment..." oninput="this.innerHTML = this.value;pybridge._add_comment(this.parentNode.parentNode.id, this.value);"></textarea></div>

</div>

<div id="2076935771336" class="normal" onclick="pybridge._select_item(this.id)">

<section class="section">

# Random Forest <span class="timestamp">Thu Nov 30 17, 18:51:20</span>

<div class="content">

**Name:**

## Model parameters

**Number of trees:**

**Maximal number of considered features:**

**Maximal tree depth:**

**Stop splitting nodes with maximum instances:**

## Data

**Data instances:**

**Features:**

**Target:**

</div>

</section>

<div class="textwrapper"><textarea placeholder="Write a comment..." oninput="this.innerHTML = this.value;pybridge._add_comment(this.parentNode.parentNode.id, this.value);"></textarea></div>

</div>

<div id="2076935771480" class="normal" onclick="pybridge._select_item(this.id)">

<section class="section">

# Linear Regression <span class="timestamp">Thu Nov 30 17, 18:51:24</span>

<div class="content">

**Name:**

## Model parameters

**Regularization:**

## Data

**Data instances:**

**Features:**

**Target:**

</div>

</section>

<div class="textwrapper"><textarea placeholder="Write a comment..." oninput="this.innerHTML = this.value;pybridge._add_comment(this.parentNode.parentNode.id, this.value);"></textarea></div>

</div>

<div id="2076933580264" class="normal" onclick="pybridge._select_item(this.id)">

<section class="section">

# Neural Network <span class="timestamp">Thu Nov 30 17, 18:51:27</span>

<div class="content">

**Name:**

## Model parameters

**Hidden layers:**

**Activation:**

**Solver:**

**Alpha:**

**Max iterations:**

## Data

**Data instances:**

**Features:**

**Target:**

</div>

</section>

<div class="textwrapper"><textarea placeholder="Write a comment..." oninput="this.innerHTML = this.value;pybridge._add_comment(this.parentNode.parentNode.id, this.value);"></textarea></div>

</div>

<div id="2076933579976" class="normal" onclick="pybridge._select_item(this.id)">

<section class="section">

# Test & Score <span class="timestamp">Thu Nov 30 17, 18:51:42</span>

<div class="content">

## Settings

**Sampling type:**

## Scores

<table>

<tbody>

<tr>

<th style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">Method</th>

<th style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">MSE</th>

<th style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">RMSE</th>

<th style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">MAE</th>

<th style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">R2</th>

</tr>

<tr>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">SVM</td>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">13670491.079</td>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">3697.363</td>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">2380.640</td>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">0.762</td>

</tr>

<tr>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">Random Forest</td>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">5030189.353</td>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">2242.808</td>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">1465.016</td>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">0.912</td>

</tr>

<tr>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">Neural Network</td>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">6128912.145</td>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">2475.664</td>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">1710.477</td>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">0.893</td>

</tr>

<tr>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">Linear Regression</td>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">6065739.506</td>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">2462.872</td>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">1669.303</td>

<td style="color:black;border:0;background:transparent;text-align:left;vertical-align:middle;">0.894</td>

</tr>

</tbody>

</table>

</div>

</section>

<div class="textwrapper"><textarea placeholder="Write a comment..." oninput="this.innerHTML = this.value;pybridge._add_comment(this.parentNode.parentNode.id, this.value);"></textarea></div>

</div>

<div id="2076968685640" class="normal" onclick="pybridge._select_item(this.id)">

<section class="section">

# Predictions <span class="timestamp">Thu Nov 30 17, 19:08:09</span>

<div class="content">

## Info

Data: 165 instances.  
Predictors: 4  
Task: Regression

## Data & Predictions

<table>

<tbody>

<tr>

<th>Linear Regression</th>

<th>Random Forest</th>

<th>SVM</th>

<th>Neural Network</th>

<th>price</th>

<th>symboling</th>

<th>make</th>

<th>fuel-type</th>

<th>aspiration</th>

<th>num-of-doors</th>

<th>body-style</th>

<th>drive-wheels</th>

<th>engine-location</th>

<th>wheel-base</th>

<th>length</th>

<th>width</th>

<th>height</th>

<th>curb-weight</th>

<th>engine-type</th>

<th>num-of-cylinders</th>

<th>engine-size</th>

<th>fuel-system</th>

<th>bore</th>

<th>stroke</th>

<th>compression-ratio</th>

<th>horsepower</th>

<th>peak-rpm</th>

<th>city-mpg</th>

<th>highway-mpg</th>

</tr>

<tr>

<th>15</th>

<td>5093.9</td>

<td>5537.1</td>

<td>5005.4</td>

<td>5133.7</td>

<td>5151.0</td>

<td>2.0</td>

<td>chevrolet</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>88.4</td>

<td>141.1</td>

<td>60.3</td>

<td>53.2</td>

<td>1488.0</td>

<td>l</td>

<td>three</td>

<td>61.0</td>

<td>2bbl</td>

<td>2.91</td>

<td>3.03</td>

<td>9.50</td>

<td>48.0</td>

<td>5100.0</td>

<td>47.0</td>

<td>53.0</td>

</tr>

<tr>

<th>124</th>

<td>5620.7</td>

<td>5899.9</td>

<td>5577.9</td>

<td>5323.9</td>

<td>5348.0</td>

<td>1.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>95.7</td>

<td>158.7</td>

<td>63.6</td>

<td>54.5</td>

<td>1985.0</td>

<td>ohc</td>

<td>four</td>

<td>92.0</td>

<td>2bbl</td>

<td>3.05</td>

<td>3.03</td>

<td>9.00</td>

<td>62.0</td>

<td>4800.0</td>

<td>35.0</td>

<td>39.0</td>

</tr>

<tr>

<th>98</th>

<td>6292.2</td>

<td>5661.8</td>

<td>7036.5</td>

<td>5425.4</td>

<td>5572.0</td>

<td>1.0</td>

<td>plymouth</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>157.3</td>

<td>63.8</td>

<td>50.8</td>

<td>1918.0</td>

<td>ohc</td>

<td>four</td>

<td>90.0</td>

<td>2bbl</td>

<td>2.97</td>

<td>3.23</td>

<td>9.40</td>

<td>68.0</td>

<td>5500.0</td>

<td>37.0</td>

<td>41.0</td>

</tr>

<tr>

<th>27</th>

<td>5920.7</td>

<td>5742.5</td>

<td>6746.5</td>

<td>5596.7</td>

<td>5399.0</td>

<td>1.0</td>

<td>honda</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>150.0</td>

<td>64.0</td>

<td>52.6</td>

<td>1837.0</td>

<td>ohc</td>

<td>four</td>

<td>79.0</td>

<td>1bbl</td>

<td>2.91</td>

<td>3.07</td>

<td>10.10</td>

<td>60.0</td>

<td>5500.0</td>

<td>38.0</td>

<td>42.0</td>

</tr>

<tr>

<th>125</th>

<td>6052.4</td>

<td>6413.4</td>

<td>5786.3</td>

<td>5596.8</td>

<td>6338.0</td>

<td>1.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>95.7</td>

<td>158.7</td>

<td>63.6</td>

<td>54.5</td>

<td>2040.0</td>

<td>ohc</td>

<td>four</td>

<td>92.0</td>

<td>2bbl</td>

<td>3.05</td>

<td>3.03</td>

<td>9.00</td>

<td>62.0</td>

<td>4800.0</td>

<td>31.0</td>

<td>38.0</td>

</tr>

<tr>

<th>18</th>

<td>5949.2</td>

<td>5760.6</td>

<td>7001.2</td>

<td>5638.8</td>

<td>5572.0</td>

<td>1.0</td>

<td>dodge</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>157.3</td>

<td>63.8</td>

<td>50.8</td>

<td>1876.0</td>

<td>ohc</td>

<td>four</td>

<td>90.0</td>

<td>2bbl</td>

<td>2.97</td>

<td>3.23</td>

<td>9.41</td>

<td>68.0</td>

<td>5500.0</td>

<td>37.0</td>

<td>41.0</td>

</tr>

<tr>

<th>60</th>

<td>5883.4</td>

<td>5624.0</td>

<td>6983.9</td>

<td>5748.9</td>

<td>5389.0</td>

<td>2.0</td>

<td>mitsubishi</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>157.3</td>

<td>64.4</td>

<td>50.8</td>

<td>1918.0</td>

<td>ohc</td>

<td>four</td>

<td>92.0</td>

<td>2bbl</td>

<td>2.97</td>

<td>3.23</td>

<td>9.40</td>

<td>68.0</td>

<td>5500.0</td>

<td>37.0</td>

<td>41.0</td>

</tr>

<tr>

<th>43</th>

<td>5362.1</td>

<td>5629.8</td>

<td>7469.7</td>

<td>5878.4</td>

<td>5195.0</td>

<td>1.0</td>

<td>mazda</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.1</td>

<td>159.1</td>

<td>64.2</td>

<td>54.1</td>

<td>1890.0</td>

<td>ohc</td>

<td>four</td>

<td>91.0</td>

<td>2bbl</td>

<td>3.03</td>

<td>3.15</td>

<td>9.00</td>

<td>68.0</td>

<td>5000.0</td>

<td>30.0</td>

<td>31.0</td>

</tr>

<tr>

<th>19</th>

<td>5686.9</td>

<td>6157.8</td>

<td>7290.1</td>

<td>5934.4</td>

<td>6377.0</td>

<td>1.0</td>

<td>dodge</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>157.3</td>

<td>63.8</td>

<td>50.8</td>

<td>1876.0</td>

<td>ohc</td>

<td>four</td>

<td>90.0</td>

<td>2bbl</td>

<td>2.97</td>

<td>3.23</td>

<td>9.40</td>

<td>68.0</td>

<td>5500.0</td>

<td>31.0</td>

<td>38.0</td>

</tr>

<tr>

<th>112</th>

<td>6229.5</td>

<td>5816.0</td>

<td>7357.3</td>

<td>5984.3</td>

<td>5118.0</td>

<td>2.0</td>

<td>subaru</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>156.9</td>

<td>63.4</td>

<td>53.7</td>

<td>2050.0</td>

<td>ohcf</td>

<td>four</td>

<td>97.0</td>

<td>2bbl</td>

<td>3.62</td>

<td>2.36</td>

<td>9.00</td>

<td>69.0</td>

<td>4900.0</td>

<td>31.0</td>

<td>36.0</td>

</tr>

<tr>

<th>61</th>

<td>5817.6</td>

<td>6260.3</td>

<td>7295.8</td>

<td>6108.8</td>

<td>6189.0</td>

<td>2.0</td>

<td>mitsubishi</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>157.3</td>

<td>64.4</td>

<td>50.8</td>

<td>1944.0</td>

<td>ohc</td>

<td>four</td>

<td>92.0</td>

<td>2bbl</td>

<td>2.97</td>

<td>3.23</td>

<td>9.40</td>

<td>68.0</td>

<td>5500.0</td>

<td>31.0</td>

<td>38.0</td>

</tr>

<tr>

<th>62</th>

<td>6286.0</td>

<td>6516.2</td>

<td>7347.8</td>

<td>6149.2</td>

<td>6669.0</td>

<td>2.0</td>

<td>mitsubishi</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>157.3</td>

<td>64.4</td>

<td>50.8</td>

<td>2004.0</td>

<td>ohc</td>

<td>four</td>

<td>92.0</td>

<td>2bbl</td>

<td>2.97</td>

<td>3.23</td>

<td>9.40</td>

<td>68.0</td>

<td>5500.0</td>

<td>31.0</td>

<td>38.0</td>

</tr>

<tr>

<th>73</th>

<td>5402.7</td>

<td>6318.6</td>

<td>8743.3</td>

<td>6203.0</td>

<td>5499.0</td>

<td>1.0</td>

<td>nissan</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>94.5</td>

<td>165.3</td>

<td>63.8</td>

<td>54.5</td>

<td>1889.0</td>

<td>ohc</td>

<td>four</td>

<td>97.0</td>

<td>2bbl</td>

<td>3.15</td>

<td>3.29</td>

<td>9.40</td>

<td>69.0</td>

<td>5200.0</td>

<td>31.0</td>

<td>37.0</td>

</tr>

<tr>

<th>75</th>

<td>5629.0</td>

<td>6735.7</td>

<td>8769.5</td>

<td>6227.7</td>

<td>6649.0</td>

<td>1.0</td>

<td>nissan</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>94.5</td>

<td>165.3</td>

<td>63.8</td>

<td>54.5</td>

<td>1918.0</td>

<td>ohc</td>

<td>four</td>

<td>97.0</td>

<td>2bbl</td>

<td>3.15</td>

<td>3.29</td>

<td>9.40</td>

<td>69.0</td>

<td>5200.0</td>

<td>31.0</td>

<td>37.0</td>

</tr>

<tr>

<th>44</th>

<td>6664.6</td>

<td>6184.3</td>

<td>7217.5</td>

<td>6274.5</td>

<td>6095.0</td>

<td>1.0</td>

<td>mazda</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.1</td>

<td>159.1</td>

<td>64.2</td>

<td>54.1</td>

<td>1900.0</td>

<td>ohc</td>

<td>four</td>

<td>91.0</td>

<td>2bbl</td>

<td>3.03</td>

<td>3.15</td>

<td>9.00</td>

<td>68.0</td>

<td>5000.0</td>

<td>31.0</td>

<td>38.0</td>

</tr>

<tr>

<th>45</th>

<td>6703.7</td>

<td>6304.8</td>

<td>7221.8</td>

<td>6280.5</td>

<td>6795.0</td>

<td>1.0</td>

<td>mazda</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.1</td>

<td>159.1</td>

<td>64.2</td>

<td>54.1</td>

<td>1905.0</td>

<td>ohc</td>

<td>four</td>

<td>91.0</td>

<td>2bbl</td>

<td>3.03</td>

<td>3.15</td>

<td>9.00</td>

<td>68.0</td>

<td>5000.0</td>

<td>31.0</td>

<td>38.0</td>

</tr>

<tr>

<th>113</th>

<td>5321.8</td>

<td>7051.6</td>

<td>7539.9</td>

<td>6308.9</td>

<td>7053.0</td>

<td>2.0</td>

<td>subaru</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>157.9</td>

<td>63.6</td>

<td>53.7</td>

<td>2120.0</td>

<td>ohcf</td>

<td>four</td>

<td>108.0</td>

<td>2bbl</td>

<td>3.62</td>

<td>2.64</td>

<td>8.70</td>

<td>73.0</td>

<td>4400.0</td>

<td>26.0</td>

<td>31.0</td>

</tr>

<tr>

<th>100</th>

<td>6667.4</td>

<td>6340.5</td>

<td>7567.1</td>

<td>6387.7</td>

<td>6229.0</td>

<td>1.0</td>

<td>plymouth</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>157.3</td>

<td>63.8</td>

<td>50.6</td>

<td>1967.0</td>

<td>ohc</td>

<td>four</td>

<td>90.0</td>

<td>2bbl</td>

<td>2.97</td>

<td>3.23</td>

<td>9.40</td>

<td>68.0</td>

<td>5500.0</td>

<td>31.0</td>

<td>38.0</td>

</tr>

<tr>

<th>16</th>

<td>6193.6</td>

<td>6240.5</td>

<td>6878.9</td>

<td>6387.8</td>

<td>6295.0</td>

<td>1.0</td>

<td>chevrolet</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>94.5</td>

<td>155.9</td>

<td>63.6</td>

<td>52.0</td>

<td>1874.0</td>

<td>ohc</td>

<td>four</td>

<td>90.0</td>

<td>2bbl</td>

<td>3.03</td>

<td>3.11</td>

<td>9.60</td>

<td>70.0</td>

<td>5400.0</td>

<td>38.0</td>

<td>43.0</td>

</tr>

<tr>

<th>126</th>

<td>6041.0</td>

<td>6437.9</td>

<td>6069.5</td>

<td>6504.0</td>

<td>6488.0</td>

<td>1.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>95.7</td>

<td>158.7</td>

<td>63.6</td>

<td>54.5</td>

<td>2015.0</td>

<td>ohc</td>

<td>four</td>

<td>92.0</td>

<td>2bbl</td>

<td>3.05</td>

<td>3.03</td>

<td>9.00</td>

<td>62.0</td>

<td>4800.0</td>

<td>31.0</td>

<td>38.0</td>

</tr>

<tr>

<th>127</th>

<td>4788.6</td>

<td>7221.2</td>

<td>8489.7</td>

<td>6560.2</td>

<td>6918.0</td>

<td>0.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>wagon</td>

<td>fwd</td>

<td>front</td>

<td>95.7</td>

<td>169.7</td>

<td>63.6</td>

<td>59.1</td>

<td>2280.0</td>

<td>ohc</td>

<td>four</td>

<td>92.0</td>

<td>2bbl</td>

<td>3.05</td>

<td>3.03</td>

<td>9.00</td>

<td>62.0</td>

<td>4800.0</td>

<td>31.0</td>

<td>37.0</td>

</tr>

<tr>

<th>21</th>

<td>6658.6</td>

<td>6374.1</td>

<td>7567.5</td>

<td>6751.8</td>

<td>6229.0</td>

<td>1.0</td>

<td>dodge</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>157.3</td>

<td>63.8</td>

<td>50.6</td>

<td>1967.0</td>

<td>ohc</td>

<td>four</td>

<td>90.0</td>

<td>2bbl</td>

<td>2.97</td>

<td>3.23</td>

<td>9.40</td>

<td>68.0</td>

<td>5500.0</td>

<td>31.0</td>

<td>38.0</td>

</tr>

<tr>

<th>25</th>

<td>4324.3</td>

<td>6275.7</td>

<td>4903.8</td>

<td>6753.8</td>

<td>6479.0</td>

<td>2.0</td>

<td>honda</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>86.6</td>

<td>144.6</td>

<td>63.9</td>

<td>50.8</td>

<td>1713.0</td>

<td>ohc</td>

<td>four</td>

<td>92.0</td>

<td>1bbl</td>

<td>2.91</td>

<td>3.41</td>

<td>9.60</td>

<td>58.0</td>

<td>4800.0</td>

<td>49.0</td>

<td>54.0</td>

</tr>

<tr>

<th>28</th>

<td>8101.8</td>

<td>6533.9</td>

<td>8018.6</td>

<td>6865.2</td>

<td>6529.0</td>

<td>1.0</td>

<td>honda</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>150.0</td>

<td>64.0</td>

<td>52.6</td>

<td>1940.0</td>

<td>ohc</td>

<td>four</td>

<td>92.0</td>

<td>1bbl</td>

<td>2.91</td>

<td>3.41</td>

<td>9.20</td>

<td>76.0</td>

<td>6000.0</td>

<td>30.0</td>

<td>34.0</td>

</tr>

<tr>

<th>29</th>

<td>8226.7</td>

<td>6697.9</td>

<td>8032.6</td>

<td>6878.4</td>

<td>7129.0</td>

<td>1.0</td>

<td>honda</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>150.0</td>

<td>64.0</td>

<td>52.6</td>

<td>1956.0</td>

<td>ohc</td>

<td>four</td>

<td>92.0</td>

<td>1bbl</td>

<td>2.91</td>

<td>3.41</td>

<td>9.20</td>

<td>76.0</td>

<td>6000.0</td>

<td>30.0</td>

<td>34.0</td>

</tr>

<tr>

<th>26</th>

<td>6757.1</td>

<td>6702.5</td>

<td>7095.7</td>

<td>6939.8</td>

<td>6855.0</td>

<td>2.0</td>

<td>honda</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>86.6</td>

<td>144.6</td>

<td>63.9</td>

<td>50.8</td>

<td>1819.0</td>

<td>ohc</td>

<td>four</td>

<td>92.0</td>

<td>1bbl</td>

<td>2.91</td>

<td>3.41</td>

<td>9.20</td>

<td>76.0</td>

<td>6000.0</td>

<td>31.0</td>

<td>38.0</td>

</tr>

<tr>

<th>74</th>

<td>7558.5</td>

<td>7207.5</td>

<td>8966.7</td>

<td>6947.4</td>

<td>7099.0</td>

<td>1.0</td>

<td>nissan</td>

<td>diesel</td>

<td>std</td>

<td>two</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>94.5</td>

<td>165.3</td>

<td>63.8</td>

<td>54.5</td>

<td>2017.0</td>

<td>ohc</td>

<td>four</td>

<td>103.0</td>

<td>idi</td>

<td>2.99</td>

<td>3.47</td>

<td>21.90</td>

<td>55.0</td>

<td>4800.0</td>

<td>45.0</td>

<td>50.0</td>

</tr>

<tr>

<th>38</th>

<td>6800.0</td>

<td>7614.5</td>

<td>10323.6</td>

<td>6971.8</td>

<td>6785.0</td>

<td>0.0</td>

<td>isuzu</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>rwd</td>

<td>front</td>

<td>94.3</td>

<td>170.7</td>

<td>61.8</td>

<td>53.5</td>

<td>2337.0</td>

<td>ohc</td>

<td>four</td>

<td>111.0</td>

<td>2bbl</td>

<td>3.31</td>

<td>3.23</td>

<td>8.50</td>

<td>78.0</td>

<td>4800.0</td>

<td>24.0</td>

<td>29.0</td>

</tr>

<tr>

<th>17</th>

<td>6780.5</td>

<td>6433.1</td>

<td>8709.7</td>

<td>6979.1</td>

<td>6575.0</td>

<td>0.0</td>

<td>chevrolet</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>94.5</td>

<td>158.8</td>

<td>63.6</td>

<td>52.0</td>

<td>1909.0</td>

<td>ohc</td>

<td>four</td>

<td>90.0</td>

<td>2bbl</td>

<td>3.03</td>

<td>3.11</td>

<td>9.60</td>

<td>70.0</td>

<td>5400.0</td>

<td>38.0</td>

<td>43.0</td>

</tr>

<tr>

<th>46</th>

<td>6583.7</td>

<td>6624.0</td>

<td>9021.3</td>

<td>7049.5</td>

<td>6695.0</td>

<td>1.0</td>

<td>mazda</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>93.1</td>

<td>166.8</td>

<td>64.2</td>

<td>54.1</td>

<td>1945.0</td>

<td>ohc</td>

<td>four</td>

<td>91.0</td>

<td>2bbl</td>

<td>3.03</td>

<td>3.15</td>

<td>9.00</td>

<td>68.0</td>

<td>5000.0</td>

<td>31.0</td>

<td>38.0</td>

</tr>

<tr>

<th>22</th>

<td>7423.5</td>

<td>7117.0</td>

<td>8940.3</td>

<td>7052.4</td>

<td>7609.0</td>

<td>1.0</td>

<td>dodge</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>157.3</td>

<td>63.8</td>

<td>50.6</td>

<td>1989.0</td>

<td>ohc</td>

<td>four</td>

<td>90.0</td>

<td>2bbl</td>

<td>2.97</td>

<td>3.23</td>

<td>9.40</td>

<td>68.0</td>

<td>5500.0</td>

<td>31.0</td>

<td>38.0</td>

</tr>

<tr>

<th>47</th>

<td>6528.4</td>

<td>6995.5</td>

<td>9052.7</td>

<td>7067.2</td>

<td>7395.0</td>

<td>1.0</td>

<td>mazda</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>93.1</td>

<td>166.8</td>

<td>64.2</td>

<td>54.1</td>

<td>1950.0</td>

<td>ohc</td>

<td>four</td>

<td>91.0</td>

<td>2bbl</td>

<td>3.08</td>

<td>3.15</td>

<td>9.00</td>

<td>68.0</td>

<td>5000.0</td>

<td>31.0</td>

<td>38.0</td>

</tr>

<tr>

<th>120</th>

<td>8247.4</td>

<td>7722.2</td>

<td>10659.9</td>

<td>7139.5</td>

<td>7463.0</td>

<td>0.0</td>

<td>subaru</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>wagon</td>

<td>fwd</td>

<td>front</td>

<td>97.0</td>

<td>173.5</td>

<td>65.4</td>

<td>53.0</td>

<td>2290.0</td>

<td>ohcf</td>

<td>four</td>

<td>108.0</td>

<td>2bbl</td>

<td>3.62</td>

<td>2.64</td>

<td>9.00</td>

<td>82.0</td>

<td>4800.0</td>

<td>28.0</td>

<td>32.0</td>

</tr>

<tr>

<th>130</th>

<td>7016.5</td>

<td>7125.0</td>

<td>8259.5</td>

<td>7247.4</td>

<td>6938.0</td>

<td>0.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>95.7</td>

<td>166.3</td>

<td>64.4</td>

<td>53.0</td>

<td>2081.0</td>

<td>ohc</td>

<td>four</td>

<td>98.0</td>

<td>2bbl</td>

<td>3.19</td>

<td>3.03</td>

<td>9.00</td>

<td>70.0</td>

<td>4800.0</td>

<td>30.0</td>

<td>37.0</td>

</tr>

<tr>

<th>101</th>

<td>5784.4</td>

<td>6942.3</td>

<td>9212.9</td>

<td>7264.1</td>

<td>6692.0</td>

<td>1.0</td>

<td>plymouth</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>167.3</td>

<td>63.8</td>

<td>50.8</td>

<td>1989.0</td>

<td>ohc</td>

<td>four</td>

<td>90.0</td>

<td>2bbl</td>

<td>2.97</td>

<td>3.23</td>

<td>9.40</td>

<td>68.0</td>

<td>5500.0</td>

<td>31.0</td>

<td>38.0</td>

</tr>

<tr>

<th>134</th>

<td>8565.1</td>

<td>7380.3</td>

<td>7684.8</td>

<td>7279.9</td>

<td>7738.0</td>

<td>0.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>95.7</td>

<td>166.3</td>

<td>64.4</td>

<td>53.0</td>

<td>2094.0</td>

<td>ohc</td>

<td>four</td>

<td>98.0</td>

<td>2bbl</td>

<td>3.19</td>

<td>3.03</td>

<td>9.00</td>

<td>70.0</td>

<td>4800.0</td>

<td>38.0</td>

<td>47.0</td>

</tr>

<tr>

<th>31</th>

<td>6937.5</td>

<td>7302.4</td>

<td>10297.8</td>

<td>7356.6</td>

<td>7295.0</td>

<td>0.0</td>

<td>honda</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>wagon</td>

<td>fwd</td>

<td>front</td>

<td>96.5</td>

<td>157.1</td>

<td>63.9</td>

<td>58.3</td>

<td>2024.0</td>

<td>ohc</td>

<td>four</td>

<td>92.0</td>

<td>1bbl</td>

<td>2.92</td>

<td>3.41</td>

<td>9.20</td>

<td>76.0</td>

<td>6000.0</td>

<td>30.0</td>

<td>34.0</td>

</tr>

<tr>

<th>102</th>

<td>7708.0</td>

<td>7538.9</td>

<td>9450.4</td>

<td>7427.3</td>

<td>7609.0</td>

<td>1.0</td>

<td>plymouth</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>167.3</td>

<td>63.8</td>

<td>50.8</td>

<td>2191.0</td>

<td>ohc</td>

<td>four</td>

<td>98.0</td>

<td>2bbl</td>

<td>2.97</td>

<td>3.23</td>

<td>9.40</td>

<td>68.0</td>

<td>5500.0</td>

<td>31.0</td>

<td>38.0</td>

</tr>

<tr>

<th>115</th>

<td>8231.6</td>

<td>7350.0</td>

<td>10209.1</td>

<td>7463.3</td>

<td>7126.0</td>

<td>0.0</td>

<td>subaru</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>97.2</td>

<td>172.0</td>

<td>65.4</td>

<td>52.5</td>

<td>2145.0</td>

<td>ohcf</td>

<td>four</td>

<td>108.0</td>

<td>2bbl</td>

<td>3.62</td>

<td>2.64</td>

<td>9.50</td>

<td>82.0</td>

<td>4800.0</td>

<td>32.0</td>

<td>37.0</td>

</tr>

<tr>

<th>114</th>

<td>6450.7</td>

<td>7466.7</td>

<td>7902.1</td>

<td>7466.9</td>

<td>7603.0</td>

<td>2.0</td>

<td>subaru</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>4wd</td>

<td>front</td>

<td>93.3</td>

<td>157.3</td>

<td>63.8</td>

<td>55.7</td>

<td>2240.0</td>

<td>ohcf</td>

<td>four</td>

<td>108.0</td>

<td>2bbl</td>

<td>3.62</td>

<td>2.64</td>

<td>8.70</td>

<td>73.0</td>

<td>4400.0</td>

<td>26.0</td>

<td>31.0</td>

</tr>

<tr>

<th>132</th>

<td>6871.9</td>

<td>7887.7</td>

<td>9778.3</td>

<td>7500.1</td>

<td>7898.0</td>

<td>0.0</td>

<td>toyota</td>

<td>diesel</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>95.7</td>

<td>166.3</td>

<td>64.4</td>

<td>53.0</td>

<td>2275.0</td>

<td>ohc</td>

<td>four</td>

<td>110.0</td>

<td>idi</td>

<td>3.27</td>

<td>3.35</td>

<td>22.50</td>

<td>56.0</td>

<td>4500.0</td>

<td>34.0</td>

<td>36.0</td>

</tr>

<tr>

<th>131</th>

<td>6719.6</td>

<td>7159.3</td>

<td>6799.2</td>

<td>7509.7</td>

<td>7198.0</td>

<td>0.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>95.7</td>

<td>166.3</td>

<td>64.4</td>

<td>52.8</td>

<td>2109.0</td>

<td>ohc</td>

<td>four</td>

<td>98.0</td>

<td>2bbl</td>

<td>3.19</td>

<td>3.03</td>

<td>9.00</td>

<td>70.0</td>

<td>4800.0</td>

<td>30.0</td>

<td>37.0</td>

</tr>

<tr>

<th>30</th>

<td>7594.8</td>

<td>7210.1</td>

<td>10325.2</td>

<td>7521.1</td>

<td>7295.0</td>

<td>0.0</td>

<td>honda</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>96.5</td>

<td>163.4</td>

<td>64.0</td>

<td>54.5</td>

<td>2010.0</td>

<td>ohc</td>

<td>four</td>

<td>92.0</td>

<td>1bbl</td>

<td>2.91</td>

<td>3.41</td>

<td>9.20</td>

<td>76.0</td>

<td>6000.0</td>

<td>30.0</td>

<td>34.0</td>

</tr>

<tr>

<th>148</th>

<td>8934.1</td>

<td>7760.9</td>

<td>10414.5</td>

<td>7530.4</td>

<td>7775.0</td>

<td>2.0</td>

<td>volkswagen</td>

<td>diesel</td>

<td>std</td>

<td>two</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>97.3</td>

<td>171.7</td>

<td>65.5</td>

<td>55.7</td>

<td>2261.0</td>

<td>ohc</td>

<td>four</td>

<td>97.0</td>

<td>idi</td>

<td>3.01</td>

<td>3.40</td>

<td>23.00</td>

<td>52.0</td>

<td>4800.0</td>

<td>37.0</td>

<td>46.0</td>

</tr>

<tr>

<th>63</th>

<td>7349.2</td>

<td>8115.3</td>

<td>8966.5</td>

<td>7587.9</td>

<td>7689.0</td>

<td>1.0</td>

<td>mitsubishi</td>

<td>gas</td>

<td>turbo</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.0</td>

<td>157.3</td>

<td>63.8</td>

<td>50.8</td>

<td>2145.0</td>

<td>ohc</td>

<td>four</td>

<td>98.0</td>

<td>spdi</td>

<td>3.03</td>

<td>3.39</td>

<td>7.60</td>

<td>102.0</td>

<td>5500.0</td>

<td>24.0</td>

<td>30.0</td>

</tr>

<tr>

<th>99</th>

<td>8275.4</td>

<td>8157.0</td>

<td>8973.3</td>

<td>7726.3</td>

<td>7957.0</td>

<td>1.0</td>

<td>plymouth</td>

<td>gas</td>

<td>turbo</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>157.3</td>

<td>63.8</td>

<td>50.8</td>

<td>2128.0</td>

<td>ohc</td>

<td>four</td>

<td>98.0</td>

<td>spdi</td>

<td>3.03</td>

<td>3.39</td>

<td>7.60</td>

<td>102.0</td>

<td>5500.0</td>

<td>24.0</td>

<td>30.0</td>

</tr>

<tr>

<th>133</th>

<td>8169.0</td>

<td>7813.6</td>

<td>7857.7</td>

<td>7778.0</td>

<td>7788.0</td>

<td>0.0</td>

<td>toyota</td>

<td>diesel</td>

<td>std</td>

<td>four</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>95.7</td>

<td>166.3</td>

<td>64.4</td>

<td>52.8</td>

<td>2275.0</td>

<td>ohc</td>

<td>four</td>

<td>110.0</td>

<td>idi</td>

<td>3.27</td>

<td>3.35</td>

<td>22.50</td>

<td>56.0</td>

<td>4500.0</td>

<td>38.0</td>

<td>47.0</td>

</tr>

<tr>

<th>69</th>

<td>8098.2</td>

<td>7846.5</td>

<td>10880.1</td>

<td>7781.3</td>

<td>6989.0</td>

<td>1.0</td>

<td>mitsubishi</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>96.3</td>

<td>172.4</td>

<td>65.4</td>

<td>51.6</td>

<td>2365.0</td>

<td>ohc</td>

<td>four</td>

<td>122.0</td>

<td>2bbl</td>

<td>3.35</td>

<td>3.46</td>

<td>8.50</td>

<td>88.0</td>

<td>5000.0</td>

<td>25.0</td>

<td>32.0</td>

</tr>

<tr>

<th>122</th>

<td>9077.6</td>

<td>8428.6</td>

<td>11362.7</td>

<td>7801.5</td>

<td>8013.0</td>

<td>0.0</td>

<td>subaru</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>wagon</td>

<td>4wd</td>

<td>front</td>

<td>96.9</td>

<td>173.6</td>

<td>65.4</td>

<td>54.9</td>

<td>2420.0</td>

<td>ohcf</td>

<td>four</td>

<td>108.0</td>

<td>2bbl</td>

<td>3.62</td>

<td>2.64</td>

<td>9.00</td>

<td>82.0</td>

<td>4800.0</td>

<td>23.0</td>

<td>29.0</td>

</tr>

<tr>

<th>128</th>

<td>5063.1</td>

<td>7911.3</td>

<td>8947.0</td>

<td>7803.3</td>

<td>7898.0</td>

<td>0.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>wagon</td>

<td>4wd</td>

<td>front</td>

<td>95.7</td>

<td>169.7</td>

<td>63.6</td>

<td>59.1</td>

<td>2290.0</td>

<td>ohc</td>

<td>four</td>

<td>92.0</td>

<td>2bbl</td>

<td>3.05</td>

<td>3.03</td>

<td>9.00</td>

<td>62.0</td>

<td>4800.0</td>

<td>27.0</td>

<td>32.0</td>

</tr>

<tr>

<th>76</th>

<td>6226.5</td>

<td>7443.0</td>

<td>8909.4</td>

<td>7804.3</td>

<td>7499.0</td>

<td>1.0</td>

<td>nissan</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>94.5</td>

<td>165.3</td>

<td>63.8</td>

<td>54.5</td>

<td>1971.0</td>

<td>ohc</td>

<td>four</td>

<td>97.0</td>

<td>2bbl</td>

<td>3.15</td>

<td>3.29</td>

<td>9.40</td>

<td>69.0</td>

<td>5200.0</td>

<td>31.0</td>

<td>37.0</td>

</tr>

<tr>

<th>20</th>

<td>8669.7</td>

<td>7997.4</td>

<td>8815.8</td>

<td>7819.4</td>

<td>7957.0</td>

<td>1.0</td>

<td>dodge</td>

<td>gas</td>

<td>turbo</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>157.3</td>

<td>63.8</td>

<td>50.8</td>

<td>2128.0</td>

<td>ohc</td>

<td>four</td>

<td>98.0</td>

<td>mpfi</td>

<td>3.03</td>

<td>3.39</td>

<td>7.60</td>

<td>102.0</td>

<td>5500.0</td>

<td>24.0</td>

<td>30.0</td>

</tr>

<tr>

<th>70</th>

<td>8410.4</td>

<td>8203.9</td>

<td>10918.5</td>

<td>7861.5</td>

<td>8189.0</td>

<td>1.0</td>

<td>mitsubishi</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>96.3</td>

<td>172.4</td>

<td>65.4</td>

<td>51.6</td>

<td>2405.0</td>

<td>ohc</td>

<td>four</td>

<td>122.0</td>

<td>2bbl</td>

<td>3.35</td>

<td>3.46</td>

<td>8.50</td>

<td>88.0</td>

<td>5000.0</td>

<td>25.0</td>

<td>32.0</td>

</tr>

<tr>

<th>116</th>

<td>7067.5</td>

<td>7528.9</td>

<td>10206.5</td>

<td>7866.0</td>

<td>7775.0</td>

<td>0.0</td>

<td>subaru</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>97.2</td>

<td>172.0</td>

<td>65.4</td>

<td>52.5</td>

<td>2190.0</td>

<td>ohcf</td>

<td>four</td>

<td>108.0</td>

<td>2bbl</td>

<td>3.62</td>

<td>2.64</td>

<td>9.50</td>

<td>82.0</td>

<td>4400.0</td>

<td>28.0</td>

<td>33.0</td>

</tr>

<tr>

<th>150</th>

<td>9141.2</td>

<td>7824.6</td>

<td>10631.8</td>

<td>8002.7</td>

<td>7995.0</td>

<td>2.0</td>

<td>volkswagen</td>

<td>diesel</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>97.3</td>

<td>171.7</td>

<td>65.5</td>

<td>55.7</td>

<td>2264.0</td>

<td>ohc</td>

<td>four</td>

<td>97.0</td>

<td>idi</td>

<td>3.01</td>

<td>3.40</td>

<td>23.00</td>

<td>52.0</td>

<td>4800.0</td>

<td>37.0</td>

<td>46.0</td>

</tr>

<tr>

<th>77</th>

<td>6149.5</td>

<td>7776.6</td>

<td>9012.1</td>

<td>8120.4</td>

<td>7999.0</td>

<td>1.0</td>

<td>nissan</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>wagon</td>

<td>fwd</td>

<td>front</td>

<td>94.5</td>

<td>170.2</td>

<td>63.8</td>

<td>53.5</td>

<td>2037.0</td>

<td>ohc</td>

<td>four</td>

<td>97.0</td>

<td>2bbl</td>

<td>3.15</td>

<td>3.29</td>

<td>9.40</td>

<td>69.0</td>

<td>5200.0</td>

<td>31.0</td>

<td>37.0</td>

</tr>

<tr>

<th>149</th>

<td>8605.3</td>

<td>8159.0</td>

<td>10556.6</td>

<td>8340.6</td>

<td>7975.0</td>

<td>2.0</td>

<td>volkswagen</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>97.3</td>

<td>171.7</td>

<td>65.5</td>

<td>55.7</td>

<td>2209.0</td>

<td>ohc</td>

<td>four</td>

<td>109.0</td>

<td>mpfi</td>

<td>3.19</td>

<td>3.40</td>

<td>9.00</td>

<td>85.0</td>

<td>5250.0</td>

<td>27.0</td>

<td>34.0</td>

</tr>

<tr>

<th>65</th>

<td>7808.2</td>

<td>8498.9</td>

<td>8737.0</td>

<td>8358.4</td>

<td>8499.0</td>

<td>3.0</td>

<td>mitsubishi</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>96.3</td>

<td>173.0</td>

<td>65.4</td>

<td>49.4</td>

<td>2328.0</td>

<td>ohc</td>

<td>four</td>

<td>122.0</td>

<td>2bbl</td>

<td>3.35</td>

<td>3.46</td>

<td>8.50</td>

<td>88.0</td>

<td>5000.0</td>

<td>25.0</td>

<td>32.0</td>

</tr>

<tr>

<th>78</th>

<td>6854.3</td>

<td>7770.8</td>

<td>8442.4</td>

<td>8477.1</td>

<td>8249.0</td>

<td>2.0</td>

<td>nissan</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hardtop</td>

<td>fwd</td>

<td>front</td>

<td>95.1</td>

<td>162.4</td>

<td>63.8</td>

<td>53.3</td>

<td>2008.0</td>

<td>ohc</td>

<td>four</td>

<td>97.0</td>

<td>2bbl</td>

<td>3.15</td>

<td>3.29</td>

<td>9.40</td>

<td>69.0</td>

<td>5200.0</td>

<td>31.0</td>

<td>37.0</td>

</tr>

<tr>

<th>32</th>

<td>9039.0</td>

<td>8610.0</td>

<td>9712.2</td>

<td>8685.8</td>

<td>7895.0</td>

<td>0.0</td>

<td>honda</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>96.5</td>

<td>167.5</td>

<td>65.2</td>

<td>53.3</td>

<td>2236.0</td>

<td>ohc</td>

<td>four</td>

<td>110.0</td>

<td>1bbl</td>

<td>3.15</td>

<td>3.58</td>

<td>9.00</td>

<td>86.0</td>

<td>5800.0</td>

<td>27.0</td>

<td>33.0</td>

</tr>

<tr>

<th>33</th>

<td>9452.7</td>

<td>9071.5</td>

<td>9763.2</td>

<td>8757.2</td>

<td>9095.0</td>

<td>0.0</td>

<td>honda</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>96.5</td>

<td>167.5</td>

<td>65.2</td>

<td>53.3</td>

<td>2289.0</td>

<td>ohc</td>

<td>four</td>

<td>110.0</td>

<td>1bbl</td>

<td>3.15</td>

<td>3.58</td>

<td>9.00</td>

<td>86.0</td>

<td>5800.0</td>

<td>27.0</td>

<td>33.0</td>

</tr>

<tr>

<th>23</th>

<td>8313.2</td>

<td>9706.2</td>

<td>12110.5</td>

<td>8804.6</td>

<td>8921.0</td>

<td>-1.0</td>

<td>dodge</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>wagon</td>

<td>fwd</td>

<td>front</td>

<td>103.3</td>

<td>174.6</td>

<td>64.6</td>

<td>59.8</td>

<td>2535.0</td>

<td>ohc</td>

<td>four</td>

<td>122.0</td>

<td>2bbl</td>

<td>3.34</td>

<td>3.46</td>

<td>8.50</td>

<td>88.0</td>

<td>5000.0</td>

<td>24.0</td>

<td>30.0</td>

</tr>

<tr>

<th>151</th>

<td>8812.5</td>

<td>8158.1</td>

<td>10590.3</td>

<td>8810.2</td>

<td>8195.0</td>

<td>2.0</td>

<td>volkswagen</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>97.3</td>

<td>171.7</td>

<td>65.5</td>

<td>55.7</td>

<td>2212.0</td>

<td>ohc</td>

<td>four</td>

<td>109.0</td>

<td>mpfi</td>

<td>3.19</td>

<td>3.40</td>

<td>9.00</td>

<td>85.0</td>

<td>5250.0</td>

<td>27.0</td>

<td>34.0</td>

</tr>

<tr>

<th>103</th>

<td>8303.2</td>

<td>9634.4</td>

<td>12117.5</td>

<td>8906.8</td>

<td>8921.0</td>

<td>-1.0</td>

<td>plymouth</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>wagon</td>

<td>fwd</td>

<td>front</td>

<td>103.3</td>

<td>174.6</td>

<td>64.6</td>

<td>59.8</td>

<td>2535.0</td>

<td>ohc</td>

<td>four</td>

<td>122.0</td>

<td>2bbl</td>

<td>3.35</td>

<td>3.46</td>

<td>8.50</td>

<td>88.0</td>

<td>5000.0</td>

<td>24.0</td>

<td>30.0</td>

</tr>

<tr>

<th>152</th>

<td>9304.2</td>

<td>8546.0</td>

<td>10651.0</td>

<td>8919.8</td>

<td>8495.0</td>

<td>2.0</td>

<td>volkswagen</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>97.3</td>

<td>171.7</td>

<td>65.5</td>

<td>55.7</td>

<td>2275.0</td>

<td>ohc</td>

<td>four</td>

<td>109.0</td>

<td>mpfi</td>

<td>3.19</td>

<td>3.40</td>

<td>9.00</td>

<td>85.0</td>

<td>5250.0</td>

<td>27.0</td>

<td>34.0</td>

</tr>

<tr>

<th>80</th>

<td>10615.0</td>

<td>9208.8</td>

<td>10825.1</td>

<td>8959.1</td>

<td>9549.0</td>

<td>0.0</td>

<td>nissan</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>97.2</td>

<td>173.4</td>

<td>65.2</td>

<td>54.7</td>

<td>2302.0</td>

<td>ohc</td>

<td>four</td>

<td>120.0</td>

<td>2bbl</td>

<td>3.33</td>

<td>3.47</td>

<td>8.50</td>

<td>97.0</td>

<td>5200.0</td>

<td>27.0</td>

<td>34.0</td>

</tr>

<tr>

<th>118</th>

<td>8764.3</td>

<td>9713.5</td>

<td>11421.1</td>

<td>9092.3</td>

<td>9233.0</td>

<td>0.0</td>

<td>subaru</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>4wd</td>

<td>front</td>

<td>97.0</td>

<td>172.0</td>

<td>65.4</td>

<td>54.3</td>

<td>2385.0</td>

<td>ohcf</td>

<td>four</td>

<td>108.0</td>

<td>2bbl</td>

<td>3.62</td>

<td>2.64</td>

<td>9.00</td>

<td>82.0</td>

<td>4800.0</td>

<td>24.0</td>

<td>25.0</td>

</tr>

<tr>

<th>34</th>

<td>8795.6</td>

<td>9492.6</td>

<td>11575.3</td>

<td>9108.9</td>

<td>8845.0</td>

<td>0.0</td>

<td>honda</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>96.5</td>

<td>175.4</td>

<td>65.2</td>

<td>54.1</td>

<td>2304.0</td>

<td>ohc</td>

<td>four</td>

<td>110.0</td>

<td>1bbl</td>

<td>3.15</td>

<td>3.58</td>

<td>9.00</td>

<td>86.0</td>

<td>5800.0</td>

<td>27.0</td>

<td>33.0</td>

</tr>

<tr>

<th>129</th>

<td>11463.8</td>

<td>11911.7</td>

<td>9719.9</td>

<td>9207.3</td>

<td>8778.0</td>

<td>0.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>wagon</td>

<td>4wd</td>

<td>front</td>

<td>95.7</td>

<td>169.7</td>

<td>63.6</td>

<td>59.1</td>

<td>3110.0</td>

<td>ohc</td>

<td>four</td>

<td>92.0</td>

<td>2bbl</td>

<td>3.05</td>

<td>3.03</td>

<td>9.00</td>

<td>62.0</td>

<td>4800.0</td>

<td>27.0</td>

<td>32.0</td>

</tr>

<tr>

<th>79</th>

<td>10193.6</td>

<td>9341.1</td>

<td>9424.9</td>

<td>9270.7</td>

<td>8949.0</td>

<td>0.0</td>

<td>nissan</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>97.2</td>

<td>173.4</td>

<td>65.2</td>

<td>54.7</td>

<td>2324.0</td>

<td>ohc</td>

<td>four</td>

<td>120.0</td>

<td>2bbl</td>

<td>3.33</td>

<td>3.47</td>

<td>8.50</td>

<td>97.0</td>

<td>5200.0</td>

<td>27.0</td>

<td>34.0</td>

</tr>

<tr>

<th>72</th>

<td>9227.5</td>

<td>9352.9</td>

<td>11991.8</td>

<td>9323.3</td>

<td>9279.0</td>

<td>-1.0</td>

<td>mitsubishi</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>96.3</td>

<td>172.4</td>

<td>65.4</td>

<td>51.6</td>

<td>2403.0</td>

<td>ohc</td>

<td>four</td>

<td>110.0</td>

<td>spdi</td>

<td>3.17</td>

<td>3.46</td>

<td>7.50</td>

<td>116.0</td>

<td>5500.0</td>

<td>23.0</td>

<td>30.0</td>

</tr>

<tr>

<th>49</th>

<td>10943.2</td>

<td>9617.9</td>

<td>11580.1</td>

<td>9373.8</td>

<td>8495.0</td>

<td>0.0</td>

<td>mazda</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>98.8</td>

<td>177.8</td>

<td>66.5</td>

<td>55.5</td>

<td>2410.0</td>

<td>ohc</td>

<td>four</td>

<td>122.0</td>

<td>2bbl</td>

<td>3.39</td>

<td>3.39</td>

<td>8.60</td>

<td>84.0</td>

<td>4800.0</td>

<td>26.0</td>

<td>32.0</td>

</tr>

<tr>

<th>51</th>

<td>10943.2</td>

<td>9617.9</td>

<td>11580.1</td>

<td>9373.8</td>

<td>10245.0</td>

<td>0.0</td>

<td>mazda</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>98.8</td>

<td>177.8</td>

<td>66.5</td>

<td>55.5</td>

<td>2410.0</td>

<td>ohc</td>

<td>four</td>

<td>122.0</td>

<td>2bbl</td>

<td>3.39</td>

<td>3.39</td>

<td>8.60</td>

<td>84.0</td>

<td>4800.0</td>

<td>26.0</td>

<td>32.0</td>

</tr>

<tr>

<th>71</th>

<td>10149.5</td>

<td>9327.2</td>

<td>12034.2</td>

<td>9385.0</td>

<td>9279.0</td>

<td>1.0</td>

<td>mitsubishi</td>

<td>gas</td>

<td>turbo</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>96.3</td>

<td>172.4</td>

<td>65.4</td>

<td>51.6</td>

<td>2403.0</td>

<td>ohc</td>

<td>four</td>

<td>110.0</td>

<td>spdi</td>

<td>3.17</td>

<td>3.46</td>

<td>7.50</td>

<td>116.0</td>

<td>5500.0</td>

<td>23.0</td>

<td>30.0</td>

</tr>

<tr>

<th>138</th>

<td>10528.9</td>

<td>9641.4</td>

<td>10700.8</td>

<td>9424.4</td>

<td>9639.0</td>

<td>2.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hardtop</td>

<td>rwd</td>

<td>front</td>

<td>98.4</td>

<td>176.2</td>

<td>65.6</td>

<td>52.0</td>

<td>2536.0</td>

<td>ohc</td>

<td>four</td>

<td>146.0</td>

<td>mpfi</td>

<td>3.62</td>

<td>3.50</td>

<td>9.30</td>

<td>116.0</td>

<td>4800.0</td>

<td>24.0</td>

<td>30.0</td>

</tr>

<tr>

<th>154</th>

<td>9569.0</td>

<td>9715.0</td>

<td>11167.6</td>

<td>9435.8</td>

<td>9995.0</td>

<td>2.0</td>

<td>volkswagen</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>97.3</td>

<td>171.7</td>

<td>65.5</td>

<td>55.7</td>

<td>2300.0</td>

<td>ohc</td>

<td>four</td>

<td>109.0</td>

<td>mpfi</td>

<td>3.19</td>

<td>3.40</td>

<td>10.00</td>

<td>100.0</td>

<td>5500.0</td>

<td>26.0</td>

<td>32.0</td>

</tr>

<tr>

<th>137</th>

<td>10560.1</td>

<td>9379.2</td>

<td>10705.6</td>

<td>9442.2</td>

<td>8449.0</td>

<td>2.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hardtop</td>

<td>rwd</td>

<td>front</td>

<td>98.4</td>

<td>176.2</td>

<td>65.6</td>

<td>52.0</td>

<td>2540.0</td>

<td>ohc</td>

<td>four</td>

<td>146.0</td>

<td>mpfi</td>

<td>3.62</td>

<td>3.50</td>

<td>9.30</td>

<td>116.0</td>

<td>4800.0</td>

<td>24.0</td>

<td>30.0</td>

</tr>

<tr>

<th>136</th>

<td>10061.4</td>

<td>9555.9</td>

<td>9095.9</td>

<td>9481.4</td>

<td>9538.0</td>

<td>1.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>rwd</td>

<td>front</td>

<td>94.5</td>

<td>168.7</td>

<td>64.0</td>

<td>52.6</td>

<td>2300.0</td>

<td>dohc</td>

<td>four</td>

<td>98.0</td>

<td>mpfi</td>

<td>3.24</td>

<td>3.08</td>

<td>9.40</td>

<td>112.0</td>

<td>6600.0</td>

<td>26.0</td>

<td>29.0</td>

</tr>

<tr>

<th>135</th>

<td>10381.3</td>

<td>9540.0</td>

<td>10832.2</td>

<td>9597.4</td>

<td>9298.0</td>

<td>1.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>sedan</td>

<td>rwd</td>

<td>front</td>

<td>94.5</td>

<td>168.7</td>

<td>64.0</td>

<td>52.6</td>

<td>2265.0</td>

<td>dohc</td>

<td>four</td>

<td>98.0</td>

<td>mpfi</td>

<td>3.24</td>

<td>3.08</td>

<td>9.40</td>

<td>112.0</td>

<td>6600.0</td>

<td>26.0</td>

<td>29.0</td>

</tr>

<tr>

<th>35</th>

<td>7973.2</td>

<td>9876.8</td>

<td>11106.6</td>

<td>9777.5</td>

<td>10295.0</td>

<td>0.0</td>

<td>honda</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>96.5</td>

<td>175.4</td>

<td>62.5</td>

<td>54.1</td>

<td>2372.0</td>

<td>ohc</td>

<td>four</td>

<td>110.0</td>

<td>1bbl</td>

<td>3.15</td>

<td>3.58</td>

<td>9.00</td>

<td>86.0</td>

<td>5800.0</td>

<td>27.0</td>

<td>33.0</td>

</tr>

<tr>

<th>121</th>

<td>9860.0</td>

<td>9975.3</td>

<td>11368.6</td>

<td>9856.1</td>

<td>10198.0</td>

<td>0.0</td>

<td>subaru</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>wagon</td>

<td>fwd</td>

<td>front</td>

<td>97.0</td>

<td>173.5</td>

<td>65.4</td>

<td>53.0</td>

<td>2455.0</td>

<td>ohcf</td>

<td>four</td>

<td>108.0</td>

<td>mpfi</td>

<td>3.62</td>

<td>2.64</td>

<td>9.00</td>

<td>94.0</td>

<td>5200.0</td>

<td>25.0</td>

<td>31.0</td>

</tr>

<tr>

<th>117</th>

<td>9811.5</td>

<td>9656.4</td>

<td>11209.0</td>

<td>9903.5</td>

<td>9960.0</td>

<td>0.0</td>

<td>subaru</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>97.2</td>

<td>172.0</td>

<td>65.4</td>

<td>52.5</td>

<td>2340.0</td>

<td>ohcf</td>

<td>four</td>

<td>108.0</td>

<td>mpfi</td>

<td>3.62</td>

<td>2.64</td>

<td>9.00</td>

<td>94.0</td>

<td>5200.0</td>

<td>26.0</td>

<td>32.0</td>

</tr>

<tr>

<th>153</th>

<td>9469.9</td>

<td>9088.5</td>

<td>11470.8</td>

<td>9952.0</td>

<td>9495.0</td>

<td>2.0</td>

<td>volkswagen</td>

<td>diesel</td>

<td>turbo</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>97.3</td>

<td>171.7</td>

<td>65.5</td>

<td>55.7</td>

<td>2319.0</td>

<td>ohc</td>

<td>four</td>

<td>97.0</td>

<td>idi</td>

<td>3.01</td>

<td>3.40</td>

<td>23.00</td>

<td>68.0</td>

<td>4500.0</td>

<td>37.0</td>

<td>42.0</td>

</tr>

<tr>

<th>48</th>

<td>10677.9</td>

<td>9776.8</td>

<td>9692.5</td>

<td>9988.3</td>

<td>8845.0</td>

<td>1.0</td>

<td>mazda</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>98.8</td>

<td>177.8</td>

<td>66.5</td>

<td>53.7</td>

<td>2385.0</td>

<td>ohc</td>

<td>four</td>

<td>122.0</td>

<td>2bbl</td>

<td>3.39</td>

<td>3.39</td>

<td>8.60</td>

<td>84.0</td>

<td>4800.0</td>

<td>26.0</td>

<td>32.0</td>

</tr>

<tr>

<th>50</th>

<td>10677.9</td>

<td>9776.8</td>

<td>9692.5</td>

<td>9988.3</td>

<td>10595.0</td>

<td>1.0</td>

<td>mazda</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>98.8</td>

<td>177.8</td>

<td>66.5</td>

<td>53.7</td>

<td>2385.0</td>

<td>ohc</td>

<td>four</td>

<td>122.0</td>

<td>2bbl</td>

<td>3.39</td>

<td>3.39</td>

<td>8.60</td>

<td>84.0</td>

<td>4800.0</td>

<td>26.0</td>

<td>32.0</td>

</tr>

<tr>

<th>37</th>

<td>12492.9</td>

<td>10105.4</td>

<td>11166.5</td>

<td>10036.0</td>

<td>10345.0</td>

<td>1.0</td>

<td>honda</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>96.5</td>

<td>169.1</td>

<td>66.0</td>

<td>51.0</td>

<td>2293.0</td>

<td>ohc</td>

<td>four</td>

<td>110.0</td>

<td>2bbl</td>

<td>3.15</td>

<td>3.58</td>

<td>9.10</td>

<td>100.0</td>

<td>5500.0</td>

<td>25.0</td>

<td>31.0</td>

</tr>

<tr>

<th>156</th>

<td>9254.7</td>

<td>9428.9</td>

<td>8510.4</td>

<td>10037.0</td>

<td>9980.0</td>

<td>3.0</td>

<td>volkswagen</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>94.5</td>

<td>165.7</td>

<td>64.0</td>

<td>51.4</td>

<td>2221.0</td>

<td>ohc</td>

<td>four</td>

<td>109.0</td>

<td>mpfi</td>

<td>3.19</td>

<td>3.40</td>

<td>8.50</td>

<td>90.0</td>

<td>5500.0</td>

<td>24.0</td>

<td>29.0</td>

</tr>

<tr>

<th>140</th>

<td>11645.1</td>

<td>12127.3</td>

<td>10872.7</td>

<td>10060.8</td>

<td>11199.0</td>

<td>2.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hardtop</td>

<td>rwd</td>

<td>front</td>

<td>98.4</td>

<td>176.2</td>

<td>65.6</td>

<td>52.0</td>

<td>2679.0</td>

<td>ohc</td>

<td>four</td>

<td>146.0</td>

<td>mpfi</td>

<td>3.62</td>

<td>3.50</td>

<td>9.30</td>

<td>116.0</td>

<td>4800.0</td>

<td>24.0</td>

<td>30.0</td>

</tr>

<tr>

<th>64</th>

<td>9890.7</td>

<td>9519.7</td>

<td>9957.7</td>

<td>10212.4</td>

<td>9959.0</td>

<td>3.0</td>

<td>mitsubishi</td>

<td>gas</td>

<td>turbo</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>96.3</td>

<td>173.0</td>

<td>65.4</td>

<td>49.4</td>

<td>2370.0</td>

<td>ohc</td>

<td>four</td>

<td>110.0</td>

<td>spdi</td>

<td>3.17</td>

<td>3.46</td>

<td>7.50</td>

<td>116.0</td>

<td>5500.0</td>

<td>23.0</td>

<td>30.0</td>

</tr>

<tr>

<th>52</th>

<td>10467.1</td>

<td>10483.2</td>

<td>10146.4</td>

<td>10279.6</td>

<td>11245.0</td>

<td>0.0</td>

<td>mazda</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>98.8</td>

<td>177.8</td>

<td>66.5</td>

<td>55.5</td>

<td>2425.0</td>

<td>ohc</td>

<td>four</td>

<td>122.0</td>

<td>2bbl</td>

<td>3.39</td>

<td>3.39</td>

<td>8.60</td>

<td>84.0</td>

<td>4800.0</td>

<td>26.0</td>

<td>32.0</td>

</tr>

<tr>

<th>139</th>

<td>10677.7</td>

<td>10912.9</td>

<td>8963.6</td>

<td>10696.6</td>

<td>9989.0</td>

<td>2.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>rwd</td>

<td>front</td>

<td>98.4</td>

<td>176.2</td>

<td>65.6</td>

<td>52.0</td>

<td>2551.0</td>

<td>ohc</td>

<td>four</td>

<td>146.0</td>

<td>mpfi</td>

<td>3.62</td>

<td>3.50</td>

<td>9.30</td>

<td>116.0</td>

<td>4800.0</td>

<td>24.0</td>

<td>30.0</td>

</tr>

<tr>

<th>155</th>

<td>11825.0</td>

<td>9924.3</td>

<td>15111.7</td>

<td>10952.9</td>

<td>11595.0</td>

<td>3.0</td>

<td>volkswagen</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>convertible</td>

<td>fwd</td>

<td>front</td>

<td>94.5</td>

<td>159.3</td>

<td>64.2</td>

<td>55.6</td>

<td>2254.0</td>

<td>ohc</td>

<td>four</td>

<td>109.0</td>

<td>mpfi</td>

<td>3.19</td>

<td>3.40</td>

<td>8.50</td>

<td>90.0</td>

<td>5500.0</td>

<td>24.0</td>

<td>29.0</td>

</tr>

<tr>

<th>39</th>

<td>11051.8</td>

<td>11472.2</td>

<td>9903.3</td>

<td>10982.0</td>

<td>11048.0</td>

<td>2.0</td>

<td>isuzu</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>rwd</td>

<td>front</td>

<td>96.0</td>

<td>172.6</td>

<td>65.2</td>

<td>51.4</td>

<td>2734.0</td>

<td>ohc</td>

<td>four</td>

<td>119.0</td>

<td>spfi</td>

<td>3.43</td>

<td>3.23</td>

<td>9.20</td>

<td>90.0</td>

<td>5000.0</td>

<td>24.0</td>

<td>29.0</td>

</tr>

<tr>

<th>143</th>

<td>8974.2</td>

<td>11206.4</td>

<td>8493.5</td>

<td>11217.1</td>

<td>11248.0</td>

<td>-1.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>102.4</td>

<td>175.6</td>

<td>66.5</td>

<td>53.9</td>

<td>2458.0</td>

<td>ohc</td>

<td>four</td>

<td>122.0</td>

<td>mpfi</td>

<td>3.31</td>

<td>3.54</td>

<td>8.70</td>

<td>92.0</td>

<td>4200.0</td>

<td>27.0</td>

<td>32.0</td>

</tr>

<tr>

<th>141</th>

<td>11950.0</td>

<td>12332.7</td>

<td>9156.5</td>

<td>11345.2</td>

<td>11549.0</td>

<td>2.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>rwd</td>

<td>front</td>

<td>98.4</td>

<td>176.2</td>

<td>65.6</td>

<td>52.0</td>

<td>2714.0</td>

<td>ohc</td>

<td>four</td>

<td>146.0</td>

<td>mpfi</td>

<td>3.62</td>

<td>3.50</td>

<td>9.30</td>

<td>116.0</td>

<td>4800.0</td>

<td>24.0</td>

<td>30.0</td>

</tr>

<tr>

<th>123</th>

<td>11397.6</td>

<td>12061.4</td>

<td>12590.9</td>

<td>11562.6</td>

<td>11694.0</td>

<td>0.0</td>

<td>subaru</td>

<td>gas</td>

<td>turbo</td>

<td>four</td>

<td>wagon</td>

<td>4wd</td>

<td>front</td>

<td>96.9</td>

<td>173.6</td>

<td>65.4</td>

<td>54.9</td>

<td>2650.0</td>

<td>ohcf</td>

<td>four</td>

<td>108.0</td>

<td>mpfi</td>

<td>3.62</td>

<td>2.64</td>

<td>7.70</td>

<td>111.0</td>

<td>4800.0</td>

<td>23.0</td>

<td>23.0</td>

</tr>

<tr>

<th>119</th>

<td>12079.6</td>

<td>10486.0</td>

<td>12135.1</td>

<td>11724.1</td>

<td>11259.0</td>

<td>0.0</td>

<td>subaru</td>

<td>gas</td>

<td>turbo</td>

<td>four</td>

<td>sedan</td>

<td>4wd</td>

<td>front</td>

<td>97.0</td>

<td>172.0</td>

<td>65.4</td>

<td>54.3</td>

<td>2510.0</td>

<td>ohcf</td>

<td>four</td>

<td>108.0</td>

<td>mpfi</td>

<td>3.62</td>

<td>2.64</td>

<td>7.70</td>

<td>111.0</td>

<td>4800.0</td>

<td>24.0</td>

<td>29.0</td>

</tr>

<tr>

<th>106</th>

<td>12835.9</td>

<td>12804.1</td>

<td>11084.4</td>

<td>12438.1</td>

<td>11850.0</td>

<td>3.0</td>

<td>saab</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>99.1</td>

<td>186.6</td>

<td>66.5</td>

<td>56.1</td>

<td>2658.0</td>

<td>ohc</td>

<td>four</td>

<td>121.0</td>

<td>mpfi</td>

<td>3.54</td>

<td>3.07</td>

<td>9.31</td>

<td>110.0</td>

<td>5250.0</td>

<td>21.0</td>

<td>28.0</td>

</tr>

<tr>

<th>159</th>

<td>11838.7</td>

<td>12211.1</td>

<td>12386.1</td>

<td>12696.6</td>

<td>12290.0</td>

<td>0.0</td>

<td>volkswagen</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>wagon</td>

<td>fwd</td>

<td>front</td>

<td>100.4</td>

<td>183.1</td>

<td>66.9</td>

<td>55.1</td>

<td>2563.0</td>

<td>ohc</td>

<td>four</td>

<td>109.0</td>

<td>mpfi</td>

<td>3.19</td>

<td>3.40</td>

<td>9.00</td>

<td>88.0</td>

<td>5500.0</td>

<td>25.0</td>

<td>31.0</td>

</tr>

<tr>

<th>83</th>

<td>14742.9</td>

<td>13921.8</td>

<td>15606.7</td>

<td>13056.7</td>

<td>13499.0</td>

<td>0.0</td>

<td>nissan</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>100.4</td>

<td>184.6</td>

<td>66.5</td>

<td>55.1</td>

<td>3060.0</td>

<td>ohcv</td>

<td>six</td>

<td>181.0</td>

<td>mpfi</td>

<td>3.43</td>

<td>3.27</td>

<td>9.00</td>

<td>152.0</td>

<td>5200.0</td>

<td>19.0</td>

<td>25.0</td>

</tr>

<tr>

<td colspan="30">**+ 65 more**</td>

</tr>

</tbody>

</table>

</div>

</section>

<div class="textwrapper"><textarea placeholder="Write a comment..." oninput="this.innerHTML = this.value;pybridge._add_comment(this.parentNode.parentNode.id, this.value);"></textarea></div>

</div>

<div id="2076968685784" class="normal" onclick="pybridge._select_item(this.id)">

<section class="section">

# File <span class="timestamp">Thu Nov 30 17, 19:09:40</span>

<div class="content">

## File

**File name:**

**Format:**

## Data

**Data instances:**

**Features:**

</div>

</section>

<div class="textwrapper"><textarea placeholder="Write a comment..." oninput="this.innerHTML = this.value;pybridge._add_comment(this.parentNode.parentNode.id, this.value);"></textarea></div>

</div>

<div id="2076968687800" class="normal" onclick="pybridge._select_item(this.id)">

<section class="section">

# Impute <span class="timestamp">Thu Nov 30 17, 19:10:11</span>

<div class="content">

**Default method:**

**Specific imputers:**

</div>

</section>

<div class="textwrapper"><textarea placeholder="Write a comment..." oninput="this.innerHTML = this.value;pybridge._add_comment(this.parentNode.parentNode.id, this.value);"></textarea></div>

</div>

<div id="2076780143672" class="normal" onclick="pybridge._select_item(this.id)">

<section class="section">

# Predictions <span class="timestamp">Thu Nov 30 17, 19:10:47</span>

<div class="content">

## Info

Data: 29 instances.  
Predictors: 4  
Task: Regression

## Data & Predictions

<table>

<tbody>

<tr>

<th>Linear Regression</th>

<th>Random Forest</th>

<th>SVM</th>

<th>Neural Network</th>

<th>price</th>

<th>symboling</th>

<th>normalized-losses</th>

<th>make</th>

<th>fuel-type</th>

<th>aspiration</th>

<th>num-of-doors</th>

<th>body-style</th>

<th>drive-wheels</th>

<th>engine-location</th>

<th>wheel-base</th>

<th>length</th>

<th>width</th>

<th>height</th>

<th>curb-weight</th>

<th>engine-type</th>

<th>num-of-cylinders</th>

<th>engine-size</th>

<th>fuel-system</th>

<th>bore</th>

<th>stroke</th>

<th>compression-ratio</th>

<th>horsepower</th>

<th>peak-rpm</th>

<th>city-mpg</th>

<th>highway-mpg</th>

</tr>

<tr>

<th>1</th>

<td>16696.1</td>

<td>16680.1</td>

<td>15684.5</td>

<td>16706.6</td>

<td>?</td>

<td>-2.0</td>

<td>103.0</td>

<td>volvo</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>rwd</td>

<td>front</td>

<td>104.3</td>

<td>188.8</td>

<td>67.2</td>

<td>56.2</td>

<td>2912.0</td>

<td>ohc</td>

<td>four</td>

<td>141.0</td>

<td>mpfi</td>

<td>3.78</td>

<td>3.15</td>

<td>9.5</td>

<td>114.0</td>

<td>5400.0</td>

<td>23.0</td>

<td>28.0</td>

</tr>

<tr>

<th>2</th>

<td>16940.2</td>

<td>16575.2</td>

<td>15536.9</td>

<td>16636.2</td>

<td>?</td>

<td>-1.0</td>

<td>74.0</td>

<td>volvo</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>wagon</td>

<td>rwd</td>

<td>front</td>

<td>104.3</td>

<td>188.8</td>

<td>67.2</td>

<td>57.5</td>

<td>3034.0</td>

<td>ohc</td>

<td>four</td>

<td>141.0</td>

<td>mpfi</td>

<td>3.78</td>

<td>3.15</td>

<td>9.5</td>

<td>114.0</td>

<td>5400.0</td>

<td>23.0</td>

<td>28.0</td>

</tr>

<tr>

<th>3</th>

<td>19887.5</td>

<td>18759.9</td>

<td>16132.8</td>

<td>18356.3</td>

<td>?</td>

<td>-1.0</td>

<td>95.0</td>

<td>volvo</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>rwd</td>

<td>front</td>

<td>109.1</td>

<td>188.8</td>

<td>68.9</td>

<td>55.5</td>

<td>2952.0</td>

<td>ohc</td>

<td>four</td>

<td>141.0</td>

<td>mpfi</td>

<td>3.78</td>

<td>3.15</td>

<td>9.5</td>

<td>114.0</td>

<td>5400.0</td>

<td>23.0</td>

<td>28.0</td>

</tr>

<tr>

<th>4</th>

<td>22701.6</td>

<td>19036.8</td>

<td>17623.8</td>

<td>21752.3</td>

<td>?</td>

<td>-1.0</td>

<td>95.0</td>

<td>volvo</td>

<td>gas</td>

<td>turbo</td>

<td>four</td>

<td>sedan</td>

<td>rwd</td>

<td>front</td>

<td>109.1</td>

<td>188.8</td>

<td>68.8</td>

<td>55.5</td>

<td>3049.0</td>

<td>ohc</td>

<td>four</td>

<td>141.0</td>

<td>mpfi</td>

<td>3.78</td>

<td>3.15</td>

<td>8.7</td>

<td>160.0</td>

<td>5300.0</td>

<td>19.0</td>

<td>25.0</td>

</tr>

<tr>

<th>5</th>

<td>20469.4</td>

<td>18307.7</td>

<td>19887.4</td>

<td>16116.3</td>

<td>?</td>

<td>-1.0</td>

<td>95.0</td>

<td>volvo</td>

<td>diesel</td>

<td>turbo</td>

<td>four</td>

<td>sedan</td>

<td>rwd</td>

<td>front</td>

<td>109.1</td>

<td>188.8</td>

<td>68.9</td>

<td>55.5</td>

<td>3217.0</td>

<td>ohc</td>

<td>six</td>

<td>145.0</td>

<td>idi</td>

<td>3.01</td>

<td>3.40</td>

<td>23.0</td>

<td>106.0</td>

<td>4800.0</td>

<td>26.0</td>

<td>27.0</td>

</tr>

<tr>

<th>6</th>

<td>6368.5</td>

<td>7216.7</td>

<td>6971.7</td>

<td>7612.1</td>

<td>?</td>

<td>0.0</td>

<td>91.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>95.7</td>

<td>166.3</td>

<td>64.4</td>

<td>52.8</td>

<td>2122.0</td>

<td>ohc</td>

<td>four</td>

<td>98.0</td>

<td>2bbl</td>

<td>3.19</td>

<td>3.03</td>

<td>9.0</td>

<td>70.0</td>

<td>4800.0</td>

<td>28.0</td>

<td>34.0</td>

</tr>

<tr>

<th>7</th>

<td>7102.1</td>

<td>7352.9</td>

<td>8469.1</td>

<td>7410.2</td>

<td>?</td>

<td>0.0</td>

<td>91.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>95.7</td>

<td>166.3</td>

<td>64.4</td>

<td>52.8</td>

<td>2140.0</td>

<td>ohc</td>

<td>four</td>

<td>98.0</td>

<td>2bbl</td>

<td>3.19</td>

<td>3.03</td>

<td>9.0</td>

<td>70.0</td>

<td>4800.0</td>

<td>28.0</td>

<td>34.0</td>

</tr>

<tr>

<th>8</th>

<td>6552.8</td>

<td>7352.0</td>

<td>8236.6</td>

<td>2707.5</td>

<td>?</td>

<td>1.0</td>

<td>168.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>sedan</td>

<td>rwd</td>

<td>front</td>

<td>94.5</td>

<td>168.7</td>

<td>64.0</td>

<td>52.6</td>

<td>2169.0</td>

<td>ohc</td>

<td>four</td>

<td>98.0</td>

<td>2bbl</td>

<td>3.19</td>

<td>3.03</td>

<td>9.0</td>

<td>70.0</td>

<td>4800.0</td>

<td>29.0</td>

<td>34.0</td>

</tr>

<tr>

<th>9</th>

<td>6232.8</td>

<td>7347.1</td>

<td>6576.3</td>

<td>4095.6</td>

<td>?</td>

<td>1.0</td>

<td>168.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>rwd</td>

<td>front</td>

<td>94.5</td>

<td>168.7</td>

<td>64.0</td>

<td>52.6</td>

<td>2204.0</td>

<td>ohc</td>

<td>four</td>

<td>98.0</td>

<td>2bbl</td>

<td>3.19</td>

<td>3.03</td>

<td>9.0</td>

<td>70.0</td>

<td>4800.0</td>

<td>29.0</td>

<td>34.0</td>

</tr>

<tr>

<th>10</th>

<td>8419.6</td>

<td>10033.1</td>

<td>9883.0</td>

<td>9663.1</td>

<td>?</td>

<td>-1.0</td>

<td>65.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>102.4</td>

<td>175.6</td>

<td>66.5</td>

<td>54.9</td>

<td>2326.0</td>

<td>ohc</td>

<td>four</td>

<td>122.0</td>

<td>mpfi</td>

<td>3.31</td>

<td>3.54</td>

<td>8.7</td>

<td>92.0</td>

<td>4200.0</td>

<td>29.0</td>

<td>34.0</td>

</tr>

<tr>

<th>11</th>

<td>10780.7</td>

<td>10220.7</td>

<td>12518.4</td>

<td>11672.8</td>

<td>?</td>

<td>-1.0</td>

<td>65.0</td>

<td>toyota</td>

<td>diesel</td>

<td>turbo</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>102.4</td>

<td>175.6</td>

<td>66.5</td>

<td>54.9</td>

<td>2480.0</td>

<td>ohc</td>

<td>four</td>

<td>110.0</td>

<td>idi</td>

<td>3.27</td>

<td>3.35</td>

<td>22.5</td>

<td>73.0</td>

<td>4500.0</td>

<td>30.0</td>

<td>33.0</td>

</tr>

<tr>

<th>12</th>

<td>8630.7</td>

<td>10202.7</td>

<td>8448.6</td>

<td>11114.4</td>

<td>?</td>

<td>-1.0</td>

<td>65.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>102.4</td>

<td>175.6</td>

<td>66.5</td>

<td>53.9</td>

<td>2414.0</td>

<td>ohc</td>

<td>four</td>

<td>122.0</td>

<td>mpfi</td>

<td>3.31</td>

<td>3.54</td>

<td>8.7</td>

<td>92.0</td>

<td>4200.0</td>

<td>27.0</td>

<td>32.0</td>

</tr>

<tr>

<th>13</th>

<td>8835.5</td>

<td>10003.9</td>

<td>10131.3</td>

<td>10143.6</td>

<td>?</td>

<td>-1.0</td>

<td>65.0</td>

<td>toyota</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>102.4</td>

<td>175.6</td>

<td>66.5</td>

<td>54.9</td>

<td>2414.0</td>

<td>ohc</td>

<td>four</td>

<td>122.0</td>

<td>mpfi</td>

<td>3.31</td>

<td>3.54</td>

<td>8.7</td>

<td>92.0</td>

<td>4200.0</td>

<td>27.0</td>

<td>32.0</td>

</tr>

<tr>

<th>14</th>

<td>14345.7</td>

<td>14222.7</td>

<td>12151.9</td>

<td>13742.1</td>

<td>?</td>

<td>3.0</td>

<td>186.0</td>

<td>plymouth</td>

<td>gas</td>

<td>turbo</td>

<td>two</td>

<td>hatchback</td>

<td>rwd</td>

<td>front</td>

<td>95.9</td>

<td>173.2</td>

<td>66.3</td>

<td>50.2</td>

<td>2818.0</td>

<td>ohc</td>

<td>four</td>

<td>156.0</td>

<td>spdi</td>

<td>3.59</td>

<td>3.86</td>

<td>7.0</td>

<td>145.0</td>

<td>5000.0</td>

<td>19.0</td>

<td>24.0</td>

</tr>

<tr>

<th>15</th>

<td>23328.0</td>

<td>16073.3</td>

<td>13515.8</td>

<td>21934.5</td>

<td>?</td>

<td>3.0</td>

<td>186.0</td>

<td>porsche</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>rwd</td>

<td>front</td>

<td>94.5</td>

<td>168.9</td>

<td>68.3</td>

<td>50.2</td>

<td>2778.0</td>

<td>ohc</td>

<td>four</td>

<td>151.0</td>

<td>mpfi</td>

<td>3.94</td>

<td>3.11</td>

<td>9.5</td>

<td>143.0</td>

<td>5500.0</td>

<td>19.0</td>

<td>27.0</td>

</tr>

<tr>

<th>16</th>

<td>33880.8</td>

<td>34614.6</td>

<td>31456.0</td>

<td>34288.0</td>

<td>?</td>

<td>3.0</td>

<td>186.0</td>

<td>porsche</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hardtop</td>

<td>rwd</td>

<td>rear</td>

<td>89.5</td>

<td>168.9</td>

<td>65.0</td>

<td>51.6</td>

<td>2756.0</td>

<td>ohcf</td>

<td>six</td>

<td>194.0</td>

<td>mpfi</td>

<td>3.74</td>

<td>2.90</td>

<td>9.5</td>

<td>207.0</td>

<td>5900.0</td>

<td>17.0</td>

<td>25.0</td>

</tr>

<tr>

<th>17</th>

<td>5968.9</td>

<td>6893.9</td>

<td>8881.0</td>

<td>7768.4</td>

<td>?</td>

<td>1.0</td>

<td>122.0</td>

<td>nissan</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>94.5</td>

<td>165.3</td>

<td>63.8</td>

<td>54.5</td>

<td>1938.0</td>

<td>ohc</td>

<td>four</td>

<td>97.0</td>

<td>2bbl</td>

<td>3.15</td>

<td>3.29</td>

<td>9.4</td>

<td>69.0</td>

<td>5200.0</td>

<td>31.0</td>

<td>37.0</td>

</tr>

<tr>

<th>18</th>

<td>6048.0</td>

<td>7776.6</td>

<td>9000.9</td>

<td>8111.2</td>

<td>?</td>

<td>1.0</td>

<td>103.0</td>

<td>nissan</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>wagon</td>

<td>fwd</td>

<td>front</td>

<td>94.5</td>

<td>170.2</td>

<td>63.8</td>

<td>53.5</td>

<td>2024.0</td>

<td>ohc</td>

<td>four</td>

<td>97.0</td>

<td>2bbl</td>

<td>3.15</td>

<td>3.29</td>

<td>9.4</td>

<td>69.0</td>

<td>5200.0</td>

<td>31.0</td>

<td>37.0</td>

</tr>

<tr>

<th>19</th>

<td>5886.6</td>

<td>7226.9</td>

<td>8799.3</td>

<td>6255.7</td>

<td>?</td>

<td>1.0</td>

<td>128.0</td>

<td>nissan</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>94.5</td>

<td>165.3</td>

<td>63.8</td>

<td>54.5</td>

<td>1951.0</td>

<td>ohc</td>

<td>four</td>

<td>97.0</td>

<td>2bbl</td>

<td>3.15</td>

<td>3.29</td>

<td>9.4</td>

<td>69.0</td>

<td>5200.0</td>

<td>31.0</td>

<td>37.0</td>

</tr>

<tr>

<th>20</th>

<td>6313.4</td>

<td>6889.1</td>

<td>7370.5</td>

<td>6872.6</td>

<td>?</td>

<td>1.0</td>

<td>128.0</td>

<td>nissan</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>hatchback</td>

<td>fwd</td>

<td>front</td>

<td>94.5</td>

<td>165.6</td>

<td>63.8</td>

<td>53.3</td>

<td>2028.0</td>

<td>ohc</td>

<td>four</td>

<td>97.0</td>

<td>2bbl</td>

<td>3.15</td>

<td>3.29</td>

<td>9.4</td>

<td>69.0</td>

<td>5200.0</td>

<td>31.0</td>

<td>37.0</td>

</tr>

<tr>

<th>21</th>

<td>30404.4</td>

<td>29474.0</td>

<td>31663.7</td>

<td>29312.6</td>

<td>?</td>

<td>-1.0</td>

<td>93.0</td>

<td>mercedes-benz</td>

<td>diesel</td>

<td>turbo</td>

<td>four</td>

<td>sedan</td>

<td>rwd</td>

<td>front</td>

<td>115.6</td>

<td>202.6</td>

<td>71.7</td>

<td>56.3</td>

<td>3770.0</td>

<td>ohc</td>

<td>five</td>

<td>183.0</td>

<td>idi</td>

<td>3.58</td>

<td>3.64</td>

<td>21.5</td>

<td>123.0</td>

<td>4350.0</td>

<td>22.0</td>

<td>25.0</td>

</tr>

<tr>

<th>22</th>

<td>44175.6</td>

<td>34774.6</td>

<td>37287.1</td>

<td>39800.1</td>

<td>?</td>

<td>-1.0</td>

<td>93.0</td>

<td>mercedes-benz</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>rwd</td>

<td>front</td>

<td>115.6</td>

<td>202.6</td>

<td>71.7</td>

<td>56.5</td>

<td>3740.0</td>

<td>ohcv</td>

<td>eight</td>

<td>234.0</td>

<td>mpfi</td>

<td>3.46</td>

<td>3.10</td>

<td>8.3</td>

<td>155.0</td>

<td>4750.0</td>

<td>16.0</td>

<td>18.0</td>

</tr>

<tr>

<th>23</th>

<td>44035.6</td>

<td>33308.4</td>

<td>37304.9</td>

<td>44032.3</td>

<td>?</td>

<td>3.0</td>

<td>142.0</td>

<td>mercedes-benz</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>convertible</td>

<td>rwd</td>

<td>front</td>

<td>96.6</td>

<td>180.3</td>

<td>70.5</td>

<td>50.8</td>

<td>3685.0</td>

<td>ohcv</td>

<td>eight</td>

<td>234.0</td>

<td>mpfi</td>

<td>3.46</td>

<td>3.10</td>

<td>8.3</td>

<td>155.0</td>

<td>4750.0</td>

<td>16.0</td>

<td>18.0</td>

</tr>

<tr>

<th>24</th>

<td>48859.7</td>

<td>36984.2</td>

<td>42994.0</td>

<td>46092.1</td>

<td>?</td>

<td>0.0</td>

<td>192.0</td>

<td>mercedes-benz</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>rwd</td>

<td>front</td>

<td>120.9</td>

<td>208.1</td>

<td>71.7</td>

<td>56.7</td>

<td>3900.0</td>

<td>ohcv</td>

<td>eight</td>

<td>308.0</td>

<td>mpfi</td>

<td>3.80</td>

<td>3.35</td>

<td>8.0</td>

<td>184.0</td>

<td>4500.0</td>

<td>14.0</td>

<td>16.0</td>

</tr>

<tr>

<th>25</th>

<td>21414.7</td>

<td>18732.5</td>

<td>18783.4</td>

<td>21587.4</td>

<td>?</td>

<td>1.0</td>

<td>158.0</td>

<td>audi</td>

<td>gas</td>

<td>turbo</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>105.8</td>

<td>192.7</td>

<td>71.4</td>

<td>55.9</td>

<td>3086.0</td>

<td>ohc</td>

<td>five</td>

<td>131.0</td>

<td>mpfi</td>

<td>3.13</td>

<td>3.40</td>

<td>8.3</td>

<td>140.0</td>

<td>5500.0</td>

<td>17.0</td>

<td>20.0</td>

</tr>

<tr>

<th>26</th>

<td>22841.4</td>

<td>17108.7</td>

<td>15885.7</td>

<td>23082.6</td>

<td>?</td>

<td>0.0</td>

<td>142.0</td>

<td>audi</td>

<td>gas</td>

<td>turbo</td>

<td>two</td>

<td>hatchback</td>

<td>4wd</td>

<td>front</td>

<td>99.5</td>

<td>178.2</td>

<td>67.9</td>

<td>52.0</td>

<td>3053.0</td>

<td>ohc</td>

<td>five</td>

<td>131.0</td>

<td>mpfi</td>

<td>3.13</td>

<td>3.40</td>

<td>7.0</td>

<td>160.0</td>

<td>5500.0</td>

<td>16.0</td>

<td>22.0</td>

</tr>

<tr>

<th>27</th>

<td>24315.2</td>

<td>10120.5</td>

<td>17467.0</td>

<td>22104.7</td>

<td>?</td>

<td>2.0</td>

<td>192.0</td>

<td>bmw</td>

<td>gas</td>

<td>std</td>

<td>two</td>

<td>sedan</td>

<td>rwd</td>

<td>front</td>

<td>101.2</td>

<td>176.8</td>

<td>64.8</td>

<td>54.3</td>

<td>2395.0</td>

<td>ohc</td>

<td>four</td>

<td>108.0</td>

<td>mpfi</td>

<td>3.50</td>

<td>2.80</td>

<td>8.8</td>

<td>101.0</td>

<td>5800.0</td>

<td>23.0</td>

<td>29.0</td>

</tr>

<tr>

<th>28</th>

<td>24483.4</td>

<td>10162.5</td>

<td>17636.8</td>

<td>18946.4</td>

<td>?</td>

<td>0.0</td>

<td>192.0</td>

<td>bmw</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>rwd</td>

<td>front</td>

<td>101.2</td>

<td>176.8</td>

<td>64.8</td>

<td>54.3</td>

<td>2395.0</td>

<td>ohc</td>

<td>four</td>

<td>108.0</td>

<td>mpfi</td>

<td>3.50</td>

<td>2.80</td>

<td>8.8</td>

<td>101.0</td>

<td>5800.0</td>

<td>23.0</td>

<td>29.0</td>

</tr>

<tr>

<th>29</th>

<td>7423.5</td>

<td>7117.0</td>

<td>8940.3</td>

<td>7052.4</td>

<td>?</td>

<td>1.0</td>

<td>148.0</td>

<td>dodge</td>

<td>gas</td>

<td>std</td>

<td>four</td>

<td>sedan</td>

<td>fwd</td>

<td>front</td>

<td>93.7</td>

<td>157.3</td>

<td>63.8</td>

<td>50.6</td>

<td>1989.0</td>

<td>ohc</td>

<td>four</td>

<td>90.0</td>

<td>2bbl</td>

<td>2.97</td>

<td>3.23</td>

<td>9.4</td>

<td>68.0</td>

<td>5500.0</td>

<td>31.0</td>

<td>38.0</td>

</tr>

</tbody>

</table>

</div>

</section>

<div class="textwrapper"><textarea placeholder="Write a comment..." oninput="this.innerHTML = this.value;pybridge._add_comment(this.parentNode.parentNode.id, this.value);">Test Data</textarea></div>

</div>