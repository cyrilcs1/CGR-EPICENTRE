Notes for the program 'cgrforepicentre'

This programs reads two seperate data, plot its CGR and compaare them using proximity index.

At first you may have to create an excel file with the zones numbers in wrt time as input data. Sample for input data is given is the excel file 'cgrindianplatev2totaldata.xlsx'. 
How this data is created can be seen by obseving the excel file 'total dta 1975-2018v3.xlsx'

 

Input data

Specify the name of excelfiles which contain EQ data in 'filename' and 'filename1'.

b03,b1,b2,b3,b4,b5 and b6 corresponds to the order of the CGR plots. (default value is 3,4,5,6,7,8 and 9 respectivley)


Outputs ( In workspace)

no1-Absolute value of number of data points lying in binboundary 'A'  for the EQ  data specified in 'filename'.
no2-Absolute value of number of data points lying in binboundary 'B'  for the EQ  data specified in 'filename'.
no3-Absolute value of number of data points lying in binboundary 'C'  for the EQ  data specified in 'filename'.
no4-Absolute value of number of data points lying in binboundary 'D'  for the EQ  data specified in 'filename'.

noo1-Absolute value of number of data points lying in binboundary 'A'  for the EQ  data specified in 'filename1'.
noo2-Absolute value of number of data points lying in binboundary 'B'  for the EQ  data specified in 'filename1'.
noo3-Absolute value of number of data points lying in binboundary 'C'  for the EQ  data specified in 'filename1'.
noo4-Absolute value of number of data points lying in binboundary 'D' for the EQ  data specified in 'filename1'.


percentno1- no1 in Percentage. 
percentno2- no2 in Percentage.
percentno3- no3 in Percentage.
percentno4- no4 in Percentage.

percentnoo1- noo1 in Percentage. 
percentnoo2- noo2 in Percentage.
percentnoo3- noo3 in Percentage.
percentnoo4- noo4 in Percentage.

similarityindexmatr- Row 1 :positive proximity indices of order b03,b1,b2,b3,b4,b5 and b6 respectivley.
similarityindexmatr- Row 2 :Negative k-mer indices of order b03, b1,b2,b3,b4,b5 and b6 respectivley. 
 ( The sum of same order positive and negative k-mer indices should be 0).

combinedthreebitbxad- boxadresses of CGR plot of order 'b03' (column 1 ) and its corresponding absolute and percentage values (col 2 and 3 respectivley) for 'filename'. 
combinedthreebitbxad1- boxadresses of CGR plot of order 'b03' (column 1 ) and its corresponding absolute and percentage values (col 2 and 3 respectivley) for 'filename1'. 

(1234 in adress corresponds to respective bin boundaries , in order use a diiferent set of characters or numerals to represent binboundaries modify the variable 'letters'.)

combinedfrbitbxad- boxadresses of CGR plot of order 'b1' (column 1 ) and its corresponding absolute and percentage values (col 2 and 3 respectivley) for 'filename'. 
combinedfrbitbxad1- boxadresses of CGR plot of order 'b1' (column 1 ) and its corresponding absolute and percentage values (col 2 and 3 respectivley) for 'filename1'. 

combinedfivebitbxad,combinedsixbitbxad,combinedsevenbitbxad,combinedeitbitbxad,combinedninebitbxad :- Same as combinedthreebitbxad , but of order b2,b3,b4,b5and b6 respectivley.
combinedfivebitbxad1,combinedsixbitbxad1,combinedsevenbitbxad1,combinedeitbitbxad1,combinedninebitbxad1 :- Same as combinedthreebitbxad1 , but of order b2,b3,b4,b5and b6 respectivley.



Figures

Fig1:-   CGR PC plot of order b03 (left to right)  of 'filename' and 'filename1'.
Fig 2 :- CGR PC plot of order b1 and b2 (left to right)  of 'filename'.
Fig 3 :- CGR PC plot of order b3 and b4 (left to right)  of 'filename'.
Fig 4 :- CGR PC plot of order b5 and b6 (left to right)  of 'filename'.

Fig 5 :- CGR PC plot of order b1 and b2 (left to right)  of 'filename1'.
Fig 6 :- CGR PC plot of order b3 and b4 (left to right)  of 'filename1'.
Fig 7 :- CGR PC plot of order b5 and b6 (left to right)  of 'filename1'.




The figures obtained  have to be modified in type of coloring and Color datamax values for a better dispaly.Sample template for PC plots of order 4,5 and 6 are attached.