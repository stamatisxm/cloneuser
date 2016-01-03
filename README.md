#cloneuser

##cloneuser – { Flexible User Cloning Utility }
**cloneuser** is a simple shell application that helps you clone users for any purpose

###{ Program Options }
Usage: **cloneuser \[olduser\] \[newuser\]**

###{ Program Setup }
This program is going to be installed by default in your **$HOME/bin** directory, however, in order for it to work properly, it has to run with superuser privileges upon invocation so it has to be moved into the **/usr/local/bin** directory (or **/bin** or **/usr/bin**, but **/usr/local/bin** is recommended).


Download the tarball containing the cloneuser utility from the link towards the bottom and do the following:

Move the downloaded tar file into your home directory

Expand the tar file in a terminal by issuing:
**tar xf cloneuser<version>.tar**

Move the executable from your **$HOME/bin** into **/usr/local/bin** by running:

**sudo mv $HOME/bin/cloneuser /usr/local/bin**

Invoke the program from the terminal, running **sudo cloneuser** to see a message for the program usage
