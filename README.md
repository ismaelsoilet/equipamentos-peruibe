# Equipamentos Públicos – Peruíbe/SP

Site estático com lista de equipamentos públicos de Saúde e Educação do município de Peruíbe/SP.

## Deploy no Vercel

### Opção 1 – Via CLI
```bash
npm i -g vercel
cd equipamentos-peruibe
vercel --prod
```

### Opção 2 – Via GitHub
1. Faça push deste repositório para o GitHub
2. Acesse [vercel.com/new](https://vercel.com/new)
3. Importe o repositório
4. Clique em **Deploy** (sem nenhuma configuração extra necessária)

## Estrutura
```
equipamentos-peruibe/
├── index.html      # App completo (single-file)
├── vercel.json     # Configuração Vercel
└── README.md       # Este arquivo
```

## Funcionalidades
- 🏥 **38 equipamentos de Saúde** (USAFA, UPA, SAMU, CAPS, AME…)
- 🏫 **41 equipamentos de Educação** (EMEI, EMEF, EMEIF)
- 🔍 Busca em tempo real por nome, endereço ou tipo
- 🎛️ Filtros rápidos por categoria/tipo
- 🗺️ Botão "Ir até lá" com link direto para Google Maps (coordenadas geográficas exatas)
- 📱 Design mobile-first, responsivo

## Tecnologia
Single-page HTML estático — sem dependências externas, sem servidor, sem build step.
