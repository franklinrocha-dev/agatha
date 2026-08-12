# Para Agatha Folls

Site romântico, moderno e responsivo dedicado a Agatha Folls.

## Requisitos

- Node.js 18+
- npm

## Instalação

```bash
npm install
```

## Execução em desenvolvimento

```bash
npm run dev -- --host
```

Acesse o projeto no navegador na porta 5173.

## Build de produção

```bash
npm run build
```

Para visualizar a versão de produção localmente:

```bash
npm run preview -- --host
```

## Personalização

Todos os textos, datas, horários, links e imagens principais estão centralizados em:

- `src/data/siteData.js`

### Onde substituir:

- Nome da Agatha: `agathaName`
- Data do primeiro contato: `firstContactDate`
- Hora do primeiro contato: `firstContactTime`
- Data do encontro: `meetingDate`
- Horário do encontro: `meetingTime`
- Nome do local: `locationName`
- Link do Google Maps: `googleMapsLink`
- Textos do site: `hero`, `about`, `story`, `letter`, etc.
- Lista de gostos: `interests`
- Fotos da Agatha: `agathaPhotos`
- Fotos do La Taipa: `laTaipaPhotos`

## Pastas de imagens

As imagens locais devem ser colocadas em:

- `public/images/`

Use imagens pessoais com autorização prévia antes de publicar. O projeto não deve coletar dados nem incluir rastreadores.

## Observação de privacidade

- Não inclua dados pessoais que não tenham sido fornecidos e autorizados.
- Não publique coordenadas pessoais ou informações privadas.
- Mantenha as fotos locais no projeto.
