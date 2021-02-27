# Exercism

Vou subir os exercícios do [exercism](https://exercism.io/my/tracks) nesse repositório.

Não consegui subir o primeiro exercício, mas esse era o mais trivial.

- [**Solução Reverse String**](https://github.com/luishads/exercism-kotlin/blob/master/reverse-string/src/main/kotlin/ReverseString.kt) 

  ````kotlin
  fun reverse(input: String): String {
     return input.reversed()
  }
  ````
- [**Solução Tow-fer**](https://github.com/luishads/exercism-kotlin/blob/master/two-fer/src/main/kotlin/TwoFer.kt)
  
	````kotlin
  internal fun twofer(name: String): String {
    if (name.isEmpty()) {
        return "One for you, one for me."
    } else {
            return "One for $name, one for me."
    }
}
  ````