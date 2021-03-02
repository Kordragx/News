# NewsList APP

API:  https://hn.algolia.com/api/v1/search_by_date?query=mobile
Arquitectura MVVM
Consideraciones
 - Buscar la ruta del proyecto y ejecutar pod install en la terminal
 - Se filtra listado que no contenga titulo (title o storyTitle) ni url.
 - No se utiliza hora local, sólo Date() para comparar de mejor forma la fecha (created_at)
 - No están implementados los UnitCase, ya que sólo los he estudiado pero no aplicado.
