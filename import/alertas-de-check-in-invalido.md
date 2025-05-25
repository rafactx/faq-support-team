# Alertas de check-in invalido

* Os alertas de check-in inválido apresentam um mapa com os Pings GPS e o PDV da visita (somente se estiver georreferenciado no registro). No entanto, existem casos em que não são apresentados Pings GPS no mapa, mesmo aparecendo Pings no status day. Isso acontece porque a regra é a seguinte:\
  **Somente pings dentro do período da visita** (ou seja, entre o horário do check-in e o horário do check-out) serão exibidos os Pings GPS na tela de alerta de operação para check-in inválido.
