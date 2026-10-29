# Palavras da Escritura

Jogo de palavras cruzadas bíblicas no estilo CodyCross, organizado por assunto e fase.

**Abrir o app:** https://eneas-ena.github.io/escritura/

## Como funciona

- App feito em página web; abre direto no navegador.
- Os dados ficam salvos no Supabase, por isso aparecem iguais em todos os aparelhos.
- Os serviços externos, como a inteligência artificial, passam pelo Worker `palavras-biblia` no Cloudflare; as chaves secretas ficam guardadas lá, nunca neste código.

## Observações

- `gerador.html` é a página que gera as fases.

## Como publicar uma nova versão

1. Nesta página do repositório, clique em **Add file → Upload files**.
2. Arraste os arquivos novos, com os mesmos nomes dos antigos.
3. Clique em **Commit changes**.

Em um ou dois minutos a nova versão está no ar no mesmo endereço.

---
Desenvolvido por Bispo Enéas Araújo.
