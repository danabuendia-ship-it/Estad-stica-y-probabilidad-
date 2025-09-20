---
title: "Nominal 1"
author: "BUENDIA CAMACHO DANA PAOLA"
date: "2025-09-19"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

```{r}

sexo <- c("NA","NA","NA","Femenino","NA","Femenino","Femenino", 
          "Femenino","NA","Masculino","Femenino","Femenino", 
          "Masculino","Femenino","NA","Masculino","NA","NA", 
          "Masculino","Masculino","Masculino","Masculino", 
          "NA","Femenino","NA")

# total de datos
length(sexo)
```


```{r}
#Con NA
table(sexo, useNA = "ifany")

# F. sin NA
tabla_sexo <- table(na.omit(sexo))
tabla_sexo

```

```{r}

porcentajes <- prop.table(tabla_sexo) * 100
porcentajes


prop.table(tabla_sexo)

```

```{r}

max_freq <- max(tabla_sexo)
moda <- names(tabla_sexo)[tabla_sexo == max_freq]
moda
```


```{r}
barplot(tabla_sexo,
        col = c("red", "pink", "purple"),
        main = "Distribución de Sexo",
        ylab = "Frecuencia")
```

```{r}
pie(tabla_sexo,
    col = c("red", "pink", "purple"),
    main = "Distribución de Sexo",
    labels = paste(names(tabla_sexo), round(porcentajes, 1), "%"))
```

----------------------------CODIGO 2----------------------------

---
title: "NOMINALES 2"
author: "BUENDIA CAMACHO DANA PAOLA"
date: "2025-09-19"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

```{r}

Nacionalidades <- c("Boliviana","Peruana","Venezolana","Cubana",
                    "Mexicana","Colombiana","Colombiana",
                    "Brasileña","Colombiana","Venezolana","Chilena",
                    "Argentina","Mexicana","Mexicana","Argentina",
                    "Mexicana","Argentina","Brasileña","Mexicana",
                    "Uruguaya","Argentina","Argentina","Colombiana",
                    "Cubana","Boliviana","Peruana","Boliviana",
                    "Boliviana","Peruana","Uruguaya","Chilena",
                    "Uruguaya","Venezolana","Uruguaya","Argentina",
                    "Venezolana","Uruguaya","Cubana","Venezolana",
                    "Cubana","Chilena","Argentina","Peruana",
                    "Boliviana","Cubana","Venezolana","Colombiana",
                    "Mexicana","Uruguaya","Argentina")

# total de datos
length(Nacionalidades)
```

```{r}

table(Nacionalidades, useNA = "ifany")


tabla_Nacionalidades <- table(na.omit(Nacionalidades))
tabla_Nacionalidades

```

```{r}

porcentajes <- prop.table(tabla_Nacionalidades) * 100
porcentajes


prop.table(tabla_Nacionalidades)

```

```{r}

max_freq <- max(tabla_Nacionalidades)
moda <- names(tabla_Nacionalidades)[tabla_Nacionalidades == max_freq]
moda
```

```{r}
barplot(tabla_Nacionalidades,
        col = c("red","brown","skyblue","lightgreen","violet","green","blue",
            "black","orange","beige"),
        main = "Distribución de Nacionalidades",
        ylab = "Frecuencia")
```

```{r}
pie(tabla_Nacionalidades,
    col = c("plum","gray","orange",
            "cadetblue","brown","green","beige",
            "red","salmon","magenta"),
    main = "Distribución de Nacionalidades",
    labels = paste(names(tabla_Nacionalidades), round(porcentajes, 1), "%"))

```
------------------------CODIGO 3------------------------

---
title: "Nominal 3"
author: "BUENDIA CAMACHO DANA PAOLA"
date: "2025-09-19"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```



```{r}

ojos<- c("gris","azul","ambar","negro","avellana","cafe",
                  "avellana","azul","verde","ambar","avellana",
                  "cafe","cafe","azul","verde","azul","avellana",
                  "verde","verde","verde","gris","negro","avellana",
                  "negro","gris","negro","avellana","azul","ambar","verde")

#  total de datos
length(ojos)
```


```{r}

table(ojos, useNA = "ifany")


tabla_ojos <- table(na.omit(ojos))
tabla_ojos

```

```{r}

porcentajes <- prop.table(tabla_ojos) * 100
porcentajes

# Proporciones
prop.table(tabla_ojos)

```

```{r}

