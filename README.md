# 📱 Social Media – Site Interativo de Redes Sociais

Este projeto apresenta suas redes sociais de forma **visual, moderna e interativa**, simulando a interface de um **smartphone real** dentro do navegador.  
O usuário pode navegar entre as telas usando **botões laterais**, que alteram o conteúdo exibido dentro de um *iframe* central.

## 🌐 Como acessar online
Você pode acessar a versão online do projeto diretamente pelo GitHub Pages:

👉 [Clique aqui para acessar o Social Media](https://rasyonheneyah.github.io/social-media/)

## 🚀 Funcionalidades
- Interface simulando um **iPhone**.
- Navegação entre redes sociais usando **botões circulares**.
- Exibição interna via **iframe**, carregando páginas como:
  - Home  
  - YouTube  
  - Instagram  
  - GitHub  
  - (Twitter e Facebook desativados como exemplo)
- Efeitos visuais de **hover**, sombras e transições.
- Layout responsivo e adaptado a telas maiores.

## 🧰 Tecnologias utilizadas
- **HTML5**
- **CSS3**
- **Iframe** para troca dinâmica de conteúdo
- Imagens customizadas para ícones das redes sociais

## 🖥️ Como funciona

O site usa um **iframe** central que funciona como a “tela” do celular:

```
<iframe name="tela" id="tela" src="tela-home.html"></iframe>
```
Os botões laterais mudam apenas o conteúdo do iframe, sem recarregar a página:
```
<a href="tela-instagram.html" class="botao" target="tela"></a>
```
Isso cria uma experiência fluida, como um mini-app navegável.
