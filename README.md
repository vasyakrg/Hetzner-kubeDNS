# Hetzner-kubeDNS

Мой вариант прокидывания трафика на локальный куб через внешний traefik + автосоздание субдомена в Hetzner

- в endpoints указать правильные адреса нод куба
- в ингресе доменное имя, которое хотим привязать
- в external-dns - указать свой токен от провайдера, который привязывает домены и фильтр по доменам (если нужен)
- и наконец создать траефик контроллер
