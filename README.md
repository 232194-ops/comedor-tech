# Comedor-Tech

Sistema de reserva y control de acceso al comedor universitario.

## Ramas del proyecto

- **master**: rama principal, solo acepta correcciones ya validadas de los colaboradores.
- **main**: modifica la parte de identificación del lector/comensal (login.html).
- **test**: implementa el login y la inicialización de usuarios (administrador y colaborador).

## Flujo de trabajo

1. Cada colaborador trabaja en su rama (main o test), con al menos 5 commits por iteración.
2. Se generan cambios simultáneos sobre las mismas líneas para provocar un conflicto entre main y test.
3. El conflicto se resuelve con P4Merge.
4. El master valida la resolución final antes de subirla a GitHub.
