# Adalab-Modulo-3-ejercicio-intermedio

### Este proyecto tiene como objetivo analizar diversas estadísticas de canciones disponibles en Spotify y los datos de sus videos musicales en YouTube. 

## Descripción del Dataframe
El dataframe incluye información sobre canciones y videos musicales, integrando datos de Spotify y YouTube. Contiene un total de 27 variables:

#### Variables de Spotify
1. Track: Nombre de la canción tal como aparece en Spotify.
2. Artist: Nombre del artista.
3. Url_spotify: URL de la canción en Spotify.
4. Album: Álbum en el que se encuentra la canción.
5. Album_type: Tipo de publicación de la canción en Spotify (single o álbum).
6. Uri: Enlace de Spotify para encontrar la canción a través de la API.
7. Danceability: Medida de 0.0 a 1.0 que indica la idoneidad para bailar, basada en elementos musicales como el tempo y la estabilidad del ritmo.
8. Energy: Medida de 0.0 a 1.0 que representa la intensidad y actividad perceptiva de la canción. Las pistas energéticas suelen ser rápidas y ruidosas.
9. Key: Clave de la pista, representada con números enteros según la notación Pitch Class (0 = C, 1 = C♯/D♭, etc.).
10. Loudness: Sonoridad global de la pista en decibelios (dB), promediada en toda la canción.
11. Speechiness: Medida de la presencia de palabras habladas en una pista. Los valores superiores a 0.66 indican pistas compuestas principalmente por palabras habladas.
12. Acousticness: Medida de confianza de 0.0 a 1.0 para determinar si la pista es acústica.
13. Instrumentalness: Predice si una pista no contiene voces. Valores superiores a 0.5 sugieren que la canción es instrumental.
14. Liveness: Indica la probabilidad de que la pista se haya grabado en vivo. Valores superiores a 0.8 indican una alta probabilidad de que la pista sea en directo.
15. Valence: Medida de 0.0 a 1.0 que describe la positividad musical de una pista. Valores altos indican una sensación positiva (felicidad, alegría).
16. Tempo: Tempo estimado de la pista en pulsaciones por minuto (BPM).
17. Duration_ms: Duración de la pista en milisegundos.
18. Stream: Número de streams de la canción en Spotify.
#### Variables de YouTube
19. Url_youtube: URL del video relacionado con la canción en YouTube.
20. Title: Título del video en YouTube.
21. Channel: Nombre del canal que publicó el video.
22. Views: Número de vistas del video en YouTube.
23. Likes: Número de "me gusta" del video.
24. Comments: Número de comentarios en el video.
25. Description: Descripción del video en YouTube.
26. Licensed: Indica si el video contiene contenido con licencia, es decir, si fue subido a un canal vinculado a un socio de contenido de YouTube y luego reclamado por dicho socio.
27. official_video: Valor booleano que indica si el video es el oficial de la canción.

## Estructura del Proyecto
1. Exploración de Datos: Analizar y describir las variables principales del dataframe (importado del csv 'Spotify_Youtube').
2. Análisis de Correlación (patrones): Estudiar la relación entre las características de las canciones y su rendimiento en Spotify y YouTube.
3. Visualización de Datos: Crear gráficos que representen la relación entre las distintas métricas.
4. Conclusiones: Resumir los hallazgos principales y su relevancia.

## Requisitos
Para llevar a cabo este ejercicio, se recomienda tener conocimientos básicos en:

- Python
- Pandas para el manejo de datos
- Matplotlib y Seaborn para visualización de datos
- Análisis de datos y estadística básica
- Análisis de datos y estadística básica
