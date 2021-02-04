# Code Camp 2021



# Initial steps (configuration)

```bash
# ver la version
git --version
# configurar tu usuario para que cada que hagas un commit quede rastreado tu nombre y correo
git config --global user.name "Nombre"

git config --global user.email "tuemail@example.com"

```



# Crear un repositorio

> sabias que a diferencia de otros VCS git puede ser usado offline ❓

```bash
# crear un folder 'hola-mundo/'
mkdir hola-mundo
# movernos dentro del folder
cd hola-mundo
# inicializar git
git init
```

> 💡 Listo! eso es todo


# Commit

```bash
# crear archivo
touch file.txt
# comienza el flujo de trabajo en git

git status

git add file.txt

git commit -m "cree mi primer archivo"
```

> sabrias explicar que sucedio ❓