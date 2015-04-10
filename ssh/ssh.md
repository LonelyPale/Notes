ssh
===

    ssh-keygen -t rsa -P ""
    ssh-keygen -t dsa -P '' -f ~/.ssh/id_dsa
    cat $HOME/.ssh/id_rsa.pub >> $HOME/.ssh/authorized_keys
    ssh localhost
    exit

