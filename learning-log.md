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

<img src="assets/image-04.jpeg" alt="Study note image" width="300">

the basic thing about mypy is that it checks and tell us if the type hints are beginning followed or not and python will run the program and won't consider type hints they are just for developers to see and understand what it's output and more are meant to be and in it -

Also studied uv -

<img src="assets/image-05.jpeg" alt="Study note image" width="300">

Also studied exception handling in it

Try - try this if error occurred try except

Except - if error occurs do this

Else - if no error occur

Finally - do this ni matter what

Raise - we raise error by ourself

Aug 10 - completed expection handling

<img src="assets/image-06.jpeg" alt="Study note image" width="300">

Still i was thinking to begin logging but bad sleep( not that didn't sleep for 8 hours but for sure didn't sleep well) and not enough time got better if me still I'll continue Tommorow.

Aug 11 - completed logging, the 5 levels are not mentioned here

<img src="assets/image-07.jpeg" alt="Study note image" width="300">

<img src="assets/image-08.jpeg" alt="Study note image" width="300">

Aug 12 - completed pytest -

I think I will easily forget a lot of functions and mostly the writing schema but most probably remember the working of it, which I think is the main part

<img src="assets/image-09.jpeg" alt="Study note image" width="300">

Aug 13 - didn't do much practices pytest a bit mostly the async with patch part and again studying OOP (classes, inheritance), decorators, generators, iterators,

context manage because I studied them through YouTube so it was almost an overview in other words I skipped oops because I studied them a while ago but don't remember them much and the rest topics were studied via YouTube so I think that not all topics of it were covered and I didn't grasp it.

For example -  I saw a video of tech with tim on pytest it has the topics till manual mock creation but further topics like async and patch were mentioned so like I said the topics I studied through YouTube might be missing some topics so I'll study them again mostly through chatgpt but also watch some more videos

Aug 14 -

<img src="assets/image-10.jpeg" alt="Study note image" width="300">

Also studied ABC and abstract methods

Aug 15 -

<img src="assets/image-11.jpeg" alt="Study note image" width="300">

<img src="assets/image-12.jpeg" alt="Study note image" width="300">

<img src="assets/image-13.jpeg" alt="Study note image" width="300">

<img src="assets/image-14.jpeg" alt="Study note image" width="300">

Aug 16 -

<img src="assets/image-15.jpeg" alt="Study note image" width="300">

Aug 17 - today I studied

<img src="assets/image-16.jpeg" alt="Study note image" width="300">

Also some introduction to git and GitHub mainly decided to watch code with Harry git and GitHub tutorial for beginners (full course video).

Yes I admit that I didn't study much, these topics are not lengthy enough for a day, I'll try to be productive enough each day and continue my learning.

Aug 18 - watched the code with Harry git and GitHub tutorial for beginners (full course video) till branches.

Aug 19 - completed the code with Harry git and GitHub tutorial for beginners (full course video).

Aug 20 - light study - reviewed the code with Harry git and GitHub tutorial for beginners (full course video).

September 16 - i studied general relational sql using syntax that is largely related to postgresql, not entirely mysql or postgresql, later in the roadmap I'll study postgresql after that, some day i'll study MySQL if it is necessary

<img src="assets/image-17.jpeg" alt="Study note image" width="300">

September 17 -

<img src="assets/image-18.jpeg" alt="Study note image" width="300">

September 18 -

<img src="assets/image-02.jpeg" alt="Study note image" width="300">

September 19 -

<img src="assets/image-19.jpeg" alt="Study note image" width="300">

September 20 -

<img src="assets/image-03.jpeg" alt="Study note image" width="300">

September 21 -

<img src="assets/image-01.jpeg" alt="Study note image" width="300">

<img src="assets/image-20.jpeg" alt="Study note image" width="300">

September 22 -

<img src="assets/image-21.jpeg" alt="Study note image" width="300">

<img src="assets/image-22.jpeg" alt="Study note image" width="300">

<img src="assets/image-23.jpeg" alt="Study note image" width="300">

Key takeaway - numpy is like in between C++and python, numpy have contiguous memory layout, statically typed and more which resembles with C++ which helps in it faster execution time but uses python syntax, so like front is python back is C ++.

Difficulty - I'm still not much familiar with numpy, it's functions and how they operate not like I don't get it, I just don't have such a grasp to be a bit confident with them, so most probably I will watch a video after I complete it with AI.

September 23 -

<img src="assets/image-24.jpeg" alt="Study note image" width="300">

Also completed video by coding with Sagar,

Title - numpy for data science | full course | Sagar Chouskey.

Key takeaway -

- Numpy is fast mainly because it's built - in operations do a lot of work in optimized C.

- Numba can be used when normal python code is slow. It JIT - compiled supported code into machine code at runtime.

Syntax - @jit(nopython = True)

September 24 –

<img src="assets/image-25.jpeg" alt="Study note image" width="300">

<img src="assets/image-26.jpeg" alt="Study note image" width="300">

September 25 –

<img src="assets/image-27.jpeg" alt="Study note image" width="300">

<img src="assets/image-28.jpeg" alt="Study note image" width="300">

<img src="assets/image-29.jpeg" alt="Study note image" width="300">

<img src="assets/image-30.jpeg" alt="Study note image" width="300">

Key Takeaway –

Numpy : basic indexing/slicing in numpy returns view, advanced indexing returns a copy while other operations depend on the operation.Pandas :  derived dataframes/series from operations behave as copies under Copy-on-Write, i.e. pandas may share the underlying data internally, but creates a copy when modification requires it.

So in short, pandas has a more consistent copy behavior, while in numpy it depends on the type of operation.

.
