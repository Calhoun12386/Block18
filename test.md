1. A function called "multiplication" that returns the product of the two input numbers.

    Expect multiply(2,3) to be 6
    Expect multiply("2","3") to be a number 
    Expect multiply(-2,3) to be a negative number
    Expect multiply(-2,-3) to be a positive number
    Expect multiply("a","b") to be an error
    Expect multiply(2,"c") to be an error
    Expect multiply(5) to be an error
    Expect multiply(1,2,3) to be an error

2. A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.
    
    Expect concatOdds([1,2,3],[4,5,6]) to be an array
    Expect concatOdds([1,2,3],[3,2,1,1,-5]) to be [-5,1,3]
    Expect concatOdds([2,4,6,0],[8,10,12,0]) to be an empty array
    Expect concatOdds([],[]) to be an empty array
    Expect concatOdds(["a","b","c"],["d","e","f",]) to be an error
    Expect concatOdds([1,2,"c"],[1,2,"s"]) to be an error
    Expect concatOdds(["hello",true],["world",false]) to be an error

Functional Tests

3. A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.

- when the user checks out with an empty basket the should be shown an error and prompted to continue shopping.

- when the user is checking out they should have a link to continue shopping.

- when the user adds a item to the basket and uses the back button the recently item added is saved in the basket.

- when a guest logs in or creates an account durring the checkout their basket is saved.

- when a logged in user closes the browser their items are saved in the basket when they log back in.

- when the user checks out as a guest they should be asked if they want to create an account using the details they just entered.

- when the user is checking out they should be able to change quantities and delete items in the basket.
    