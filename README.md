Questo branch viene (ab) usato dalle GitHub Actions per poter sfruttare la
cache in quanto la cache NON è utilizzabile per le Actions di tipo issues.

ATTENZIONE: dato che l'ultimo commit di questo branch viene sempre riscritto
dall'action si prega di usare git rebase -i (con git push -f) per mettere
SEMPRE il commit con la issue come ULTIMO commit onde evitare spiacevoli
riscritture.
