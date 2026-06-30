# Registros de la Propiedad de España

Catálogo abierto de **todas las oficinas del Registro de la Propiedad de España**, con su **dirección** y el **enlace** a su ficha oficial en el directorio del Colegio de Registradores (registradores.org).

Hasta donde he podido comprobar, **no existía un único listado público** y limpio de los registros de la propiedad con su dirección y enlace. Esta es la razón de publicarlo: que cualquiera pueda usarlo libremente.

---

##  Archivo recomendado (el bueno)

**`Registros de la Propiedad de España (sin duplicados) 2026.xlsx`**

Hoja `Registros` · **una fila por oficina** (sin duplicados) · **1.061 registros**.

Cada oficina aparece **una sola vez**. Es la versión que debes usar.

| Columna | Descripción | Ejemplo |
|---|---|---|
| **Nombre completo** | Nombre del registro tal cual, incluye el número si lo tiene. | `VITORIA - GASTEIZ 5` |
| **Nombre** | Nombre del registro sin el número. | `VITORIA - GASTEIZ` |
| **Número** | Número del registro dentro de la localidad (vacío si no está numerado). | `5` |
| **Dirección** | Dirección de la oficina del registro. | `Portal de Castilla, 5 y 7` |
| **Enlace** | Hipervínculo (clicable) a la ficha del registro en registradores.org. | |
| **Provincia** | Provincia donde está la oficina (**nombre**, nomenclatura oficial INE). | `Bizkaia` |
| **Municipio** | Municipio sede de la oficina (**nombre**, nomenclatura INE). Vacío si no se ha podido determinar con seguridad. | `Bilbao` |

> Las columnas **Provincia** y **Municipio** llevan el **nombre** oficial (INE), no un código.
> En ~110 oficinas el **Municipio** queda vacío porque su nombre no se corresponde con un municipio del catálogo INE (p. ej. agrupaciones tipo «Tomos Generales» o sedes cuyo nombre no casa con un municipio). La **Provincia** está siempre informada.

---

##  Otro archivo incluido (vista por municipio)

**`Registros de la Propiedad por Municipio (España) 2026.xlsx`**

Listado complementario con **una fila por cada municipio de España** (10.536), indicando **qué registro de la propiedad le corresponde** a cada municipio. Útil si lo que necesitas es *“¿qué registro me toca según mi municipio?”*. En este archivo un mismo registro aparece repetido en todos los municipios que atiende; **no es el catálogo de oficinas** (para eso, usa el archivo recomendado de arriba).

---

##  Cobertura

- **1.061** oficinas de Registro de la Propiedad distintas (catálogo sin duplicados).
- La gran mayoría incluyen **dirección** y **enlace** a su ficha oficial.
- Quedan sin dirección/enlace unos pocos registros que **no aparecen** en el directorio oficial (<https://www.registradores.org/directorio/-/registros/propiedad>). Es posible que hayan **cerrado, se hayan fusionado o renumerado**, pero **no puedo confirmarlo**.

---

##  Fuentes y método

- **Oficinas, direcciones y enlaces:** directorio público de **registradores.org** (Colegio de Registradores de la Propiedad, Mercantiles y de Bienes Muebles de España).
- **Asignación municipio → registro y nombres geográficos:** **códigos y nomenclatura del INE** (provincias y municipios).
- La deduplicación se hizo por **enlace** (cada ficha de registradores.org = una oficina), y la sede (provincia/municipio) se resolvió cruzando el nombre de la oficina con el callejero del INE, normalizando acentos, mayúsculas y formas bilingües.
- **Fecha de recopilación:** 2026. Los datos pueden cambiar con el tiempo (nuevas oficinas, traslados, renumeraciones).

---

##  Uso

- Abre el `.xlsx` con Excel, LibreOffice Calc o Google Sheets.
- La columna **Enlace** es clicable y lleva a la ficha oficial de cada registro.
- Puedes filtrar por **Provincia** o **Municipio** para localizar el registro que te corresponde.

---

##  Aviso legal y descargo de responsabilidad

- Este es un proyecto **no oficial** y **sin ánimo de lucro**. **No** está afiliado, avalado ni asociado con el Colegio de Registradores, el INE ni ningún organismo público.
- Los datos se han recopilado de **fuentes públicas** y se ofrecen **«tal cual» (as is), sin garantía** de exactitud, integridad ni vigencia.
- La información **puede contener errores u omisiones** y **quedar desactualizada**. Antes de tomar cualquier decisión legal, administrativa o económica, **verifica siempre** los datos en la **fuente oficial**: <https://www.registradores.org>.
- El autor **no se hace responsable** de ningún daño o perjuicio derivado del uso de estos datos.
- Las marcas, nombres y enlaces citados pertenecen a sus respectivos titulares. Si eres titular de derechos y deseas alguna corrección o retirada, abre una *issue*.

---

##  Contribuir

¿Has detectado un registro mal asignado, una dirección incorrecta o un cambio reciente? Abre una **issue** o envía un **pull request** indicando registro, provincia/municipio y la corrección.

---

*Última actualización del conjunto de datos: 2026.*
