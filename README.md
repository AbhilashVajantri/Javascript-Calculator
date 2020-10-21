# Javscript-Calculator
    •	The Background colour is displayed using the statement,
Bgcolor = ”#D0D0D0”
    •	A text field of size=36 is applied to the form “form1”. The buttons, that contain the digits and operators, are displayed on the form. For example, button “7” is displayed using the statement, <TD><Input type=”button” value=”7” onClick=”calc(‘7’)”>
    •	When the button with the label 7 is clicked, the function “calc()” is called by passing a value 7 to the function. The calc() function will store this value in the variable ‘ch’.

If this value in ch is not equal to ‘=’ or ‘C’, the value is displayed on the text field “text” through the statement, document.form1.text1.value += ch;

This process is carried out till ch is not equal to “=” or “C”. When the ‘=’ button is clicked, the value is stored in ch and so the statement.
document.form1.text1.value = eval(document.form1.text1.value);
is evaluated. The function eval() will evaluate the expression which is formed by the string, by converting the string to numerical values of appropriate data type. This value is then displayed in the text field.
    •	If the button “C” is clicked, ch will contain the value ‘C’, and the statement,
document.form1.text1.value = “”;
	will be executed and a blank character will be displayed in  the text field.
	
