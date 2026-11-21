# Configuração do servidor MPPT24

Módulo do [MPPT24OS](https://github.com/mppt24/MPPT24OS) para reunir rotinas de configuração e atualização de um servidor Linux.

## Estado atual

Os dois scripts públicos são esboços. Quando executados, escrevem apenas uma mensagem no terminal. A configuração e a atualização do sistema ainda estão em preparação.

| Ficheiro | Finalidade prevista |
| --- | --- |
| [`scripts/setup.sh`](scripts/setup.sh) | Configuração inicial do servidor |
| [`scripts/update.sh`](scripts/update.sh) | Atualização do servidor |

## Experimentar os esboços

Com Bash, abre a pasta do repositório e executa:

```bash
bash scripts/setup.sh
bash scripts/update.sh
```

Para conhecer o servidor e os restantes componentes, consulta a [apresentação do ESCUDO](https://github.com/mppt24/MPPT24OS#mppt24-escudo).

## Licença

[MIT](LICENSE).
