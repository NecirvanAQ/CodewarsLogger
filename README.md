# CodewarsGitHubLogger

This program allows you to connect to [Codewars](https://www.codewars.com) by using your credentials
(through the GitHub OAuth sign in option) and extract all the code of each programming language of
every kata you have completed.

Click on the hamburger button next to the word "README.md" this file to open the table of contents and
jump to the sections that are relevant to you. To keep this file simple and short, I only describe here
the most important information, and a summary of other topics. To see all the information, go to the
[repository wiki](https://github.com/JoseDeFreitas/CodewarsGitHubLogger/wiki).

## Why?

I developed this small program because GitHub is the biggest portfolio for all kind of programmers
(along with websites and/or other media profiles). A key skill every programmer should have is problem
solving (algorithms, paradigms, data structures, etc.), and Codewars is a very good platform to
practice this hability because of its structure, support of multiple programming languages, user rank
system, easily (with moderation) code challenge creation system and social interaction between users
(similar code-challenges, comments, votes, and more).

By having a repository that contains all the code challenges you have completed, everyone (including
recruiters) can see what you've done, what languages do you use with ease and your strenghts and
weaknesses. You could do this manually, but going to all the pages of solutions of all the katas you've
completed (plus more than one programming language if available) would take you a lot of time (and
you'd have to update it every time you complete a kata).

This repository allows you to copy in your repository the code of the completed challanges you've done
automatically: you don't have to do anything. Moreover, the files and directories are stored in such a
way that it's easy to navigate through them.

## Usage

To use this program you just need an initial configuration. After that, you just have to sit and watch
everything copying automatically. Below is the ordered list of steps you must follow to get all working
(I suppose that you already have both a GitHub account and a Codewars account):

1. Click on the green button "Use this template".
2. Choose a name for your repository and click on "Create repository from template".
3. Go to the settings of your new repository and then to the "Secrets" tab.
4. Create these 3 secrets by clicking the button "New repository secret":
   1. `USERNAME_GITHUB`: your GitHub username.
   2. `PASSWORD_GITHUB`: your GitHub password.
   3. `CODEWARS_USERNAME`: your Codewars username.
5. Go to the "Actions" tab of the repository and click on the "Start project" workflow.
6. Click on the button "Run workflow" (with the `main` branch selected) and again in the green "Run workflow" button.

And that's it! Keep in mind that it will take some time the first time you run it (especially if you
have completed a lot of katas).

You can customize some aspects of the program, such as the content of the README.md files,
the name and the directory of the INDEX.md file and other stuff. Head to the "[Customisation page]()" in
the wiki of this repository to learn more about what you can do. Also, head to the "[Privacy page]()" in
the wiki to learn about the protection of your credentials. I recommend you take a read on the entire
wiki because there is useful and important information for you to know.

If you have any issue, please [open an issue]() explaining what's happening.

## Disclaimer
