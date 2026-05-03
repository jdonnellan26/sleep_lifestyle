# Read Me


<link href="README_files/libs/htmltools-fill-0.5.9/fill.css" rel="stylesheet" />
<script src="README_files/libs/htmlwidgets-1.6.4/htmlwidgets.js"></script>
<script src="README_files/libs/plotly-binding-4.12.0/plotly.js"></script>
<script src="README_files/libs/setprototypeof-0.1/setprototypeof.js"></script>
<script src="README_files/libs/typedarray-0.1/typedarray.min.js"></script>
<script src="README_files/libs/jquery-3.5.1/jquery.min.js"></script>
<link href="README_files/libs/crosstalk-1.2.2/css/crosstalk.min.css" rel="stylesheet" />
<script src="README_files/libs/crosstalk-1.2.2/js/crosstalk.min.js"></script>
<link href="README_files/libs/plotly-htmlwidgets-css-2.25.2/plotly-htmlwidgets.css" rel="stylesheet" />
<script src="README_files/libs/plotly-main-2.25.2/plotly-latest.min.js"></script>

## Sleep Health and Lifestyle Analysis

### Project Overview

This project analyzes how lifestyle and health factors influence sleep
duration and sleep quality using the Sleep Health and Lifestyle Dataset
from Kaggle. The dataset contains information on 374 individuals across
10 occupations, including variables related to sleep habits, stress,
BMI, physical activity, and sleep disorders.

### Research Question

How do occupation, stress level, BMI category, physical activity, and
sleep disorders affect sleep duration and sleep quality?

### Variables Used:

- Gender
- Age
- Occupation
- Sleep Duration
- Quality of Sleep
- Physical Activity Level
- Stress Level
- BMI Category
- Sleep Disorder
- Heart Rate

### Key Findings

- Occupations with shorter average sleep duration tend to report higher
  average stress levels.
- Individuals with insomnia generally sleep fewer hours than individuals
  without a sleep disorder.
- Individuals with sleep apnea show the greatest variability in sleep
  duration.
- Higher BMI categories are associated with greater prevalence of sleep
  disorders, especially sleep apnea.
- Sleep disorder prevalence varies by occupation, with some occupations
  showing stronger patterns of insomnia or sleep apnea.

## Primary Visualizations

### Stress and Sleep by Occupation

This plotly visualization shows the negative relationship between
average sleep duration and average stress levels across occupations.

