# Macbook-Touchbar-Reset
Zsh (Shell) script that fixes the intermittent issue of the Macbook touchbar crashing, such as 
when it goes completely black, various options disappear, or you are unable to navigate after
clicking on an option.
## How to Run (Terminal Commands)

Clone the project

```bash
  git clone https://github.com/Andy-Wu12/Macbook-Touchbar-Reset.git
```

Go to the project directory

```bash
  cd Macbook-Touchbar-Reset-main
```
\
\
You need to provide execute permissions to the ```resetTouchbar.sh``` file and
will need your **Terminal** application to do so.

Once **Terminal** is open, navigate to the directory where your file is stored
and run the command

```bash
  chmod +x resetTouchbar.sh
```

You should see the following permissions set for the file after running ```ls -l```:
```-rwxr-xr-x```

You should now be able to run this script with one of the following commands
```bash
  ./resetTouchbar.sh
```
```bash
  zsh ./resetTouchbar.sh
```
```bash
  bash ./resetTouchbar.sh
```

And entering your password, as the script requires **sudo permission**

## How to Run (Double-click file)
An alternative (and easier) way to run the script is to take advantage of
the built-in **Get Info** feature. This option is preferable as it simplifies the execution
process by only requiring you to double-click on the file to run the script.

1. After providing execute permission to the script as shown in the previous section,
   right click on the file and click **Get Info**

2. Click on the dropdown menu in the **Open with** section and select **Other**

3. Click on the dropdown menu in the **Enable** section and select **All Applications**

4. Navigate to your **Applications** folder, then to **Utilities**

5. Select the **Terminal** and click **Add**

At this point you should be able to double-click the ```resetTouchbar.sh``` file
and have it run automatically, only requesting your password for **sudo permission**

Should you need to edit the file after this setup, you can always right-click on the file, select **Open with**, and
choose your preferred text editor to do so

