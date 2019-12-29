# Accounting with MaxMSP

This is a tool which can aid norwegian based freelancers and small business owners to fill out their [Income statement 1](https://www.skatteetaten.no/en/forms/income-statement-1/) ([næringsoppgave 1](https://www.skatteetaten.no/skjema/naringsoppgave-1/)) RF-1175, by using image file names to generate spreadsheets.

Being a freelancer with sole proprietorship, I usually end up with a zillion screenshots, pdf´s and photos of reciepts and invoices every turn of the year. I therefore made this app to help organize and streamline my accounting in accordance with the RF-1175 operating income and cost sections 9910 and 9900.

![income](/img/inntekt.png "Income spreadsheet preview")  

## How to use

Generating spreadsheets by analyzing file names requires a system of file labeling. Every reciept and invoice has the same syntax and labeling "code":

 > "01.26.19 3400 430kr.pdf"
 
 > *mm/dd/yy - cost/income category - sum*

Section 9910 and 9900 of RF-1175 specifies many different cost and income categories. However, for my simple needs, the system only reads 11 main cost categories and 6 main income categories:

|           9910 - operating costs                         |           9900 - operating income   |            
|----------------------------------------------------------|:-----------------------------------:|            
| 4005 - varekostnad                                       | 3000 - salgsinntekt og uttak, avgiftspliktig
| 4500 - fremmedytelse                                     | 3100 - Salgsinntekt og uttak, avgiftspliktig innenfor merverdigavgiftsloven
| 6300 - leie av lokaler                                   | 3200 - Salgsinntekt og uttak, utenfor merverdigavgifts loven
| 6400 - andre leiekostnader                               | 3300 - Offentlige avgifter vedrørende salg
| 6500 - verktøy, inventar                                 | 3400 - Offentlige tilskudd/refusjon
| 6995 - kontorkostnader                                   | 3900 - Andre driftsinntekter
| 7165 - reise- og diettkostnader                          | 
| 7330 - salgs og reklamekostnader                         | 
| 7500 - forsikringspremie                                 | 
| 7700 - annen kostnad                                     | 
| 7098 - privat bruk av elektronisk kommunikasjon          | 
| 7080 - Bilkostnader. Bruk av bil i næring                | 




1. Specific file names. (kategorier)

2. Import folder into app

3. Click "eksporter". .csv format in source folder. 


insert gif


* App is in norwegian, but the income and expense category codes are the same. 
