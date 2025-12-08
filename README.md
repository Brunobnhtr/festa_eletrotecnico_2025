# Confraternização SENAI — Eletrotécnica 2025

Site da confraternização da turma de Eletrotécnica 2025 do SENAI, com efeitos 3D de rolagem.

## 📱 Testando no Celular

### Opção 1: Usar um servidor local (recomendado)

1. **Instale Python** (caso não tenha):
   - Windows: Baixe em [python.org](https://www.python.org)

2. **Abra o terminal na pasta do projeto** e execute:
   ```bash
   python -m http.server 8000
   ```

3. **Encontre seu IP local** (abra PowerShell e execute):
   ```bash
   ipconfig
   ```
   Procure por "IPv4 Address" (exemplo: 192.168.x.x)

4. **No celular**, abra o navegador e acesse:
   ```
   http://192.168.x.x:8000/festa_novo.html
   ```

### Opção 2: Usar ngrok (acesso remoto)

1. **Baixe ngrok**: [ngrok.com](https://ngrok.com)

2. **Com o servidor rodando**, em outro terminal:
   ```bash
   ngrok http 8000
   ```

3. **Copie a URL gerada** (exemplo: https://abc123.ngrok.io) e acesse no celular

### Opção 3: Usar GitHub Pages (deploy automático)

Após fazer push para o GitHub, ative GitHub Pages nas configurações do repositório.

## 🚀 Subir para GitHub

### 1. Crie um repositório no GitHub

- Acesse [github.com/new](https://github.com/new)
- Nome: `festa-senai` (ou outro nome)
- Descrição: "Confraternização SENAI Eletrotécnica 2025"
- Deixe Public
- Clique em "Create repository"

### 2. Adicione o repositório remoto e faça push

```bash
git remote add origin https://github.com/SEU_USUARIO/festa-senai.git
git branch -M main
git push -u origin main
```

### 3. Ative GitHub Pages

- Vá em: Settings → Pages
- Source: Deploy from a branch
- Branch: main / (root)
- Save

Seu site estará disponível em: `https://seu_usuario.github.io/festa-senai/`

## 📁 Estrutura

- `festa_novo.html` - Nova versão com efeitos 3D de rolagem
- `festa.html` - Versão anterior
- `Turma.jpeg` - Foto da turma
- `README.md` - Este arquivo

## ✨ Características

- ✅ Efeitos 3D parallax
- ✅ Design responsivo
- ✅ Animações suaves
- ✅ Formulário de participantes
- ✅ Sistema de pagamento via PIX
- ✅ Dark mode com gradientes

---

**Desenvolvido com ❤️ para a turma de Eletrotécnica 2025**
