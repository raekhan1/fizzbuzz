# fizzbuzz
counter3 = 0
counter5 = 0

for i in range (0,100):
    
   if counter3 == 3 and counter5 == 5:
        print("fizz buzz")
        counter3 = 0
        counter5 = 0
        
   elif counter3 == 3:
        print ("fizz")
        counter3 = 0
    

   elif counter5 == 5:
        print ("buzz")
        counter5 = 0
               
   else:
        print (i)

   counter3 += 1
   counter5 += 1
