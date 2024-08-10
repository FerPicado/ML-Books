# Carga y Exploración de Datos

- Se cargan los datos de un archivo CSV.
- Exploración inicial con `head()`, `info()`, `describe()` y `hist()`.

# División del Conjunto de Datos

- División aleatoria manual y con `train_test_split`.
- Estratificación basada en la categoría de ingresos (`income_cat`) con `StratifiedShuffleSplit`.

# Análisis Exploratorio de Datos (EDA)

- Visualización de distribuciones y correlaciones.
- Creación de nuevas características (`rooms_per_house`, `bedrooms_ratio`, `people_per_house`).

# Preprocesamiento

- Relleno de valores nulos con la mediana usando `SimpleImputer`.
- Codificación de variables categóricas con `OrdinalEncoder` y `OneHotEncoder`.

# Escalamiento y Transformaciones

- Escalamiento de características numéricas con `MinMaxScaler` y `StandardScaler`.
- Aplicación de kernel RBF para similitud de edad y ubicación.

# Transformadores Personalizados

- `FunctionTransformer` para log y similitud RBF.
- `StandardScalerClone` y `ClusterSimilarity`.

# Pipeline y ColumnTransformer

- Creación de `Pipeline` para numéricas y categóricas.
- Uso de `ColumnTransformer` y `make_column_transformer` para aplicar transformaciones específicas a columnas.
- Ejemplo de pipeline complejo incluyendo ratios, log y similitud de cluster.

# Preparación Final de Datos

- Transformación final de los datos con el preprocesamiento definido.
- Verificación de las características transformadas y sus nombres.

# Consejos Importantes

- **Recomendación**: Usa `make_column_transformer` para aplicar transformaciones específicas a columnas en un solo paso.
- **Consejo**: Simplifica y organiza mejor tu preprocesamiento de datos con `ColumnTransformer`.
