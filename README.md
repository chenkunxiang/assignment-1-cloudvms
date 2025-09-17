# This is going to be a tutorial on how to make a virutal machine in both google cloud and oracle cloud using the ubuntu image.

[This is a Link to the tutorial](https://www.loom.com/share/ce54e8b30661444d8f259bfb3c2b0845)

## Google Cloud
1. Create and login to your Google cloud account.
2. Click the "sandwich" icon on the top right and scroll down to "Computer Engine."
3. From there click create instance.
4. Double check and make sure several things are in place:
- Smallest Machine that you need.
- Ubuntu image.
- Area is set up in the server closest to you.
5. Create and wait for your instance to be created.
6. Click the SSH icon to launch the virtual machine in a seperate window.
7. Enter the commnand 'sudo apt-get update'.
8. Once you are done using the VM, exit the window and terminate the machine in the the actions tab.

## Oracle Cloud
1. Create and login to your Oracle cloud account.
2. Click "create instance".
3. Set image to Ubuntu and the machine itself to the smallest or free settings.
4. Once the machine is running open the terminal.
5. Enter the command "chmod 600 (path to private key)" so that your actual machine can read the key.
6. Enter the command "ssh -i (path to private key)ubuntu@(public ip)".
7. Enter the commnand 'sudo apt-get update'.
8. Once you are done using the VM, exit the window and terminate the machine in the the actions tab.
