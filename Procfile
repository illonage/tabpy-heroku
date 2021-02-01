web: export TABPY_PORT=$PORT && 
if ["$USERNAME"]; then
    export TABPY_PWD_FILE=./file.txt && tabpy-user add -u $USERNAME -p $PASSWORD -f ./file.txt && tabpy
else 
    tabpy
fi