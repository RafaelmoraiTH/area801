# Assets e Recursos para o Área 801

Repositório centralizado para armazenamento de assets, CSS e JavaScript destinados ao uso no blog do Área 801 e outros projetos.

## 📁 Estrutura do Repositório

### 📂 Assets (Imagens WEBP)
Todas as imagens estão otimizadas no formato WEBP para melhor performance, servidas via CDN jsDelivr.

| Pasta | Conteúdo | Nomenclatura |
|-------|----------|-------------|
| **banner** | Barras de progresso do perfil | `[id].webp` |
| **emojis** | Emojis utilizados dentro do jogo | `[id].webp` |
| **esferas** | Esferas do Transformice | `[id].webp` (exceto Esferas de Iniciantes) |
| **flash** | Banners da Flash Squad | `[data].webp` |
| **inventario** | Itens do inventário | `[id].webp` |
| **loja** | Itens de eventos da loja | `[data].webp` |
| **mapas** | Mapas de eventos | `[nome do mapa/evento].webp` |
| **medalhas** | Medalhas do jogo | `[id].webp` |
| **modos** | Modos de jogo padrão | `[nome do modo].webp` |
| **modules** | Imagens de modos e módulos | `[nome do modo/module].webp` |
| **npcs** | NPCs no Transformice | `[nome do npc].webp` |
| **social** | Widget de redes sociais | `[rede social].webp` |
| **titulos** | Texto com todos os títulos | - |

### 📂 Script
Códigos JavaScript organizados por categoria de uso.

| Pasta | Tipo | Descrição |
|-------|------|-----------|
| **custom** | Atualizável | Scripts que recebem atualizações periódicas |
| `baus.js` | - | Funcionalidades específicas para baús |
| **vendor** | Estável | Scripts únicos que cumprem seu objetivo |
| `gameplay.js` | - | Funcionalidades relacionadas ao "Jogar Transformice" |
| `search.js` | - | Sistema de busca e filtragem do evento Maravilhas |

### 📂 Styles
Folhas de estilo CSS para diferentes páginas e funcionalidades.

| Arquivo | Destino |
|---------|---------|
| `baus.css` | Estilos para baús |
| `blog.css` | Estilos não utilizados do blog |
| `bouboum.css` | Estilos para o tutorial do Bouboum |
| `deadmaze.css` | Estilos para a dressroom do Dead Maze |
| `iframe.css` | Estilos para iframes específicos |
| `jogar.css` | Estilos para páginas com "Jogar" |
| `loja.css` | Estilos para loja |
| `main.css` | Estilos principais |
| `standalones.css` | Estilos para a página de standalones |
| `wonderland.css` | Estilos para o evento Maravilhas |

## 🚀 Como Usar

### Para Assets (Imagens)
```html
<!-- Exemplo usando jsDelivr CDN -->
<img src="https://cdn.jsdelivr.net/gh/rafaelmoraith/area801/assets/inventario/123.webp" />
```

### Para CSS
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/rafaelmoraith/area801@main/styles/main.css" />
```

### Para JavaScript
```html
<script src="https://cdn.jsdelivr.net/gh/rafaelmoraith/area801@main/script/vendor/search.js"></script>
```

## ⚡ Otimizações

• **Formato WEBP:** Todas as imagens convertidas para melhor compressão.\
• **CDN jsDelivr:** Entrega rápida através de rede global de conteúdo.\
• **Estrutura organizada:** Facilita manutenção e localização de arquivos.\
• **Categorização clara:** Separação lógica entre assets, scripts e styles.

## 📝 Notas de Manutenção

• Novos estilos CSS são criados apenas quando necessário.\
• Scripts na pasta `vendor` raramente precisam de atualizações.\
• Assets são adicionados conforme necessidade de novos conteúdos.\
• Sempre testar em ambiente de desenvolvimento antes de aplicar em produção.

**Criado por Rafaelmorai**
