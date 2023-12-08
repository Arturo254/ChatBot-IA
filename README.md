# Chat Bot IA 
#### by Arturo Cervantes 
## Noticias

¡Chatbot UI 2.0 ya está disponible Completamente gratis!

[![Mi botón](https://img.shields.io/badge/Chat-brightgreen)](https://chat-bot-ia.vercel.app/es)

# El proyecto es completamente Open Source

[![Mi botón](https://img.shields.io/badge/GitLab-grey?style=for-the-badge&logo=gitlab)](https://gitlab.com/artuscervantes111/ChatBot-UI)


![logo](https://github.com/Arturo254/chat-bot-web-page/assets/87346871/bd6696cc-459b-43e9-94be-1c8b7af7223a)

## Acerca de

Chatbot UI es una interfaz de usuario de chat de código abierto para modelos de IA.

## Actualizaciones

La interfaz de usuario del Chatbot se actualizará con el tiempo.

Espere mejoras frecuentes.

**Siguiente:**

- [ ] Compartir
- [ ] "Bots"

## Desplegar
*No disponible por el momento*



## Ejecutando localmente

**1. Clonar repositorio**

```bash
git clone  https://github.com/mckaywrigley/chatbot-ui.git
```

**2. Instalar dependencias**

```bash
npm install
```

**3. Proporcionar clave API de OpenAI**

Cree un archivo .env.local en la raíz del repositorio con su clave API de OpenAI:

```bash
OPENAI_API_KEY=TU_LLAVE
```

> Puede configurar `OPENAI_API_HOST` donde el acceso al host oficial de OpenAI esté restringido o no esté disponible, lo que permite a los usuarios configurar un host alternativo para sus necesidades específicas.

> Además, si tiene varias organizaciones OpenAI, puede configurar `OPENAI_ORGANIZATION` para especificar una.

**4. Ejecutar aplicación**

```bash
npm ejecutar dev
```

**5. Úsalo**

Deberías poder empezar a chatear.

## Configuración

Al implementar la aplicación, se pueden configurar las siguientes variables de entorno:

| Environment Variable              | Default value                  | Description                                                                                                                               |
| --------------------------------- | ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------- |
| OPENAI_API_KEY                    |                                | The default API key used for authentication with OpenAI                                                                                   |
| OPENAI_API_HOST                   | `https://api.openai.com`       | The base url, for Azure use `https://<endpoint>.openai.azure.com`                                                                         |
| OPENAI_API_TYPE                   | `openai`                       | The API type, options are `openai` or `azure`                                                                                             |
| OPENAI_API_VERSION                | `2023-03-15-preview`           | Only applicable for Azure OpenAI                                                                                                          |
| AZURE_DEPLOYMENT_ID               |                                | Needed when Azure OpenAI, Ref [Azure OpenAI API](https://learn.microsoft.com/zh-cn/azure/cognitive-services/openai/reference#completions) |
| OPENAI_ORGANIZATION               |                                | Your OpenAI organization ID                                                                                                               |
| DEFAULT_MODEL                     | `gpt-3.5-turbo`                | The default model to use on new conversations, for Azure use `gpt-35-turbo`                                                               |
| NEXT_PUBLIC_DEFAULT_SYSTEM_PROMPT | [see here](utils/app/const.ts) | The default system prompt to use on new conversations                                                                                     |
| NEXT_PUBLIC_DEFAULT_TEMPERATURE   | 1                              | The default temperature to use on new conversations                                                                                       |
| GOOGLE_API_KEY                    |                                | See [Custom Search JSON API documentation][GCSE]                                                                                          |
| GOOGLE_CSE_ID                     |                                | See [Custom Search JSON API documentation][GCSE]                                                                                          |
Si no Tiene  una clave API de OpenAI con `OPENAI_API_KEY`, los usuarios deberán proporcionar su propia clave.

Si no tiene una clave API de OpenAI, puede obtener una [aquí](https://platform.openai.com/account/api-keys).
