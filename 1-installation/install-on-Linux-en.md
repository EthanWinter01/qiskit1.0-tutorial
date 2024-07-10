# How to Install Miniconda on on Ubuntu
date written: 2024-07-10

## Why we use Miniconda?
Conda is a two-in-one tool that manages both software environments and packages for your computer. It's particularly useful when you need different versions of the same program to run different applications. Conda creates isolated environments, so each program uses its own set of software and doesn't interfere with others.

Conda comes in two flavors: Anaconda and Miniconda. Anaconda is a larger package that includes Conda, a Python environment, and many popular data science tools. It's ideal for big or exploratory projects where you might need a lot of different software. Miniconda is slimmer, containing only the core Conda and Python tools. It's better for smaller projects or situations where storage space is limited.

Choose Miniconda if:
- The project is small or needs only a few packages
- You already know the tools that the project needs
- You prefer to manually install the needed software
- Your computer has storage limitations


## Step 1: Install Miniconda
Download the Miniconda installer script
```bash
 $ wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
```

## Step 2: Run the installation script
```bash
 $ bash Miniconda3-latest-Linux-x86_64.sh
```
the installer will displays a message when install successful
```txt
 In order to continue the installation process, please review the license agreement.
 Please, press ENTER to continue
```

## Step 3: Verify installation directory
```txt
 Miniconda3 will now be installed in this location: 
 /home/pythonuser/miniconda3    

 - Press ENTER to confirm the location   
 - Press CTRL-C to abort the installation   
 - Or specify a different location below
```
Note: pythonuser is just a directory to of your user, you can press ENTER to continue with this default directory

## Step 4: Initialize Miniconda
```txt
 installation finished.
 Do you wish the installer to initialize Miniconda3
 by running conda init? [yes|no]
```
Note: for another version, it could have said otherwise, most common answer is just to type 'yes'