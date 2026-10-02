# NOME DO SITE

Site de notícias simples, feito com HTML, com foco em informação, vida saudável e conhecimento.

Projeto desenvolvido para praticar HTML semântico e recursos avançados de marcação, mídia e formulários.

## Páginas

| Página | Arquivo | Descrição |
| --- | --- | --- |
| Home | `index.html` | Página inicial com as notícias em destaque. |
| Matéria | `materia.html` | Página de uma notícia completa. |
| Modalidade e tempo | `modalidade-tempo.html` | Previsão do tempo e sugestões de atividades físicas de acordo com o clima. |
| Podcast e vídeos | `podcast-videos.html` | Vídeo sobre os riscos da Inteligência Artificial, com dicas de proteção. |

## Recursos de HTML utilizados

**Marcação avançada**
- `abbr` para siglas, com o significado no atributo `title`.
- `mark` para destacar avisos importantes.
- `del` e `ins` para mostrar textos removidos e adicionados.
- `blockquote` e `cite` para citações e nomes de obras.
- `progress` para mostrar o andamento de uma tarefa.
- `meter` na previsão do tempo (umidade do ar e chance de chuva).

**Conteúdo interativo e mídia**
- `details` e `summary` para blocos que abrem e fecham com um clique.
- `figure` e `figcaption` para imagens e vídeos com legenda.
- `video` com `controls` para exibir um vídeo local.

**Formulário de feedback**
- `type="date"` para a data da visita.
- `type="range"` para a nota do site, de 0 a 10.
- `type="file"` para anexar um print da tela.
- `datalist` com sugestões das páginas do site.
- `required` nos campos obrigatórios.
- `placeholder` com exemplos de preenchimento.

## Estrutura de pastas

```
NOME-DO-REPOSITORIO/
├── index.html
├── materia.html
├── modalidade-tempo.html
├── podcast-videos.html
├── img/
├── videos/
│   └── riscos-ia.mp4
└── README.md
```

## Como abrir o projeto

1. Clone o repositório:
```bash
   git clone https://github.com/Dev-Jhonata-Batista/NOME-DO-REPOSITORIO.git
```
2. Entre na pasta do projeto.
3. Abra o arquivo `index.html` no navegador (dois cliques no arquivo já funcionam).

Não é preciso instalar nada.

## Tecnologias

- HTML5

## Observações

- O formulário de feedback ainda não salva os dados, porque o site não tem backend. Ele serve para praticar os recursos de formulário do HTML.
- O vídeo fica na pasta `videos/`. Se ele não for enviado junto com o projeto, a página de vídeos não vai conseguir reproduzi-lo.

## Autor

Feito por **Jhonata Batista**.

- GitHub: [Dev-Jhonata-Batista](https://github.com/Dev-Jhonata-Batista)