Click the below link for the output:
VERCEL LINK:https://age-calculator-app-main-hazel.vercel.app/


Introduction:
*This mini project is basically to calculate the exact age by taking the input of three thing:
        1:Day 
        2:Month
        3:Year
Languages Used:
1:HTML
2:TAILWINDCSS
3:JAVA SCRIPT
Code Explanation:
* we need to calculate the exact age to this current day;
* so, we are using Date object to know the date,month,year;
* date object is predefined it containes many methods which we can access to ;
* By getting the date,month,year of current using date object we are taking input values using id
* As the input the user is giving is string we are converting into integer by using ParseInt method

  CALCULATING YEAR:
  * we are subtracting current year and inputyear
 
  
  CALCULATING MONTH:
  * we are subtracting current month and inputmonth
  * but there some case where the current month is less than input month
  * Ex:june 12 is current month -july 15 is input month so such case need to be handled
  * After calculating month from step one if it is less than 0 just add 12 to your month and year--;


    CALCULATING DAYS:
  * we are subtracting current date and inputdate
  * but there some case where the current date is less than input date
  * Ex:june 12 is current date -july 15 is input date so such cases to be handled
  * { ageMonth--;
     const lastDayOfMonth = new Date(currentYear, currentMonth - 1, 0).getDate();
    ageDay += lastDayOfMonth;
    } by use this above code those cases are handled


    *after getting the days,month,year we are manipulating the styles accordingly.
