Hola Git 
Qué debe hacer el colaborador (usuario 2)

Una vez que acepta la invitación, en SU computadora:

git clone https://github.com/JosethJax/Ejercicio5To.git
cd Ejercicio5To
git checkout usuario2/ajustes-diseño


Luego:

# hace cambios
git add .
git commit -m "Ajustes de diseño del usuario 2"
git push


📌 Esos commits quedan firmados con su usuario, eso es lo que revisa el profe.

✅ Cómo “forzar” que no toquen main (opcional, nivel pro)

En GitHub:

Settings → Branches

Add rule para main

Marca:

✅ Require pull request

✅ Require approvals

👉 Así nadie puede hacer push directo a main, solo vía PR.

🧪 Flujo ideal (lo que tú ya estás haciendo)
main
 └── develop
      ├── usuario1/nueva-funcionalidad
      └── usuario2/ajustes-diseño


✔️ Perfecto para trabajo en equipo
✔️ Muy bien visto académicamente
✔️ Clarísimo para evaluación

💡 Extra tip para que te lo califiquen bien

Dile a cada usuario que:

Haga mínimo 2 commits

Con mensajes claros

Y luego un Pull Request a develop

Si quieres, dime:

qué pide exactamente tu profe

cuántos integrantes son

y te digo exactamente cómo entregarlo para sacar 10/10 💯😎
