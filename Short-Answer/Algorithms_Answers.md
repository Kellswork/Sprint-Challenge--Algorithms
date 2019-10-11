#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)  a = 0 =>  c
    while a(a < n * n * n) => O(n)
    a = a + n * n => O(1)
    
    run time complexity => O(n)
    the while loops works based on the data that is given as n
    the loop runs n number of times no mater the value of n being calaculated
    the while loop would have to run based on n times at the end

b) sum = 0 => O(1)
    for i in range(n): => O(n)
      j = 1 => O(1)
      while j < n: => O(n)
        j *= 2 => O(1)
        sum += 1 => O(1)
    it's a nested loop, the loop runs based on the square of n.
    it first iterates through n in the for loop making the big O notation O(n)
    for the second loop, the while loop is also run based of n because the while loop ending is dependent on the value of n
    which makes the big O notation O(n), bring all together we have O(n^2) as the run time complexity


c) O(n)
    this is a recursive function with a run time complexity of O(n)
    because the amount of time the function is executed is dependent on the value provided as "bunnies"

## Exercise II
 - start from f - 1 floor and drop the eggs
 - check if the eggs break
 - if the eggs break, go down the floor again, check if the egg breaks
 - if they break, drop down to the next floor that's f-2, if it doesn't break return the current floor
 - run time complexity is O(f)

