# 🌍 WorldWise – Travel Map Notes

Aplicativo React para registrar e explorar os lugares que você já visitou. Desenvolvido no *Ultimate React Course* com Jonas Schmedtmann, incorpora conceitos como React Router, Context API, e mapas interativos com **Leaflet**.

---

## 🚀 Tecnologias

- React + JavaScript (ou TypeScript)
- React Router (navegação SPA)
- Context API para estado global (usuário, locais, filtros)
- Leaflet.js para renderização de mapas
- json-server para simular backend com dados de locais

---

## 🎯 Funcionalidades

- Marcar locais visitados via clique no mapa
- CRUD de pins: criar, editar descrições, remover
- Listar locais visitados com filtro por cidade ou país
- Visualização com rotas SPA e navegação intuitiva
- Estado compartilhado gerenciado por Context API

---

## 🛠️ Instalação & Execução

Clone o repositório:

```bash
git clone https://github.com/GuilhermeSouza01/world-wise.git
cd world-wise
```
Instale dependências:
```bash
npm install
# ou
yarn install
```
Inicie o servidor mock JSON:
```bash
npm run server
```
Em outro terminal, execute a aplicação React:
```bash
npm run dev
```
Acesse http://localhost:3000 no navegador.
