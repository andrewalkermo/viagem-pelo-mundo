# Entrada
### Formato
[[SENTIDO]](#SENTIDO),[[LONGITUDE_ORIGEM]](#LONGITUDE_ORIGEM),[[LONGITUDE_DESTINO]](#LONGITUDE_DESTINO),[[DURACAO_VIAGEM]](#DURACAO_VIAGEM),[[DATETIME]](#DATETIME)
### Exemplo
[O](#SENTIDO),[53O](#LONGITUDE_ORIGEM),[75L](#LONGITUDE_DESTINO),[46:52:10](#DURACAO_VIAGEM),[2021-10-22 10:32:54](#DATETIME)

# Saída
### Formato
[[DATETIME]](#DATETIME)
### Exemplo
[2021-10-23 09:10:54](#DATETIME)

## SENTIDO
### Formato
Letra "O" para Oeste ou "L" para Leste
### Exemplo
O
## LONGITUDE_ORIGEM
### Formato
decimal, seguido da letra "O" para Oeste ou "L" para Leste
### Exemplo
32L

## LONGITUDE_DESTINO
### Formato
decimal, seguido da letra "O" para Oeste ou "L" para Leste
### Exemplo
59O

## DURACAO_VIAGEM
### Formato
time (HH:ii:ss)
### Exemplo
15:32:59

## DATETIME
### Formato
datetime (yyyy-mm-dd HH:ii:ss)
### Exemplo
2021-10-27 22:01:52
