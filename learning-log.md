Started : aug 5 2026

Aug 5 - studied about uv(init,add,remove), decorators, generators/iterators(essential) and context managers.

Aug - 6 studied file handling mainly use of with.

Aug 7 - studied modules/packages and json

Still I'll study json Tommorow too.

Aug 8 - studied json and it's structure how to access data while accessing we can do it either by list method ([int]) or dictionary method([""]), it has different data types and

mainly -

load - loads the json into python dictionary.

loads - serialise json string to python dictionary.

Dump - dumps python dictionary into file as json .

dumps -  serialise python dictionary to json string .

Also studied CSV and it's structure it is mainly rows and columns, stores everything as string and iteration is done through rows and

mainly -

reader - with this we can access the data like list

DictReader - with this we can access the data like dictionary not related dictionary just the method like row[""] but we still have to iterate through like list

DictWriter - takes two arguments first the file where to write second fieldlines

Writeheader - writes the fildelines as header

Next - if used reader then it skips the header

Writerow - writes one row

Writwrows - writes all the rows

Aug 9 - today I studied type hint(mypy) in it -

![Study note image](assets/image-01.jpeg)

the basic thing about mypy is that it checks and tell us if the type hints are beginning followed or not and python will run the program and won't consider type hints they are just for developers to see and understand what it's output and more are meant to be and in it -

Also studied uv -

![Study note image](assets/image-02.jpeg)

Also studied exception handling in it

Try - try this if error occurred try except

Except - if error occurs do this

Else - if no error occur

Finally - do this no matter what

Raise - we raise error by ourself

Aug 10 - completed expection handling

![Study note image](assets/image-03.jpeg)

Aug 11 - completed logging, the 5 levels are not mentioned here

![Study note image](assets/image-04.jpeg)

![Study note image](assets/image-05.jpeg)

Aug 12 - completed pytest -

I think I will easily forget a lot of functions and mostly the writing schema but most probably remember the working of it, which I think is the main part

![Study note image](assets/image-06.jpeg)

Aug 13 - didn't do much practices pytest a bit mostly the async with patch part and again studying OOP (classes, inheritance), decorators, generators, iterators,

context manage because I studied them through YouTube so it was almost an overview in other words I skipped oops because I studied them a while ago but don't remember them much and the rest topics were studied via YouTube so I think that not all topics of it were covered and I didn't grasp it.

For example -  I saw a video of tech with tim on pytest it has the topics till manual mock creation but further topics like async and patch were mentioned so like I said the topics I studied through YouTube might be missing some topics so I'll study them again mostly through chatgpt but also watch some more videos

Aug 14 -

![Study note image](assets/image-07.jpeg)

Also studied ABC and abstract methods

Aug 15 -

![Study note image](assets/image-08.jpeg)

![Study note image](assets/image-09.jpeg)

![Study note image](assets/image-10.jpeg)

![Study note image](assets/image-11.jpeg)

Aug 16 -

![Study note image](assets/image-12.jpeg)

Aug 17 - today I studied

![Study note image](assets/image-13.jpeg)

Also some introduction to git and GitHub mainly decided to watch code with Harry git and GitHub tutorial for beginners (full course video).

Yes I admit that I didn't study much, these topics are not lengthy enough for a day, I'll try to be productive enough each day and continue my learning.

Aug 18 - watched the code with Harry git and GitHub tutorial for beginners (full course video) till branches.

Aug 19 - completed the code with Harry git and GitHub tutorial for beginners (full course video).

Aug 20 - light study - reviewed the code with Harry git and GitHub tutorial for beginners (full course video).

September 16 - i studied general sql syntax and relational databases concepts. this was not specifically mysql or postgresql, later in the roadmap i'll study postgresql and i'll consider mysql separately if it becomes useful

![Study note image](assets/image-14.jpeg)

September 17 -

![Study note image](assets/image-15.jpeg)

September 18 -

![Study note image](assets/image-16.jpeg)

September 19 -

![Study note image](assets/image-17.jpeg)

September 20 -

![Study note image](assets/image-18.jpeg)

September 21 -

![Study note image](assets/image-19.jpeg)

![Study note image](assets/image-20.jpeg)

September 22 -

![Study note image](assets/image-21.jpeg)

![Study note image](assets/image-22.jpeg)

![Study note image](assets/image-23.jpeg)

Key takeaway - numpy is faster than normal python code and the reason why it is that even though we use python syntax, a lot of the computation is executed in optimized compiled C and C++ code underneath. 

Difficulty - I'm still not much familiar with numpy, it's functions and how they operate not like I don't get it, I just don't have such a grasp to be a bit confident with them, so most probably I will watch a video after I complete it with AI.

September 23 -

![Study note image](assets/image-24.jpeg)

Also completed video by coding with Sagar,

Title - numpy for data science | full course | Sagar Chouskey.

Key takeaway -

- Numba can be used to speed up supported Python code. It JIT-compiles the code into machine code at runtime.
Syntax - @jit(nopython = True)
