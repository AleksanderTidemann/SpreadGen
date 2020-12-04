# Accounting in MaxMSP

Tool designed to aid norwegian-based freelancers and small business owners fill out their [Income statement 1](https://www.skatteetaten.no/en/forms/income-statement-1/) RF-1175 ([næringsoppgave 1](https://www.skatteetaten.no/skjema/naringsoppgave-1/)). Uses document filenames to generate spreadsheets.

![income](/img/inntekt.png "Income spreadsheet preview")  

# How to use

## 1. Labeling

Every reciept and invoice has the same syntax and labeling "code":

 > "01.26.19 3400 430kr.pdf"
 
The formatting is as such; *mm/dd/yy - cost/income category - sum*. Section 9910 and 9900 of the RF-1175 form specifies a whole variety of cost and income categories. However, due to my fairly simple needs, this program only supports a general selections of these categories:

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

## 2 Drag & Drop

You can now drag and drop the entire folder onto the apps UI. By clicking "Eksporter" your spreadsheets will be generated as .csv files in the root dir.

![process](/img/process.gif)

Happy accounting!
