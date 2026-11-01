# React Products – Laboratorio Endpoint (Desarrollo Web 2)

> Reemplaza este archivo por el README.md descargado del Aula Virtual y completa tus datos.

## Datos del estudiante
- Nombre:
- Carnet:
- Asignatura: Desarrollo Web 2
- Tutor: Vladimir Mate

## Ejecución
```bash
npm install
npm run dev
```
Abrir http://localhost:5173/

## Endpoints utilizados (https://dummyjson.com/products)
| Operación | Método | Endpoint | Función |
|---|---|---|---|
| Obtener productos | GET | /products | getProducts() |
| Producto por ID | GET | /products/:id | getProductById() |
| Buscar | GET | /products/search?q= | searchProducts() |
| Categorías | GET | /products/categories | getCategories() |
| Por categoría | GET | /products/category/:category | getProductsByCategory() |
| Paginar | GET | /products?limit=&skip= | getProducts(limit, skip) |
| Crear | POST | /products/add | createProduct() |
| Actualizar | PUT | /products/:id | updateProduct() |
| Eliminar | DELETE | /products/:id | deleteProduct() |
