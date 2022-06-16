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
   <br> Answer: You can find the answer [here](https://scoutapm.com/blog/django-and-the-n1-queries-problem#:~:text=Tools%20to%20Fix%20the%20N,model%20alongside%20the%20original%20query.)
9. What is the difference between select related and prefetch related 
<br> Answer: you can find a solid answer [here](https://stackoverflow.com/questions/31237042/whats-the-difference-between-select-related-and-prefetch-related-in-django-orm)

10. Tell me the difference between get and filter method <br>

    `filter()` will always give you a `QuerySet`, even if only a single object matches the query - in this case, it will be a QuerySet containing a single element.

    If you know there is only one object that matches your query, you can use the `get()` method on a Manager which returns the object directly:
    ```python
     one_entry = Entry.objects.get(pk=1)
    ```
    You can use any query expression with get(), just like with filter() - again, see Field lookups below.

    <i>Note that there is a difference between using get(), and using filter() with a slice of [0]. If there are no results that match the query, get() will raise a DoesNotExist exception. This exception is an attribute of the model class that the query is being performed on - so in the code above, if there is no Entry object with a primary key of 1, Django will raise Entry.DoesNotExist.</i>



11. Pickling QuerySets
12. Write the bast practice of writing django URLs. 
 



# Django rest Framework
1. What is the perpose of serialization ? 
2. What is the benifit of using DRF? 
3. What problem solve by DRF? 
4. Write a class based view for crud operaton 
5. what need to import while creating a class based view? <br>
   Answer: APIView

# REST API
- Explain REST API Design Principles<br>
  Answer: You can find it [here](https://www.astera.com/type/blog/rest-api-definition/)
    
- Tell me the different HTTP status code of REST API  

   Answer: You can find it [here](https://restfulapi.net/http-status-codes/)
- If the request data is not available which status code will invioked ? <br>
Status code: 404

# System Design & TDD
- Do you have ever implmented your code with SOLID principle? if YES then Explain solid principle
- How unit test is related to SOLID principle 
- What are the befinfits of Unit test
- What step should follow when designing a system 
- Which two key item you taking care when writing any kinda code.
- Design a system which can upload content 
    requirements: 
          - System launched in 3 countries (Canada, Singapore , Australia)
        
- Design a system for parking mantainance. Mention that what step you follow and describe each step 


# Data Structure
- What are the disadvantages of Hashing Algorithm 