max_freq <- max(tabla_ojos)
moda <- names(tabla_ojos)[tabla_ojos == max_freq]
moda
```


```{r}
barplot(tabla_ojos,
        col = c("red","salmon","blue","green",
                "purple","magenta","violet"),
        main = "Distribución de Color de ojos",
        ylab = "Frecuencia")
```

```{r}
pie(tabla_ojos,
    col = c("blue","red","salmon","magenta",
                "green","purple","brown"),
    main = "Distribución de Color de ojos",
    labels = paste(names(tabla_ojos), round(porcentajes, 1), "%"))

```

------------------CODIGO 4------------------------------------

---
title: "NOMINAL 4"
author: "BUENDIA CAMACHO DANA PAOLA"
date: "2025-09-20"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

```{r}

marcas <- c("Apple", "Samsung", "LG", "Huawei", "OnePlus", "Sony",
            "Apple", "Samsung", "Huawei", "Huawei", "Nokia", "OnePlus",
            "Motorola", "Xiaomi", "Samsung", "Apple", "Apple", "Motorola",
            "Samsung", "Samsung", "Huawei", "Motorola", "Nokia", "OnePlus",
            "Huawei", "Huawei", "Apple", "LG", "Apple", "Xiaomi", "LG",
            "OnePlus", "OnePlus", "LG", "Sony", "Samsung", "Apple", "Xiaomi",
            "Oppo", "Motorola", "LG", "Samsung", "Motorola", "Samsung", 
            "Nokia", "OnePlus", "OnePlus", "Oppo", "Sony", "Nokia", "Huawei",
            "LG", "Sony", "Xiaomi", "LG", "Huawei", "LG", "Nokia", "Xiaomi",
            "Sony", "OnePlus", "LG", "Xiaomi", "OnePlus", "Oppo", "Nokia",
            "Huawei", "Xiaomi", "Oppo", "Oppo")

# Total datos
length(marcas)

```

```{r}
# Tabla de frecuencias
tabla_marcas <- table(na.omit(marcas))
tabla_marcas

```

```{r}
# Porcentajes
porcentajes <- prop.table(tabla_marcas) * 100
porcentajes

# Proporciones
prop.table(tabla_marcas)

```

```{r}

max_freq <- max(tabla_marcas)
moda <- names(tabla_marcas)[tabla_marcas == max_freq]
moda

```

```{r}

barplot(tabla_marcas,
        col = rainbow(length(tabla_marcas)),
        main = "Distribución de Marcas de Celular",
        ylab = "Frecuencia",
        las = 2)

```

```{r}

pie(tabla_marcas,
    col = rainbow(length(tabla_marcas)),
    main = "Distribución de Marcas de Celular",
    labels = paste(names(tabla_marcas), round(porcentajes, 1), "%"))

```

---------------------CODIGO 5---------------------


---
title: "NOMINAL 5"
author: "BUENDIA CAMACHO DANA PAOLA"
date: "2025-09-20"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```
```{r}
estado_civil <- c(
  "Viudo", "Viudo", "Unión libre", "Soltero", "Viudo", "Unión libre", 
  "Divorciado", "Casado", "Unión libre", "Viudo", "Viudo", "Soltero", 
  "Divorciado", "Divorciado", "Divorciado", "Unión libre", "Casado", 
  "Unión libre", "Casado", "Soltero", "Viudo", "Casado", "Casado", 
  "Divorciado", "Unión libre", "Soltero", "Divorciado", "Divorciado", 
  "Casado", "Unión libre", "Soltero", "Viudo", "Soltero", "Divorciado", 
  "Viudo", "Viudo", "Soltero", "Divorciado", "Viudo", "Viudo", "Soltero", 
  "Unión libre", "Divorciado"
)
```

```{r}

tabla_estado <- table(na.omit(estado_civil))
tabla_estado
```

```{r}
# Porcentajes
porcentajes <- prop.table(tabla_estado) * 100
porcentajes

# Proporciones
prop.table(tabla_estado)

```

```{r}

max_freq <- max(tabla_estado)
moda <- names(tabla_estado)[tabla_estado == max_freq]
moda
```

```{r}

barplot(tabla_estado,
        col = terrain.colors(length(tabla_estado)),
        main = "Distribución de Estado Civil",
        ylab = "Frecuencia",
        las = 2)

```

```{r}

pie(tabla_estado,
    col = terrain.colors(length(tabla_estado)),
    main = "Distribución de Estado Civil",
    labels = paste(names(tabla_estado), round(porcentajes, 1), "%"))

```


