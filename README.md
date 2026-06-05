[**English**](https://github.com/nncat01/sr-conf-ru/blob/main/README.en.md) | **Русский**

# sr-conf-ru

Конфигурации маршрутизации для популярного Proxy/VPN клиента Shadowrocket, разработанного специально для ОС от Apple
# 
Конфигурации делятся на два типа:

default - в качестве Proxy/VPN конфигурации используется та, которую пользователь выбрал на главном экране

select - в качестве Proxy/VPN конфигураций используются NL AWG 2.0 и WARP AWG 2.0 для некоторых ресурсов (этот вариант делался в первую очередь под себя)

| Конфиг маршрутизации | Источник CIDR и доменов | Публичный DNS |
|-----------|-----------|-----------|
| [RU_GL2_D_A](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/default/GeoLite2/RU_GL2_D_A.conf), [RU_GL2_S_A](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/select/GeoLite2/RU_GL2_S_A.conf) | GeoLite2 + blackmatrix7 + misha-tgshv | AdGuard DNS |
| [RU_GL2_D_C](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/default/GeoLite2/RU_GL2_D_C.conf), [RU_GL2_S_C](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/select/GeoLite2/RU_GL2_S_C.conf) | GeoLite2 + blackmatrix7 + misha-tgshv | Cloudflare DNS |
| [RU_GL2_D_G](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/default/GeoLite2/RU_GL2_D_G.conf), [RU_GL2_S_G](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/select/GeoLite2/RU_GL2_S_G.conf) | GeoLite2 + blackmatrix7 + misha-tgshv | AdGuard DNS |
| [RU_RCVPN_D_A](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/default/roscomvpn/RU_RCVPN_D_A.conf), [RU_RCVPN_S_A](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/select/roscomvpn/RU_RCVPN_S_A.conf) | roscomvpn-routing (адаптация конфига для Happ под SR) | AdGuard DNS |
| [RU_RCVPN_D_C](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/default/roscomvpn/RU_RCVPN_D_C.conf), [RU_RCVPN_S_C](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/select/roscomvpn/RU_RCVPN_S_C.conf) | roscomvpn-routing (адаптация конфига для Happ под SR) | Cloudflare DNS |
| [RU_RCVPN_D_G](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/default/roscomvpn/RU_RCVPN_D_G.conf), [RU_RCVPN_S_G](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/select/roscomvpn/RU_RCVPN_S_G.conf) | roscomvpn-routing (адаптация конфига для Happ под SR) | AdGuard DNS |
| [RU_RCVPN-WL_D_A](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/default/roscomvpn/RU_RCVPN-WL_D_A.conf), [RU_RCVPN-WL_S_A](https://github.com/nncat01/sr-conf-ru/raw/refs/heads/main/select/roscomvpn/RU_RCVPN-WL_S_A.conf) | roscomvpn-routing (адаптация конфига для Happ под SR, whitelist версия) | AdGuard DNS |
| RU_RCVPN-WL_D_C, RU_RCVPN-WL_S_C | roscomvpn-routing (адаптация конфига для Happ под SR, whitelist версия) | Cloudflare DNS |
| RU_RCVPN-WL_D_G, RU_RCVPN-WL_S_G | roscomvpn-routing (адаптация конфига для Happ под SR, whitelist версия) | AdGuard DNS |
| RU_SRR_D_A, RU_SRR_S_A | simple-ru-routing (адаптация конфига для Happ под SR) | AdGuard DNS |
| RU_SRR_D_C, RU_SRR_S_C | simple-ru-routing (адаптация конфига для Happ под SR) | Cloudflare DNS |
| RU_SRR_D_G, RU_SRR_S_G | simple-ru-routing (адаптация конфига для Happ под SR) | AdGuard DNS |

