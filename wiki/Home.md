# SigmaOS-insomnia

SigmaOS integration component for **Insomnia API client**.

## Commands

```bash
sigmaos-insomnia install   # install package + deploy defaults
sigmaos-insomnia deploy    # copy config templates to $HOME
sigmaos-insomnia status    # binary/package/config report
sigmaos-insomnia reset     # remove deployed config
sigmaos-insomnia open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
