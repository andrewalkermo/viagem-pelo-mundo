# Entrada
### Formato
[[DATETIME]](#DATETIME),[[LONGITUDE_ORIGEM]](#LONGITUDE_ORIGEM),[[LONGITUDE_DESTINO]](#LONGITUDE_DESTINO),[[DURACAO_VIAGEM]](#DURACAO_VIAGEM),[[SENTIDO]](#SENTIDO)
### Exemplo
[2021-10-22 10:32:54](#DATETIME),[53](#LONGITUDE_ORIGEM),[75](#LONGITUDE_DESTINO),[46:52:10](#DURACAO_VIAGEM),[O](#SENTIDO)

# Saída
### Formato
[[DATETIME]](#DATETIME)
### Exemplo
[2021-10-23 09:10:54](#DATETIME)

# DATETIME
### Formato
datetime (yyyy-mm-dd HH:ii:ss)
### Exemplo
2021-10-27 22:01:52

# LONGITUDE_ORIGEM
### Formato
decimal
### Exemplo
32

# LONGITUDE_DESTINO
### Formato
decimal
### Exemplo
59

# DURACAO_VIAGEM
### Formato
time (HH:ii:ss)
### Exemplo
15:32:59

# SENTIDO
### Formato
Letra inicial em caixa alta de Oeste ou Leste (O/L)
### Exemplo
O