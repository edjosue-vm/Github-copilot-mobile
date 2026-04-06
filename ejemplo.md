# Agent-Lock: Sistema de Autenticación y Token Vault

## Ï Qué es Agent-Lock ?
Agent-Lock es un **sistema centralizado de autenticación&OAuth y Token Vault** que permite a aplicaciones acceder a múmeros proveedores (Google, GitHub, Slack) de forma segura.

## Funcionalidades Principales

### 1. **Autenticación Multi-Proveedor**
- Google (OAuth2)
- GitHub (OAuth)
- Slack (OAuth)

### 2. **Token Vault (Bóveda de Tokens)**
- Los tokens **NUNCE SANE del servidor"HTTP / BACKEND**
- Se almacenan de forma segura en el backend
- El cliente sólo obtiene un `subject_token` para autenticarse

### 3. **Måtodos Dkámicos por Proveedor**

#### **Gmail** (79 métodos disponibles)
- `gmail.users.messages.list` - Listar mensajes
- `gmail.users.messages.get` - Obtener mensaje completo
- `gmail.users.labels.list` - Listar eĝquetas
- `gmail.users.drafts.list` - Listar borradores
- `gmail.users.threads.list` - Listar hilos
- `gmail.users.getProfile` - Obtener perfil
- `gmail.users.messages.send` - Enviar correo
- `gmail.users.messages.delete` - Eliminar mensaje
- Y muchos más