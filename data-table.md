
| ID | Department | Salary      | Location |
|----|------------|-------------|----------|
| 6  | Marketing  | $60,000.00  | London   |


| ID | Name  | Age | Department | Salary      | Join Date | Location | Manager    |
|----|-------|-----|------------|-------------|-----------|----------|------------|
| 1  | Alice | 30  | HR         | $50,000.00  | 1/15/2021 | Baku     | John Doe   |
| 2  | Bob   | 25  | IT         | $55,000.00  | 3/22/2022 | New York | Jane Smith |
| 3  | Carol | 27  | Marketing  | $60,000.00  | 6/10/2020 | London   | Alice Lee  |
| 4  | Dave  | 35  | IT         | $70,000.00  | 8/30/2019 | New York | Jane Smith |
| 5  | Eve   | 29  | HR         | $52,000.00  | 2/18/2023 | Baku     | John Doe   |
| 6  | Frank | 40  | Finance    | $75,000.00  | 11/5/2018 | Istanbul | Robert Brown |
| 7  | Grace | 32  | Marketing  | $62,000.00  | 7/19/2021 | London   | Alice Lee  |
| 8  | Henry | 28  | IT         | $58,000.00  | 9/25/2022 | New York | Jane Smith |

___________________________________________________________________________________________________________________
EXPLANATION						
FORMULA => =XLOOKUP(B3,A7:A15,CHOOSECOLS(A7:H15,4,5,7))						
						
Cell B3: Contains the dynamic search value, which is the ID number you are searching for.						
Range A7:A15 : This range contains the list of ID numbers you are searching against.						
Function CHOOSECOLS(A7:H15, 4, 5, 7): This function selects columns 4, 5, and 7 from the range A7.  It retrieves data from these specific columns for the matched ID.						
Range A7:H15 :: Represents the entire table from which data is retrieved, excluding headings.						
Columns 4, 5, and 7: Specify the column numbers from which you want to retrieve data.			
____________________________________________________________________________________________________________________

