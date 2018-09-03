---
layout: post
title:  "How Poetry Taught Me To Use Github"
date:   2018-09-03 09:45:00 +0100
categories: general
---
I started actively pushing content to Github recently. I have not been pushing Open Source contributions, Components or anything of the like - I have been pushing poetry. I do this beacuse it is what I love the most, after coding. I remain ever grateful that I took the initiative to make my first `git commit`.

Now, I want to breakdown the process for new coders, so that they can become comfortable with working with Github too. I will be breaking down several ways to push content to Github. For the purpose of this article, I will assume that readers are familiar with Terminal usage (GitBash or otherwise).

* * *
#### >> Pushing to a repository with a README file
There are just a few essential steps to this:

1. Click the green **Clone or download** button on the repository page.
<img src="http://res.cloudinary.com/poetrique/image/upload/v1535965331/allbuy-i-ng/gallery/git-clone.png" />

2. Use the **Clone with HTTPS** option, and copy the link provided.
<img src="http://res.cloudinary.com/poetrique/image/upload/v1535965671/allbuy-i-ng/gallery/git-clone2.png" />

3. Run `git clone https://github.com/UserProfile/repository.git` in the terminal. Here, **_UserProfile_** and **_repository_** will be replaced by the values provided in the copied link.
  
4. Run `git init` in the terminal. This will initialize the folder/repository that you have on your local computer system.

5. Run `git add .` in the terminal. This will track any changes made to the folder on your system, since the last commit. If this is the first time you are committing the contents of the folder, it will add everything.

6. Run `git commit -m"insert Message here"`. This will prepare the added/tracked changes to the folder on your system for pushing to Github. Here, **_insert Message here_** can be replaced with any relevant commit message of your choice.

7. Run `git push origin master`. Note that the last word in the command **_master_**, is not a fixed entry when running `git push`. It can be replaced with any relevant "branch_name".

* * *
##### Note
This is just _Part 1_ in a series. Please reach out, if I have made any error, or if there is any part of this article I could have explained better. My email is at the footer of this page. Thanks! **Code In Peace**