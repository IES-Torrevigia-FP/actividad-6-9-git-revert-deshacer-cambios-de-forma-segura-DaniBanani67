# Reflexión

git revert deshace los cambios de un commit creando otro commit nuevo que los invierte

La diferencia con git reset es que reset borra commits del historial, mientras que revert mantiene todo el historial

Se prefiere usar revert cuando el proyecto ya se ha compartido con otras personas, porque no cambia la historia del repositorio

Por eso se dice que es un "forward undo", porque deshace cambios avanzando con un nuevo commit en lugar de borrar los anteriores