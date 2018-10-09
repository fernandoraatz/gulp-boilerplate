# Gulp

Estrutura de automatização com Gulp.   

---

## Descrição

- Concatena e minifica arquivos javascript e sass/css.  
- Testa o código javascript.  
- Corrige problemas de NodeStream do Gulp.   
- Insere automaticamente vendor prefixes.  
- Gera mapeamento de Sass para o navegador.  
- Gera um servidor com LiveReload.

## Pré Requisitos

Ter instalado node e o gulp

Instalar os módulos

```css
npm install --global gulp-cli
```

## Procedimentos

Instalar os módulos

```css
sudo npm install
```

Rodar as tarefas com watch e o servidor:

```css
gulp
```

Rodar as tarefas sem o servidor:

```css
gulp watch
```

Servidor fica disponível na porta 8080:

```css
localhost:8080
```

---

## Estrutura Básica

Estrutura básica de pastas e arquivos:

- *gulpfile.js*
- *package.json*


## Javascript

Estrutura básica em Javascript

### Descrição

- Cria um objeto App com 3 objetos principais
- Core, component e controller
- Separando por módulos

---
