# Dra. Wlamar Alves | Nutricionista

Site de página única da Dra. Wlamar Alves, nutricionista em Salto, SP e online.
HTML, CSS e JavaScript puros, sem build. Os botões de agendamento abrem o WhatsApp (11) 97096-3665.

## Estrutura

```
index.html                página completa (estilos e scripts dentro do arquivo)
img/wlamar.jpg            foto principal
img/apple-touch-icon.png  ícone ao salvar na tela do celular
vercel.json               configuração da Vercel (URLs limpas)
```

## Publicar

1. GitHub: crie um repositório, clique em Add file > Upload files e ARRASTE a pasta `img` junto com os arquivos (o botão de escolher arquivos não envia pastas). Commit changes.
2. Vercel: Add New > Project > importe o repositório. Framework Preset "Other", sem build. Nome do projeto: `wlamar-alves`.
3. Deploy. Cada novo commit publica a atualização sozinho.

Se usar outro nome de projeto na Vercel, troque `wlamar-alves.vercel.app` nas linhas `og:image`, `og:url` e `canonical` do `index.html`.

## Imagens

Ao trocar uma imagem mantendo o mesmo nome, aumente o `?v=1` nos links do `index.html` (ex.: `?v=2`).

## Editar conteúdo

- WhatsApp: variável `numero` no fim do `index.html` e os links `wa.me`.
- Mensagem automática: atributo `data-wa` dos botões.
- Cores: variáveis no início do `<style>` (`--cacau`, `--mocha`, `--caramelo`, `--rose`, `--champanhe`).
