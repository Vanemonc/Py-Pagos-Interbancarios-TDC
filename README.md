# 🏦 Banco de Venezuela - Aplicación Web

## 🚀 Inicio Rápido

### 📝 Credenciales de Acceso
```
Usuario: cliente1  | Contraseña: 1234  | Balance: Bs. 25,000.50
Usuario: cliente2  | Contraseña: 5678  | Balance: Bs. 42,000.80  
Usuario: cliente3  | Contraseña: 9012  | Balance: Bs. 8,900.25
```

### 🖥️ Cómo Ejecutar
1. Abrir `index.html` en cualquier navegador
2. Usar las credenciales de prueba
3. Explorar el dashboard bancario

## � Funcionalidades Principales

### ✅ **Sistema Unificado**
- **1 Cliente = 1 Cuenta = Máximo 1 Tarjeta**
- **Tipo único**: Tarjeta de Crédito Estándar
- **Moneda**: Bolívares Venezolanos (VES)
- **Prefijo de tarjetas**: 4532 (Banco de Venezuela)

### ✅ **Gestión de Cuentas**
- Consulta de saldo en tiempo real
- Historial de transacciones
- Tipos: Ahorros y Corriente

### ✅ **Tarjetas de Crédito Estándar**  
- Solicitud automatizada con validaciones
- Control de límites y crédito disponible
- Simulador de compras con tarjeta
- Sistema de pagos desde cuenta principal
- Estados: Activa, Pendiente, Bloqueada

### ✅ **Dashboard Interactivo**
- Interfaz responsive con Bootstrap 5
- Operaciones en tiempo real
- Notificaciones contextuales
- Animaciones fluidas

## 🔐 Credenciales de Prueba

| Usuario   | Contraseña | Cuenta | Tarjeta de Crédito |
|-----------|------------|--------|---------------------|
| cliente1  | 1234       | Ahorros (Bs. 25,000.50) | ✅ **Estándar** - Límite Bs. 20,000 |
| cliente2  | 5678       | Corriente (Bs. 42,000.80) | ✅ **Estándar** - Límite Bs. 50,000 |
| cliente3  | 9012       | Ahorros (Bs. 8,900.25) | ❌ Sin tarjeta (puede solicitar) |

> **Nota**: Todas las tarjetas son del mismo tipo **"Estándar"**, pero con límites de crédito personalizados según el perfil financiero del cliente.

## 📁 Estructura de Archivos

```
PRUEBA/
├── index.html          # Página de login
├── dashboard.html      # Panel principal del cliente
├── css/
│   └── styles.css      # Estilos CSS personalizados
└── js/
    ├── auth.js         # Sistema de autenticación y datos
    ├── app.js          # Lógica principal de la aplicación
    └── dashboard.js    # Funcionalidades del dashboard
```

## 🛠️ Instalación y Uso

### Opción 1: Uso Directo
1. Abre el archivo `index.html` en tu navegador web
2. Usa cualquiera de las credenciales de prueba para iniciar sesión
3. Explora todas las funcionalidades disponibles

### Opción 2: Servidor Local (Recomendado)
```bash
# Si tienes Python instalado:
cd PRUEBA
python -m http.server 8000

# Si tienes Node.js instalado:
cd PRUEBA
npx http-server

# Luego abre: http://localhost:8000
```

## 💡 Nuevas Funcionalidades del Sistema

### 🎯 Modelo de Negocio Simplificado
- **1 Cliente = 1 Cuenta Principal = Máximo 1 Tarjeta de Crédito**
- Sistema más realista y fácil de gestionar
- Relación directa entre cuenta y tarjeta

### 💳 Gestión Avanzada de Tarjeta
- **Simulador de compras**: Usa tu tarjeta para compras ficticias
- **Sistema de pagos**: Paga la deuda desde tu cuenta principal  
- **Control de límites**: Validación automática de crédito disponible
- **Historial detallado**: Todas las operaciones se registran

### 🔒 Validaciones de Seguridad
- Verificación de saldo mínimo para solicitud de tarjeta (10% del límite)
- Control de crédito disponible en compras
- Validación de fondos suficientes para pagos
- Prevención de sobreendeudamiento

### ⚡ Operaciones en Tiempo Real
- Los cambios se reflejan inmediatamente en el dashboard
- Cálculo automático de crédito disponible
- Actualización dinámica de saldos y límites

## 🎮 Casos de Uso Principales

### 👤 Para Cliente Nuevo (cliente3)
1. **Login** con credenciales
2. **Ver su cuenta** de ahorros con Bs. 8,900.25
3. **Solicitar tarjeta** de crédito (límite apropiado para su saldo)
4. **Esperar activación** (3 segundos simulados)
5. **Usar la tarjeta** para compras
6. **Pagar la deuda** desde su cuenta

### 💳 Para Cliente con Tarjeta (cliente1, cliente2)
1. **Ver tarjeta existente** con límites y deuda actual en bolívares
2. **Simular compras** y ver cómo afecta el crédito disponible
3. **Pagar deuda** y liberar crédito
4. **Monitorear historial** de todas las operaciones

## 🎯 Casos de Uso

### Para el Cliente
1. **Iniciar Sesión**: Acceder con credenciales válidas
2. **Consultar Saldos**: Ver el estado de todas sus cuentas
3. **Revisar Transacciones**: Historial detallado de movimientos
4. **Solicitar Tarjeta**: Proceso completo de solicitud de tarjeta de crédito
5. **Gestionar Tarjetas**: Ver límites, saldos utilizados y disponibles

### Para Desarrolladores
- Base sólida para sistema de pagos más complejo
- Estructura modular fácil de extender
- Código documentado y organizado
- Integración lista para APIs reales

## 🚀 Próximos Pasos (Para el Ecosistema Completo)

1. **APIs REST**: Crear servicios web para comunicación entre bancos
2. **Comercios**: Desarrollar terminales punto de venta
3. **Switch de Pagos**: Sistema de enrutamiento inteligente
4. **Base de Datos**: Migrar de localStorage a base de datos real
5. **Seguridad**: Implementar encriptación y certificados SSL

## 📝 Notas Importantes

- Este es un **sistema de demostración** con datos ficticios
- Las tarjetas generadas son **solo para pruebas**
- Los procesos bancarios están **simulados**
- Ideal para aprendizaje y desarrollo de prototipos

## 🤝 Contribuciones

Este proyecto es parte de un ecosistema de pagos electrónicos más amplio. Perfecto para:
- Estudiantes de ingeniería de software
- Proyectos académicos de sistemas distribuidos
- Prototipos de fintech
- Aprendizaje de metodologías ágiles (Scrum)

---

**Desarrollado para el proyecto de Ecosistema de Pagos Electrónicos**  
*Noviembre 2025*