# JARKOM Soal Shift Modul 4

## Daftar isi

- [Anggota Kelompok](#anggota-kelompok)

## Anggota Kelompok F07

| NRP        | NAMA                       |
| ---------- | -------------------------- |
| 5025201145 | Mochamad Revanza Kurniawan |
| 5025201208 | Bagus Febrian Dali Hidayat |
| 5025201241 | Jabalnur                   |

## CPT - VLSM
Pertama-tama, bagi topologi yang sudah diberikan ke dalam beberapa subnet kecil sesuai kebutuhan:
![vslm_subnet](https://user-images.githubusercontent.com/73029778/204071976-134c07dc-52e4-426c-b211-facaaa42ceb5.png)

Tentukan jumlah IP yang diperlukan beserta dengan netmasknya untuk setiap subnet yang ada :

|  Subnet   | Jumlah IP | Netmask |
| :-------: | :-------: | :-----: |
|    A1     |   1001    |   /22   |
|    A2     |    501    |   /23   |
|    A3     |   271     |   /23   |
|    A4     |   251     |   /24   |
|    A5     |   212     |   /24   |
|    A6     |    121    |   /25   |
|    A7     |    121    |   /25   |
|    A8     |     71    |   /25   |
|    A9     |     51    |   /26   |
|    A10    |     2     |   /30   |
|    A11    |     2     |   /30   |
|    A12    |     2     |   /30   |
|    A13    |     2     |   /30   |
|    A14    |     2     |   /30   |
|    A15    |     2     |   /30   |
|    A16    |     2     |   /30   |
|    A17    |     2     |   /30   |
|    A18    |     2     |   /30   |
| **Total** | **2618**  | **/20** |

Berdasarkan data tersebut, susun tree subnet VLSM seperti berikut :
![vslm_tree](https://user-images.githubusercontent.com/73029778/204072083-bf3e616a-0581-46ce-b799-8d64cf25d178.png)

Dengan demikian, didapatkan NID untuk masing - masing subnet sebagai berikut :
|  Subnet   | Network ID| Netmask |
| :-------: | :-------: | :-----: |
|    A1     |10.32.8.0  |   255.255.252.0   |
|    A2     |    10.32.6.0    |   255.255.254.0   |
|    A3     |   10.32.4.0     |   255.255.254.0   |
|    A4     |   10.32.3.0     |   255.255.255.0   |
|    A5     |   10.32.2.0     |   255.255.255.0   |
|    A6     |    10.32.1.128    |   255.255.255.128   |
|    A7     |     10.32.1.0    |   255.255.255.128   |
|    A8     |     10.32.0.128    |   255.255.255.128   |
|    A9     |     10.32.0.64     |   255.255.255.192   |
|    A10    |     10.32.0.32     |   255.255.255.252   |
|    A11    |     10.32.0.28     |   255.255.255.252   |
|    A12    |     10.32.0.24     |   255.255.255.252   |
|    A13    |     10.32.0.20     |   255.255.255.252   |
|    A14    |     10.32.0.16     |   255.255.255.252   |
|    A15    |     10.32.0.12     |   255.255.255.252   |
|    A16    |     10.32.0.8    |   255.255.255.252   |
|    A17    |     10.32.0.4     |   255.255.255.252   |
|    A18    |     10.32.0.0     |   255.255.255.252   |

Masing - masing interface pada sebuah subnet dapat diberikan IP sesuai dengan aturan yang telah diberikan di atas.

- Guideau
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072533-8241cf7f-7f6c-49b0-9eec-3a04b7e3d246.png">

- The Minister
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072544-4b87e27b-37c5-4292-81d1-8433828d6373.png">

- The Daundless
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072549-fcde2320-cadd-4122-ae5c-0b1817ab3415.png">

- Johan
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072571-476768b7-05bc-45f0-b85a-5cb9dc55cb8f.png">

- Phanora
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072580-4753072c-a71b-4c43-a86e-a5d540e9e64c.png">

- The Order
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072584-1acc2de7-eaff-4797-92d2-d3e59d2cda08.png">

- Ashaf
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072594-de34de38-3869-4061-a147-72d77c61769d.png">

- The Refonance
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072626-057d2186-3ebe-4d4a-9b00-6539b813c713.png">

- The Beast
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072643-8415d885-b215-43ea-be05-94845973f587.png">

- The Instrument
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072650-bf013ad5-38f1-47a9-88fc-17cf5f735511.png">

- Matt Cugat
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072655-05bf0247-79d7-4156-bc59-a9e3e28471bc.png">

- The Firefist
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072664-b59376f4-b256-4c7b-962f-31a7148cc45b.png">

- Keith
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072764-6ae6b2b0-20e0-41bb-bf1d-2d8153d912ea.png">

- The Queen
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072769-895273a4-8b5e-4ec4-8947-ee48ef2e7bf2.png">

- The Witch
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072773-9b56878d-77d4-4785-97a6-cf5c54321e07.png">

- Oakleave
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072776-75adab69-b125-47a2-9e1b-768dd1b650bf.png">

- The Magical
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072789-e9de93e3-d1d3-426b-91a8-15c21be0904f.png">

- Corvekt
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072794-65e110ff-2111-41b4-9e4c-7cabbc461b3a.png">

- Haines
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072797-9f42fa6c-e86a-4a7a-b459-32afa6444819.png">

- The Profound
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072808-71df8206-14b4-4834-953c-57cfa48f2c59.png">

- Spendrow
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072814-82ea7591-dc51-41ff-9a29-92c3c854ef2c.png">

- Helga
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204072820-ced74989-5fa7-4f3f-9c6e-26a1638b412e.png">

## Routing
Pada kasus topologi yang sudah kami buat ini, route table yang ada pada masing - masing router adalah sebagai berikut :
<table style="border-collapse:collapse;border-spacing:0" class="tg"><thead><tr><th style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;font-weight:bold;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal"><span style="font-weight:bold">Router</span></th><th style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;font-weight:bold;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal"><span style="font-weight:bold">Subnet</span></th><th style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;font-weight:bold;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal"><span style="font-weight:bold">Network</span></th><th style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;font-weight:bold;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal"><span style="font-weight:bold">Netmask</span></th><th style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;font-weight:bold;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal"><span style="font-weight:bold">Nexthop</span></th></tr></thead><tbody><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:center;vertical-align:middle;word-break:normal" rowspan="14">The Resonance</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A1</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.8.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.252.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.26</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A4</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.3.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.26</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A9</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.64</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.192</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.26</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A13</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.20</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.252</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.26</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A14</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.16</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.252</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.26</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A2</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.6.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.254.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.14</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A5</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.2.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.14</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A6</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.1.128</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.128</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.14</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A7</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.1.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.128</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.14</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A8</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.128</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.128</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.14</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A10</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.32</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.252</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.14</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A16</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.8</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.252</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.14</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A17</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.4</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.252</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.14</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A3</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.8.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.252.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.2</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:middle;word-break:normal" rowspan="4">The Order</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">default</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">0.0.0.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">0.0.0.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.25</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A1</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.8.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.252.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.22</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A4</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.3.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.22</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A14</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.16</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.252</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.22</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:middle;word-break:normal" rowspan="2">The Minister</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">default</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">0.0.0.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">0.0.0.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.21</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A4</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.3.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.18</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">The Dauntless</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">default</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">0.0.0.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">0.0.0.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.17</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:middle;word-break:normal" rowspan="6">The Instrument</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">default</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">0.0.0.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">0.0.0.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.13</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A2</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.6.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.254.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.10</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A5</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.2.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.10</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A10</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.32</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.252</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.10</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A7</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.1.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.128</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.6</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A8</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.128</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.128</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.6</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:middle;word-break:normal" rowspan="2">The Firefist</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">default</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">0.0.0.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">0.0.0.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.9</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">A10</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.32</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">255.255.255.252</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.2.3</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">The Queen</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">default</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">0.0.0.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">0.0.0.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.2.1</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">The Profound</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">default</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">0.0.0.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">0.0.0.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.5</td></tr><tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">The Magical</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">default</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">0.0.0.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">0.0.0.0</td><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:bottom;word-break:normal">10.32.0.1</td></tr></tbody></table>

## Testing
<img width="629" alt="image" src="https://user-images.githubusercontent.com/73029778/204075966-ed6f8482-8a1e-43e3-a1c9-69a639b57a4a.png">

## GNS3 - CIDR

Didapatkan subnet sebagai berikut
![cidr_subnet](https://user-images.githubusercontent.com/73029778/204073643-d403258d-5397-4624-ac14-3f1832419413.png)

Dari gambar diatas dapat kita buat tree subnet CIDR seperti berikut :
![cidr_tree](https://user-images.githubusercontent.com/73029778/204073649-c22ab099-6556-4a6e-90a4-7c27045515cd.png)

- Subnet A: <br>

|  Subnet A | Jumlah IP | Netmask |
| :-------: | :-------: | :-----: |
|    A1     |   1001    |   /22   |
|    A2     |    501    |   /23   |
|    A3     |   271     |   /23   |
|    A4     |   251     |   /24   |
|    A5     |   212     |   /24   |
|    A6     |    121    |   /25   |
|    A7     |    121    |   /25   |
|    A8     |     71    |   /25   |
|    A9     |     51    |   /26   |
|    A10    |     2     |   /30   |
|    A11    |     2     |   /30   |
|    A12    |     2     |   /30   |
|    A13    |     2     |   /30   |
|    A14    |     2     |   /30   |
|    A15    |     2     |   /30   |
|    A16    |     2     |   /30   |
|    A17    |     2     |   /30   |
|    A18    |     2     |   /30   |
| **Total** | **2618**  | |

- Subnet B:<br>

| Subnet B    | Jumlah IP | Netmask |
| ----------- | --------- | ------- |
| B1 (A4+A14) | 253       | /23     |
| B2 (A5+A10) | 214       | /23     |
| B3 (A7+A8)  | 192       | /24     |
| B4 (A3+A18) | 273       | /22     |
| A1          | 1001      | /22     |
| A2          | 501       | /23     |
| A6          | 121       | /25     |
| A9          | 51        | /26     |
| A11         | 2         | /30     |
| A12         | 2         | /30     |
| A13         | 2         | /30     |
| A15         | 2         | /30     |
| A16         | 2         | /30     |
| A17         | 2         | /30     |
| **Total**   | **2618**  | |

- Subnet C:<br>

| Subnet C    | Jumlah IP | Netmask |
| ----------- | --------- | ------- |
| C1 (B1+A1)  | 1254      | /21     |
| C2 (B2+A2)  | 715       | /22     |
| C3 (B3+A17) | 194       | /23     |
| C4 (B4+A11) | 275       | /21     |
| A6          | 121       | /25     |
| A9          | 51        | /26     |
| A12         | 2         | /30     |
| A13         | 2         | /30     |
| A15         | 2         | /30     |
| A16         | 2         | /30     |

- Subnet D<br>

| Subnet D    | Jumlah IP | Netmask |
| ----------- | --------- | ------- |
| D1 (C1+A13) | 1256      | /20     |
| D2 (C2+A16) | 717       | /21     |
| D3 (C3+A6)  | 315       | /22     |
| C4          | 275       | /21     |
| A9          | 51        | /26     |
| A12         | 2         | /30     |
| A15         | 2         | /30     |

- Subnet E<br>

| Subnet E   | Jumlah IP | Netmask |
| ---------- | --------- | ------- |
| E1 (D1+A9) | 1307      | /19     |
| E2 (D2+D3) | 1032      | /20     |
| C4         | 275       | /21     |
| A12        | 2         | /30     |
| A15        | 2         | /30     |

- Subnet F<br>

| Subnet F    | Jumlah IP | Netmask |
| ----------- | --------- | ------- |
| F1 (E1+A12) | 1309      | /18     |
| F2 (E2+A15) | 1034      | /19     |
| C4          | 275       | /21     |

- Subnet G<br>

| Subnet G   | Jumlah IP | Netmask |
| ---------- | --------- | ------- |
| G1 (C4+F2) | 1309      | /18     |
| F1         | 1309      | /18     |

- Subnet H<br>

| Subnet H   | Jumlah IP | Netmask |
| ---------- | --------- | ------- |
| H1 (G1+F1) | 2618      | /17     |

Kemudian buat topologi pada GNS3 seperti berikut:
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204074932-ecbe2b94-7181-47a7-ae95-e33ec7ceecc2.png">

Untuk konfigurasinya sebagai berikut

- Guideau
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075210-e7f3c11c-8294-460b-8ff0-9e42226fb7ca.png">

- The Minister
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075216-4155c11d-e5c1-4bc4-91ec-1b211c8ef28f.png">

- The Daundless
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075221-fc329f87-35f0-4bcc-80b2-b5a0bf99f427.png">

- Johan
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075230-d9ea0cc3-5f44-4ec9-98f7-da8d61bd3af6.png">

- Phanora
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075235-c73062b8-b569-4389-86de-a9e25d971e75.png">

- The Order
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075240-e8d5adaa-9e55-41df-81ab-d2ceac9fe1c0.png">

- Ashaf
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075248-b453ca3d-e3fa-4c51-bc9d-1b07d87312b7.png">

- The Refonance
```
auto eth1
iface eth1 inet static
	address 10.32.32.1
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.32.144.1
	netmask 255.255.255.252

auto eth3
iface eth3 inet static
	address 10.32.162.1
	netmask 255.255.255.252

auto eth4
iface eth4 inet static
	address 10.32.164.1
	netmask 255.255.255.252
```

- The Beast
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075266-18ecfeb9-769b-4051-89a5-885d63e7c3fb.png">

- The Instrument
```
auto eth0
iface eth0 inet static
	address 10.32.144.2
	netmask 255.255.255.252
	gateway 10.32.144.1

auto eth1
iface eth1 inet static
	address 10.32.138.1
	netmask 255.255.255.128

auto eth2
iface eth2 inet static
	address 10.32.132.1
	netmask 255.255.255.252

auto eth3
iface eth3 inet static
	address 10.32.137.1
	netmask 255.255.255.252
```

- Matt Cugat
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075293-2a40a288-c101-4d4d-bd40-066060a6d6ed.png">

- The Firefist
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075311-152824e6-f0b7-4b16-b006-fc5db8f9794d.png">

- Keith
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075316-7f59da19-d399-4ee1-a5ec-af98062bfe6d.png">

- The Queen
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075323-74eceb7b-f4df-43f0-bf4a-a03a7ccf2d8b.png">

- The Witch
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075330-075a0c7f-92af-43ba-a5e6-264a384a06ca.png">

- Oakleave
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075341-2bb1408b-c7a3-4736-af7a-38cac676fe4f.png">

- The Magical
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075356-fe5e7a26-7507-452e-80b2-7c3f34532c51.png">

- Corvekt
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075363-b9e033cc-fec6-45d5-93b5-c058d88035ee.png">

- Haines
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075380-76596de8-f17e-4d9a-a004-fcfac65e0dad.png">

- The Profound
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075391-d01c80d0-ae07-4df6-bbef-1e900d33ca4c.png">

- Spendrow
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075402-d5d5fafe-26b1-49f6-a1fb-b0327048c558.png">

- Helga
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075395-c83eedda-c8bd-43a2-b4b4-2378fa7b7250.png">

## Testing
Lakukan ping antar node. Di sini kami melakukan ping dari node `ashaf` ke node `helga`
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/73029778/204075730-79410abc-d516-44a6-b5cb-b8f0f7c3ea51.png">



