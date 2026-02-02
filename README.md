
# Anamnese Numerológica — PWA (Instalável no iOS)

Este pacote contém o app PWA pronto para publicação no GitHub Pages e teste local no PC.

## Conteúdo
- pwa_index.html
- app.js
- styles.css
- manifest.webmanifest
- service-worker.js
- /pwa_icons
  - icon-192.png
  - icon-512.png
  - maskable-512.png
  - apple-touch-icon-180.png
- start-server.bat (Windows)
- start-server.sh (Mac/Linux)

## Como testar LOCALMENTE (PC)
> O Service Worker exige servidor local (não funciona via `file://`).

### Windows
1. Clique duas vezes em `start-server.bat`.
2. Abra http://localhost:8080/pwa_index.html no navegador.

### Mac/Linux
```bash
chmod +x start-server.sh
./start-server.sh
```
Abra http://localhost:8080/pwa_index.html

## Como publicar no GitHub Pages (PC)
1. Acesse https://github.com/new e crie o repositório público `anamnese-app`.
2. Entre no repositório → **Add file → Upload files** → Arraste TODO o conteúdo desta pasta.
3. Vá em **Settings → Pages**:
   - Source: `Deploy from a branch`
   - Branch: `main`  /  Folder: `/ (root)`  → **Save**
4. Aguarde 1–3 minutos. Seu app abrirá em:
   `https://SEU_USUARIO.github.io/anamnese-app/`

### Instalar no iPhone
1. Abra a URL no Safari do iPhone.
2. Toque em **Compartilhar → Adicionar à Tela de Início**.
3. Abra pelo ícone — funciona offline após a primeira visita.

## Ícones do App
Substitua os PNGs em `/pwa_icons` quando tiver seu logo final. Os nomes devem permanecer os mesmos.
