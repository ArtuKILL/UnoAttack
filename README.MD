# Proyecto Uno Attack

- [Proyecto Uno Attack](#proyecto-uno-attack)
  - [Para Iniciar el Proyecto](#para-iniciar-el-proyecto)
    - [**Dependencias**](#dependencias)
    - [**Setup**](#setup)
    - [En caso de no tener Visual Studio](#en-caso-de-no-tener-visual-studio)
    - [**Verificar que todo vaya bien**](#verificar-que-todo-vaya-bien)
  - [Lista de Recursos](#lista-de-recursos)

## Para Iniciar el Proyecto
  
### **Dependencias**

- **node**, comprobar con:

  ```bash
  ❯ node -v
  v14.10.0
  ```

  [Descarga Node ⬇](https://nodejs.org/es/)
  
- **npm**, comprobar con:
  
  ```bash
  ❯ npm -v
  6.14.8
  ```

  Si tienes node instalado lo más probable es que tambien tengas [npm](https://www.npmjs.com/).

### **Setup**

Luego de tener las dependencias clona el repositorio, después ejecutar el comando `npm install` para que instale localmente las dependencias del `package.json`.

```bash
npm install
```

> **⚠ Advertencia**  
> Si no tienes Visual Studio instalado el modulo `serialport` va a fallar en la instalación.

### En caso de no tener Visual Studio  

Si no tienes Visual Studio y no lo quieres descargar puedes descargarte las herramientas de desarrollo de windows. No sé por que pero `serialport` usa algunas dependencias que tiene Visual Studio.  

**Ejecutar** el siguiente comando para instalar las herramientas de desarrollo de windows:  

```bash
npm install --g --production windows-build-tools
```

### **Verificar que todo vaya bien**

Luego de hacer los pasos anteriores tratra de correr el programa usando  

```bash
npm start
```

Y deberias ver algo parecido a esto:

![Imagen de la vista](https://i.imgur.com/KlJ2uNe.png)

## Lista de Recursos  

- [NODE.JS](https://nodejs.org/es/)
- [NPM](https://www.npmjs.com/)
- [ELECTRON.JS](https://www.electronjs.org/docs/tutorial/quick-start)
- [SERIALPORT](https://serialport.io/)
