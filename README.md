"# project_test" 

1 git init repository

2 git push origin

3 git fetch to update

make a conflict:

copy folder of repository, origin folder mark as A, copied folder mark as B;

Eidt file README.md, comit and push in A, but not do this in B.

Eidt file README.md for anothor info in B, but not do this at A.

Fetch remote B, merge B so here will be a confilct.

4 summarize the above experiment, my git workflow:

Respository of Tom and Jerry is same (version 1);

Tom: Tom edit, commit and push to origin respository(version 2);

Jerry: Jerry has two branch {master, edit_branch} in his respository;

Jerry: Jerry eidt code files in edit_branch, and commit (version 3);

Jerry: Jerry checkout master branch, and pull origin respository;

Jerry: Jerry checkout eidt_branch, merge master branch;

Jerry: Jerry resolve conflict in eidt_branch, and commit a version after merge(version 4), and push to origin respository;


