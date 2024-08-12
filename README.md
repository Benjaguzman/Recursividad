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
