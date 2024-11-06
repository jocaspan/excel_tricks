# excel_tricks

Create a Formula to find the background colors property (38) of given cell. 

Formulas -> NameManager (NamensManager): You have to create the formula to be used afterwards

Click on new and give a name eg. color_filled

=ZELLE.ZUORDNEN(38;MonInpCfg!C2)

Repeat the same procedure if the color needed for another column. You CANNOT reuse the same formula as per limitaion in the relative path of excel. 
=ZELLE.ZUORDNEN(38;F2)"
