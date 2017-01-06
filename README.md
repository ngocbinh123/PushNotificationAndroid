# PushNotificationAndroid
                       MUC LUC
1. Nhận thông tin và thông báo trên thanh status
2. Chạm để vào ứng dụng có thông báo đó
3. Thông báo lên màn hình chính, màn hình khóa.
4. Bật thông báo led(nếu điện thoại có hỗ trợ led).
5. Thông báo bằng tiếng, rung, bật sang màn hình.
6. Đối với tin nhắn có thể trả lời tự động từ màn hình notification sau khi dropdown hoặc các activity tương tự.
a. Notification noti = new Notification.Builder(Context)
.setContentTitle(“Important message for you...”)
.setContentText(subject)
.setSmallIcon(R.drawable.new_mail)
.setLargeIcon(aBitmap)
.build();
7.