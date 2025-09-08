# 📋 Instruções para Personalização

## 🎯 Estrutura Criada

```
.github/
└─ profile/
   └─ README.md          # Perfil da organização no GitHub
assets/
└─ banner.svg            # Banner com gradiente roxo/preto (SVG)
.github/workflows/
├─ snake.yml             # Workflow para animação snake
└─ waka.yml              # Workflow para estatísticas WakaTime
README.md                # README principal do repositório
```

## 🔧 Próximos Passos

### 1. Converter Banner SVG para PNG
O arquivo `assets/banner.svg` precisa ser convertido para PNG:
- Use ferramentas online como [SVG to PNG Converter](https://convertio.co/svg-png/)
- Ou use ferramentas locais como Inkscape, GIMP, ou Adobe Illustrator
- Salve como `assets/banner.png` (1200x300px recomendado)

### 2. Configurar Secrets no GitHub
No repositório GitHub, vá em **Settings > Secrets and variables > Actions** e adicione:
- `WAKATIME_API_KEY`: [Sua chave WakaTime será fornecida separadamente]

### 3. Substituir Placeholders
Substitua todos os placeholders `{{...}}` nos arquivos:

#### Valores Sugeridos:
- `{{ORG_NAME}}` → **Fainow**
- `{{ORG_TAGLINE}}` → **Fast Applied Artificial Inteligence**
- `{{ORG_PITCH}}` → **Sem enrolação, Fazemos o básico bem feito, adoramos um problema**
- `{{PRIMARY_COLOR_HEX}}` → **#8B5CF6** (roxo)
- `{{ACCENT_COLOR_HEX}}` → **#000000** (preto)
- `{{WEBSITE_URL}}` → **https://about.agenciaorchestra.ai/**
- `{{EMAIL_CONTATO}}` → **fainowadm@gmail.com**
- `{{LINKEDIN_URL}}` → **www.linkedin.com/in/antônio-marberger-736a441b6**
- `{{TWITTER_URL}}` → **[URL do Twitter]**
- `{{ORG_USERNAME_FOR_WIDGETS}}` → **FainowAI** (ou usuário específico)
- `{{ORG_GITHUB_HANDLE}}` → **FainowAI**

### 4. Ativar Workflows
Os workflows serão executados automaticamente:
- **snake.yml**: Diariamente às 03:00 (gerar animação snake no branch `output`)
- **waka.yml**: Segundas-feiras às 03:15 (atualizar stats WakaTime semanal)

### 5. Personalizar Conteúdo
- Edite os links dos repositórios destacados
- Ajuste as tecnologias no tech stack
- Personalize as cores dos badges
- Adicione/remova seções conforme necessário

## 🎨 Cores da Marca
- **Primária**: #8B5CF6 (roxo)
- **Secundária**: #000000 (preto)
- **Gradiente**: Roxo → Preto (horizontal)

## 📱 Compatibilidade
- ✅ Tema claro/escuro do GitHub
- ✅ Responsivo para mobile
- ✅ SVGs com fundo transparente
- ✅ Emojis GitHub Flavored Markdown

## 🚀 Recursos Incluídos
- 📊 Estatísticas GitHub automáticas
- 🐍 Animação snake das contribuições
- ⏱️ Estatísticas WakaTime
- 🏆 Trophies e achievements
- 📈 Gráfico de atividade
- 💬 Quotes dinâmicas
- 🎯 Badges personalizáveis

---
*Estrutura criada com ❤️ para FainowAI*
