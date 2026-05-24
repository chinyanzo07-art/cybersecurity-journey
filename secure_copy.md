HOST TO REMOTE
scp important.txt ubuntu@192.168.1.30:/home/ubuntu/transferred.txt
important.txt [text file]
ubuntu[remote user]
192[remote ip]
/home/ubuntu[directory]
transferred.txt[name of the file to store as on remote machine]


REMOTE TO HOST
scp ubuntu@192.168.1.30:/home/ubuntu/documents.txt notes.txt
ubuntu[remote user]
192 [remote ip]
documents.txt [remote file name]
notes.txt [file name to store on host system]