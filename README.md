# Interview-Practice-Full-Stack
Interview Practice Questions from Udacity Full Stack Nanodegree

1.<i><b> What is the most influential book or blog post you’ve read regarding web development?</b></i><br>
  I have not read a book or a blog post regarding web development. But what influenced me to learn this field was a video that I saw on Udacity's website. It was a student success story of a student that ended up working at Google.
  I got interested in programming in general since I was little. I used to play games and wonder how they were made. Then websites came along as I grew up and again I was wondering how they were made. The time came to choose my profession and I chose programming. Web development and specifically full stack is what I chose to learn because I wanted to be able to build something and to build it from scratch. Throughout the course we've built several projects and I enjoyed the process as well ass seeing the end result.<br>
2. <i><b>Tell me about a web application you have built. Why did you choose to build it? What did you learn? What challenges did you face and how did you overcome them?</b></i><br>
  I want to tell you about first web page I ever built. I chose to build it, because I was curious to see how is it done. I learned that it is not as hard as it seemed and that with enough time and effort you can build any web application you want. Every step of the way was a bit of a challenge since I knew nothing about programming. So I did a bit of research using Google and voilà there was a web page with my name on it that I wrote in a simple notepad.<br>
3. <i><b>Write a function in Python that takes a list of strings and returns a single string that is an HTML unordered list (< ul > ... < /ul >) of those strings. You should include a brief explanation of your code. Then, what would you have to consider if the original list was provided by user input?</b></i>
```
#define a list with strings
languages = ["Python", "HTML", "CSS", "JavaScript"];
  
#define a function that takes in a list and return unordered html list
def htmlList (list):
  ulList = "<ul>"
  #iterate through a list and return a list item
  for i in list:
    ulList += "<li>" + i + "<li>"
  ulList += "<ul>"
    
  return ulList
    
htmlList(languages)
```

Things to consider if the original list was provided by user input:
- Possible html/script injection. To prevent this I would escape the data received by the user input.
- Format of the input. To make sure the input is a string I would put a conditional statement.
<br>
4. <i><b>List 2-3 attacks that web applications are vulnerable to. How do these attacks work? How can we prevent those attacks? </b></i><br>

5. <i><b>Expand on the starter code and include a route that simulates rolling two dice and returns the result in JSON. You should include a brief explanation of your code.</b></i>

6. <i><b>If you were to start your full-stack developer position today, what would be your goals a year from now?</b></i><br>
