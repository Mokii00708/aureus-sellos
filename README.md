# Aureus · historial anclado

Cada día hábil, tras el cierre de Nueva York, el sistema publica aquí un manifiesto con la huella SHA-256 del último eslabón del historial sellado de cada cartera y de su código, y un sello de tiempo RFC 3161 firmado por una autoridad independiente (`.tsr`). Así se puede comprobar que el historial que se enseña hoy ya existía en esas fechas y no se ha retocado.

Comprobar un día: `openssl ts -verify -data anclas/AAAA-MM-DD.json -in anclas/AAAA-MM-DD.tsr -CAfile <raíz de la TSA>`

| Sesión | Huella del manifiesto | Último eslabón de cada cartera | Código |
|---|---|---|---|
| 2026-10-16 | `f7088aa8492a5550` | cartera #7 `78f5ea2a5f02` · principal #7 `ae6c85435279` · u_khannah__trend_following_sma #1 `7d7de6a60b94` · u_khannah__trend_momentum_monthly #1 `7e463b497e8d` · vitrina #7 `1c8c59c315ee` | `20533bb25f1b` |
| 2026-10-15 | `2d4164ec6342e94b` | cartera #6 `d19ea0d2bf07` · principal #6 `ec5473eef969` · vitrina #6 `e4ee5b54cf3a` | `57b7f1ff9048` |

Carteras de papel (dinero simulado con precios reales). No es asesoramiento financiero.
