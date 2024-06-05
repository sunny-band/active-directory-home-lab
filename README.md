# active-directory-home-lab
This is a personal project aimed at gaining knowledge of Active Directory and emulating real-world tasks as an IT Help Desk/Service Desk position. Methods can include the following: adding/removing/disabling users, conducting password resets, and managing group policies. 


Credits to **Josh Madakor** for making a tutorial video on how to set up Active Directory using virtual machines. https://youtu.be/MHsI8hJmggI?si=_xakUNLCsHSqyDe0



## 1. Currently using Windows Server 2019 running inside VirtualBox. At startup, the Server Manager appears. Select "Active Directory Users and Computers" from the "Tools" dropdown box.
![1](https://github.com/sunny-band/active-directory-home-lab/assets/144818374/96c11fde-85b4-4c0b-aa42-32b007bc77ef)

## 2. There are hundreds of users in a domain. We can conduct a password reset if a user has forgotten their password. Right-click on a user's name and select "Reset Password..."
![2](https://github.com/sunny-band/active-directory-home-lab/assets/144818374/2945b8cd-c828-4dba-b379-08be2b611d17)


## 3. Enter a temporary password for the user. Additionally, please check the box next to "User must change password at next logon" to ensure the user can enter a new password. Click OK.
![3](https://github.com/sunny-band/active-directory-home-lab/assets/144818374/ef60eaec-daf7-4487-8f9c-9b7fdab3c1e2)


## 4. Using another instance of VirtualBox, connect to a client computer (Windows 10 Pro). Let the user log in with the temporary password. Make sure this message pops up.
![4](https://github.com/sunny-band/active-directory-home-lab/assets/144818374/1651a4a1-b539-49a0-90e6-f29afa8acb55)


## 5. If successful, the password will be changed.
![5](https://github.com/sunny-band/active-directory-home-lab/assets/144818374/0a20004e-c4c2-4e3b-bb9c-ceb0ae3bc8bd)


## 6. Example of user successfully logged in to the desktop.
![6](https://github.com/sunny-band/active-directory-home-lab/assets/144818374/03bb2fee-1fcc-4e10-b86f-b6acaa701e01)


## 7. We can also disable users' accounts.
![7](https://github.com/sunny-band/active-directory-home-lab/assets/144818374/c5e224cf-1720-40d7-b76b-99df99ae9a01)


## 8. User's account has been disabled.
![8](https://github.com/sunny-band/active-directory-home-lab/assets/144818374/d9a991b2-5c30-40a6-821c-7230bb41c9c1)


## 9. Message on client computer's side.
![9](https://github.com/sunny-band/active-directory-home-lab/assets/144818374/ed0b7e9a-ce07-4c76-90a4-5b3cc4f7d927)


## 10. The Server Manager can also manage group policies -- how users will have access to certain Windows features.
![10](https://github.com/sunny-band/active-directory-home-lab/assets/144818374/b983ee20-d79b-42df-87b5-c4c1c13ca9e9)


## 11. Setting the permissions to the start menu to be full-screen.
![11](https://github.com/sunny-band/active-directory-home-lab/assets/144818374/3a3c61e5-3967-4e6a-87b7-15d2e96df929)


## 12. Properties menu.
![12](https://github.com/sunny-band/active-directory-home-lab/assets/144818374/c7728541-bd81-469a-a8fb-9be749c4867b)


## 13. Client computer in effect.
![13](https://github.com/sunny-band/active-directory-home-lab/assets/144818374/f9e45bdc-8641-4caa-bd07-aea8651549e3)

