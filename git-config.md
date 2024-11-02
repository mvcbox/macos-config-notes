# Configuration `core.sshCommand`
```
git clone -c "core.sshCommand=ssh -i ~/.ssh/id_rsa_example -F /dev/null" git@github.com:example/example.git
cd example/
git pull
git push
```
or
```
git config --local core.sshCommand "ssh -i ~/.ssh/id_rsa_example -F /dev/null"
```
