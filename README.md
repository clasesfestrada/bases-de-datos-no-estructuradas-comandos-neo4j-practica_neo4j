# practica_neo4j

Repositorio mínimo para ejecutar **Neo4j** en **GitHub Codespaces** usando una distribución Linux (Ubuntu) vía Dev Containers.

## Requisitos

- GitHub Codespaces habilitado para el repositorio.

## Uso en Codespaces

1. Abre este repositorio en un Codespace.
2. El entorno levantará:
   - Un contenedor Linux (`mcr.microsoft.com/devcontainers/base:ubuntu`) para desarrollo.
   - Un servicio Neo4j (`neo4j:5.26`).
3. Accede a Neo4j Browser en el puerto reenviado **7474**.
4. Conéctate con:
   - Usuario: `neo4j`
   - Contraseña por defecto: `Neo4jStrongPass_2026!`

> Recomendado: configura un secret de Codespaces llamado `NEO4J_PASSWORD` para reemplazar la contraseña por defecto.

## Puertos

- `7474`: Neo4j Browser (HTTP)
- `7687`: Bolt
