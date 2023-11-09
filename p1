//PROBLEMA 1
//---------------------
//El siguiente programa ...
object PalabraConMasVocales {
  def contarVocales(palabra: String): Int = {
    palabra.toLowerCase.count(c => "aeiou".contains(c))
  }

  def palabraConMasVocales(palabras: Array[String]): String = {
    if (palabras.isEmpty) {
      "No se proporcionaron palabras."
    } else {
      palabras.maxBy(contarVocales)
    }
  }

  def main(args: Array[String]): Unit = {
    if (args.nonEmpty) {
      val palabraResultante = palabraConMasVocales(args)
      println(s"La palabra con más vocales es: $palabraResultante")
    } else {
      println("Por favor, proporciona una lista de palabras como argumentos.")
    }
  }
}
