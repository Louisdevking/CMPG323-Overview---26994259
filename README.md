# CMPG323-Overview---26994259
CMPG 323  OVERVIEW for LP Muller 26994259

project and
repository context and how they are
integrated

Repository keeps the files of the code and is the source for version control. Github allows to completely manage projects by adding Projects,Milestones etc. We will use the projects section for admin purposes and we will pull and push to the repository. The code and project details is all in the same repo.

Branching strategy.

We use branches to allow for better syncronisation and workflow between developers. It doesnt make sense to keep commiting to the same branch. There will be a ton of duplicate code and merging errors. We create seperate branches to work on isolated instances and once everything is thoroughly tested we can eventually merge with main and have everything in one project.

 .gitignore
Simply a file that allows users to ignore certain files when pushing and pulling. simply add the file with its extension name to the gitignore

storage of credentials and sensitive
information

we can store encrypted secrets on the repository as well. And distrubute encryption key as needed.
