# Pymaceuticals analysis by using matplotlib
It is a set of data of Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

# Analysis
- A set of Capomulin and Ramicane data presents well that actual population than other drug data. That's standard of deviation (STD) and the standard error of the mean(SEM) are 4.994774 / 0.329346 (Capomulin), 4.846308 / 0.320955 (Ramicane)

<img
  src="image\avg_std.jpg"
  width="500"
  height="350"
/>

- Capomunlin and Ramicane is tested more than others.

<img
  src="image\test_number.jpg"
  width="500"
  height="350"
/>

- The ratio of sex was very close(Male:51%, Female: 49%). This allow you to control the error from gender differnces and to represent gender well

<img
  src="image\sex.jpg"
  width="500"
  height="350"
/>

- - Break up the treatment into two groups by Drug Regimen :
> + The first group: 'Capomulin'and 'Ramicane'
> + The second group: 'Infubinol'and 'Ceftamin'

    1. There is likely to be a similarity between'Capomulin'and 'Ramicane'(The first group). And There is likely to be a similarity between 'Infubinol'and 'Ceftamin'(The second group). However there is likely to be a difference between the two groups. Because the median line of a box plot lies outside of the box of another group's box plot.   
    2. The first group('Capomulin'and 'Ramicane') produces more consistent and effective results than the second group('Infubinol'and 'Ceftamin'). The box of the first group is shorter than that of the second group. It is mean that the data of the first group is less dispersed.   
    3. However There is more scattered data in Capomulin, Ramicane and Infubinol than Ceftamin. The whiskers of Ceftamin is shoter than others.

<img
  src="image\box.jpg"
  width="500"
  height="350"
/>    

- Capomulin drug has the effect of reducing tumor volume after a certain period of time.(mouse id 'l509' shows)

<img
  src="image\time.jpg"
  width="500"
  height="350"
/>   

- There is a positive correlation between weight and tumor volume(0.84).
- We can predict that the volume of the tumor will increase as the weight increases through linear regression analysis. But it does not mean that weight causes volume of the tumor

<img
  src="image\linear.jpg"
  width="500"
  height="350"
/>  