Este é o readme do meu primeiro projeto como exemplo na apostila da Campus Code.
Estou seguindo os passos da apostila, assim, posso fixar o conteúdo e ampliar minha
aprendizagem para a próxima etapa do treinadev.

Esse é o erro que eu recebi quando fui clonar o projeto.


petrovapierce@pcdabianca:~/workspace/meu_projeto$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   README.md

petrovapierce@pcdabianca:~/workspace/meu_projeto$ git commit
[master 72169ce] Mensagem de commit no editor
 1 file changed, 3 insertions(+), 1 deletion(-)
petrovapierce@pcdabianca:~/workspace/meu_projeto$ git status
On branch master
nothing to commit, working tree clean
petrovapierce@pcdabianca:~/workspace/meu_projeto$ git log
commit 72169ce7dd83332e40cf9f6e6d72cba738bce243 (HEAD -> master)
Author: biancavonposer <biancavonposer@gmail.com>
Date:   Sat Jul 24 13:27:12 2021 -0300

    Mensagem de commit no editor

commit 16e8037103111613e6505f913b05a65b6d0db4c4
Author: biancavonposer <biancavonposer@gmail.com>
Date:   Sat Jul 24 13:24:19 2021 -0300

    Adiciona texto em inglês ao README.md

commit 4ffd3f124650b69a70d45e2ca85117730278c9ee
Author: biancavonposer <biancavonposer@gmail.com>
Date:   Sat Jul 24 13:22:05 2021 -0300

    Altera o README.md

commit a434dc67d505d960d6c909c1fb9f2b769839c840
Author: biancavonposer <biancavonposer@gmail.com>
Date:   Sat Jul 24 13:00:48 2021 -0300

    Meu primeiro commit


petrovapierce@pcdabianca:~/workspace/meu_projeto$ ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key (/home/petrovapierce/.ssh/id_rsa): 
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /home/petrovapierce/.ssh/id_rsa.
Your public key has been saved in /home/petrovapierce/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:KQdHpL5WvOauN0ZR11l135ylzqQTN/7bs00ydKrJIks petrovapierce@pcdabianca
The key's randomart image is:
+---[RSA 2048]----+
|       .o    . o*|
|       o  . . oo*|
|      o .. .. =.+|
|     . +..   O . |
|      o S.  o = .|
|       =..   o + |
|      o.E     + o|
|     . += .. o =+|
|      .=++ .+  o=|
+----[SHA256]-----+
petrovapierce@pcdabianca:~/workspace/meu_projeto$ cat ~/.ssh/id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDB9Q0Pllr93U4Fnyv3SSF220brAqRpC3DlRrUf8KmdnpX3wNXgyXx5QV2e3jC2xduu3Oq89ty4v8bcppGENcpcc9wbsLyws1m3Jz7oKEqf1TWKhTz6PNpw/TKP6CmoCZuQWfpMuwira3/YgtxbAR9H9R4noo/+u9Pdu6fFznRXhcb6g+4/Hd3HFQhErM0hGJ/CGbPRzhtP+dFcKQq+RYeWBQnrGWjD5K726BvnPdr+klZ0EEpUt+N4vDOey7tCPO0Ia2PmwYgI/vkxgM6+OG3c5a5EKSwp3sUrgwha75mY+WXlkng9dKaVqjd1nOjRd/EUzwLFpKKbN8VpNrr51T8f petrovapierce@pcdabianca
petrovapierce@pcdabianca:~/workspace/meu_projeto$ git clone git@github.com:biancavonposer/exemplo_git.git
Cloning into 'exemplo_git'...
The authenticity of host 'github.com (140.82.114.4)' can't be established.
RSA key fingerprint is SHA256:nThbg6kXUpJWGl7E1IGOCspRomTxdCARLviKw6E5SY8.
Are you sure you want to continue connecting (yes/no)? yes
Warning: Permanently added 'github.com,140.82.114.4' (RSA) to the list of known hosts.
ERROR: Repository not found.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
petrovapierce@pcdabianca:~/workspace/meu_projeto$ cd exemplo_git
bash: cd: exemplo_git: No such file or directory
petrovapierce@pcdabianca:~/workspace/meu_projeto$ git clone git@github.com:biancavonposer/exemplo_git.git 
Cloning into 'exemplo_git'...
Warning: Permanently added the RSA host key for IP address '140.82.113.4' to the list of known hosts.
ERROR: Repository not found.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
petrovapierce@pcdabianca:~/workspace/meu_projeto$ git clone README.md@github.com:biancavonposer/exemplo_git.git
Cloning into 'exemplo_git'...
Warning: Permanently added the RSA host key for IP address '140.82.113.3' to the list of known hosts.
README.md@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
petrovapierce@pcdabianca:~/workspace/meu_projeto$ cd --
petrovapierce@pcdabianca:~$ cd workspace/
petrovapierce@pcdabianca:~/workspace$ git clone git@github.com:SEU_LOGIN/exemplo_git.git 
Cloning into 'exemplo_git'...
Warning: Permanently added the RSA host key for IP address '20.201.28.151' to the list of known hosts.
^[[D^[[D^[[D^[[D^[[DERROR: Repository not found.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
petrovapierce@pcdabianca:~/workspace$ git clone git@github.com:SEU_LOGIN/exemplo_git.git 
Cloning into 'exemplo_git'...
ERROR: Repository not found.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
petrovapierce@pcdabianca:~/workspace$ git clone git@github.com:biancavonposer/exemplo_git.git teste_projeto_git 
Cloning into 'teste_projeto_git'...
ERROR: Repository not found.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
petrovapierce@pcdabianca:~/workspace$ git remote -v
origin	https://github.com/biancavonposer/cookbook.rb.git (fetch)
origin	https://github.com/biancavonposer/cookbook.rb.git (push)
petrovapierce@pcdabianca:~/workspace$ git clone git@github.com:biancavonposer/meu_projeto.git
fatal: destination path 'meu_projeto' already exists and is not an empty directory.
petrovapierce@pcdabianca:~/workspace$ git clone git@github.com:biancavonposer/mkdir_git.git
Cloning into 'mkdir_git'...
ERROR: Repository not found.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
petrovapierce@pcdabianca:~/workspace$ sudo git clone git@github.com:biancavonposer/mkdir_git.git
[sudo] password for petrovapierce: 
Cloning into 'mkdir_git'...
The authenticity of host 'github.com (140.82.114.4)' can't be established.
RSA key fingerprint is SHA256:nThbg6kXUpJWGl7E1IGOCspRomTxdCARLviKw6E5SY8.
Are you sure you want to continue connecting (yes/no)? yes
Warning: Permanently added 'github.com,140.82.114.4' (RSA) to the list of known hosts.
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
petrovapierce@pcdabianca:~/workspace$ cd ~
petrovapierce@pcdabianca:~$ 
