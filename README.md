# clase3 gitlab workshop

## create user in gitlab and login
https://gitlab.com


## install git command line tool
```
brew install git 
brew install gh
```

## connect your command line to github
```
gh auth login
```

Copy this string and paste it into GitLab: 
User Settings -> SSH Keys -> Add New Key

## Obtener el repositorio clase3
```
cd carpeta_de_trabajo
git clone https://github.com/ngiaved/clase3
```

## Crear una rama
```
git checkout -b feature/test
```

## Realizar un commit
```
echo "test" >> ingestion_config.txt
git add ingestion_config.txt
git commit -m "feat: test1"
git push
```
## crear un merge reqest

```
gh pr create
gh pr view
```
## revisar la ejecución de un runner

