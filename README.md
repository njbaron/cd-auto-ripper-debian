# CD Auto Ripper
Ripping audio on ubuntu server with abcde, system.d and udev rules.

# How to install
Only works on debian atm.

Dependencies
* ansible

Run the following command to install with the ansible playbook
```shell
ansible-playbook -i "`hostname`," playbook_install.yaml -K
```

# How to use
1. insert disk into drive
2. wait for the whuring to stop
3. retrieve the disk that was ejected
4. repeat

# Useful links
* https://askubuntu.com/questions/788327/use-abcde-to-produce-high-quality-flac-and-mp3-output-with-album-art-under-xenia
* https://github.com/asigner/abcde-auto-cd-ripper
* https://gist.github.com/docPhil99/1a57ab0fc7d2066143e7ea06ed064ddd
