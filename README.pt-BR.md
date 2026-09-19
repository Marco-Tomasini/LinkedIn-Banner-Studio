# LinkedIn Banner Studio

<p align="left">
  <a href="README.md">English</a> •
  <b>Português</b>
</p>

---

Gerador visual de banners para LinkedIn, voltado a perfis de tecnologia. O projeto é uma página estática: preencha seus dados, escolha o modelo e exporte um PNG no tamanho recomendado para o LinkedIn (`1584 × 396 px`).

## Recursos

- Seis modelos de composição para o banner.
- Quatro estilos de cores prontos e uma paleta personalizada com fundo, destaques e texto configuráveis.
- Nome, cargo, instituição e tecnologias personalizáveis.
- Logos por upload ou URL para a instituição e cada tecnologia, com ajuste individual de `50%` a `300%` ao lado da prévia.
- Opção de selos com logos ampliadas.
- Guia opcional da área coberta pela foto de perfil do LinkedIn.
- Visualização em tela cheia com zoom, pinça, arrastar e ajuste à tela.
- Layout adaptado para celular e desktop.
- Exportação direta em PNG de `1×` a `5×` (até `7920 × 1980 px`).

## Como usar

1. Abra [index.html](index.html) em um navegador moderno.
2. Informe nome, subtítulo, instituição e tecnologias.
3. Escolha um estilo e um modelo.
4. Opcionalmente, envie logos ou informe URLs públicas de imagens.
5. Escolha a escala de exportação de `1×` a `5×` e clique em **Baixar PNG**.

`1×` gera o tamanho recomendado pelo LinkedIn (`1584 × 396 px`). Escalas maiores redesenham o banner em alta resolução; são úteis para guardar uma versão-mestre ou editar em outras ferramentas.

Para definir uma categoria própria para uma tecnologia, separe-a com `|`:

```text
PHP | Backend, JavaScript | Frontend, SQL | Banco de dados
```

## Tela cheia no celular

Em modo tela cheia, o banner abre ampliado em aparelhos na vertical para facilitar a leitura. Use os botões `−` e `+`, o gesto de pinça e o arrastar para navegar. O botão **Ajustar** volta a mostrar o banner completo.

## Tecnologias

- HTML, CSS e JavaScript puros.
- [Tailwind CSS](https://tailwindcss.com/) via CDN.
- [Font Awesome](https://fontawesome.com/) e Google Fonts via CDN.

Não é necessário instalar pacotes nem executar um servidor para usar o projeto.

## Publicação no GitHub Pages

O arquivo de entrada do projeto é o `index.html`, portanto ele é reconhecido automaticamente pelo GitHub Pages.

O repositório já possui um workflow em [`.github/workflows/static.yml`](.github/workflows/static.yml): após um `push` na branch `main`, ele publica a versão atualizada pelo GitHub Actions.

O projeto está publicado em:

[https://marco-tomasini.github.io/LinkedIn-Banner-Studio/](https://marco-tomasini.github.io/LinkedIn-Banner-Studio/)

Para novas cópias do projeto, acesse **Settings → Pages** no repositório e selecione **GitHub Actions** como fonte de implantação. Após o workflow concluir, a publicação ficará disponível na URL correspondente ao usuário e repositório.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## Créditos

- Base inicial do projeto: [Isabela de Oliveira](https://github.com/isabela728).
- Evoluções, funcionalidades e aprimoramentos posteriores: [Marco Tomasini](https://github.com/marco-tomasini).
