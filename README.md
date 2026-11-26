# Robo_Arm
A robot arm

CAD Document: https://cad.onshape.com/documents/f34527b56647466d89ce7569/w/5220c680e211ef186ea40329/e/83a75c2d30c398b04529bd0e

This project is a 4-axis Robotic Arm. It has 4 motors: 1 for the turning, one for the shoulder, one for the bicep, and one for the claw. 
It has a very small claw, so it is more for show than for functionality. 
It is connected to a simple Arduino Elegoo Uno and will be controlled by 2 joysticks.


<img width="952" height="727" alt="image" src="https://github.com/user-attachments/assets/4d338942-ba6b-498f-85dd-55b42c4312a3" />

<img width="1022" height="702" alt="image" src="https://github.com/user-attachments/assets/ce3a2c1a-d42d-430f-abb3-a4c35d2e5f88" />


Parts:
- Arduino - for the computing and thinking stuff
- joystick modules - intuitive movement of the arm
- servos - movement of the arms

| Parts | Costs | Link |
| -- | -- | -- |
| Servos | 9.98 | https://www.walmart.com/ip/4Pcs-Updated-MG90S-Servo-Motor-LINKPAL-MG90S-Metal-Geared-RC-Micro-Servo-Motor-9G-Compatible-for-RC-Model-Helicopter-Airplane-Remote-Control/268868020?classType=REGULAR&athbdg=L1600&from=/search |
| 3D Prints | 6.85 | https://hackclub.slack.com/archives/D0CMARRDR09/p1795712294302719 |
| Joystick Module | 3.28 | https://www.aliexpress.us/item/3256812408836398.html?spm=a2g0o.productlist.main.2.2b242337mCqBhP&algo_pvid=d9f71aa0-d2c4-4d3b-99fb-b6f11a75e941&algo_exp_id=d9f71aa0-d2c4-4d3b-99fb-b6f11a75e941-1&pdp_ext_f=%7B%22order%22%3A%2228%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%213.29%211.65%21%21%2121.88%2110.94%21%402103292b17923732943921068e0df7%2112000058780623935%21sea%21US%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A1092fe7e%3Bm03_new_user%3A-29895&curPageLogUid=as56PJy8lQAg&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012595151150%7C_p_origin_prod%3A |
| 9V battery clip | 3.03 | https://www.aliexpress.us/item/3256809198615022.html?spm=a2g0o.productlist.main.19.60cb1ade6235IU&algo_pvid=1eb2bcb8-61b3-4eba-aeca-aeba7036526e&algo_exp_id=1eb2bcb8-61b3-4eba-aeca-aeba7036526e-18&pdp_ext_f=%7B%22order%22%3A%22259%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%213.03%211.09%21%21%2120.18%217.26%21%402101e80b17923737169458603e10ab%2112000048940343732%21sea%21US%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A1092fe7e%3Bm03_new_user%3A-29895%3BpisId%3A5000000218159425&curPageLogUid=r6PXolRDKWrl&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009384929774%7C_p_origin_prod%3A |
| Screws and Nuts | 15.79 | https://www.aliexpress.us/item/3256806823773268.html?spm=a2g0o.productlist.main.7.34b76564iNWUtq&algo_pvid=c2a426c4-cc99-4260-a751-51322b69f0e9&algo_exp_id=c2a426c4-cc99-4260-a751-51322b69f0e9-6&pdp_ext_f=%7B%22order%22%3A%221017%22%2C%22eval%22%3A%221%22%2C%22orig_sl_item_id%22%3A%221005007010088020%22%2C%22orig_item_id%22%3A%221005005204331487%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%2115.79%217.62%21%21%21104.69%2150.48%21%402101d33417957141931392409e0fda%2112000039048071412%21sea%21US%218335656895%21X%211%210%21n_tag%3A-29911%3Bd%3A1092fe7e%3Bm03_new_user%3A-29895&curPageLogUid=N5e71X4dJuz8&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007010088020%7C_p_origin_prod%3A1005005204331487 |
| Tax and Shipping | 6 |  |
| Total | 44.93 | |


Connections:
1) Connect the Base Disk 1 to the 3 cm standoffs and, on top of that, place the base disk that has holes for the servo
2) Connect the servo to that base disk
3) Place 1 cm standoffs on their respective holes, and connect the next base disk
4) Connect the Servo to the servo arm
5) Place the big cylinder freestanding in the center
6) Connect the servo arm to the cylinder
7) Add the last base disk on top
8) Place the shoulder servo bracket on top
9) Connect the Servo and Servo Arm
10) Connect the shoulder U bracket
11) Connect the Bicep bottom U bracket
12) Connect the Servo to that
13) Connect the Bicep top bracket
14) Connect the Wrist U bracket
15) Connect the servo and Servo Arm
16) Connect the hand U Bracket
17) Connect the Gear and Gear pieces
18) Connect the Servo at the End 
