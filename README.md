# Zendesk Coding Challenge:

A Zendesk Ticket Viewer CLI App created for Zendesk Coding Challenge.<br /><br />

## Development environment and Dependencies

- Programming Language: Python 3.6.0
- Development environment: Windows 10 Home


## Application Architecture-MVC Pattern Passive View:

Unlike most MVC-style configurations, Passive View results in no dependencies between view and model. As with these the UI is split between a view that handles display and a controller that responds to user gestures. The significant change with Passive View is that the view is made completely passive and is no longer responsible for updating itself from the model. Controller handles responses to user events and does all the updating of the view.<br />For more info, read: https://martinfowler.com/eaaDev/PassiveScreen.html.

## Installation & Set-up
This app has been written in Python 3.6.0. The following are the installation instructions of Python 3.6.0 on 64-bit: Windows 10 and Mac OS X 10.11. 

### Python 3.6.0 Installation:
#### Mac OS X 10.11:
For installing Python 3.6.0 on Mac, 
Go to https://www.python.org/downloads/mac-osx/ and under **"Python 3.6.0 - 2016-12-13"** click on **"Download Mac OS X 64-bit/32-bit installer"** 
Download the one suitable for your machine. 
Run the installer and follow the steps to get a full standard installation of Python 3.6.0 on your system.

#### Windows 10:
To install Python 3.6.0, head to https://www.python.org/downloads/release/python-360/ and download the file which says **"Windows x86-64 executable installer"**. 
After downloading, run the executable and chose **Add Python 3.6 to PATH** option. 
Then follow the instrcutions to get a full installation of Python 3.6.0 on your system.

### Installation of Libraries used:

The libraries used are:

- **sys** (For exiting, using application packages etc.)
- **requests** (for API access and response)
- **mock, unittest** (for testing)
- **json** (for loading JSON data from file)
- **datetime** (for formatting dates)
- **math** (for rounding up page numbers)

Out of these, **sys**, **json**, **math** and **unittest** are built-in in a standard Python 3.6.0 installation.

#### Mac OS X 10.11:
On terminal, type:
```shell
pip3.6 install mock
pip3.6 install datetime
pip3.6 install requests
```
#### Windows 10:
On command line, type:
```shell
pip install mock
pip install datetime
pip install requests
```

## Application Usage:
To start using this app, download the git repository or the zip file. Open terminal/command line and go in the **controller** folder of this application through **cd** commands. Then type:<br /><br />
**For Mac OS X 10.11:**
```shell
python3.6 appController.py
```
**For Windows 10:**
```shell
python appController.py
```
Use 'u' and 'd' (up and down) to page through tickets when viewing all tickets. Enter ticket ID after entering '2' to view specific ticket. The rest of the controls are shown in the terminal by running the app that displays command menu

## Testing:
For testing this app, go to the **"tests"** folder within the app on command line/terminal by using **cd** commands. Then type:<br /><br />
**For Mac OS X 10.11 :**
```shell
python3.6 testTicketViewer.py -b
```
**For Windows 10:**
```shell
python testTicketViewer.py -b
```
**NOTE:** **"-b"** is used for supressing print statements during unit testing.<br /><br/>

## Additional Information
The application has been tested in Mac OS installed on Virtual Machine through VirtualBox.
Please contact me if there are any installation issues in Mac through mail - saumya96pandey@gmail.com

## References
https://developer.zendesk.com/rest_api/docs/support/introduction


