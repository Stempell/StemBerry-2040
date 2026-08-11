# StemBerry-2040
A RP2040 devboard! Im doing it for Hack Club's Macondo program. It features two buttons for reset and bootsel and two onboard led's (and also a cool evangelion-themed silkscreen art)
It plugs in to breadboards an female headers just like a standard pi pico.
I made this project to learn about making microcontrollers and more advanced pcb's and to have some microcontrollers for personal use. This project taught me a lot. It was also my first time working with restricted space on the board, so every trace and component placement had to be well thought.

<img width="429" height="873" alt="Zrzut ekranu 2026-08-11 022354" src="https://github.com/user-attachments/assets/7a4e0b25-b339-44b2-9e7a-748548297c33" />

<img width="406" height="868" alt="Zrzut ekranu 2026-08-11 022414" src="https://github.com/user-attachments/assets/efbae1af-0b3e-4679-ac16-8e53be2978cc" />

<img width="877" height="522" alt="Zrzut ekranu 2026-08-11 125254" src="https://github.com/user-attachments/assets/4f162108-00fa-4801-8695-fb8f5c0e96aa" />

The button on the left enters into BOOTSEL mode. The one on the right resets the board.
To upload code press the BOOTSEL button while booting up the board. It will then appear as a USB device on your pc, so you can drop the code in.

## Schematic

<img width="972" height="670" alt="Zrzut ekranu 2026-08-11 124234" src="https://github.com/user-attachments/assets/d89aeb59-b17b-4d30-8f67-dc03e2e34df9" />

## Pcb
<img width="287" height="651" alt="Zrzut ekranu 2026-08-11 131834" src="https://github.com/user-attachments/assets/33f3d8bf-bb8a-45ca-b125-02bfe5365bd2" />

## JLCPCB bill of materials
<img width="1127" height="896" alt="Zrzut ekranu 2026-08-11 125004" src="https://github.com/user-attachments/assets/12078f26-b608-450b-8ce3-5c70af397e28" />

You will also need to hand solder two 1x20 male to male pin headers like these ones:

https://pl.aliexpress.com/item/1005007486600604.html?spm=a2g0o.detail.pcDetailTopMoreOtherSeller.1.3aacPweuPweunK&gps-id=pcDetailTopMoreOtherSeller&scm=1007.40050.354490.0&scm_id=1007.40050.354490.0&scm-url=1007.40050.354490.0&pvid=687313aa-89cb-461f-b6b6-9fdf85656003&_t=gps-id%3ApcDetailTopMoreOtherSeller%2Cscm-url%3A1007.40050.354490.0%2Cpvid%3A687313aa-89cb-461f-b6b6-9fdf85656003%2Ctpp_buckets%3A668%232846%238111%231996&pdp_ext_f=%7B%22order%22%3A%221255%22%2C%22eval%22%3A%221%22%2C%22sceneId%22%3A%2230050%22%2C%22fromPage%22%3A%22recommend%22%7D&pdp_npi=6%40dis%21PLN%214.29%214.29%21%21%211.12%211.12%21%400b88abba17864469134574151e101b%2112000040991067942%21rec%21PL%216850984236%21XZ%211%210%21n_tag%3A-29919%3Bd%3A9d0c4368%3Bm03_new_user%3A-29895&utparam-url=scene%3ApcDetailTopMoreOtherSeller%7Cquery_from%3A%7Cx_object_id%3A1005007486600604%7C_p_origin_prod%3A

If you wish to learn how to make a devboard like this one yourself, or any other devboard similar to this one check out the guide i used:

https://macondo.hackclub.com/docs/build-a-devboard
