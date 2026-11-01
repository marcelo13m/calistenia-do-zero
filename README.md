# CALISTENIA: DO ZERO — PWA

Projeto web instalável no Android, sem framework e sem dependências externas para funcionar.

## O que já funciona
- Interface responsiva para celular.
- Programa semanal de seis dias de atividade e um dia de descanso.
- Treinos de 20–30 minutos, com volume inicial baixo.
- Biblioteca com instruções, dose inicial e cuidados.
- Botões de busca de demonstrações no YouTube (pesquisa por movimento; não são vídeos individuais validados).
- Checklist de sessão concluída.
- Diário de treino e revisão semanal.
- Salvamento local no aparelho via `localStorage`.
- Cache básico para abrir o aplicativo offline depois da primeira visita.
- Manifest e service worker para instalação como PWA.

## Como instalar no Android
1. Publique esta pasta em um endereço HTTPS. GitHub Pages é uma opção gratuita.
2. Abra o endereço no Chrome do Android.
3. Abra o menu do navegador e escolha **Instalar app** ou **Adicionar à tela inicial**.
4. Abra pelo ícone instalado.

## Publicar gratuitamente no GitHub Pages
1. Crie um repositório público no GitHub.
2. Envie todos os arquivos e a pasta `icons`.
3. No repositório, abra Settings → Pages.
4. Em Build and deployment, escolha Deploy from a branch.
5. Selecione `main` e `/ (root)`, salve.
6. Aguarde a publicação e abra o endereço HTTPS no Chrome do celular.

## Privacidade e limitações
- Diário, checklist e revisão ficam no armazenamento local do navegador/aparelho.
- Não há conta, sincronização em nuvem nem backup automático. Limpar dados do navegador pode apagar registros.
- Vídeos abrem uma pesquisa do YouTube. O projeto não afirma que cada resultado foi verificado individualmente.
- Sem barra ou equipamento seguro, movimentos de puxada para costas ficam limitados. Não improvise ancoragem em portas, mesas ou móveis.
- O programa é educativo e geral. Reduza ou interrompa exercícios diante de dor, tontura ou mal-estar.

## Alterar o conteúdo
- `app.js`: biblioteca, treinos, progressão e acompanhamento.
- `styles.css`: cores, layout e tipografia.
- `index.html`: estrutura visual.
