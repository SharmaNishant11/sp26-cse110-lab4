1. 3
   It will print 3 since i is of var type and can be accessed outside of the loop. In addition, the length of the price array is 3 and the loop increments i 3 times.

2. 150
   discountedPrice is of var type and can be accesed outside of the loop. Also, the last value that got calculated was 300 * 0.5 which is 150 and is assigned to discountedPrice.

3. 150
   finalPrice is also of var type and can be accesed at the end. Also, the last value that got calculated was Math.round(300*100/100) = 300 and was stored in finalPrice.

4. The function would return [50, 100, 150]. Since every variable is of type var, the code functions normally and the discounted prices is calculated and pushed onto the array giving [50, 100, 150]
   
5. Error: variable *i* is of type let so it cannot be accessed outside of the loop.
   
6. Error: variable *discountedPrice* is of type let so it cannot be accessed outside of the loop.

7. 150
   finalPrice has the scope of the function so at the end of the loop the finalprice is calculated as 150 ( 300*0.5 and then 300*100/100) which is then printed out

8. The function would return [50, 100, 150]. No variable is accessed outside of its scope and the code runs correctly. Discounted prices are calculated and pushed onto the array giving [50, 100, 150] 

9. Error: variable *i* is of type let so it cannot be accessed outside of the loop.
    
10. 3
    The code returns the length of the prices array which is 3.

11. The function would return [50, 100, 150]. No variable is accessed outside of its scope and the code runs correctly. 
    Length is never reassigned and since we are not reassigning the discounted array but rather modifying the content there is no error. Finally, discounted prices are calculated and pushed onto the array giving [50, 100, 150] 

12. A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]

13. A. 32 
    B. 1
    C. 3
    D. 3null
    E. 4
    F. 0
    G. 3undefined
    H. NaN

14. A. true
    B. false
    C. true
    D. false
    E. false
    F. true

15. == only checks the value but === checks the value and the data type.
    For example, 2=='2' would be true because both have the same value of 2. However, 2==='2' would be false since the types are different.

16. 
