File data: db_airbnb và file postman sử dụng để test api (local) đính kèm, bên cạnh localhost:8080/swagger.

Cần thêm file .env khi run local:
DATABASE_URL="mysql://root:1234-pw@localhost:3306/db_airbnb?schema=public" SECRET_KEY="NODE"

Dự án được deploy trên remote server:
http://103.82.25.42:3000/swagger

Viết thêm API getBookingByRoomId để tìm xem vào những ngày nào room đã được book rồi.
Booking and update booking APIs có test xem room có available vào ngày muốn checkIn hay không.
