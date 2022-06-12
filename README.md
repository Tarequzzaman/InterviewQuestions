# InterviewQuestions
Feel free to add questions on each sections  or you can add another sections like Java, Javascript , go etc. Just send me a pull request. Please read questions carefully before sending pull request. We do not add repeated questions


# Python
1. Tell me about mutable and immutable functions
2. What are the mutable and immutable datastructure in python 
3. Tell me about generator function. 
4. How generator function works 
5. How lumbda function works ?
6. Can you please explian lumbda function 
7. Is there any restriction on input variable of Lumbda function ? 
8. Tell me about list comprehension with an example 
9. what is loose couping 
10. Explain python namespace 
11. Pyhton garbage collection 
12. Does pyhton support multiple inheritence? If yes the explain how multiple inheritance works in python 
13. Variable scope in pyhton. tell me the output of this code 
    ```python
    temp = 10
    def func():
        temp = 20
        print(temp)
    print(temp)
    func()
    print(temp)

    ```

14. Expain Stack queue. 
15. Expain map on python. (filter and reduce)
16. Is python string are immutable ? Expalin with an example
17. Imagine that you have a lumbda function which take a variable and squire it? If I provide you a list of numners how can your squire them?  
Solutions: <br>
    Way 1: 
    ```python
    data = lambda x: x ** 2
    numbers = [1, 2, 3, 4]
    output = []
    for number in numbers:
        output.append(data(number))
    print(output)
    ```
    Best Way: 
    ```python 
    numbers = [1, 2, 3, 4]
    result = map(lambda x: x ** 2, numbers)
    print(list(result))
    ```

# Django 
1. Explain Django middlewire 
2. Have you written any custom middlewire by yourself? If yes then please explain me how ?
3. Hove you ever use decorator function 
4. Write a code for decorator as caching 
5. Is django support multilayer docorator? If support then tell me which order are they works 
6. Django request lifecycle 
7. How django get data from database? or Explan how orm works 
8. How django solve n+1 complex query 
9. What is the difference between select related and prefetch related 
10. Tell me the difference between get and filter method 
11. Pickling QuerySets
12. If the request data is not available which status code will invioked ? <br>
404
13. Write the bast practice of writing django URLs. 
 



# Django rest Framework
1. What is the perpose of serialization ? 
2. What is the benifit of using DRF? 
3. What problem solve by DRF? 
4. Write a class based view for crud operaton 
5. what need to import while creating a class based view? <br>
   Answer: APIView

   

