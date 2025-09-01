# Matriz de escenarios y pruebas

## Ejemplo de casos a probar

- Disco vacío, instalación personalizada con LUKS+BTRFS+Hibernate.
- Con Windows + espacio libre, usar libre y validar boots.
- Redimensionar NTFS/ext4, chequear backup y restore.
- Detectar Ubuntu existente y ofrecer respaldo.
- Disco lleno sin redimensionables: bloquear, wipe, otro disco.
- BitLocker: requerir recovery key.
- Hibernación: validar resume y swap.
- Boot menu: presencia correcta de entradas.

## TODO
- Completar matriz con todos escenarios y corner cases.
- Añadir scripts de test automáticos.
