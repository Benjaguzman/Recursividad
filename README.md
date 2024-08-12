# Recursividad
:smile:

<pre>fun numerosDesc(n: Int) {
    if(n <= 0)
    {
        return
    }
    println(n)
    numerosDesc(n - 1)
}
fun main()
{
    val num = 5
    numerosDesc(num)
}</pre>
# Funcion
1- La funcion reursiva llamada - numeroDesc - que imprime los numeros en orden descendientes desde un valor entero dado hasta 1.

## Componentes
Caso base

<pre>
    if(n = <=0)
        {
        return
        }
</pre>
La condicion que termina la recursion y evita un ciclo infinito
