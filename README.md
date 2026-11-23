# Hilo Nativo — Votación del Catálogo de Prendas (Juego 1 · v8.0)

Aplicación web estática e interactiva para que los socios de **Hilo Nativo** (Cristian, John, Laura y Mileidy) evalúen los **31 ítems de prendas y accesorios** (cubriendo **5 pilares estéticos**: Urbano, Aesthetic Y2K, Deportivo, Casual-Formal y **Rockero / Alternativo**) propuestos para **"Vestidor de Impacto" (v8.0)**, dejen comentarios o propuestas nuevas y exporten directamente el *fixture* de datos compatible con Django (`python manage.py loaddata`).

## Flujo de Votación para Socios
1. Abre el enlace publicado en **GitHub Pages** desde tu celular o computador.
2. Selecciona tu nombre en la barra superior (`Cristian`, `John`, `Laura` o `Mileidy`).
3. Revisa las **6 láminas ilustradas** (vista de 5 estilos y las 5 categorías unificadas en español: Superiores, Inferiores, Chaquetas y Piezas, Calzado y Accesorios) y vota uno a uno los 31 ítems (`✅ Aprobar`, `✏️ Ajustar`, `❌ Descartar`) agregando notas si deseas cambios.
4. Si sugieres una prenda adicional o un ajuste general, escríbelo en la sección **"💡 Propuestas de nuevas prendas o comentarios generales"**.
5. Al finalizar, pulsa **`📦 Consolidar y Exportar mi Votación (.json)`** y sube el archivo descargado a la carpeta `Votacion_Prendas` en Google Drive.

## Consolidación y Paso a Django
En la sección **"⚙️ Integración a Django y Consenso del Equipo"**, carga los archivos JSON de los 4 socios usando **`📥 Importar / Consolidar Votos (.json)`** para visualizar la matriz de consenso y descargar **`garments_consensus_fixture.json`**.
