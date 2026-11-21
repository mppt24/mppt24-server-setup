# Configuração do servidor MPPT24

Módulo do [MPPT24OS](https://github.com/mppt24/MPPT24OS) para reunir rotinas de configuração e atualização de um servidor Linux.

Se queres conhecer o servidor em funcionamento, abre o [infográfico do ESCUDO](https://github.com/mppt24/MPPT24OS#mppt24-escudo).

[Infográfico e guia do módulo](GUIA.md)

## Estado · Em evolução

Os dois scripts públicos são esboços. Quando executados, escrevem apenas uma mensagem no terminal. A configuração e a atualização do sistema ainda estão em preparação.

| Ficheiro | Finalidade prevista |
| --- | --- |
| [`scripts/setup.sh`](scripts/setup.sh) | Configuração inicial do servidor |
| [`scripts/update.sh`](scripts/update.sh) | Atualização do servidor |

## Experimentar os esboços

<details>
<summary>Ver os comandos que escrevem uma mensagem no terminal</summary>

Com Bash, abre a pasta do repositório e executa:

```bash
bash scripts/setup.sh
bash scripts/update.sh
```

</details>

## Licença

[MIT](LICENSE).
