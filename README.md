# Hotel Nieto — sitio web

Sitio web estático responsive para Hotel Nieto, Cartagena de Indias.

## Publicar con GitHub Pages
1. En GitHub abre **Settings → Pages**.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Elige la rama **main** y la carpeta **/(root)**, y guarda.
4. GitHub publicará el sitio en https://hnieto27.github.io/Hotel-Nieto/ (puede tardar unos minutos).

## Configuración obligatoria antes de recibir clientes
- En `index.html`, reemplaza `WHATSAPP_NUMBER='573000000000'` por el WhatsApp oficial con indicativo de país, solo números.
- Confirma dirección, servicios, políticas, impuestos, disponibilidad y tarifas oficiales antes de anunciar el hotel.
- El inventario mostrado es una propuesta conceptual de 100 habitaciones: 34 King Deluxe, 33 Queen Familiar y 33 Suite Nieto.
- Tarifas base ilustrativas: $450.000, $520.000 y $780.000 COP por habitación/noche. Deben ajustarse por temporada, impuestos, ocupación y estrategia comercial.

## Concierge
La interfaz incluye un concierge conversacional de demostración con respuestas guiadas y acceso a WhatsApp. **No es todavía un modelo de IA conectado**. Para convertirlo en concierge AI real 24/7, conectar un backend seguro (por ejemplo, una función serverless) con un proveedor de IA, cargar una base de conocimiento validada del hotel y proteger la clave API como secreto del servidor. Nunca insertar claves privadas en el JavaScript del navegador.

## Archivos
- `index.html`: sitio completo, estilos, reserva por WhatsApp y concierge de demostración.
