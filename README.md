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
| 3D Prints | 17.58 | https://trade.jlcpcb.com/checkout/proxyPayPreCheck?systemType=order_tdp&calType=PROXY_PAY&batchNum=W2026101909233095&bizKey=634899494928015362 |
| Joystick Module | 3.28 | https://www.aliexpress.us/item/3256812408836398.html?spm=a2g0o.productlist.main.2.2b242337mCqBhP&algo_pvid=d9f71aa0-d2c4-4d3b-99fb-b6f11a75e941&algo_exp_id=d9f71aa0-d2c4-4d3b-99fb-b6f11a75e941-1&pdp_ext_f=%7B%22order%22%3A%2228%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%213.29%211.65%21%21%2121.88%2110.94%21%402103292b17923732943921068e0df7%2112000058780623935%21sea%21US%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A1092fe7e%3Bm03_new_user%3A-29895&curPageLogUid=as56PJy8lQAg&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012595151150%7C_p_origin_prod%3A |
| 9V battery clip | 3.03 | https://www.aliexpress.us/item/3256809198615022.html?spm=a2g0o.productlist.main.19.60cb1ade6235IU&algo_pvid=1eb2bcb8-61b3-4eba-aeca-aeba7036526e&algo_exp_id=1eb2bcb8-61b3-4eba-aeca-aeba7036526e-18&pdp_ext_f=%7B%22order%22%3A%22259%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%213.03%211.09%21%21%2120.18%217.26%21%402101e80b17923737169458603e10ab%2112000048940343732%21sea%21US%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A1092fe7e%3Bm03_new_user%3A-29895%3BpisId%3A5000000218159425&curPageLogUid=r6PXolRDKWrl&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009384929774%7C_p_origin_prod%3A |
| M2 Screw and Nut Kit | 5.79 | https://www.aliexpress.us/item/3256808477927081.html?spm=a2g0o.productlist.main.9.569b5efccLAawv&algo_pvid=6f5b4206-1f66-4977-8bc2-a6b5b7ece8a6&algo_exp_id=6f5b4206-1f66-4977-8bc2-a6b5b7ece8a6-8&pdp_ext_f=%7B%22order%22%3A%228%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%215.32%215.32%21%21%215.32%215.32%21%402101ca9517923740378271192e0f93%2112000046148370210%21sea%21US%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A1092fe7e%3Bm03_new_user%3A-29895&curPageLogUid=7Gwdt0wlP8cN&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008664241833%7C_p_origin_prod%3A |
| M3 Screw and Nut Kit | 7.91 | https://www.aliexpress.us/item/3256808477927081.html?spm=a2g0o.productlist.main.9.569b5efccLAawv&algo_pvid=6f5b4206-1f66-4977-8bc2-a6b5b7ece8a6&algo_exp_id=6f5b4206-1f66-4977-8bc2-a6b5b7ece8a6-8&pdp_ext_f=%7B%22order%22%3A%228%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%215.32%215.32%21%21%215.32%215.32%21%402101ca9517923740378271192e0f93%2112000046148370210%21sea%21US%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A1092fe7e%3Bm03_new_user%3A-29895&curPageLogUid=7Gwdt0wlP8cN&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008664241833%7C_p_origin_prod%3A |
| Tax and Shipping | 16.08 |  |
| Total | 63.65 | |
