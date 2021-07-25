Este é o readme do meu primeiro projeto como exemplo na apostila da Campus Code.
Estou seguindo os passos da apostila, assim, posso fixar o conteúdo e ampliar minha
aprendizagem para a próxima etapa do treinadev.

Esse é o erro que eu recebi quando fui clonar o projeto.




   
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
