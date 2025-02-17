import pandas as pd
# Crear un diccionario con los datos
data = {
    "Motivo de muerte": [
        "Falla sistema urinario", "Neoplasia", "Infeccioso", "Trauma",
        "Falla sistema cardiovascular", "Muerte súbita", "Cuerpo extraño"
    ],
    "0 a 4 años": [16, 13, 23, 19, 4, 3, 1],
    "5 a 9 años": [33, 23, 15, 5, 6, 3, 5],
    "10 a 14 años": [47, 50, 13, 3, 9, 1, 0],
    "15 años o más": [43, 37, 2, 1, 2, 0, 0]
}

# Crear el DataFrame
df = pd.DataFrame(data)

# Mostrar el DataFrame
print(df)

