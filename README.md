Nguyễn Văn Tùng
Link chuẩn: https://github.com/Tung-Pro/Deha-Academy-Dev-php-git-Lab

Getting started
WorkFlow of # Deha-Academy-Dev-php-git-Lab

## 1. Tạo projects:
echo "# Deha-Academy-Dev-php-git-Lab" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

touch index.html

git add index.html

git remote add origin git@github.com:Tung-Pro/Deha-Academy-Dev-php-git-Lab.git

git push -u origin main

![Screenshot from 2024-12-21 10-25-48](https://github.com/user-attachments/assets/3e39c49f-c98f-4b9a-9f87-5d3063d7f368)

## 2. Tạo nhánh Develop
git checkout -b develop

git push origin develop

![Screenshot from 2024-12-21 10-30-23](https://github.com/user-attachments/assets/3440010c-7575-4723-87b1-8e71787763bf)

## 3. Tạo nhánh feature
git checkout -b feature/login

touch login.html

vi login.html

vi index.html

git commit -m'edit index.html and create login.html'

git push origin feature/login

![image](https://github.com/user-attachments/assets/077a10a1-c82f-409b-85c7-782114a044da)

git checkout -b feature/loout

touch logout.html

vi logout.html

vi index.html

git commit -m'create logout.html and edit index.html'

git push origin feature/logout

![image](https://github.com/user-attachments/assets/4a519ef3-52f7-4395-94e3-bb170091eba6)

## 4. Merge các nhánh feature trên server Github

![image](https://github.com/user-attachments/assets/d54b9597-3044-4d73-b9f2-9174cbae8de9)

![image](https://github.com/user-attachments/assets/97bf7566-4712-4a3d-a07b-5dd3ba9e4b6c)

## 5. Tái hiện trường hợp conflix
Trong khi merge feature/logout thì gặp CONFLIX

![image](https://github.com/user-attachments/assets/f50b9a58-a567-4baa-b2f3-44e4b3da545e)

Đã sửa bằng cách chấp nhận 'Accept Both Changes'

![image](https://github.com/user-attachments/assets/9ebb32e6-33c0-4137-a1ad-7da0521b6d92)

## 6. Tạo nhánh release
git checkout -b release/v1.1.0

git commit -m'edit index.html and relese/v1.1.0'

git push origin release/v1.1.0

![image](https://github.com/user-attachments/assets/78f9f596-68f4-4bcb-a64f-22011030d844)

## 7. Tạo và xử lý Hotfix
git checkout -b hotfix/v1.1.1

vi index.html

git commit -m'edit index.html and hotfix/v1.1.1'

git push origin hotfix/v1.1.1

![image](https://github.com/user-attachments/assets/8bdab114-6f08-4e06-bebf-e049660e599a)

## 8. Merge Hotfix vào main và develop
git checkout main

git merge hotfix/fix-login-bug

git push

![image](https://github.com/user-attachments/assets/9d811f84-2d63-4074-9935-57dfa80d290f)

git checkout develop

git merge hotfix/fix-login-bug

git push

![image](https://github.com/user-attachments/assets/190426a0-1352-42be-ad5d-dfec47b972e3)

