# Assignment-3
Module 1
1) Hospitalisation Details-(using count if)15
   Medical Examination - 2
2) Replace values from ? to SEP
3) Medical examanitaion-refrence-new query-select the column-home-group by- count
4)R1013 -Most counted

Data transformation

1) Select the column-transform-split column-by delimiter- comma-left most-okay-trim-again select column-split column-by delimiter- space -left most-okay and re arrange the column name and give names to each

2) Select the number of surgeries- replace- value to find- no major sugery-replace with 0-okay
3)-select the column-Format- Trim, Clean, lower Case
4)if [BMI] = null then "Unknown"
else if [BMI] <18.5 then "Under weight"
else if [BMI] <25 then "Normal Weight"
else if [BMI] <30 then "Over Weight"
else "Obesity"

5)if [HBA1C] < 5.7 then "Normal"
else if [HBA1C] < 6.5 then "Prediabetes"
else "Diabetes"
6)Select all three columns-transform-merge-custom- dateof birth-using locale- date English us
7)=DATEDIF([@[Date of Birth]], DATE(2023,6,8),"Y")
8)select the column and change the signs to $
