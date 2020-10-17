(D)RAE - Consulta los diccionarios de la RAE
=========================================

Fork del proyecto de Marbely Veroy.

El módulo **rae** contiene las siguientes clases:
- **Article**
- **DA** (Diccionario de americanismos) *En desarrollo*
- **DEJ** (Diccionario del español jurídico) *En desarrollo*
- **DLE** (Diccionario de la lengua española)
- **DPD** (Diccionario panhispánico de dudas) *En desarrollo*

Métodos estáticos de la clase DLE
---------------------------------
- anagrams(word)
- autocomplete(substr)
- conjugate_id(verb_id)
- conjugate_verb(verb)
- contains(substring)
- ends_with(suffix)
- exact(word)
- get_lemmas()
- random_word()
- search_id(word_id)
- search_word(word, m=None)
- starts_with(prefix)
- todays_word()

---

Historial de cambios
--------------------

-- Versión 0.0.5: Añadido install_requires en setup.py

-- Subo el proyecto a PyPI (https://pypi.org/project/rae/) Versión 0.0.4

-- Cambio de nombre del proyecto a RAE

-- Expresiones regulares en vez de index() y slicing

-- Corregido error en DLE._options()
-- Pequeñas mejoras en el código

-- Añadidas letras mayúsculas en DLE.get_lemmas()

-- Añadida función DLE.autocomplete()
-- filter() en vez de list comprehension
-- Creación de la clase DA

-- Corregido otro error en DLE.get_lemmas()
-- Orden imports
-- New-style classes

-- Corregido pequeño error en DLE.get_lemmas()

-- Añadida compatibilidad con Python 2

-- Creación de las clases _Shared, DLE, DPD y DEJ
-- Conjugación de verbos
-- Palabra aleatoria
-- Búsqueda exacta
-- Empieza por
-- Termina en
-- Contiene
-- Anagramas
-- Palabra del día
-- Listado de palabras del diccionario
-- Cambio de nombre del proyecto a pyRAE

-- Subo la primera versión de dle-rae a GitHub. Sólo se pueden buscar las
  definiciones de una palabra
