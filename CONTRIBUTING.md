# Guía de contribución

## Diarios de investigación

### Propósito

Cuando se realicen issues que impliquen investigaciones, es importante commitear los "diarios de investigación" en formato markdown. Esta práctica ayuda a:

1. **Eliminar la dependencia de enlaces a chatbots**: Los textos de conversaciones con LLMs (como Gemini, ChatGPT, etc.) se preservan en el repositorio en lugar de depender de enlaces externos que pueden desaparecer.

2. **Evitar el vendor lock-in del hosting Git**: Al estar en el historial de commits, todos los clones del repositorio contienen esta información, no solo la instancia alojada en GitHub.

### Práctica recomendada

Cuando trabajes en un issue que requiera investigación:

1. **Crea archivos markdown** con los textos de tus investigaciones, especialmente aquellos procedentes de LLMs o conversaciones con herramientas de IA.

2. **Commitea estos archivos** durante el proceso de investigación, no solo al final.

3. **Preserva el historial**: Estos archivos quedan registrados en la historia de commits, incluso si se eliminan antes del merge final.

4. **Opcional: Eliminar antes del merge**: Si los diarios de investigación no tienen cabida en el contenido principal del repositorio, pueden eliminarse antes de mergear. Lo importante es que ya están en el historial de Git.

### Estructura sugerida

Puedes crear tus diarios de investigación con nombres descriptivos, por ejemplo:

```
investigacion-[tema]-[fecha].md
diario-issue-[numero].md
notas-investigacion-[descripcion].md
```

### Beneficios

- **Transparencia**: Otros colaboradores pueden ver el proceso de investigación que llevó a una solución.
- **Continuidad**: Si alguien más retoma el trabajo, tiene contexto completo.
- **Independencia**: No dependemos de servicios externos para preservar el conocimiento.
- **Autonomía**: El repositorio es autónomo y contiene toda su historia, sin depender de un proveedor específico de hosting.