<div class="plotly html-widget html-fill-item" id="htmlwidget-a15b1274c23cc70b50ab" style="width:672px;height:480px;"></div>
<script type="application/json" data-for="htmlwidget-a15b1274c23cc70b50ab">{"x":{"data":[{"x":[7.1135135135135137],"y":[4.5945945945945947],"text":"Occupation: Accountant","type":"scatter","mode":"markers","marker":{"autocolorscale":false,"color":"rgba(166,206,227,1)","opacity":1,"size":15.118110236220474,"symbol":"circle","line":{"width":1.8897637795275593,"color":"rgba(166,206,227,1)"}},"hoveron":"points","name":"Accountant","legendgroup":"Accountant","showlegend":true,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[6.9704225352112674],"y":[6.732394366197183],"text":"Occupation: Doctor","type":"scatter","mode":"markers","marker":{"autocolorscale":false,"color":"rgba(31,120,180,1)","opacity":1,"size":15.118110236220474,"symbol":"circle","line":{"width":1.8897637795275593,"color":"rgba(31,120,180,1)"}},"hoveron":"points","name":"Doctor","legendgroup":"Doctor","showlegend":true,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[7.9873015873015873],"y":[3.8888888888888884],"text":"Occupation: Engineer","type":"scatter","mode":"markers","marker":{"autocolorscale":false,"color":"rgba(178,223,138,1)","opacity":1,"size":15.118110236220474,"symbol":"circle","line":{"width":1.8897637795275593,"color":"rgba(178,223,138,1)"}},"hoveron":"points","name":"Engineer","legendgroup":"Engineer","showlegend":true,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[7.4106382978723406],"y":[5.0638297872340425],"text":"Occupation: Lawyer","type":"scatter","mode":"markers","marker":{"autocolorscale":false,"color":"rgba(51,160,44,1)","opacity":1,"size":15.118110236220474,"symbol":"circle","line":{"width":1.8897637795275593,"color":"rgba(51,160,44,1)"}},"hoveron":"points","name":"Lawyer","legendgroup":"Lawyer","showlegend":true,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[6.9000000000000004],"y":[5],"text":"Occupation: Manager","type":"scatter","mode":"markers","marker":{"autocolorscale":false,"color":"rgba(251,154,153,1)","opacity":1,"size":15.118110236220474,"symbol":"circle","line":{"width":1.8897637795275593,"color":"rgba(251,154,153,1)"}},"hoveron":"points","name":"Manager","legendgroup":"Manager","showlegend":true,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[7.0630136986301366],"y":[5.5479452054794534],"text":"Occupation: Nurse","type":"scatter","mode":"markers","marker":{"autocolorscale":false,"color":"rgba(227,26,28,1)","opacity":1,"size":15.118110236220474,"symbol":"circle","line":{"width":1.8897637795275593,"color":"rgba(227,26,28,1)"}},"hoveron":"points","name":"Nurse","legendgroup":"Nurse","showlegend":true,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[6.3735294117647063],"y":[7.0588235294117645],"text":"Occupation: Salesperson","type":"scatter","mode":"markers","marker":{"autocolorscale":false,"color":"rgba(253,191,111,1)","opacity":1,"size":15.118110236220474,"symbol":"circle","line":{"width":1.8897637795275593,"color":"rgba(253,191,111,1)"}},"hoveron":"points","name":"Salesperson","legendgroup":"Salesperson","showlegend":true,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[6],"y":[7],"text":"Occupation: Scientist","type":"scatter","mode":"markers","marker":{"autocolorscale":false,"color":"rgba(255,127,0,1)","opacity":1,"size":15.118110236220474,"symbol":"circle","line":{"width":1.8897637795275593,"color":"rgba(255,127,0,1)"}},"hoveron":"points","name":"Scientist","legendgroup":"Scientist","showlegend":true,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[6.75],"y":[6],"text":"Occupation: Software Engineer","type":"scatter","mode":"markers","marker":{"autocolorscale":false,"color":"rgba(202,178,214,1)","opacity":1,"size":15.118110236220474,"symbol":"circle","line":{"width":1.8897637795275593,"color":"rgba(202,178,214,1)"}},"hoveron":"points","name":"Software Engineer","legendgroup":"Software Engineer","showlegend":true,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[6.6899999999999995],"y":[4.5250000000000004],"text":"Occupation: Teacher","type":"scatter","mode":"markers","marker":{"autocolorscale":false,"color":"rgba(106,61,154,1)","opacity":1,"size":15.118110236220474,"symbol":"circle","line":{"width":1.8897637795275593,"color":"rgba(106,61,154,1)"}},"hoveron":"points","name":"Teacher","legendgroup":"Teacher","showlegend":true,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[5.7999999999999998,5.8341772151898734,5.868354430379747,5.9025316455696197,5.9367088607594933,5.9708860759493669,6.0050632911392405,6.0392405063291141,6.0734177215189868,6.1075949367088604,6.141772151898734,6.1759493670886076,6.2101265822784812,6.244303797468354,6.2784810126582276,6.3126582278481012,6.3468354430379748,6.3810126582278475,6.4151898734177211,6.4493670886075947,6.4835443037974683,6.5177215189873419,6.5518987341772146,6.5860759493670882,6.6202531645569618,6.6544303797468354,6.688607594936709,6.7227848101265817,6.7569620253164553,6.7911392405063289,6.8253164556962025,6.8594936708860761,6.8936708860759488,6.9278481012658224,6.962025316455696,6.9962025316455696,7.0303797468354432,7.0645569620253159,7.0987341772151895,7.1329113924050631,7.1670886075949367,7.2012658227848103,7.235443037974683,7.2696202531645566,7.3037974683544302,7.3379746835443038,7.3721518987341774,7.4063291139240501,7.4405063291139237,7.4746835443037973,7.5088607594936709,7.5430379746835445,7.5772151898734172,7.6113924050632908,7.6455696202531644,7.679746835443038,7.7139240506329116,7.7481012658227844,7.782278481012658,7.8164556962025316,7.8506329113924052,7.8848101265822788,7.9189873417721515,7.9531645569620251,7.9873417721518987,8.0215189873417714,8.0556962025316459,8.0898734177215186,8.1240506329113913,8.1582278481012658,8.1924050632911403,8.226582278481013,8.2607594936708857,8.2949367088607602,8.3291139240506329,8.3632911392405056,8.3974683544303801,8.4316455696202528,8.4658227848101255,8.5],"y":[7.7944996109358282,7.7326799536601918,7.6708602963845554,7.6090406391089225,7.547220981833286,7.4854013245576514,7.423581667282015,7.3617620100063803,7.2999423527307457,7.2381226954551092,7.1763030381794746,7.1144833809038381,7.0526637236282035,6.9908440663525688,6.9290244090769342,6.8672047518012977,6.8053850945256631,6.7435654372500284,6.681745779974392,6.6199261226987574,6.5581064654231209,6.4962868081474863,6.4344671508718516,6.372647493596217,6.3108278363205805,6.2490081790449441,6.1871885217693094,6.1253688644936748,6.0635492072180401,6.0017295499424037,5.9399098926667691,5.8780902353911326,5.816270578115498,5.7544509208398633,5.6926312635642269,5.6308116062885922,5.5689919490129558,5.5071722917373229,5.4453526344616865,5.3835329771860518,5.3217133199104154,5.259893662634779,5.1980740053591461,5.1362543480835097,5.074434690807875,5.0126150335322386,4.9507953762566039,4.8889757189809693,4.8271560617053328,4.7653364044296982,4.7035167471540618,4.6416970898784271,4.5798774326027925,4.5180577753271578,4.4562381180515214,4.3944184607758867,4.3325988035002503,4.2707791462246156,4.208959488948981,4.1471398316733445,4.0853201743977099,4.0235005171220735,3.9616808598464406,3.8998612025708042,3.8380415452951677,3.7762218880195348,3.7144022307438966,3.6525825734682638,3.5907629161926291,3.5289432589169927,3.4671236016413545,3.4053039443657216,3.3434842870900869,3.2816646298144505,3.2198449725388159,3.1580253152631812,3.0962056579875448,3.0343860007119101,2.9725663434362772,2.910746686160639],"text":"","type":"scatter","mode":"lines","name":"fitted values","line":{"width":3.7795275590551185,"color":"rgba(229,229,229,1)","dash":"solid"},"hoveron":"points","showlegend":false,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null}],"layout":{"margin":{"t":40.840182648401829,"r":7.3059360730593621,"b":37.260273972602747,"l":31.415525114155255},"paper_bgcolor":"rgba(255,255,255,1)","font":{"color":"rgba(0,0,0,1)","family":"","size":14.611872146118724},"title":{"text":"The Effects of Stress on Sleep by Occupation","font":{"color":"rgba(0,0,0,1)","family":"","size":17.534246575342465},"x":0,"xref":"paper"},"xaxis":{"domain":[0,1],"automargin":true,"type":"linear","autorange":false,"range":[5.665,8.6349999999999998],"tickmode":"array","ticktext":["6","7","8"],"tickvals":[6,7,8],"categoryorder":"array","categoryarray":["6","7","8"],"nticks":null,"ticks":"","tickcolor":null,"ticklen":3.6529680365296811,"tickwidth":0,"showticklabels":true,"tickfont":{"color":"rgba(77,77,77,1)","family":"","size":11.68949771689498},"tickangle":-0,"showline":false,"linecolor":null,"linewidth":0,"showgrid":true,"gridcolor":"rgba(235,235,235,1)","gridwidth":0.66417600664176002,"zeroline":false,"anchor":"y","title":{"text":"Average Sleep Duration","font":{"color":"rgba(0,0,0,1)","family":"","size":14.611872146118724}},"hoverformat":".2f"},"yaxis":{"domain":[0,1],"automargin":true,"type":"linear","autorange":false,"range":[2.6665590399218795,8.0386872571745869],"tickmode":"array","ticktext":["3","4","5","6","7","8"],"tickvals":[3,4,5,6,7,8],"categoryorder":"array","categoryarray":["3","4","5","6","7","8"],"nticks":null,"ticks":"","tickcolor":null,"ticklen":3.6529680365296811,"tickwidth":0,"showticklabels":true,"tickfont":{"color":"rgba(77,77,77,1)","family":"","size":11.68949771689498},"tickangle":-0,"showline":false,"linecolor":null,"linewidth":0,"showgrid":true,"gridcolor":"rgba(235,235,235,1)","gridwidth":0.66417600664176002,"zeroline":false,"anchor":"x","title":{"text":"Average Stress Level","font":{"color":"rgba(0,0,0,1)","family":"","size":14.611872146118724}},"hoverformat":".2f"},"shapes":[],"showlegend":false,"legend":{"bgcolor":null,"bordercolor":null,"borderwidth":0,"font":{"color":"rgba(0,0,0,1)","family":"","size":11.68949771689498}},"hovermode":"closest","barmode":"relative"},"config":{"doubleClick":"reset","modeBarButtonsToAdd":["hoverclosest","hovercompare"],"showSendToCloud":false},"source":"A","attrs":{"fa04d955c53":{"x":{},"y":{},"label":{},"colour":{},"type":"scatter"},"fa08e074f0":{"x":{},"y":{},"label":{},"colour":{}}},"cur_data":"fa04d955c53","visdat":{"fa04d955c53":["function (y) ","x"],"fa08e074f0":["function (y) ","x"]},"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.20000000000000001,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot","plotly_sunburstclick"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>

This boxplot compares sleep duration across sleep disorder groups.

![](README_files/figure-commonmark/unnamed-chunk-3-1.png)

### Interactive Shiny App

This project includes a Shiny app that allows users to:

- Filter occupations

- Select custom x and yaxis variables

- Generate scatterplots of sleep-related variables

- View summary statistics tables

- Explore sleep disorder distributions
