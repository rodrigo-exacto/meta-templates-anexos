# meta-templates-anexos

Acervo público de anexos usados nos **templates de mensagem da Meta (WhatsApp Business)**: cabeçalhos de imagem, documento e vídeo.

> ⚠️ **Repositório PÚBLICO.** Coloque aqui só material genérico (logos, banners, manuais, comunicados padrão).
> **Nunca** coloque boletos, dados de moradores, CPFs ou qualquer informação pessoal (LGPD).

## Estrutura

| Pasta         | Uso                              | Formatos aceitos pela Meta | Limite |
|---------------|----------------------------------|----------------------------|--------|
| `imagens/`    | Cabeçalho do tipo IMAGE          | JPG, PNG                   | 5 MB   |
| `documentos/` | Cabeçalho do tipo DOCUMENT       | PDF                        | 100 MB |
| `videos/`     | Cabeçalho do tipo VIDEO          | MP4 (H.264 + AAC)          | 16 MB  |

## Como usar o link no template

Use a URL do **GitHub Pages** (entrega o `Content-Type` correto, que a Meta exige):

```
https://rodrigo-exacto.github.io/meta-templates-anexos/<pasta>/<arquivo>
```

Exemplo: `https://rodrigo-exacto.github.io/meta-templates-anexos/imagens/logo-exacto.png`

Não use o link `github.com/.../blob/...` (é uma página HTML, não o arquivo).

## Convenções

- Nomes em minúsculas, sem acento nem espaço: `comunicado-assembleia-2026.pdf`
- Não sobrescreva um arquivo que já está em uso num template aprovado. Crie uma versão nova (`-v2`), porque a Meta pode ter feito cache do arquivo.
- Depois do push, o Pages leva cerca de 1 minuto para publicar.
