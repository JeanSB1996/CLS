# CLS

Repositorio de documentos de **Cleantech - Atacama Salt Lakes SpA**. Contiene
facturas, certificados, contratos y otra documentación histórica. El archivo
`Libro7.xlsx` actúa como índice de todo el material.

## Requisitos

- Python 3.9 o superior
- Paquetes: `openpyxl`, `PyPDF2`

## Uso

Para actualizar el índice de documentos ejecuta:

```bash
python3 scripts/update_index.py
```

Por defecto el script busca los archivos dentro de la carpeta
`Cleantech - Atacama Salt Lakes SpA` y actualiza `Libro7.xlsx` añadiendo una
descripción breve de cada PDF. Puedes indicar otras rutas usando los argumentos
`--docs` y `--excel`.

## Git LFS

Los PDF e imágenes se gestionan con **Git LFS**. Para clonar correctamente el
repositorio instala LFS y ejecuta:

```bash
git lfs install
```

## Licencia

Los documentos son privados y se comparten sólo con fines administrativos. No
redistribuir sin autorización.
