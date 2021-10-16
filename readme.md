# Iniciar proyecto de git
git init

# Preparar archivos que se convertiran en git
git add .
## El punto es para agregar todos los archivos modificados

# Creamos un commit con mensaje 
git commit -m "Aqui va la descripcion"

# Agregar remoto "Solo la primera vez"
git remote add origin https://github.com/ArturomcReyes/projectBRB.git

# Enviar commits al servidor de GitHub 
git push -u origin master 