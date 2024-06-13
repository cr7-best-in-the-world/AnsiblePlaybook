--> to run the playbook, navigate to the playbook directory and run this command
$ansible-playbook -i hosts.ini playbook.yml --ask-become-pass

--> make sure the file source location is specified properly, if you are running the above command from
    playbook directory, then in the copy task, specify the source file location properly /role_name/files/filename
