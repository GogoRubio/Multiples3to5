# Multiples3to5

main = putStrLn (show respuesta)
--en esta parte a la variable respuesta le damos la suma de la lista X donde X pertenecera a la lista de 0 a 999 y pedira el residuo(mod) de 3 o de 5 como se ve a continuacion --
respuesta = sum [x | x <- [0..999], (mod x 3) == 0 || (mod x 5) == 0]

