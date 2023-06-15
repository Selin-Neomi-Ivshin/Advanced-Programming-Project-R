# **The relationship between gun control laws and incidents of mass shooting, with aspect of legislation on restricting firearm access for individuals with a history of substance abuse and alcohol issues**
---
---


## **The data:**
***

In our project we are using 2 data sets:

### **1. Data set "Mass Shooting":**

In the mass shooting data set each row represents an event of mass shooting and the different categories are features that characterize the event, most of the features are characterizing the shooter himself. Each subcategory is a column in the data set. 

The columns of this data set:

        o From the "Date" category, we used these subcategories:
                > Year - The year that the mass shooting occurred


        o From the "Location" category, we used these subcategories:
                > State - The state that the mass shooting occurred.


        o From the "Victims" category, we used these subcategories:
                > Number killed - The number of people that got killed in the mass shooting.
                > Number injured - The number of people that got injured in the mass shooting.


        o From the "Offender Background" category, we used these subcategories:
                > Age - The age of the offender.
                > Gender - The Gender of the offender. Male = 0, Female = 1. 
                > Race - The Race of the offender. White = 0, Black = 1, Latinx = 2, Asian = 3, Middle Eastern = 4, Native American = 5
                > Religion - The Religion of the offender. None = 0, Christian = 1, Muslim = 2, Buddhist = 3, Cultural spirituality/other = 4, Jewish = 5.
                > Military service - Were the offender at the military. No = 0, Yes = 1, Joined but did not make it through training = 2


        o From the "Crime And Violence" category, we used these subcategories:
                > Criminal Record - Whether an offender had a previous criminal history. No evidence = 0, Yes = 1
                > Part 1 Crimes - Different kinds of crimes the offender committed. No evidence = 0, Homicide = 1 Forcible rape = 2, Robbery = 3, Aggravated Assault = 4, Burglary = 5. This is a feature of type 'String' the numbers can be combined. 
                > Part 2 Crimes - Different kinds of crimes the offender committed. No evidence = 0, Simple assault = 1 Fraud, forgery, embezzlement = 2, Stolen property = 3, Vandalism = 4, Weapons offenses = 5. This is a feature of type 'String' the numbers can be combined.
                > Hate group association - Whether the offender had an association with a hate group. No evidence = 0, Hate group community association = 1, Other radical group association = 2, Inspired by a hate group but no direct connection = 3, Website or chat room postings relating to hate or hate groups = 4.


        o From the "Health and mental health" category, we used these subcategories:
                > Mental illness - kinds of mental illness the offender could have. No evidence = 0, Mood disorder = 1, Thought disorder = 2, Other psychiatric disorder = 3, Indication of psychiatric disorder but no diagnosis = 4. This is a feature of type 'String' the numbers can be combined.
                > Substance use and abuse - Whether the offender had an addiction. No evidence = 0, Problem with alcohol = 1, Marijuana = 2, Other drugs = 3. This is a feature of type 'String' the numbers can be combined.


        o From the "Weapons" category, we used these subcategories:
                > Firearm proficiency - The level of professionalism of the offender. No experience = 0, Some experience (some practice before shooting, grew up around guns, owned guns for a while before shooting) = 1, More experienced (held a permit or license, certifications or classes taken, more intensive practice before shooting) = 2, Very experienced = 3 (military, hunter, sharpshooter, years of consistent practice).
                > Total weapons brought to the scene - Number of weapons brought to the scene.
                
***


### **2. Data set "Laws":**

The columns of this data set:

        o State - The state the law has or don't have effect

        o Year - The Year the law has or don't have effect

        o The rest of the columns are subcategories. Each column consists of 2 values: value 0 - the law isn't in effect and value 1 - the law is in effect. Each category represent a set of laws that limit the purchase and possession of weapons related to a certain aspect. 
        
        We choose to concentrate on this categories: 

        > Dealer regulations - laws that regulate individuals who purchase firearms, such as age restrictions and background check requirements. These laws are designed to prevent individuals who are prohibited from possessing firearms, such as convicted felons from obtaining them.

        > Possession regulations - laws that regulate the possession of firearms, such as concealed carry permit requirements and restrictions on certain types of firearms. These laws are for ensuring that individuals who possess firearms do so responsibly and safely.

        > Assault weapons and large-capacity magazines - laws that regulate the possession of assault weapons and large-capacity magazines, such as bans on specific types of firearms and limits on magazine capacity. These laws are for reducing the likelihood of gun violence.

        > Child access prevention - laws that require firearm owners to take measures to prevent children from accessing firearms, such as storing firearms in locked containers. These laws are for reducing the number of accidental shootings involving children.

        > Gun trafficking - laws that regulate the trafficking of firearms, such as laws that prohibit gun trafficking across state lines. These laws are designed to prevent criminals from obtaining firearms through illegal means.

        > Immunity - laws that provide immunity to firearm manufacturers, dealers, and sellers from liability for damages resulting from the use of firearms. These laws are for protecting firearm manufacturers, dealers, and sellers from lawsuits filed by individuals who were injured or killed by firearms.

