# **The relationship between gun control laws and incidents of mass shooting, with aspect of legislation on restricting firearm access for individuals with a history of substance abuse and alcohol issues**
---
---


## **Advanced Data Analysis in R**
***
This is a R-language project which was created as part of "Advanced Data Analysis in R" course in Ben Gurion University, Israel.

To replicate our analysis, please follow the next steps:
        o Place the two data sets "Mass Shootings" and "Laws" at the same folder.

        o Change the `Mass Shootings.xlsx` file name to `Excels/mass shooting.xlsx`.

        o Change the `Laws.xlsx` file name to `Excels/laws.xlsx`. 

        o Run the `Report Fin.rmd`

The output of this file is identical to the results we presented in the submitted report.


## **The data:**
***

In our project we are using 2 data sets:

### **1. Data set "Mass Shooting":**

In the mass shooting data set each row represents an event of mass shooting and the different categories are features that characterize the event, most of the features are characterizing the shooter himself. Each subcategory is a column in the data set. 

The columns we have used from this data set:

        o From the "Date" category, we used these subcategories:
                > Year - The year that the mass shooting occurred


        o From the "Location" category, we used these subcategories:
                > State - The state that the mass shooting occurred.


        o From the "Victims" category, we used these subcategories:
                > Number killed - The number of people that got killed in the mass shooting.
                > Number injured - The number of people that got injured in the mass shooting.


        o From the "Crime And Violence" category, we used these subcategories:
                > Part 2 Crimes - Different kinds of crimes the offender committed. No evidence = 0, Simple assault = 1 Fraud, forgery, embezzlement = 2, Stolen property = 3, Vandalism = 4, Weapons offenses = 5. This is a feature of type 'String' the numbers can be combined.


        o From the "Health and mental health" category, we used these subcategories:
                > Substance use and abuse - Whether the offender had an addiction. No evidence = 0, Problem with alcohol = 1, Marijuana = 2, Other drugs = 3. This is a feature of type 'String' the numbers can be combined.


***


### **2. Data set "Laws":**

The columns we have used from this data set:

        o State - The state the law has or don't have effect

        o Year - The Year the law has or don't have effect

        o The rest of the columns are subcategories. Each column consists of 2 values: value 0 - the law isn't in effect and value 1 - the law is in effect. Each category represent a set of laws that limit the purchase and possession of weapons related to a certain aspect. 
        
        We have combined significat subcategoris of laws under one category (using the codebook give with the data set). We choose to concentrate on this categories: 

        > Dealer regulations - laws that regulate individuals who purchase firearms, such as age restrictions and background check requirements. These laws are designed to prevent individuals who are prohibited from possessing firearms, such as convicted felons from obtaining them.

        > Inspections and Liability on Providers: Periodic inspections and holding sellers accountable for compliance with firearm sales regulations.

        > Buyer Permit & Background: Requirement for background checks and permits when purchasing firearms.

        > Age Restrictions on Firearms: Minimum age limits for purchasing or possessing firearms.

        > Ammo Restrictions: Regulations on the sale, possession, or use of ammunition.

        > Felony: Serious criminal offense punishable by imprisonment exceeding one year.
        
        > Imprisonment more than a year: Punishment for certain criminal offenses with imprisonment exceeding one year.

        > Danger to Himself or Others: Restrictions on firearms for individuals posing a risk of harm.
        
        > Mental Health: Considerations to prevent individuals with certain mental health conditions from accessing firearms.
        
        > Substance Abuse: Restrictions on firearm ownership for individuals with a history of substance abuse.

        > Public Carry: Laws governing the carrying of firearms in public places.
        
        > School and College Carry: Regulations on carrying firearms on educational institution premises.

        > Firearms Relinquishment: Legal processes requiring individuals to surrender or dispose of firearms.

        > Assault Rifles Ban: Restricting or prohibiting sale, possession, or use of firearms classified as assault rifles.

        > Magazine Ban: Limiting or prohibiting high-capacity magazines for firearms.
