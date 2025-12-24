#LAB08 : SQL injection UNION attack, finding a column containing text

Đề bài : <img width="1067" height="237" alt="image" src="https://github.com/user-attachments/assets/5cc2b7b4-295f-4374-b2d8-b007e6d575fa" />

- Kiểm tra số lượng cột ở trong bảng :
<img width="1387" height="139" alt="image" src="https://github.com/user-attachments/assets/a6f4e534-accb-4a0a-9088-89704c0e41e8" />
<img width="1394" height="136" alt="image" src="https://github.com/user-attachments/assets/490dac6f-061e-438f-9d0b-8796dd0a88f1" />
<img width="1345" height="147" alt="image" src="https://github.com/user-attachments/assets/5f0f9061-3416-4a3a-89fd-2fb9ef8f8483" />
<img width="1368" height="141" alt="image" src="https://github.com/user-attachments/assets/01411599-1952-41b5-94f6-179425e4c8f5" />

- Bảng có 3 cột ta sử dụng **UNION SELECT** để xác định cột nào tương thích với chuỗi
<img width="1310" height="149" alt="image" src="https://github.com/user-attachments/assets/b01f6ed2-69e0-4c3c-85e5-606e4a766453" />
<img width="1326" height="140" alt="image" src="https://github.com/user-attachments/assets/340b2d80-91ac-4f00-b78a-1d9550bd33c6" />
<img width="1256" height="146" alt="image" src="https://github.com/user-attachments/assets/8f72a6f9-cd58-464a-95be-b9da7f491748" />

- Chỉ có cột 2 là trả về dữ liệu tương thích với chuỗi và thêm 1 dòng là **Make the database retrieve the string: 'Oq6U3t'** :
<img width="1227" height="154" alt="image" src="https://github.com/user-attachments/assets/8e4799fb-89e2-49de-abe5-f806efd60b66" />

- Ta sử dụng **Oq6U3t** để hoàn thành bài lab
