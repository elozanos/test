# Contributing guide

**¿Querés contribuir? ¡Genial!**
Intentamos que sea fácil y ágil. Todas las contribuciones, incluso las más pequeñas, son más que bienvenidas.
Esto incluye reportes de errores, correcciones, documentación, ejemplos ...

Si tenés alguna duda o pregunta, recordá que tenemos nuestro channel de Slack [#help-mantra](https://meli.slack.com/archives/C016GDSQAHG).

# Cómo podés contribuir
* [Reportando un bug](#reportando-un-bug)
* [Proponiendo un nuevo feature o mejora](#proponiendo-un-nuevo-feature-o-mejora)
* [Sumando un PR (feature o fix)](#sumando-un-pr-%28feature-o-fix%29)

## Reportando un bug
Si querés reportar un bug hacelo [acá](https://github.com/mercadolibre/fury_backend-mantra/issues/new?labels=bug).

Al informar el bug poné un título y descripción del problema que viste. Indica una forma clara de reproducirlo, lo que estás viendo y lo que esperarías ver. Si querés sumar alguna captura de pantalla mejor :).

## Proponiendo un nuevo feature o mejora
Si querés proponer un nuevo feature o mejora hacelo [acá](https://github.com/mercadolibre/fury_backend-mantra/issues/new?labels=enhancement). 

Al proponer un nuevo feature explicá claramente la necesidad (o caso de uso) puntual que se intenta resolver, si es una mejora describí porque esta alternativa es superior a lo que existe actualmente.
Toda información adicional de contexto o capturas de pantalla son bienvenidas.

## Sumando un PR (feature o fix)
Para contribuir con un PR tené en cuenta lo siguiente:
 * Antes de enviar el PR cargá un issue (bug or feature).
 * Respetá el [GitFlow](https://furydocs.io/release-process/guide/#/lang-es/workflows/02_gitflow) utilizado.
 * El PR debe tener un título y descripción claros. Agregar el o los issues en la descripción (uno por línea).
 * Agregá pruebas que cubran todo el código nuevo o modificado, el PR debe tener 100 % de coverage. Usá los test existentes como plantilla para realizar los test case correctamente.
 * Los commits deben ser atómicos y semánticos, hacé squash commits adecuadamente antes de enviar el PR. Fixup commits pueden ser utilizadas temporalmente durante el proceso de revisión, después deberemos hacer squash para tener commits más significativos.
 * Si el PR corresponde a un nuevo kpi debe ir con otro PR que actualice la [Documentación](https://furydocs.io/backend-mantra/guide/).
 * Nos basamos en este [Coding Guide](https://golang.org/doc/effective_go).
