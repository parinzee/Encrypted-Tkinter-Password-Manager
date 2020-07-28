# Encrypted-Tkinter-Password-Manager
A small python-based password manger/generator utilizing Fernet Symmetric Encryption, SQLite, and Tkinter.

## How does it work?
This uses <a href='https://cryptography.io/en/latest/fernet/'>Fernet Encryption </a>, to encrypt your master password and .db file where your passwords are stored. The GUI is based on Tkinter which allows for easy integration, with sqlite3 and Fernet.

## Security
This program is completely offline and you can view the source code to see that it isn't sending anything over the web. Plus, the key is stored on your device so it will take a long time for someone to completely decrypt the file or the master password without the key. 

## Privacy
I respect your privacy thus this program is completly offline as I've told you. Each key is unique to you and a person without the key will have a very hard time trying to decrypt it.

## Releases
It supports MacOS, Windows, and Linux. I only have windows and mac machines so you have to compile it yourself or run the file as .py instead if you're on linux.

Releases are located <a href='https://github.com/Parinz/Tkinter-Password-Manager/releases/tag/1.0'> ***HERE*** </a>

<br/>
<br/>
<hr>



# Setup

1. It will take time to launch have **Patience**. Upon first launch, you will see this window. Set your Master Password, this is used for acessing all passwords.

![Setup](https://github.com/Parinz/Encrypted-Tkinter-Password-Manager/blob/master/Setup.png)

2. The main window will popup, you're done!

![Main Window](https://github.com/Parinz/Encrypted-Tkinter-Password-Manager/blob/master/MainScreen.png)

3. Now you can either choose to ***generate a new password*** and save it using the generate function. You could also use the ***Password Notebook*** button to add existing passwords.

## Adding Existing Passwords

1. To add existing password click on the **Password Notebook Button.**

![Adding Existing Passwords](https://github.com/Parinz/Encrypted-Tkinter-Password-Manager/blob/master/Add%20Existing%20Passwords.png)

2. A window will pop-up asking you to enter your Master Password. Enter it, then click Authenticate.

![Authenticate](https://github.com/Parinz/Encrypted-Tkinter-Password-Manager/blob/master/Authenticate.png)

3. If this is the first time you've open your Password Notebook. It will be empty just rows on top.

![Password Notebook](https://github.com/Parinz/Encrypted-Tkinter-Password-Manager/blob/master/Password_Notebook.png)

4. To add your password, click on the "Add Password" Button.

![Adding Password Button](https://github.com/Parinz/Encrypted-Tkinter-Password-Manager/blob/master/Password_Add.png)
