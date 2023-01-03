# Committee for Public Counsel Services: Biased Prosecution
Team: Samantha Shih, Oliver Samuels, and Vedika Srivastava

## Committee for Public Counsel Services (CPCS) 
CPCS is a state criminal justice agency that provides legal representation to indigent people for cases in which people have a constitutional or statutory right to counsel.  Our practice areas include public defense, juvenile delinquency, mental health commitments, and child/family law.

## Project description
CPCS has access to 'DAMION Databases', which are prosecution databases created by prosecution agencies that contain a wealth of information about criminal proceedings.  We wish to have this data analyzed to potentially detect biased prosecution practices, such as pressing charges containing mandatory minimum sentences, subsequent/habitual offender enhancements, diversion vs pleas to lesser charges, etc.

## Column descriptions
The bolded columns are the features we focused on.

| Column      | Description |
| ----------- | ----------- |
| Status      | Whether the case is ongoing or closed       |
| **Nmbr Cs**   | **A unique identifier for each case**        |
| Id Prsn Dfndnt | A unique identifier for each defendant |
| **Offense Dt** | **When the offense happened** |
| **Court Code** | **Which court the case was heard in** |
| Chrg Cnt | How many counts of the charge a person faced |
| **Chrg Code** | **A code that connects the charge to a specific offense under the law** |
| Chrg Desc | A description of the charge including a legal reference for the offense |
| Case Type | Whether the case is a felony or misdemeanor case |
| Crime Type | Which broad category of crimes the charge belongs to (Larceny, Assault and Battery, etc.) |
| **Race** | **Defendant's race** |
| Gender | Defendant's gender |
| Judge | The name of, or an identifier for, the judge for the case |
| Disp Dt | When the case was disposed |
| **Disp Type** | **The specific kind of disposition the charge had (many options)** |
| Disp Code | What kind of disposition the charge had (a few groups) |
| Disp Desc | Which group of dispositions the disposition belongs to (following Disp Code) | Sentence code | An alphanumeric code indicating which kind of sentence the defendant got |
| **Sentence Translation** | **A text description of the sentence the defendant got if found/pled guilty** |
| Min Imp Jaill Term | The length of the minimum imposed jail term |
| Min Imp Jail Term Unt | The unit of the minimum imposed jail term (days, months, years) |
| Max Imp Jail Term | The length of the maximum imposed jail term |
| Max Imp Jail Term Unt | The unit of the minimum imposed jail term (days, months, years) |
| Min Imp Jaill Spnd Term | The length of the minimum imposed suspsended term |
| Max Imp Jaill Spnd Term | The length of the minimum imposed suspsended term |
| Max Imp Susp Jail Term Unt | The unit of the imposedsuspended term (days, months, years) |
| Min Actl Jaill Impsd Term | The lower end of the range of the jail/prison term the defendant was sentenced to |
| Min Actl Jail Imp Term Unt | The units of the minimum actual jail term (days, months, years) |
| Max Actl Jail Imp Term | The upper end of the range of the jail/prison term the defendant was sentenced to |
| Max Actl Jail Imp Unt | The units of the maximum actual jail term (days, months, years) |
| Code Fclty | The correctional facility the defendant was sentenced to serve in |
| Min Imp Cmnty Srvc Term | The length of the minimum community service term |
| Min Imp Cmnty Srvc Unt | The unit of the minimum community service term (days, months, years) |
| Max Imp Cmnty Srvc | The length of the maximum community service term |
| Max Imp Cmnty Srvc Unt | The unit of the maximum community service term (days, months, years) |
| Text Cmnt | Comments from prosecutors about the case or charge |
| Desc Ofcr Agncy | Which police department's officer(s) arrested the defendant |
