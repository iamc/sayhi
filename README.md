# sayhi
Playing with GitHub forks and Pull Requests (PR). Homework for 2021-03-16-tudelft-online Software Carpentry Git lesson.

You can think of forking as a kind of `clone`, but between GitHub repos, and with GitHub being aware of a repo being forked, and where a frok "comes" from.

# sort instructions

In GitHub `fork` this repo, `clone` the forked repo (from your GitHub account) to your computer. There, add a new file named as by your GitHub username (so that you don't step on each other's foot) with a "hi!" message inside. `git add`, `commit` this new file in your local repo. Now `push` changes to your forked repo, and finally, from within GitHub interface of your forked repo, submit a pull request to this repo (iamc/sayhi).

# step-by-step

0. Check that you are logged in in GitHub
1. Click the upper rigth `Fork` button. Af you do it you will be taken to your own account, to your forked repositry. Under the repository name (<YOUR_USERNAME>/sayhy), you will see the text: "Forked from iamc/sayhi".
2. Go to your computer and `clone` YOUR fork (<YOUR_USERNAME>/sayhi) (green button, code clone, select https and copy-paste to your terminal)
3. Create a new file <YOUR_USERNAME.txt> and put some text sayinghi, and `git add`, `commit` the file in your local repository.
4. Push your local repo to GitHub remote repo with `git push origin master`
5. Now in GitHub web interface you will see something like "This branch is XX commit ahead of iamc:master.", and in the same "bar" the text `Pull request`. Click there, go through the webpage that appears (the "send" Pull Request page, it has a lot of info you can mostly ignore about branches, etc), and click the green button `Create a pull request`.
6. Now I (iamc) will get a message about your PR submissionn. As your username is unique in GitHub, and you so named the new file, there will be n o conflict with my repositry; I'll review your PR and accept it. This will be reflected in your forked repo and this will habe been your first pull request ever and your first step into the open source contribution Hall of Fame.

Enjoy!
