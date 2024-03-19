- Hướng dẫn cài thư viện bits/stdc++.h trên MacOS
1. Mở VS Code và gõ vào Terminal câu lệnh: echo | g++ -v -x c++ -E -
2. Tìm dòng lệnh như hình : /Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX.sdk/usr/include (tùy máy sẽ khác nhma cơ bản là có include và platforms là ok)
3. Click vào và bấm tổ hợp phím cmd + click (sẽ hiển thị ra thư mục file include), bấm 2 ngón vào touchpad hoặc click chuột phải vào mục file, chọn Reveal in Finder (sẽ hiển thị thư mục include dưới dạng finder)
4. Tạo 1 folder mới tên bits trong thư mục include (nhập mật khẩu máy để cấp quyền)
5. Tìm file có tên xcselect.h, mở bằng vscode, sau đó paste toàn bộ nội dung của file stdc++.h ở trên vào file xcselect.h, đổi tên file xcselect.h thành stdc++.h, sau đó kéo thả file stdc++.h vừa đổi tên vào file bits
6. Reset vscode và chạy thử với khai báo thư viện : #include <bits/stdc++.h>
