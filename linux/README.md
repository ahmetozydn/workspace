| command                                              | description                                                           | tags     |
|------------------------------------------------------|-----------------------------------------------------------------------|----------|
| sudo !!                                              | son komutu sudo izniyle tekrarlar                                     |          |
| tail -f                                              | akan içerikli getir                                                   |          |
| !123                                                 | history komutundan sonra 123. komutun terminale kopyalanmasını sağlar |          |
| $SHELL $0                                            |                                                                       |          |
| $HOME ~                                              |                                                                       |          |
| cp -r                                                | folder ve alt folderları kopyala,                                     |          |
| wc                                                   | statistics                                                            | \-c , -w |
| cat data.json \| jq '.employees \| length'           | bir arraying uzunluğunu bulmak                                        |          |
| grep -Hrn "KALov"                                    | search also subdirectories                                            |          |
| grep -Hrn "REDIS" \| awk -F '/' '{print $2}'|                                                                      |          |
| echo -n 'find length' \| wc -m                       | find lenth of the string                                              |          |
| history \| grep -i "Search_pattern"                  | history'de komut arama                                                |          |
| apropos  <command>,  <command> --help, man <command> |                                                                       |          |
| printenv                                             |                                                                       |          |
| printenv \| grep '^UD'                               |                                                                       |          |
