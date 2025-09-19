
---
title: "POLITOMICAS 1"
author: "BUENDIA CAMACHO DANA PAOLA"
date: "2025-09-19"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

```{r}
sangre <- c("A-", "AB-", "AB+", "B+", "O-", "O+", "B+", "A-", "O-", "B-", "A-", "A-", "O+", "A+",
 "O+", "AB+", "B+", "AB+", "AB-", "B-", "O-", "O+", "B+", "O+", "O+", "O+", "A+", "O-", "AB-", "A-", "B+",
 "O-", "B-", "A-", "A-", "AB-", "B+", "AB-", "A-", "B+", "A-", "AB-", "O-", "AB+", "B+", "O+", "B-", "O-", "A-",
 "AB-", "O+", "AB+", "AB+", "B+", "O-", "AB+", "AB+", "AB-", "A-", "O-", "AB+", "AB+", "A+", "A+",
 "O+", "B+", "AB-", "O-", "A-", "A+", "A+", "B-", "B-", "B-", "A+", "A-", "AB-", "A-", "A-", "AB+")
               
```

```{r}
#SUMATORIA DE DATOS
summary(sangre)
```

```{r}
sangre_ord <- sort(sangre); (sangre_ord)
```

```{r}
table(sangre) 
prop.table(table(sangre)) 
```

```{r}

freq <- table(sangre)
porc <- round(prop.table(freq)*100, 1)
mi_min <- names(freq)[which.min(freq)]
(mi_min)
mi_max <- names(freq)[which.max(freq)]
(mi_max)
```

```{r}
bar_colors <- c("pink","red","khaki",
            "blue","violet","green","brown",
            "orange")

# Gráfico
bp <- barplot(freq,
              col = bar_colors,
              main = "Tipo de Sangre",
              xlab = "",
              ylab = "Frecuencia",
              ylim = c(0, 50), # << ahora llega hasta 50
              cex.names = 0.9,
              space = 0.5
)


text(bp, freq, labels = freq, pos = 3, cex = 1, font = 2)
text(bp, freq, labels = freq, pos = 3, cex = 0.9, font = 2)
     
```

```{r}
pie(freq,
    labels = paste(names(freq), porc, "%"),
    col = rainbow(length(freq), 0.9),
    main = "Tipo de Sangre")
```

-----------------------CODIGO 2------------------------------

---
title: "POLITOMICAS 2"
author: "BUENDIA CAMACHO DANA PAOLA"
date: "2025-09-19"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

```{r}
Ocupacion <- c("Desempleado", "Estudiante", "Empleado", "Empleado", "Estudiante", "Empleado", "Empleado", "Empleado", "Jubilado", "Jubilado", "Jubilado", "Jubilado", "Jubilado", "Estudiante", "Desempleado", "Desempleado", "Jubilado", "Empleado", "Estudiante", "Estudiante", "Empleado", "Desempleado", "Estudiante", "Desempleado", "Jubilado", "Empleado", "Jubilado", "Desempleado", "Desempleado", "Desempleado")
               
```

```{r}
#Sumatoria de datos (Ocupacion)
summary(Ocupacion)
```

```{r}
Ocupacion_ord <- sort(Ocupacion); (Ocupacion_ord)
```

```{r}
table(Ocupacion) 
prop.table(table(Ocupacion))
```

```{r}

freq <- table(Ocupacion)
porc <- round(prop.table(freq)*100, 1)
mi_min <- names(freq)[which.min(freq)]
(mi_min)
mi_max <- names(freq)[which.max(freq)]
(mi_max)
```

```{r}
bar_colors <- c("pink","black","yellow",
            "red")

# Gráfico
bp <- barplot(freq,
              col = bar_colors,
              main = "Ocupacion",
              xlab = "",
              ylab = "Frecuencia",
              ylim = c(0, 50), # << ahora llega hasta 50
              cex.names = 0.9,
              space = 0.5
)

# Agregar valores encima de cada barra
text(bp, freq, labels = freq, pos = 3, cex = 1, font = 2)
text(bp, freq, labels = freq, pos = 3, cex = 0.9, font = 2)
     
```

```{r}
pie(freq,
    labels = paste(names(freq), porc, "%"),
    col = rainbow(length(freq), 0.9),
    main = "Ocupacion")
```


