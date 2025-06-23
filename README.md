# Presell Page - by WebArt3

Esta é uma página de presell (pré-venda) otimizada para campanhas de tráfego pago no Facebook, Instagram e outras plataformas.  
Ela simula um blog legítimo com tema escuro, imagens ilustrativas e integração com Pixel do Meta Ads, mantendo aparência confiável enquanto redireciona usuários reais para o destino correto.

## 🔥 Recursos principais

- Tema escuro com layout estilo blog
- Imagens ilustrativas automáticas via `picsum.photos`
- Caixa de cookies com overlay de blur
- Redirecionamento baseado no parâmetro `?web=` (Base64)
- Suporte a Pixel do Meta Ads dinâmico via parâmetro `?pxl=`
- Preservação automática dos parâmetros UTM no redirecionamento
- Redirecionamento forçado para HTTPS via `.htaccess`

## 🚀 Parâmetros de URL

| Parâmetro | Descrição |
|----------|-----------|
| `web`    | URL de destino (em base64) |
| `pxl`    | ID do Pixel do Meta Ads |
| `utm_*`  | Parâmetros de rastreio (preservados no redirecionamento) |

### Exemplo de uso

```
https://seudominio.com/?web=aHR0cHM6Ly93ZWJhcnQzLmNvbQ==&pxl=123456789&utm_source=facebook&utm_campaign=presell1
```

## 📁 Arquivos incluídos

- `index.html` — Página principal da presell
- `.htaccess` — Força uso de HTTPS
- `readme.md` — Este arquivo

## 🧠 Observações

- Certifique-se de ter SSL ativo no domínio para HTTPS funcionar corretamente.
- O botão "Aceitar e continuar" dispara o evento `Lead` no Pixel se presente.

## 🛠️ Requisitos

- Hospedagem com Apache e suporte a `.htaccess`
- Certificado SSL instalado (Let's Encrypt ou outro)

---

Criado por [WebArt3](https://webart3.com)