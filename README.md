# AgriNova-Alimentos-S.L.
Otra ejemplo de práctica de examen

## Jerarquía

- Administración y Dirección
  - Empleados
  - Plantas trabajo

- Producción
  - Clasificación productos
  - Protocolo manipulación
  - Manual envasado
  - Protocolo etiquetado
  
- Calidad y Seguridad Alimentaria
  - Certificados productos
  - Controles sanitarios
  - Auditorías calidad

-I+D
  - Inversion maquinaria
  - Investigacion productos
  
- Compras
  - Proveedores
    - Locales
    - Nacionales
    - UE
    - Extranjeros

-Ventas
  - Clientes
    - Supermercados
    - Minoristas

-Mantenimiento
 - Manual uso maquinaria
 - Fichas reparaciones

-Logística
 - Empresas transportistas
 - Protocolo de refrigeración

-Marketing
 - Campañas publicidad
 - Contratos

## Etiquetas
-Producto:crema verdura, gazpacho, salmorejo, tomate frito natural, pisto de verduras, ensalada, zumos natural, smoothie
-Lote:CV_30052026_001, GAZP_05062026_033, SALM_30052026_034,TFN_25062026_125, PV_14062026_002, ENS_20052026_021, ZN_NARJ_19052026_147, ZN_PIN_20052026_148, SMOTH_MIX_21052026
-Proveedor: local, nacional, europeo, extranjero
-Línea de producción: inspección visual, lavado, cortado, cocinado, en_proceso, en_reposo, envasado, distribucion
-Estado: natural, en_manipulacion, en_coccion, templado, frio
-Criticidad: alto, medio, bajo 
-Tipo documento: ficha de producto, informe, registro, protocolo, auditoría, documento, receta, etiqueta, incidencia, manual.

## Nomenclatura
-Ficha de producto: FP_CV_PLS_LOT_14568_20052026.PDF
-Informe de laboratorio: ILAB_14052026_LOT_14778_SEG_ALIMENTARIA.PDF
-Registro de lote:LOT_147_200520226_2544554754455.PDF
-Documento de proveedor: FACT_1245_14042026.PDF

## Plantilla metadatos
### Ficha producto
---
Codigo:ENS_MIX_22052026_1001
Nombre producto: ensalada mixta
Numero lote:1001
Fecha_fabricacion:12/03/2026
Fecha_caducidad: 22/05/2026
Ingredientes: lechuga, tomate, atun, aceitunas, cebolla, queso, zanahoria, huevo cocido, remolacha, maiz
Lugar envasado: Poligono Industrial Quinta, 02055, Sevilla
Proveedor: Huerta fresca S.L.
---

### Informes
---
Empresa auditada:AgriNova-Alimentos S.L
Empresa auditora: Auditoria Agroalimentaria 
Tipo documento: informe seguridad alimentaria
Estado documento:borrador
Area funcional: calidad y seguridad alimentaria
Auditor/a responsable: Trinidad Santos Montalbán
Hallazgos: no cumple con requisitos higienicos sanitarios
Plazo subsanacion: 12/07/2026
Fecha: 11/05/2026
---

### Registros
---
Codigo registro: RL_CV_11052026
Descripcion: lote crema de verduras
Fecha_envasado_lote: 11/05/2026
Fecha_caducidad_lote: 20/05/2026
Código_barras:587947 458789
Planta_etiquetado 7
---

## Flujo de trabajo
-Abrimos un issue para comunicar un error detectado en el control de calidad del producto--> técnico de calidad
-Creamos una nueva rama para localizar la ficha del producto y ver de qué producto se trata, numero de lote al que pertenece, fecha de compra, cantidad y proveedor--> técnico del área de calidad y seguridad alimentaria
-Localizado y revisado el proudcto creamos un pull request (una petición) para que se proceda a la retirada del producto--> responsable del área de calidad y seguridad alimentaria
-Se hace pública la retirada del producto--> operarios del área de calidad y seguridad alimentaria.
-Conservación de ficha de producto para solicitar descuentos en próximas compras.

## Ciclo de vida del documento






  
