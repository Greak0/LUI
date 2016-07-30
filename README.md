LUI
------
Linux User Info - RedHat

How to install?
------

      cd /tmp/
      git clone https://github.com/Greak0/LUI
      cd LUI
      mv lui_redhat.sh /sbin/lu
      chmod +x /sbin/lu
      lu

How to use?
------
    lui
        -h This help message.
        -i User information, use as "-i user".
        -x eXtended information.
        -a List all users.
        -l List all users with locked password.
        -u List all users with unlocked password.
        -n List users with nologin shell.

        You can use multiple arguments too, eg. "lu -l -u"
