# Assignment-12.2

Task 1
scala> var x = List("Alpha","Gamma","Omega","Zeta","Beta")

Task 2
scala> x.count(s=>s.length==4)
res72: Int = 2

Task 3
scala> x.map(s=> s.length)
res55: List[Int] = List(5, 5, 5, 4, 4)

Task 4
scala> x.filter(s=> s.contains("m"))
res25: List[String] = List(Gamma, Omega)

Task 5
scala> x.filter(s => s.startsWith("A"))
res69: List[String] = List(Alpha)
