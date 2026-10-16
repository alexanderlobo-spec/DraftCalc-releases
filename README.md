<p align="center"><img src="logo.png" width="160" alt="DraftCalc"></p>

# DraftCalc — downloads

*[English version](README.en.md)*

DraftCalc é uma planilha de cálculo para macOS e Windows, feito como hobby.
**É gratuito e não aceita pagamento de nenhum tipo**: sem venda, assinatura, anúncios ou doações.
Não é uma oferta comercial e não está em nenhuma loja.

Baseado no [GridCraft](https://github.com/storytold/gridcraft) (MIT OR Apache-2.0), com interface,
ícones e temas próprios. Os avisos de licença e as atribuições vão dentro de cada pacote.

## Downloads

| Sistema | Arquivo | Observações |
|---|---|---|
| macOS 11+ (Intel e Apple Silicon) | [`macOS/`](macOS/) — `.dmg` universal | Assinado com Developer ID e notarizado pela Apple: abre sem avisos. Arraste o DraftCalc para Aplicativos. |
| Windows 10/11 (x64) | [`windows/`](windows/) — `.msi` ou `.zip` portátil | Sem certificado de assinatura: na primeira abertura o SmartScreen pode avisar; escolha "Mais informações › Executar assim mesmo". |

Cada arquivo tem um `.sha256` ao lado para conferência.

## Como instalar

### macOS

1. Entre na pasta [`macOS/`](macOS/), clique no arquivo `.dmg` e depois no botão **Download**.
2. Abra o arquivo baixado. Aparece uma janela com o ícone do DraftCalc e a pasta Aplicativos.
3. Arraste o DraftCalc para Aplicativos.
4. Abra o DraftCalc pelo Launchpad ou pela pasta Aplicativos. Não há aviso: o app é notarizado pela Apple.
5. Pode ejetar o disco "DraftCalc" e apagar o `.dmg`.

### Windows

1. Entre na pasta [`windows/`](windows/), clique no arquivo `.msi` e depois no botão **Download**.
2. Se o download não aparecer, olhe a lista de downloads do navegador: o Edge costuma bloquear o `.msi` por não ter certificado pago. Clique nos três pontos ao lado do arquivo e escolha **Manter**. No Chrome o download costuma passar direto.
3. Dê dois cliques no arquivo baixado.
4. Se aparecer a tela azul "O Windows protegeu o computador", clique em **Mais informações** e depois em **Executar assim mesmo**. O botão só aparece depois de "Mais informações". É o SmartScreen avisando que o app não tem certificado pago; acontece só na primeira vez.
5. Siga o instalador: aceitar a licença, Instalar, Concluir. Ele pode pedir a senha de administrador.
6. O DraftCalc fica no menu Iniciar.

**Sem permissão para instalar programas?** Baixe o `.zip` portátil, descompacte numa pasta sua (Documentos, por exemplo) e abra o `DraftCalc.exe` de dentro dela. Nada é instalado.

### Atualizar

Baixe o arquivo da versão nova e instale por cima. As planilhas ficam onde você salvou; a instalação não mexe neles.

## Versão atual

0.7.0-draftcalc.2 (15/out/2026).

Novidades: faixa completa com a mesma identidade visual do DraftWord (121 ícones da família Manzana Line, cabeçalho, menus e diálogos redesenhados); menus, diálogos, menu nativo do macOS e ajuda de 514 funções em português; revisão visual dos diálogos no claro e no escuro; correção de menus que ficavam abertos sobre o diálogo. A versão anterior (draftcalc.1) trouxe a interface Manzana nas três aparências, três idiomas, salvamento automático e recuperação, botão Fechar e suporte a `.xlsx`, `.csv` e `.tsv`.

## Código-fonte

O código do DraftCalc fica em um repositório privado. Este repositório guarda só os instaladores.
