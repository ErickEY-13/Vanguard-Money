<div align="center">
  <a href="#about">
    <img src="assets/icon.png" width="120" height="120" alt="Vanguard Money logo" style="border-radius: 28px; box-shadow: 0 10px 30px rgba(17, 24, 39, 0.25);" />
  </a>
</div>

<div align="center">
  <a href="https://github.com/ErickEY-13/Vanguard-Money" target="_blank">
    <img src="assets/education.png" width="250" height="135" style="border-radius: 16px; box-shadow: 0 6px 25px rgba(0,0,0,0.22); margin: 0 10px;" alt="Vanguard Money overview" />
  </a>
  <a href="#features" target="_blank">
    <img src="assets/designs.png" width="250" height="135" style="border-radius: 16px; box-shadow: 0 6px 25px rgba(0,0,0,0.22); margin: 0 10px;" alt="Financial dashboard preview" />
  </a>
  <a href="#screenshots" target="_blank">
    <img src="assets/hackathons.png" width="250" height="135" style="border-radius: 16px; box-shadow: 0 6px 25px rgba(0,0,0,0.22); margin: 0 10px;" alt="Growth and AI insights preview" />
  </a>
  <br />
  <br />
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Outfit&size=36&duration=2500&pause=2000&color=3B82F6&center=true&width=700&height=60&lines=Vanguard+Money;Fintech+para+tu+dinero;Control,+ahorro+y+crecimiento" alt="Typing SVG" />
  </a>
</div>

<div align="center">
  <a href="#about">Acerca de</a> • <a href="#features">Solución</a> • <a href="#stack">Stack</a> • <a href="#setup">Instalación</a>
</div>

<br />

<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Riverpod](https://img.shields.io/badge/Riverpod-7C3AED?style=for-the-badge&logo=reactivestack&logoColor=white)
![Firestore](https://img.shields.io/badge/Firestore-FF8F00?style=for-the-badge&logo=firebase&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=apple&logoColor=white)

</div>

---

<a name="about"></a>

## 🚀 Acerca de Vanguard Money

Vanguard Money es una plataforma fintech móvil construida con Flutter para ayudar a personas y equipos a tomar decisiones financieras más inteligentes. La app centraliza operaciones clave como el control de ingresos y egresos, análisis de flujo de caja, planificación de presupuestos y generación de insights accionables para mejorar el ahorro y la salud financiera.

Nuestra misión es convertir la gestión del dinero en una experiencia simple, clara y estratégica para la toma de decisiones.

```dart
final vanguardMoney = {
  nombre: 'Vanguard Money',
  categoria: 'Fintech / Finanzas personales',
  plataformas: ['Android', 'iOS', 'Web'],
  stack: ['Flutter', 'Dart', 'Firebase', 'Riverpod'],
  objetivos: ['Ahorro', 'Presupuestos', 'Control financiero', 'IA'],
};
```

---

<a name="features"></a>

## ✨ Solución que construimos

### 📊 Inteligencia financiera
- Dashboard con visión general del balance.
- Seguimiento de ingresos, gastos y ahorro.
- Indicadores por periodo y tendencia de comportamiento.
- Reportes financieros diseñados para decisiones rápidas.

### 💸 Gestión de transacciones
- Registro de ingresos y egresos.
- Categorización por tipo de movimiento.
- Historial organizado y editable.
- Validaciones para un control más preciso del dinero.

### 🧠 Planes y presupuestos
- Presupuestos por categoría.
- Metas financieras y control de límites.
- Seguimiento de cumplimiento y alertas.
- Recomendaciones para optimizar el gasto.

### 🔐 Seguridad y perfil
- Autenticación con Firebase.
- Perfil personal con preferencias configurables.
- Persistencia confiable y experiencia enfocada en el usuario.
- Arquitectura preparada para crecimiento y escalabilidad.

### 🤖 IA y productividad
- Análisis inteligente de patrones de gasto.
- Recomendaciones financieras orientadas a mejores decisiones.
- Integración con experiencia asistida por IA para una mejor operación del producto.

---

<a name="stack"></a>

## 🛠️ Stack tecnológico

- Flutter + Dart
- Firebase Auth / Firestore / Storage / Core
- Riverpod para manejo de estado
- Go Router para navegación
- Provider y Shared Preferences
- Image Picker, File Picker, PDF y Printing
- Notificaciones, permisos y servicios del sistema
- Flutter SVG, Intl y utilidades de interfaz

---

<a name="setup"></a>

## 🚀 Instalación y ejecución

### 1) Clonar el repositorio

```bash
git clone https://github.com/ErickEY-13/Vanguard-Money.git
cd Vanguard-Money
```

### 2) Instalar dependencias

```bash
flutter pub get
```

### 3) Configurar Firebase

1. Crear un proyecto en Firebase.
2. Agregar `google-services.json` para Android.
3. Configurar la conexión con Firebase para Flutter.
4. Verificar permisos de autenticación, almacenamiento y base de datos.

### 4) Ejecutar la aplicación

```bash
flutter run
```

### 5) Ejecutar en un dispositivo específico

```bash
flutter devices
flutter run -d <device_id>
```

---

## 📁 Estructura del proyecto

```text
vanguardmoney/
├── android/
├── ios/
├── lib/
│   ├── app.dart
│   ├── main.dart
│   ├── core/
│   ├── features/
│   │   ├── auth/
│   │   ├── home/
│   │   ├── transactions/
│   │   ├── financial_plans/
│   │   ├── analysis/
│   │   ├── reports/
│   │   ├── notifications/
│   │   └── ...
│   └── firebase_options.dart
├── assets/
│   ├── icon.png
│   ├── education.png
│   ├── designs.png
│   └── hackathons.png
├── pubspec.yaml
├── README.md
├── firebase.json
├── analysis_options.yaml
└── .gitignore
```

---

## 📌 Estado del producto

Proyecto en desarrollo activo, orientado a convertirse en una solución financiera moderna para la gestión personal del dinero, con foco en claridad, automatización y productividad.

---

## 🤝 Contribución

Las contribuciones son bienvenidas. Si deseas colaborar, crea una rama, desarrolla tu mejora y abre un pull request.

```bash
git checkout -b feature/mejora-fintech
git commit -m "Añadir mejora financiera"
git push origin feature/mejora-fintech
```

---

<div align="center">
  <strong>Vanguard Money</strong><br />
  Más control. Mejor dinero. Mayor claridad.
</div>
