# AluraConversorMonedasChallenge
AluraConversorMonedasChallenge
# 💱 Conversor de Monedas - Alura Challenge

<p align="center">
  <img src="https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=java">
  <img src="https://img.shields.io/badge/Gson-Library-red?style=for-the-badge&logo=google">
  <img src="https://img.shields.io/badge/API-ExchangeRate-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Terminado-success?style=for-the-badge">
</p>

## 📄 Descripción

Este proyecto es una solución al **Challenge Conversor de Monedas** del programa **Oracle Next Education (ONE)**. 

El objetivo es crear una aplicación en Java que realice solicitudes a una API de tasas de cambio (ExchangeRate-API), manipule datos en formato **JSON** y filtre las monedas de interés para mostrar el resultado al usuario a través de la consola.

## ⚙️ Funcionalidades

La aplicación permite realizar conversiones en tiempo real entre las siguientes divisas (ejemplo):

1.  🇺🇸 **USD** (Dólar Estadounidense) ↔️ 🇦🇷 **ARS** (Peso Argentino)
2.  🇺🇸 **USD** (Dólar Estadounidense) ↔️ 🇧🇴 **BOB** (Boliviano boliviano)
3.  🇺🇸 **USD** (Dólar Estadounidense) ↔️ 🇧🇷 **BRL** (Real Brasileño)
4.  🇺🇸 **USD** (Dólar Estadounidense) ↔️ 🇨🇱 **CLP** (Peso Chileno)
5.  🇺🇸 **USD** (Dólar Estadounidense) ↔️ 🇨🇴 **COP** (Peso Colombiano)
6.  🇺🇸 **USD** (Dólar Estadounidense) ↔️ 🇲🇽 **MXN** (Peso Mexicano)

## 🛠️ Tecnologías Utilizadas

* **Java JDK 17**: Lenguaje principal.
* **HttpClient**: Clase nativa de Java (desde Java 11) para realizar peticiones HTTP.
* **Gson (Google)**: Librería para el parseo (deserialización) de los objetos JSON recibidos de la API.
* **ExchangeRate-API**: Servicio externo para obtener las tasas de cambio actualizadas.

## 🚀 Cómo ejecutar el proyecto

### Prerrequisitos
1.  Tener instalado **Java 17** o superior.
2.  Tener un IDE como IntelliJ IDEA, Eclipse o VS Code.
3.  Obtener una **API Key** gratuita desde [ExchangeRate-API](https://www.exchangerate-api.com/).

### Configuración
1.  Clona el repositorio:
    ```bash
    git clone [https://github.com/IBTLuisGomez/AluraConversorMonedasChallenge.git](https://github.com/IBTLuisGomez/AluraConversorMonedasChallenge.git)
    ```
2.  Abre el proyecto en tu IDE.
3.  Asegúrate de agregar la dependencia de **Gson** a tu proyecto (si usas Maven/Gradle se descargará sola, si no, debes agregar el `.jar` manualmente).

### Ejecución
Localiza la clase principal (usualmente `Principal.java` o `Main.java`) y ejecútala. Verás un menú en la consola como este:

```text
****************************************
Sea bienvenido/a al Conversor de Moneda =]

1) Dólar => Peso argentino
2) Peso argentino => Dólar
3) Dólar => Real brasileño
4) Real brasileño => Dólar
5) Dólar => Peso colombiano
6) Peso colombiano => Dólar
7) Salir

Elija una opción válida:
****************************************
