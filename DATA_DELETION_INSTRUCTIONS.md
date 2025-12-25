# Hướng dẫn Xóa Dữ liệu Người dùng (Data Deletion Instructions)

**Chinese Mate - Ứng dụng học tiếng Trung**

**Cập nhật lần cuối:** 25 tháng 12, 2024

---

## 📋 Tổng quan

Nếu bạn muốn xóa tất cả dữ liệu của mình khỏi ứng dụng Chinese Mate, hãy làm theo hướng dẫn dưới đây.

---

## 🗑️ Cách xóa dữ liệu

### Phương pháp 1: Gỡ cài đặt ứng dụng (Đơn giản nhất)

**Cách này sẽ xóa TẤT CẢ dữ liệu của bạn:**

1. Mở **Settings** (Cài đặt) trên thiết bị Android của bạn
2. Vào **Apps** (Ứng dụng) hoặc **Application Manager**
3. Tìm và chọn **Chinese Mate**
4. Click **Uninstall** (Gỡ cài đặt)
5. Xác nhận gỡ cài đặt

**Kết quả:**
- ✅ Tất cả dữ liệu học tập sẽ bị xóa
- ✅ Thông tin đăng nhập sẽ bị xóa
- ✅ Tất cả cài đặt sẽ bị xóa

**Lưu ý:** Sau khi gỡ cài đặt, bạn không thể khôi phục dữ liệu. Hãy chắc chắn bạn muốn xóa dữ liệu trước khi gỡ cài đặt.

---

### Phương pháp 2: Xóa dữ liệu trong ứng dụng

Nếu bạn muốn xóa dữ liệu nhưng vẫn giữ ứng dụng:

1. Mở ứng dụng **Chinese Mate**
2. Vào **Settings** (Cài đặt) trong ứng dụng
3. Tìm tùy chọn **"Clear Data"** hoặc **"Reset App"**
4. Xác nhận xóa dữ liệu

**Kết quả:**
- ✅ Dữ liệu học tập sẽ bị xóa
- ✅ Thông tin đăng nhập sẽ bị xóa
- ✅ Ứng dụng sẽ reset về trạng thái ban đầu

---

### Phương pháp 3: Xóa dữ liệu thủ công (Nâng cao)

Nếu bạn muốn xóa dữ liệu thủ công:

1. Mở **Settings** (Cài đặt) trên thiết bị Android
2. Vào **Apps** > **Chinese Mate**
3. Click **Storage** (Lưu trữ)
4. Click **Clear Data** (Xóa dữ liệu)
5. Xác nhận xóa

**Kết quả:**
- ✅ Database SQLite sẽ bị xóa
- ✅ Cache sẽ bị xóa
- ✅ Shared Preferences sẽ bị xóa
- ✅ Secure Storage (tokens) sẽ bị xóa

---

## 🔐 Xóa thông tin đăng nhập Facebook/Google

### Xóa thông tin Facebook

1. Đăng nhập vào ứng dụng Chinese Mate
2. Vào **Settings** > **Account**
3. Click **"Logout"** hoặc **"Disconnect Facebook"**
4. Xác nhận đăng xuất

**Lưu ý:** Để xóa hoàn toàn quyền truy cập Facebook:

1. Vào https://www.facebook.com/settings?tab=applications
2. Tìm **Chinese Mate** trong danh sách ứng dụng
3. Click **Remove** hoặc **Xóa**
4. Xác nhận xóa

### Xóa thông tin Google

1. Đăng nhập vào ứng dụng Chinese Mate
2. Vào **Settings** > **Account**
3. Click **"Logout"** hoặc **"Disconnect Google"**
4. Xác nhận đăng xuất

**Lưu ý:** Để xóa hoàn toàn quyền truy cập Google:

1. Vào https://myaccount.google.com/permissions
2. Tìm **Chinese Mate** trong danh sách ứng dụng
3. Click **Remove** hoặc **Xóa**
4. Xác nhận xóa

---

## 📧 Yêu cầu xóa dữ liệu qua email

Nếu bạn muốn yêu cầu xóa dữ liệu qua email:

1. Gửi email đến: **[Thêm email của bạn]**
2. Tiêu đề: **"Yêu cầu xóa dữ liệu - Chinese Mate"**
3. Nội dung email bao gồm:
   - Tên của bạn
   - Email đã đăng ký (nếu có)
   - User ID từ Facebook/Google (nếu có)
   - Yêu cầu xóa dữ liệu

**Thời gian xử lý:** Chúng tôi sẽ xử lý yêu cầu trong vòng 30 ngày.

---

## ⚠️ Lưu ý quan trọng

### Dữ liệu được lưu trữ ở đâu?

- **Local Storage (SQLite)**: Tất cả dữ liệu học tập được lưu trên thiết bị của bạn
- **Secure Storage**: Access tokens được lưu an toàn trên thiết bị
- **Cache**: Dữ liệu cache được lưu trên thiết bị

**Chúng tôi KHÔNG lưu trữ dữ liệu trên server hoặc cloud.**

### Dữ liệu nào sẽ bị xóa?

Khi bạn xóa dữ liệu, các thông tin sau sẽ bị xóa:
- ✅ Từ vựng đã học
- ✅ Kết quả quiz
- ✅ Tiến độ học tập
- ✅ Lịch sử học tập
- ✅ Thông tin đăng nhập (tokens)
- ✅ Cài đặt ứng dụng

