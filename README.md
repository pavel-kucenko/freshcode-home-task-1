# SOLUTIONS
- task 1
```
$mkdir ~/linuxTask
```
- task 2 (удалить все файлы, кроме тех в которых есть 'test')
```
$touch test testFile fileForTest testo Test-Testovich.bio
$rm !(*test*)
```
- task 3
```
$ln -s ./../../../bin/pwd linkPwd
$./ linkPwd
```
- task 4
```
$mkdir important
$touch 1 2 12 123 txt
$mv ??? ./important
```
- task 5
```
$env | grep LC > text.txt
```
- task 6
```
$sudo find / -name code >> text.txt
```
- task 7
```
$echo 'mpv udp://224.0.0.1:9999' > ~/startStream
$chmod a+x ~/startStream
```


