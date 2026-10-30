# Como usar este pacote de skills

Fork pessoal de [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) (MIT).

## Claude Code em qualquer computador

```bash
claude plugin marketplace add edupelizzon-collab/marketingskills
claude plugin install marketing-skills@marketingskills
```

## Claude Code na nuvem (claude.ai/code)

Abra uma sessão neste repositório. O arquivo `.claude/settings.json` ativa o plugin `marketing-skills` automaticamente.

## Chat do claude.ai (site, celular, desktop)

Envie os arquivos `<nome>-claude-web.zip` em **Customize → Skills → + Create skill → Upload a skill**. Gere os zips com:

```bash
python3 scripts/package_skills.py --target claude-web --mapped-only --output ./zips
```

## Puxar atualizações do autor original

```bash
gh repo sync edupelizzon-collab/marketingskills
```
