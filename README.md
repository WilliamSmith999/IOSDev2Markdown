# IOSDev2Markdown
[I'm a link to MarkDownSheet](./MarkDownSheet.md)


## this is a H2 sized header
#### this is a H4 sized header


A review of Starship troopers
<https://www.youtube.com/watch?v=sGF81Z1Kols>



```bash
#!/bin/bash

###### CONFIG
ACCEPTED_HOSTS="/root/.hag_accepted.conf"
BE_VERBOSE=false

if [ "$UID" -ne 0 ]
then
 echo "Superuser rights required"
 exit 2
fi

genApacheConf(){
 echo -e "# Host ${HOME_DIR}$1/$2 :"
}

```
