# reboot

> Reinicia o sistema.
> Mais informações: <https://manned.org/reboot.8>.

- Reinicia o sistema:

`reboot`

- Desliga o sistema (igual a `poweroff`):

`reboot {{[-p|--poweroff]}}`

- Suspende o sistema (igual a `halt`):

`reboot --halt`

- Reinicia imediatamente sem entrar em contato com o gerente do sistema:

`reboot {{[-f|--force]}}`

- Escreve a entrada wtmp shutdown sem reinicializar o sistema:

`reboot {{[-w|--wtmp-only]}}`
