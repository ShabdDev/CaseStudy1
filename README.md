Case Study1

Problem Statement: 
You work as a DevOps Architect in Zendrix Softwares. 
The company has been struggling to manage their product releases. 
The releases should happen on the 25th of every month. 
Suggest a Git workflow architecture for this requirement. 
Simulate this workflow by creating pseudo code files and branches and upload the same to your GitHub account. 
As a part of the solution, share the link to your GitHub repository.


solution
1. mkdir CaseStudy1
2. cd CaseStudy1
3. git init
4. nano master.txt
5. git add .
6. git commit -m "master.txt file is created"
7. git branch Test
8. git checkout Test
9. git checkout master
10. git branch F1
11. git branch F2
12. git checkout F1
13. nano f1.txt
14. git add f1.txt
15. git commit -m "f1.txt file is created in F1 branch"
16. git checkout F2
17. touch f2.txt
18. git add f2.txt
19. git commit -m "f2.txt file is committed"
20. git checkout Test
21. git merge F1
22. git merge F2 -m "F2 is merged with Test branch"
23. git branch
24. git checkout master
25. git branch Product
26. nano release.txt
27. git add .
28. git commit -m "file is created in master branch only as we have not checkout Product branch"
29. git merge product
30. ls
31. git merge Test
32. ls
33. history
