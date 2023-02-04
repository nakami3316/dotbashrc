# dotbashrc
```
vim .bashrc
```
.bashrcに下記を追加
```
function cpcd(){
    cp $1 $2
    cd $2
}

function mkcd(){
    mkdir $1
    cd $2
}
```
```
source .bashrc
```
