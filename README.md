# WSD-CAC

rajesh Pv
2147126


i have made a sample website for christ university and have included forms such as contact form ,feedback form and a user-login ( student login,teacher login and internet login)forms.
the site has being hosted under netlify.app for live experience of the form.
 



This forms in the website  validates for
  
1.name field: 	*locks numeric input
		*accepts username of varying of length between 2 to 20.
		eg: Om , RAJESH
		* accepts no special characters.
		*it will highlight the field as RED colour if there is any violation, else GREEN indicating valid input.




2.Phone Field : *locks alphabet inputs 
		*restricts input of special characters
		* input length should be exactly 10, any input less than 10 digits or greater than 10 digits marked as violation
		*it will highlight the field as RED colour if there is any violation, else GREEN indicating valid input.

3.Email Feild : *allows alphanumeric and special character inputs such as ( @ , - )
		* only input for '@' symbol in a mail.
		*accepts only domain specific mail address such as example@christuniversity.in . Any mail adress such as example@gmail.com or 
		example@yahoo.coom etc, marks as an violation and highlights RED .
		*only when specified domain mails are entered  , its is considered to be a valid email and turns the feild into GREEN indidicating a valid mail
		eg:- rajeshpv@christuniversity.in
		     2147126@christuniversity.in

3. Password Field :* minimum length of password should be 8.
		   *it must include atleast one numeric input anywhere in the string (0-9).
		   *it must include atleast one lower case character anywhere in the string (a-z).
		   *it must include atleast one upper case character anywhere in the string (A-Z).
		   it must include atleast one special character input (@$!%*?&])[A-Za-z\d@$!%*?&).
	