### Dữ liệu nào KHÔNG bị xóa?

- ❌ Thông tin trên Facebook/Google (bạn phải xóa trực tiếp trên Facebook/Google)
- ❌ Dữ liệu đã được Google Gemini API xử lý (theo chính sách của Google)

---

## 🔄 Khôi phục dữ liệu

**Lưu ý:** Sau khi xóa dữ liệu, bạn **KHÔNG THỂ khôi phục** dữ liệu. Hãy chắc chắn bạn muốn xóa dữ liệu trước khi thực hiện.

---

## 📞 Liên hệ

Nếu bạn có câu hỏi về việc xóa dữ liệu, vui lòng liên hệ:

- **Email**: [Thêm email của bạn]
- **Thời gian phản hồi**: 30 ngày

---

## ✅ Xác nhận

Sau khi xóa dữ liệu, bạn có thể:
- Cài đặt lại ứng dụng và bắt đầu từ đầu
- Đăng nhập lại bằng Facebook/Google (nếu muốn)
- Import lại dữ liệu từ đầu (nếu có)

---

**Hướng dẫn này có hiệu lực từ ngày 25 tháng 12, 2024.**

---

# Data Deletion Instructions (English)

**Chinese Mate - Chinese Learning App**

**Last Updated:** December 25, 2024

---

## 📋 Overview

If you want to delete all your data from the Chinese Mate application, please follow the instructions below.

---

## 🗑️ How to Delete Data

### Method 1: Uninstall the App (Simplest)

**This will delete ALL your data:**

1. Open **Settings** on your Android device
2. Go to **Apps** or **Application Manager**
3. Find and select **Chinese Mate**
4. Click **Uninstall**
5. Confirm uninstallation

**Result:**
- ✅ All learning data will be deleted
- ✅ Login information will be deleted
- ✅ All settings will be deleted

**Note:** After uninstalling, you cannot recover data. Make sure you want to delete data before uninstalling.

---

### Method 2: Clear Data in App

If you want to delete data but keep the app:

1. Open the **Chinese Mate** app
2. Go to **Settings** in the app
3. Find **"Clear Data"** or **"Reset App"** option
4. Confirm data deletion

**Result:**
- ✅ Learning data will be deleted
- ✅ Login information will be deleted
- ✅ App will reset to initial state

---

### Method 3: Manual Data Deletion (Advanced)

If you want to delete data manually:

1. Open **Settings** on your Android device
2. Go to **Apps** > **Chinese Mate**
3. Click **Storage**
4. Click **Clear Data**
5. Confirm deletion

**Result:**
- ✅ SQLite database will be deleted
- ✅ Cache will be deleted
- ✅ Shared Preferences will be deleted
- ✅ Secure Storage (tokens) will be deleted

---

## 🔐 Delete Facebook/Google Login Information

### Delete Facebook Information

1. Log in to Chinese Mate app
2. Go to **Settings** > **Account**
3. Click **"Logout"** or **"Disconnect Facebook"**
4. Confirm logout

**Note:** To completely remove Facebook access:

1. Go to https://www.facebook.com/settings?tab=applications
2. Find **Chinese Mate** in the app list
3. Click **Remove**
4. Confirm removal

### Delete Google Information

1. Log in to Chinese Mate app
2. Go to **Settings** > **Account**
3. Click **"Logout"** or **"Disconnect Google"**
4. Confirm logout

**Note:** To completely remove Google access:

1. Go to https://myaccount.google.com/permissions
2. Find **Chinese Mate** in the app list
3. Click **Remove**
4. Confirm removal

---

## 📧 Request Data Deletion via Email

If you want to request data deletion via email:

1. Send email to: **[Add your email]**
2. Subject: **"Data Deletion Request - Chinese Mate"**
3. Email content should include:
   - Your name
   - Registered email (if any)
   - User ID from Facebook/Google (if any)
   - Data deletion request

**Processing Time:** We will process your request within 30 days.

---

## ⚠️ Important Notes

### Where is Data Stored?

- **Local Storage (SQLite)**: All learning data is stored on your device
- **Secure Storage**: Access tokens are securely stored on your device
- **Cache**: Cache data is stored on your device

**We do NOT store data on servers or cloud.**

### What Data Will Be Deleted?

When you delete data, the following information will be deleted:
- ✅ Learned vocabulary
- ✅ Quiz results
- ✅ Learning progress
- ✅ Learning history
- ✅ Login information (tokens)
- ✅ App settings

### What Data Will NOT Be Deleted?

- ❌ Information on Facebook/Google (you must delete directly on Facebook/Google)
- ❌ Data processed by Google Gemini API (subject to Google's policy)

---

## 🔄 Data Recovery

**Note:** After deleting data, you **CANNOT recover** data. Make sure you want to delete data before proceeding.

---

## 📞 Contact

If you have questions about data deletion, please contact:

- **Email**: [Add your email]
- **Response Time**: 30 days

---

## ✅ Confirmation

After deleting data, you can:
- Reinstall the app and start fresh
- Log in again with Facebook/Google (if desired)
- Re-import data from scratch (if available)

---

**These instructions are effective from December 25, 2024.**

