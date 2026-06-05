[**English**](https://github.com/nncat01/sr-conf-ru/blob/main/README.en.md) | **Русский**

# sr-conf-ru

Конфигурации маршрутизации для популярного Proxy/VPN клиента Shadowrocket, разработанного специально для ОС от Apple
# 
Конфигурации делятся на два типа:

default - в качестве Proxy/VPN конфигурации используется та, которую пользователь выбрал на главном экране

select - в качестве Proxy/VPN конфигураций используются NL AWG 2.0 и WARP AWG 2.0 для некоторых ресурсов (этот вариант делался в первую очередь под себя)

Конфиг маршрутизации	Источник CIDR и доменов	Публичный DNS
RU_GL2_D_A   RU_GL2_S_A	GeoLite2 + blackmatrix7 + misha-tgshv 	AdGuard DNS
RU_GL2_D_C     RU_GL2_S_C	GeoLite2 + blackmatrix7 + misha-tgshv 	Cloudflare DNS
RU_GL2_D_G    RU_GL2_S_G	GeoLite2 + blackmatrix7 + misha-tgshv 	Google DNS
RU_RCVPN_D_A RU_RCVPN_S_A	hydraponique/roscomvpn-routing (адаптация конфига для Happ под SR)	AdGuard DNS
RU_RCVPN_D_C RU_RCVPN_S_C	hydraponique/roscomvpn-routing (адаптация конфига для Happ под SR)	Cloudflare DNS
RU_RCVPN_D_G RU_RCVPN_S_G	hydraponique/roscomvpn-routing (адаптация конфига для Happ под SR)	Google DNS
RU_RCVPN-WL_D_A RU_RCVPN-WL_S_A	hydraponique/roscomvpn-routing (адаптация конфига для Happ под SR, whitelist версия)	AdGuard DNS
RU_RCVPN-WL_D_C RU_RCVPN-WL_S_C	hydraponique/roscomvpn-routing (адаптация конфига для Happ под SR, whitelist версия)	Cloudflare DNS
RU_RCVPN-WL_D_G RU_RCVPN-WL_S_G	hydraponique/roscomvpn-routing (адаптация конфига для Happ под SR, whitelist версия)	Google DNS
RU_SRR_D_A   RU_SRR_S_A	frayZV/simple-ru-routing (адаптация конфига для Happ под SR)	AdGuard DNS
RU_SRR_D_C     RU_SRR_S_C	rayZV/simple-ru-routing (адаптация конфига для Happ под SR)	Cloudflare DNS
RU_SRR_D_G    RU_SRR_S_G	rayZV/simple-ru-routing (адаптация конфига для Happ под SR)	Google DNS

