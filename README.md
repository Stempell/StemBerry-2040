# StemBerry-2040
A RP2040 devboard! Im doing it for Hack Club's Macondo program. It features two buttons for reset and bootsel and two onboard led's (one for power and one is hooked up to pin15), and also a cool evangelion-themed silkscreen art!
It plugs in to breadboards an female headers just like a standard pi pico.
I made this project to learn about making microcontrollers and more advanced pcb's and to have some microcontrollers for personal use. This project taught me a lot and it was also my first time working with restricted space on the board, so every trace and component placement had to be well thought.

<img width="429" height="873" alt="Zrzut ekranu 2026-08-11 022354" src="https://github.com/user-attachments/assets/7a4e0b25-b339-44b2-9e7a-748548297c33" />

<img width="406" height="868" alt="Zrzut ekranu 2026-08-11 022414" src="https://github.com/user-attachments/assets/efbae1af-0b3e-4679-ac16-8e53be2978cc" />

<img width="877" height="522" alt="Zrzut ekranu 2026-08-11 125254" src="https://github.com/user-attachments/assets/4f162108-00fa-4801-8695-fb8f5c0e96aa" />

The button on the left enters into BOOTSEL mode. The one on the right resets the board.
To upload code press the BOOTSEL button while booting up the board. It will then appear as a USB device on your pc, so you can drop the code in.

## Schematic

<img width="972" height="670" alt="Zrzut ekranu 2026-08-11 124234" src="https://github.com/user-attachments/assets/d89aeb59-b17b-4d30-8f67-dc03e2e34df9" />

## Pcb
<img width="287" height="651" alt="Zrzut ekranu 2026-08-11 131834" src="https://github.com/user-attachments/assets/33f3d8bf-bb8a-45ca-b125-02bfe5365bd2" />

The dimensions are 21 x 51mm

## Bill of materials

| Component | Qty / board | Order qty | Ext. price | JLCPCB part |
|---|---|---|---|---|
| RP2040 | 1 | 5 | $4.94 | [C2040](https://jlcpcb.com/partdetail/C2040) |
| W25Q16JVUXIQ (flash) | 1 | 5 | $8.02 | [C2843335](https://jlcpcb.com/partdetail/C2843335) |
| XC6206P332MR-G (3.3V LDO) | 1 | 5 | $0.66 | [C5446](https://jlcpcb.com/partdetail/C5446) |
| 12MHz crystal | 1 | 5 | $0.47 | [C9002](https://jlcpcb.com/partdetail/C9002) |
| USB_C_Receptacle_USB2.0_14P | 1 | 5 | $0.92 | [C165948](https://jlcpcb.com/partdetail/C165948) |
| SW_Push | 2 | 10 | $0.55 | [C720477](https://jlcpcb.com/partdetail/C720477) |
| 100nF | 12 | 60 | $0.32 | [C1525](https://jlcpcb.com/partdetail/C1525) |
| 1uF | 2 | 10 | $0.16 | [C52923](https://jlcpcb.com/partdetail/C52923) |
| 10uF | 2 | 10 | $0.39 | [C19702](https://jlcpcb.com/partdetail/C19702) |
| 33pF | 2 | 10 | $0.07 | [C1562](https://jlcpcb.com/partdetail/C1562) |
| 5.1K | 2 | 10 | $0.06 | [C25905](https://jlcpcb.com/partdetail/C25905) |
| 27 | 2 | 20 | $0.03 | [C25156](https://jlcpcb.com/partdetail/C25156) |
| 1K | 2 | 10 | $0.07 | [C11702](https://jlcpcb.com/partdetail/C11702) |
| 10K | 1 | 5 | $0.04 | [C25744](https://jlcpcb.com/partdetail/C25744) |
| 330 | 1 | 5 | $0.04 | [C25104](https://jlcpcb.com/partdetail/C25104) |
| 470 | 1 | 5 | $0.03 | [C25117](https://jlcpcb.com/partdetail/C25117) |
| 100K | 1 | 5 | $0.04 | [C25741](https://jlcpcb.com/partdetail/C25741) |
| LED (0603) | 1 | 5 | $0.04 | [C2286](https://jlcpcb.com/partdetail/C2286) |
| LED (0805) | 1 | 5 | $0.08 | [C2297](https://jlcpcb.com/partdetail/C2297) |
| **Total** | | | **$16.93** | |

Additional charges and assembly costs rung me up $26.13
You will also need to hand solder two 1x20 male to male pin headers like these ones for like $3.17:

https://pl.aliexpress.com/item/1005007486600604.html?spm=a2g0o.detail.pcDetailTopMoreOtherSeller.1.3aacPweuPweunK&gps-id=pcDetailTopMoreOtherSeller&scm=1007.40050.354490.0&scm_id=1007.40050.354490.0&scm-url=1007.40050.354490.0&pvid=687313aa-89cb-461f-b6b6-9fdf85656003&_t=gps-id%3ApcDetailTopMoreOtherSeller%2Cscm-url%3A1007.40050.354490.0%2Cpvid%3A687313aa-89cb-461f-b6b6-9fdf85656003%2Ctpp_buckets%3A668%232846%238111%231996&pdp_ext_f=%7B%22order%22%3A%221255%22%2C%22eval%22%3A%221%22%2C%22sceneId%22%3A%2230050%22%2C%22fromPage%22%3A%22recommend%22%7D&pdp_npi=6%40dis%21PLN%214.29%214.29%21%21%211.12%211.12%21%400b88abba17864469134574151e101b%2112000040991067942%21rec%21PL%216850984236%21XZ%211%210%21n_tag%3A-29919%3Bd%3A9d0c4368%3Bm03_new_user%3A-29895&utparam-url=scene%3ApcDetailTopMoreOtherSeller%7Cquery_from%3A%7Cx_object_id%3A1005007486600604%7C_p_origin_prod%3A

Total cost: $44.43

If you wish to learn how to make a devboard like this one yourself, or any other devboard similar to this one check out the guide i used:

https://macondo.hackclub.com/docs/build-a-devboard
