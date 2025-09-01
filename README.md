# 🚀 Template de Portfólio Digital

Um template moderno e responsivo para portfólio de produtos digitais, desenvolvido com HTML, CSS e JavaScript puro.

## ✨ Características

- **Design Moderno**: Interface limpa e profissional com gradientes e animações
- **Totalmente Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- **Animações Suaves**: Efeitos de entrada e transições fluidas
- **Menu Mobile**: Navegação hamburger para dispositivos móveis
- **Filtros de Portfólio**: Sistema de filtros para organizar projetos
- **Formulário de Contato**: Formulário funcional com validação
- **SEO Otimizado**: Estrutura semântica e meta tags
- **Performance**: Código otimizado e carregamento rápido

## 📁 Estrutura do Projeto

```
portfolio-digital/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # Funcionalidades JavaScript
└── README.md           # Este arquivo
```

## 🎨 Seções Incluídas

1. **Header/Navegação**: Menu fixo com links suaves
2. **Hero Section**: Apresentação principal com call-to-action
3. **Sobre**: Informações pessoais e habilidades
4. **Serviços**: Cards com serviços oferecidos
5. **Portfólio**: Galeria de projetos com filtros
6. **Contato**: Formulário e informações de contato
7. **Footer**: Links e informações adicionais

## 🚀 Como Usar

### 1. Download e Setup
```bash
# Clone ou baixe os arquivos
# Abra o index.html em seu navegador
```

### 2. Personalização Básica

#### Informações Pessoais
Edite o arquivo `index.html` e altere:

```html
<!-- Seu nome -->
<h4>Seu Nome</h4>

<!-- Email de contato -->
<p>seu@email.com</p>

<!-- Telefone -->
<p>+55 (11) 99999-9999</p>

<!-- Localização -->
<p>São Paulo, SP - Brasil</p>
```

#### Redes Sociais
Atualize os links das redes sociais:

```html
<div class="social-links">
    <a href="https://linkedin.com/in/seu-perfil" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="https://github.com/seu-usuario" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <!-- Adicione mais redes conforme necessário -->
</div>
```

### 3. Personalização Avançada

#### Cores e Gradientes
No arquivo `styles.css`, você pode alterar as cores principais:

```css
/* Gradiente principal */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Gradiente secundário */
background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
```

#### Adicionar Projetos ao Portfólio
Para adicionar novos projetos, copie este bloco no `index.html`:

```html
<div class="portfolio-item" data-category="web">
    <div class="portfolio-image">
        <img src="caminho/para/sua/imagem.jpg" alt="Nome do Projeto">
        <div class="portfolio-overlay">
            <div class="portfolio-info">
                <h3>Nome do Projeto</h3>
                <p>Descrição do projeto</p>
                <div class="portfolio-links">
                    <a href="link-do-projeto" class="portfolio-link">
                        <i class="fas fa-external-link-alt"></i>
                    </a>
                    <a href="link-do-codigo" class="portfolio-link">
                        <i class="fas fa-github"></i>
                    </a>
                </div>
            </div>
        </div>
    </div>
</div>
```

#### Categorias de Projetos
As categorias disponíveis são:
- `web` - Projetos web
- `mobile` - Aplicativos mobile
- `design` - Design/UI/UX

#### Adicionar Habilidades
Para adicionar ou modificar habilidades na seção "Sobre":

```html
<div class="skill-item">
    <span class="skill-name">Sua Habilidade</span>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 85%"></div>
    </div>
</div>
```

### 4. Configuração do Formulário de Contato

O formulário atual simula o envio. Para torná-lo funcional, você pode:

#### Usar EmailJS
1. Cadastre-se em [EmailJS](https://www.emailjs.com/)
2. Configure um template de email
3. Adicione o script do EmailJS ao HTML
4. Modifique o JavaScript para usar EmailJS

#### Usar Netlify Forms
1. Faça deploy no Netlify
2. Adicione `netlify` ao formulário:
```html
<form id="contactForm" netlify>
```

#### Usar PHP (se tiver servidor)
Crie um arquivo `process.php` e configure o formulário para enviar para ele.

## 🎯 Funcionalidades JavaScript

### Menu Mobile
- Toggle do menu hamburger
- Fechamento automático ao clicar em links

### Filtros de Portfólio
- Filtros por categoria (Web, Mobile, Design)
- Animações suaves de transição

### Animações
- Scroll reveal para elementos
- Barras de progresso animadas
- Efeito parallax no hero
- Efeito de digitação no título

### Formulário
- Validação de campos
- Sistema de notificações
- Reset automático após envio

## 📱 Responsividade

O template é totalmente responsivo e inclui:

- **Desktop**: Layout completo com grid de 2 colunas
- **Tablet**: Layout adaptado para telas médias
- **Mobile**: Menu hamburger e layout em coluna única

## 🎨 Personalização de Cores

### Paleta de Cores Atual
- **Primária**: #667eea (Azul)
- **Secundária**: #764ba2 (Roxo)
- **Acento**: #f093fb (Rosa)
- **Texto**: #333 (Cinza escuro)
- **Fundo**: #f8f9fa (Cinza claro)

### Como Alterar Cores
1. Abra `styles.css`
2. Use Ctrl+F para encontrar as cores
3. Substitua pelos valores desejados
4. Mantenha a consistência em todo o design

## 🚀 Deploy

### GitHub Pages
1. Faça upload dos arquivos para um repositório GitHub
2. Vá em Settings > Pages
3. Selecione a branch main
4. Seu site estará disponível em `https://seu-usuario.github.io/seu-repositorio`

### Netlify
1. Acesse [Netlify](https://netlify.com)
2. Arraste a pasta do projeto
3. Seu site será publicado automaticamente

### Vercel
1. Acesse [Vercel](https://vercel.com)
2. Conecte seu repositório GitHub
3. Deploy automático a cada push

## 🔧 Otimizações Recomendadas

### Performance
- Comprima imagens antes de usar
- Use formatos modernos (WebP, AVIF)
- Considere lazy loading para imagens

### SEO
- Adicione meta tags específicas
- Configure Open Graph
- Adicione schema markup

### Acessibilidade
- Teste com leitores de tela
- Verifique contraste de cores
- Adicione alt text em imagens

## 📞 Suporte

Para dúvidas ou sugestões:
- Abra uma issue no GitHub
- Entre em contato através do formulário do site

## 📄 Licença

Este template é livre para uso pessoal e comercial. Atribuição é apreciada mas não obrigatória.

---

**Desenvolvido com ❤️ para a comunidade de desenvolvedores**
