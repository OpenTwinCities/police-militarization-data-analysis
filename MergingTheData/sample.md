| Feature | Py DataType | Description | Source | Original Column Name|
| :--- |:---:|:---:|:---:|---:|
| OriginatingFile|object|File name and sheet from which record comes.|[LESO](https://www.dla.mil/DispositionServices/Offers/Reutilization/LawEnforcement/PublicInformation/)|n/a|
| StateAbbreviation|object|Postal abbreviation for a US state or territory.|[LESO](https://www.dla.mil/DispositionServices/Offers/Reutilization/LawEnforcement/PublicInformation/)|State|
| RequestingAgency|object|Law Enforcement Agency name|[LESO](https://www.dla.mil/DispositionServices/Offers/Reutilization/LawEnforcement/PublicInformation/)|Station Name (LEA)|
| ItemDescription|object|Description of item being ordered.|[LESO](https://www.dla.mil/DispositionServices/Offers/Reutilization/LawEnforcement/PublicInformation/)| Item Name|
| RecordDate|object|Date on the original record.|[LESO](https://www.dla.mil/DispositionServices/Offers/Reutilization/LawEnforcement/PublicInformation/)| varies by file|
| AcquisitionValue|float64|Value in dollars of acquisition.|[LESO](https://www.dla.mil/DispositionServices/Offers/Reutilization/LawEnforcement/PublicInformation/)| Acquisition Value|
| Quantity|int|Number of units requested.|[LESO](https://www.dla.mil/DispositionServices/Offers/Reutilization/LawEnforcement/PublicInformation/)| Quantity|
| UnitIncrement|object|Increment of units requested.|[LESO](https://www.dla.mil/DispositionServices/Offers/Reutilization/LawEnforcement/PublicInformation/)|UI|
| AgencyType|object|Derived station type based on RequestingAgency.|derived||
| Item_FSG|object|Federal Supply Group Number|[LESO](https://www.dla.mil/DispositionServices/Offers/Reutilization/LawEnforcement/PublicInformation/)||
| Item_FSC|object|Federal Supply Classification.|[LESO](https://www.dla.mil/DispositionServices/Offers/Reutilization/LawEnforcement/PublicInformation/)||
| Item_CC|object|Country of origin from National Codification Bureau (aka NCB).|[LESO](https://www.dla.mil/DispositionServices/Offers/Reutilization/LawEnforcement/PublicInformation/)||
| Item_Code|object|Non-standard item code.|[LESO](https://www.dla.mil/DispositionServices/Offers/Reutilization/LawEnforcement/PublicInformation/)||

[source](https://towardsdatascience.com/creating-a-dataset-from-scratch-b8e2f8752436)


_italics_
**bold**
_mix **and** match_
###Headers

>block quoting text

>can span multiple

>paragraphs

* unnumbered A
    1. numbered B
 
    And a paragraph separated by a hard break (extra line) inside a list
  
  > and a quote
    2. numbered B
        * unnumbered C
        * unnumbered C
        * unnumbered C
    3. numbered B
* unnumbered A  
    this line is separated from the above and below by two blank spaces at the end  
    > and so on
* unnumbered A


![this is an image](https://github.com/barbh1307/police-militarization-data-analysis/blob/barbh1307-patch-1/MergingTheData/Images/DISP_AllStatesAndTerritoriesXLXS.png)
![another image][in doc link]
[inline link](https://www.markdowntutorial.com/lesson/3/)
[reference link][another place in doc]

[another place in doc]: https://www.markdowntutorial.com/lesson/3/
[in doc link]: https://github.com/barbh1307/police-militarization-data-analysis/blob/barbh1307-patch-1/MergingTheData/Images/DISP_Shipments_CancellationsXLSX.png
