# mpv

> Un player audio/video basato su MPlayer.
> Maggiori informazioni: <https://mpv.io/manual/stable/>.

- Riproduci un file video o audio:

`mpv {{file}}`

- Salta avanti/indietro di 5 secondi:

`{{<ArrowLeft>|<ArrowRight>}}`

- Salta indietro/avanti di 1 minuto:

`{{<ArrowDown>|<ArrowUp>}}`

- Riduci o aumenta la velocità di riproduzione del 10%:

`{{<[>|<]>}}`

- Riproduci un file a una velocità specifica (da 0.01 a 100, normalmente 1):

`mpv --speed {{velocità}} {{file}}`

- Riproduci un file usando un profilo definito nel file `mpv.conf`:

`mpv --profile {{nome_profilo}} {{file}}`
