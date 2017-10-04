# Javascript project boilerplate

## Bash function

```bash
# creates a new typescript project starter in the specified directory
newjs() {
    if [ -z "$1" ]; then
        echo "Destination folder param missing. (newjs folderName)"
    else
        git clone https://github.com/uollazzi/javascript-starter.git $1
        cd $1
        code .
    fi
}
```
