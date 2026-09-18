# LinkedIn Banner Studio

Gerador visual de banners para LinkedIn, voltado a perfis de tecnologia. O projeto é uma página estática: preencha seus dados, escolha o modelo e exporte um PNG no tamanho recomendado para o LinkedIn (`1584 × 396 px`).

## Recursos

- Seis modelos de composição para o banner.
- Quatro estilos de cores.
- Nome, cargo, instituição e tecnologias personalizáveis.
- Logos por upload ou URL para a instituição e cada tecnologia.
- Opção de selos com logos ampliadas.
- Guia opcional da área coberta pela foto de perfil do LinkedIn.
- Visualização em tela cheia com zoom, pinça, arrastar e ajuste à tela.
- Layout adaptado para celular e desktop.
- Exportação direta em PNG.

## Como usar

1. Abra [gerador_de_banner_linkedin.html](gerador_de_banner_linkedin.html) em um navegador moderno.
2. Informe nome, subtítulo, instituição e tecnologias.
3. Escolha um estilo e um modelo.
4. Opcionalmente, envie logos ou informe URLs públicas de imagens.
5. Confira a prévia e clique em **Baixar Imagem PNG (1584x396)**.

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

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## Créditos

- Base inicial do projeto: **Isabela de Oliveira** (`Isabela_oliveira3@estudante.sesisenai.org.br`).
- Evoluções, funcionalidades e aprimoramentos posteriores: mantenedor(a) atual do repositório.
