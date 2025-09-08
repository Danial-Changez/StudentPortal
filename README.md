# StudentPortal
Lab 1 of ENGG*4450 with steps.

## List of commands and steps:
1. git init
<img width="854" height="44" alt="image" src="https://github.com/user-attachments/assets/34100d76-c1dc-43a1-8e7d-8cbde5b4838a" />

2. echo "# Student Portal" > README.md
3. git add .
4. git commit -m "Initial Commit"
5. git branch -m main
<img width="820" height="57" alt="image" src="https://github.com/user-attachments/assets/5278b123-9f1d-4e37-8941-fd8d0e0e53d9" />
<img width="690" height="61" alt="image" src="https://github.com/user-attachments/assets/6bd5b31a-b4c7-42b9-b75e-ea9360181f10" />

6. git remote add origin https://github.com/Danial-Changez/StudentPortal.git
7. git push -u origin main
<img width="1175" height="151" alt="image" src="https://github.com/user-attachments/assets/8054363c-2da4-4365-a6b4-da670bd1d25a" />

8. git branch feature_login
9. git checkout feature_login
10. echo 'print("Login Succesfull")' > login.py
<img width="914" height="418" alt="image" src="https://github.com/user-attachments/assets/3ffff75a-0509-4f13-a44a-b02418044204" />

11. git add .
12. git commit -m "Added login file"
13. git push -u origin feature_login
<img width="808" height="346" alt="image" src="https://github.com/user-attachments/assets/7e4fccbe-d2a7-443e-8fee-cd97e27fc638" />

14. git checkout main
15. git merge origin/feature_login
16. git push -u origin main
<img width="815" height="345" alt="image" src="https://github.com/user-attachments/assets/65f5cbeb-b08f-44bf-a553-6e9bc7cd6fff" />

17. cd ..
18. mkdir "ClonedStudentPortal"
19. git clone "https://github.com/Danial-Changez/StudentPortal.git"
20. ls .\StudentPortal\
21. cat .\StudentPortal\login.py
<img width="1141" height="801" alt="image" src="https://github.com/user-attachments/assets/abaca84f-e6fd-439e-b605-e17e063b9d7c" />
<img width="835" height="45" alt="image" src="https://github.com/user-attachments/assets/ee0717e9-98bb-4e00-9382-c93a98bda4b2" />
