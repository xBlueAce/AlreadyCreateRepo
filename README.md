# Already Created REPO

this is what to do in the case a repo has already been created..

## Turning into a git repo

we use 
->git init

Screen Shot 2021-03-22 at 3.29.36 PM![image](https://user-images.githubusercontent.com/34463290/112067645-9e405880-8b25-11eb-90b6-73c31ad7cab2.png)



and if we use git status we see there nothign that has been committed
 -> git status

Screen Shot 2021-03-22 at 3.31.03 PM![image](https://user-images.githubusercontent.com/34463290/112067668-a8faed80-8b25-11eb-906d-d2ef7a180f1b.png)



so then we go ahead and add 
 -> git add .
 -> git add README.md 

 either or can do

Screen Shot 2021-03-22 at 3.33.57 PM![image](https://user-images.githubusercontent.com/34463290/112067713-c2039e80-8b25-11eb-91de-93162609f15e.png)


 now we commit

## be careful

now let's try pushing to git hub
via git push
we get an error

Screen Shot 2021-03-22 at 3.37.37 PM![image](https://user-images.githubusercontent.com/34463290/112067740-d0ea5100-8b25-11eb-8965-45c65564f556.png)

So to fix this we create a empty repo on git hub.

then 
->git remote add origin *insert repo*

Screen Shot 2021-03-22 at 3.41.17 PM![image](https://user-images.githubusercontent.com/34463290/112067783-e52e4e00-8b25-11eb-8817-8e24414ce525.png)


and it set up

now we push via
->git push origin master

![image](https://user-images.githubusercontent.com/34463290/112068999-40f9d680-8b28-11eb-98cb-ae57658e0ab3.png)



Source : https://www.youtube.com/watch?v=RGOj5yH7evk&ab_channel=freeCodeCamp.org
