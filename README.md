```
wget https://raw.githubusercontent.com/chubbyhippo/ideavimrc/main/.ideavimrc -P ~
```
```
curl https://raw.githubusercontent.com/chubbyhippo/ideavimrc/main/.ideavimrc -o ~/.ideavimrc
```
```
$WebClient=New-Object Net.WebClient
$Uri='https://raw.githubusercontent.com/chubbyhippo/ideavimrc/main/.ideavimrc'
$WebClient.DownloadFile($Uri, "$Home/.ideavimrc")
```
