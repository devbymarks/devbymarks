# Pac-Man Contribution Graph

O workflow está em `.github/workflows/pacman.yml` e publica os SVGs na branch `output`.

## Como executar

1. No repositório, acesse **Settings → Actions → General → Workflow permissions**.
2. Selecione **Read and write permissions** e salve, caso ainda não esteja selecionado.
3. Abra **Actions → Generate Pac-Man contribution graph → Run workflow**.
4. Aguarde a execução terminar com sucesso.
5. Confirme que a branch `output` contém:
   - `pacman-contribution-graph.svg`
   - `pacman-contribution-graph-dark.svg`

O workflow também executa automaticamente quando há push para `main` e diariamente. Se uma execução falhar, abra a execução em **Actions** e consulte a etapa marcada em vermelho.

O README usa os SVGs publicados em `output`; por isso, eles precisam existir nessa branch para o Pac-Man aparecer no perfil.
