# Phishing Page Classifier

## Problem Statement 

One of the challenges faced by our research was the unavailability of reliable training datasets. In fact, this challenge faces any researcher in the field. However, although plenty of articles about predicting phishing websites using data mining techniques have been disseminated these days, no reliable training dataset has been published publically, maybe because there is no agreement in literature on the definitive features that characterize phishing websites, hence it is difficult to shape a dataset that covers all possible features.

In this article, we shed light on the important features that have proved to be sound and effective in predicting phishing websites. In addition, we proposed some new features, experimentally assign new rules to some well-known features and update some other features.


## Dataset

The following data files have been provided 

# Data Description:

<h><b>The dataset consists of different columns with information regarding whether a website is a phising website or not.</b></h><br>

The columns are :

-having_IP_Address [-1  1] YES=1 NO=-1

-URL_Length [ 1  0 -1]

-Shortining_Service [ 1 -1]

-having_At_Symbol [ 1 -1]

-double_slash_redirecting [-1  1]

-Prefix_Suffix [-1  1]

-having_Sub_Domain [-1  0  1]

-SSLfinal_State [-1  1  0]

-Domain_registeration_length [-1  1]

-Favicon [ 1 -1]

-port [ 1 -1]

-HTTPS_token [-1  1]

-Request_URL [ 1 -1]

-URL_of_Anchor [-1  0  1]

-Links_in_tags [ 1 -1  0]

-SFH [-1  1  0]

-Submitting_to_email [-1  1]

-Abnormal_URL [-1  1]

-Redirect [0 1]

-on_mouseover [ 1 -1]

-RightClick [ 1 -1]

-popUpWidnow [ 1 -1]

-Iframe [ 1 -1]

-age_of_domain [-1  1]

-DNSRecord [-1  1]

-web_traffic [-1  0  1]

-Page_Rank [-1  1]

-Google_Index [ 1 -1]

-Links_pointing_to_page [ 1  0 -1]

-Statistical_report [-1  1]

-Result [-1  1]

## Data Analysis

### CountPlots of All columns
<div style="text-align:center">
<img src="./images/g1.png"/>
</div>
Now, we observe that the features of all columns using countplots to chechk the counts of each class in particular column.
<div style="text-align:center">
<img src="./images/g2.png"/>
</div>
### violinplot of all columns
<div style="text-align:center">
<img src="./images/g3.png"/>
</div>

<div style="text-align:center">
<img src="./images/g4.png"/>
</div>
### Barplot of Target Column
<div style="text-align:center">
<img src="./images/result.png"/>
</div>
