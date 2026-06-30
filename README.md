# Registros de la Propiedad por Municipio (España)

Conjunto de datos que asocia **cada municipio de España con su Registro de la Propiedad**, incluyendo la **dirección** de la oficina y el **enlace** a su ficha en el directorio oficial del Colegio de Registradores (registradores.org).

Hasta donde he podido comprobar, **no existía un único listado público** que cruzara *municipio → registro de la propiedad → dirección*. Esta es la razón de publicarlo: que cualquiera pueda usarlo libremente.

---

## 📂 Contenido

**Archivo:** `Registros de la Propiedad por Municipio (España) 2026.xlsx`
Hoja `Registros` · una fila por municipio · **10.536 municipios**.

| Columna | Descripción |
|---|---|
| **Nombre provincia** | Provincia del municipio |
| **Nombre municipio** | Municipio (nomenclatura INE) |
| **Nombre completo** | Nombre del Registro de la Propiedad asignado, tal cual (incluye número si lo tiene). Ej.: `VITORIA - GASTEIZ 5` |
| **Nombre** | Nombre del registro sin el número. Ej.: `VITORIA - GASTEIZ` |
| **Número** | Número del registro dentro de la localidad (vacío si el registro no está numerado). Ej.: `5` |
| **Dirección** | Dirección de la oficina del registro |
| **Enlace** | Hipervínculo (clicable) a la ficha del registro en registradores.org |

> El **código INE del municipio** (5 dígitos) se usó internamente para la asignación; el archivo publicado se centra en los nombres, la dirección y el enlace.

---

## 📊 Cobertura

- **10.536** municipios.
- **~1.059** oficinas de Registro de la Propiedad distintas.
- La gran mayoría incluyen **dirección** y **enlace** a su ficha oficial.
- Quedan **sin dirección/enlace** unos pocos registros que **no aparecen** en el directorio oficial (<https://www.registradores.org/directorio/-/registros/propiedad>). Es posible que hayan **cerrado, se hayan fusionado o renumerado**, pero **no puedo confirmarlo**:
  - **Badajoz 2** — en el directorio solo figuran Badajoz Nº 01 y Nº 03.
  - **Gijón 4** — marcado *«(ANTIGUO)»* en los datos de origen.
  - **Málaga 14** — marcado *«(ANTIGUO)»* en los datos de origen.

---

## 🗂️ Fuentes y método

- **Asignación municipio → registro** y códigos: **códigos INE** de provincia y municipio.
- **Direcciones y enlaces:** directorio público de **registradores.org** (Colegio de Registradores de la Propiedad, Mercantiles y de Bienes Muebles de España).
- El cruce entre el listado de municipios y el directorio de oficinas se hizo normalizando nombres (acentos, mayúsculas, formas bilingües tipo *Alacant/Alicante* o *Donostia/San Sebastián*, y la numeración `Nº`).
- **Fecha de recopilación:** 2026. Los datos pueden cambiar con el tiempo (nuevas oficinas, traslados, renumeraciones).

---

## 🚀 Uso

- Abre el `.xlsx` con Excel, LibreOffice Calc o Google Sheets.
- La columna **Enlace** es clicable y lleva a la ficha oficial de cada registro.
- Puedes filtrar por provincia o municipio para localizar el registro que te corresponde.

---

## ⚠️ Aviso legal y descargo de responsabilidad

- Este es un proyecto **no oficial** y **sin ánimo de lucro**. **No** está afiliado, avalado ni asociado con el Colegio de Registradores, el INE ni ningún organismo público.
- Los datos se han recopilado de **fuentes públicas** y se ofrecen **«tal cual» (as is), sin garantía** de exactitud, integridad ni vigencia.
- La información **puede contener errores u omisiones** y **quedar desactualizada**. Antes de tomar cualquier decisión legal, administrativa o económica, **verifica siempre** los datos en la **fuente oficial**: <https://www.registradores.org>.
- El autor **no se hace responsable** de ningún daño o perjuicio derivado del uso de estos datos.
- Las marcas, nombres y enlaces citados pertenecen a sus respectivos titulares. Si eres titular de derechos y deseas alguna corrección o retirada, abre una *issue*.

---

## 🤝 Contribuir

¿Has detectado un registro mal asignado, una dirección incorrecta o un cambio reciente? Abre una **issue** o envía un **pull request** indicando municipio, registro y la corrección.

---

*Última actualización del conjunto de datos: 2026.*
