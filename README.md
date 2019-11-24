# Respuestas a las preguntas

### **- ¿Que comando utilizaste en el paso 11?**

`git reset --hard HEAD~1`

### **¿Por qué?**

porque al poner --hard, deshacemos además del commit, lo que hay en el working copy

### **- ¿Qué comando o comandos utilizaste en el paso 12?**
`git reflog`
`git reset --hard f852c56`

### **¿Por qué?**
`git reflog` para ver el *hash* y `git reset --hard f852c56` para volver a ese *commit* dejando el *working copy* como estaba.

### **- El merge del paso 13, ¿Causó algún conflicto?**
No
### **¿Por qué?**
Porque no había cambios que se "pisaran" y generaran conflicto.

### **-El merge del paso 19, ¿Causó algún conflicto?¿Por qué?**
Si, porque teniamos git-nuestro.md de 2 maneras distintas, con el HTML y el otro con Markdonw

### **-El merge del paso 21, ¿Causó algún conflicto?¿Por qué?**
No, porque no teniamos ningún archivo en conflicto.

### **¿Qué comando o comandos utilizaste en el paso 25?**
`git log --graph --decorate`

### **El merge del pasado, 26, ¿Podría ser fast forward?¿Porque?**
Si, porque no hay ningun conflicto

### **-Qué comando o comandos utilizaste en el paso 27?**
`git reset HEAD~1`

### **-¿Qué comando o comandos utilizaste en el paso 28?**
`git checkout` `git-nuestro.md`
 
### **:¿Qué comando o comandos utilizaste en el paso 29?**
`git branch -D title`

### **¿Qué comando o comandos utilizaste en el paso 30?**
`git reflog` `git reset --hard 028f93a`

### **¿Qué comando o comandos usaste en el paso 32?**
`git log` `git reflog` `git checkout eb86bd904a25da558dd5a2b2d62cf4eef4096d78`

### **-¿Qué comando o comandos usaste en el punto 33?**
`git reflog` `git checkout 39da9bc`
