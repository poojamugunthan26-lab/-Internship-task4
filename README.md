# -Internship-task4
HYDRA

ydra -V -t 1 -L user.txt -P password.txt ftp://127.0.0.1:21

JOHN RIPPER

sudo nano shadow

unshadow passwd shadow > unshadow.txt

cat unshadow.txt

sudo john --wordlist=user.txt --format=crypt unshadow.txt

meta....code

METAEXPLOIT

msfconsole

use exploit/unix/ftp/vsftpd_234_backdoor


use auxiliary/scanner/smb/smb_ms17_010

ZPHISHING

Installation
 Clone this repository -

git clone --depth=1 https://github.com/htr-tech/zphisher.git

Now go to cloned directory and run zphisher.sh -

$ cd zphisher
$ bash zphisher.sh
