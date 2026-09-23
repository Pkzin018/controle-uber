# Controle Uber

Dashboard financeiro e operacional para motorista de aplicativo.

## O que o sistema acompanha

- faturamento bruto e lucro líquido;
- combustível, manutenção e depreciação;
- custo por km, R$/km e R$/hora;
- lançamentos e histórico;
- turnos ativos;
- abastecimentos e consumo real;
- despesas extras;
- metas e desempenho por período;
- visão anual e valor destinado ao patrimônio;
- backup/importação dos dados.

## Rodar online

A versão estática funciona no GitHub Pages usando o armazenamento local do navegador.
Os dados ficam somente no dispositivo/navegador em que o app for usado.

## Rodar localmente com servidor

É necessário Python 3.

### Windows

Dê dois cliques em `INICIAR.bat`.

### Linux/macOS

```bash
chmod +x INICIAR.sh
./INICIAR.sh
```

Depois abra `http://localhost:8080`.

O modo servidor habilita os recursos locais de conta, SQLite e sincronização entre dispositivos conectados ao mesmo servidor.

## Privacidade

Arquivos de banco, backups e variáveis de ambiente estão ignorados pelo Git e não devem ser publicados no repositório.

## Versão

V7.1 — refinamento visual do dashboard e gráficos.
