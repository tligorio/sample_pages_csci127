
# Gradescope Help

Gradescope will allow multiple submissions until the project deadline. You are welcome to resubmit before the deadline if you do not get full credit, but **you cannot rely on Gradescope to debug your code. Your code must run free of errors on the Linux lab machines at Hunter before you submit to Gradescope.**    

**You are responsible for ensuring your submission goes through before the deadline.** I strongly encourage you to submit early to allow yourself the time to resolve issues. The UTAs  are available in the labs to help and you may ask questions on the blackboard forum, but you cannot expect to get help minutes before the project deadline.

Gradescope doesn't provide useful compilation messages when it fails to execute. Here are some things you should check:
  
## Autograder Failures/Error Messages Upon Submission:
- If "Test compiles" fails, all other tests will fail with a "No such file or directory" message. You need to determine why your submission does not compile. The best way to debug this is to compile it with g++ on Ubuntu Linux in the lab and check the compiler error messages.  

> The autograder failed to execute correctly. Contact your course staff for help in debugging this issue. Make sure to include a link to this page so that they can help you most effectively.

Getting this message upon submission? It is not a problem with the autograder but with your submission. Please check the following before posting on the forum or going to the UTAs for help:

- Did you submit ALL the required files? This includes checking that you submitted only the required .h or .hpp and .cpp files. Please do not submit extra files.

- Check the files you submitted to Gradescope. Do the names of the files MATCH EXACTLY the names on the project specification? File names are case sensitive. The file names and extensions MUST MATCH EXACTLY those of the required files in the project specfication.

- Re-read the project description: do you provide all required methods for all your classes? If not, provide stubs for partial credit.

- Does your program run error-free on the Linux lab machines? Programs that don’t compile locally will most definitely not compile on Gradescope. If not, debug it locally and resubmit when it correctly runs there.

- Did you initialize all your variables? C++ requires that you initialize all variables else you may get unexcpected behavior.

- Are you using print statements (std::cout) for testing? Make sure to delete these before submitting, especially if they are inside of a loop.

## "No such file or directory" error:
If you get "No such file or directory" error on all the tests or on all the tests for a particular class (you are failing all the tests), check the names and extension of your files and of your #include statements. These should match exactly what is requested on the project specification. Note that in this course we are using .hpp extension for the interface files, make sure you #include "ClassName.hpp"

**If you tried all of the above and nothing worked** you may post a message on the duscussion board or seek help from our TAs in the labs (see the lab schedule on the course main page).
