
# Algortihm in Computing

We explored what algorithm is in this [article](what_is_algorithm_en.md). The question is, Why is algorithm so much related to computing? What advantage do we get in relating algorithm with computation?

With the notion of algorithm, comes the notion of **following** algorithms. Indeed, because there is no value in the text of the algorithm, rather following the algorithm to do something gives it the meaning.

Following an algorithm can be very arduous by hand. As an example, observe the following:

``` C++
Calculating the sum of an array A

1. Initial sum = 0.
2. Iterate through the elements of the array.
3. add each element to the value of sum.
```

Or in a more programming fashion, we can write:

``` C++
SUM(A)
    //Initially, the sum will be 0.
    sum = 0

    for i = 1 to A.length
        sum = sum + A[i]
    
    return sum
```

Let's say we have an array ${{arr} = \{1, 2, 3, 4\}}$. Now it is pretty easy to do it by hand, you will just have to add  ${1+2+3+4 = 10}$. But now generalizing, let's say the ${size}$ of the array ${arr}$ is ${10000}$, ${arr = \{a_1, a_2, ..., a_{10000}\}}$, it will definitely take quite some time to add ${10000}$ elements by hand, and it just grows worse as the ${size}$ of the ${array}$ increases.

Computer can do Billions of operations in an instant. It will be able to calculate the above within a fraction of second. Thus, the better choice will be to **channelize** this powerful device.

However, computer cannot think for itself. It can only follow the ***instructions*** given to it. And that ***Set of instructions*** can be called an algorithm. Thus, there is one key relationship between *algorithm* and *computers*.

---

### ***The proper utilization of computer comes with a proper algorithm.***

---

Computer has given us endless opportunities in computation, and that exploitation is only possible with an algorithm to follow. ***Thus, algorithm became the heart of computing***, and it is impossible to think of a good program without a good algorithm.


