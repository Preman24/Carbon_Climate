note: It is a grouped Final Year Project, where our topic must be aligned with one of the Sustainable Development Goals (SDGs)

# Title: Investigate the impact of carbon emissions on climate change

Climate change has always been an issue of concern for countries and people around the globe, as the composition of Earth’s atmosphere changes are caused by humans' worsening climate change. The rise in carbon emissions due to human activities has resulted in an increased concentration of greenhouse gases. The disruption of the gas balance leads to climate change and global warming. At current levels of global warming, there are already clear signs of adverse effects, and 2°C warming will have significant harmful consequences. Meanwhile, global warming has a direct effect on precipitation. More evaporation will result from increased warmth, which will increase the intensity of droughts and atmospheric humidity. Sea level rise under global warming may lead to an increased risk of storm surges. Consequently, more intense precipitation events will result from storms, whether they are tropical cyclones, isolated thunderstorms, temperature rains, or blizzards. This leads to the frequent occurrence of extreme climates. As climate change caused by increased carbon dioxide concentrations is irreparable within 1000 years of emissions ceasing, some countries have entered into contractual cooperation aimed at reducing the impacts of human activities on climate change. Examples include the International Agreement (Paris Agreement) and the United Nations Framework Convention on Climate Change (UNFCCC). Therefore, there is a need to study the causes and effects of carbon emissions and how carbon gases affect climate change. At the same time, the analyses and projections in this study will assist in the formulation and adjustment of policies to achieve the goal of sustainable development.

To achieve the goal of climate sustainability, this study aims to answer the following key questions:
1. What are the main sources of carbon emissions?
2. How do carbon emissions contribute to climate change?
3. What can be done to reduce carbon emissions and minimize climate impacts?
4. How do societal factors influence carbon emissions?

# Key Findings
Result 1.

=> Global carbon emissions increased steadily from about 25 billion tons in 2000 to nearly 34.5 billion tons by 2019, with a brief decline from 2018 to 2020 likely due to COVID-19-related economic slowdowns

=> While electricity and heat emissions rose until 2014 and then plateaued, sectors like transportation and manufacturing showed steady but slower growth; land use changes exhibited a fluctuating downward trend.

=> Electricity and heat generation are the largest contributors to carbon emissions, accounting for over 240 billion tons, followed by transportation and manufacturing, each contributing about 15-20%

Result 2.

=> Higher Carbon emissions correlate with increased average temperatures

=> Carbon emissions may disrupt the water cycle, altering precipitation patterns

=> Warmer temperatures are linked to more disasters, while the correlation between precipitation and disasters is weak (0.125), influenced by regional conditions and definitions of disasters

Result 3.

=> Compared with the 4 types of linear regression models to predict the carbon emission based on the societal factors
- Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net Regression

<img width="1183" height="584" alt="image" src="https://github.com/user-attachments/assets/f1458ae6-1a81-4423-9c55-d19f0be5f510" />


=> All models showed a good R2 performance above 0.9, indicating these models explain 90% of the variance in carbon emissions

=> Linear and Ridge models demonstrated better accuracy with MSE, RMSE, and MAE values all below 0.4, while Lasso and Elastic Net had higher error metrics, indicating weaker predictive capabilities despite high R2 values, but the Linear model was selected as the best predictive model in predicting carbon emissions

=> 3 scenario cases were developed to predict the trend from 2020 to 2030:
1. Best = all societal factors decrease by 10%
2. Base = the positive societal factors were selected to increase by 10% while the negative were selected to be decreased by 10%
3. Worst = all societal factors increase by 10%

=> The model prediction result: The observed decline in carbon emissions across all scenarios from 2020 to 2021 can be linked to COVID-19 restrictions halting many carbon-emitting activities. The best-case scenario demonstrates a consistent reduction in emissions, with projections indicating further decreases toward 2030 due to a 10% annual decrease in key features. In contrast, Case 3 anticipates a significant rise in emissions, driven by a 10% annual increase in factors like GDP and Energy Consumption. Meanwhile, Case 2 adopts a balanced approach that promotes economic growth and environmental sustainability through renewable energy, yet still shows an increase in emissions by 2030, highlighting the necessity for proactive measures to address carbon emissions effectively

Result 4.

=> The number of carbon-climate policies has shown to increase over the 2-decade period, which indicates the high severity of the situation, with the top 10 countries being mostly from developed countries, and the United States having the highest number, with almost 350 policies implemented

=> The policy sectors distribution showed 'Electricity and heat' with over 1400 policies implemented, indicating energy consumption plays a very big role in contributing to carbon emissions

=> The similarity of the policy objectives was divided based on 3 objectives: Mitigation, Adaptation, and Sustainable Development. The analysis showed Mitigation had a dominating number of countries, with over 140 implementing policies with this objective

=> The best policy effectiveness based on the policy objectives was 'Mitigation' and 'Sustainable Development' significantly reduce carbon emissions and climate impacts, with 'Mitigation' achieving the lowest changes in Carbon emissions and Precipitation, while 'Sustainable Development' minimizes Temperature and Climate-related Disaster changes; Adaptation also proves effective by reducing temperature change by 1.7 degrees Celsius, closely following Sustainable Development

=> As 'Mitigation' and 'Sustainable Development' were the most effective, word cloud analysis revealed the top 10 keywords implemented like 'Renewable' and 'Energy,' indicating a focus on clean energy transition, while collaboration with organizations such as OECD, IEA, and IRENA suggests enhanced effectiveness in achieving carbon and climate goals, alongside planned progress meetings and a tracking database for policy consistency


# Tools: Python, Pandas, sklearn, numpy, matplotlib, seaborn, nltk, wordcloud, plotly, scipy, collections, re 
