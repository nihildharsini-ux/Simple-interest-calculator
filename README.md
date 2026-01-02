Simple interest calculator

Objective:
To calculate Simple Interest using a servlet without database support.

Description:
User enters Principal (P), Rate (R), and Time (T) in an HTML form.

The servlet receives these values in the service() method, performs the calculation:
SI = (P * T * R) / 100
and prints the result to the browser.

HTML:
•	Form with P, R, T input fields

Servlet:
•	service() method
•	Input parsing from request
•	Output using PrintWriter
