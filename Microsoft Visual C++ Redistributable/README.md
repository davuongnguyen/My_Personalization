# Microsoft Visual C++ Redistributable

Microsoft Visual C++ Redistributable là một gói phần mềm cung cấp các thành phần và thư viện thời gian chạy cho các ứng dụng được viết bằng ngôn ngữ lập trình Microsoft Visual C++. Nó giúp các ứng dụng chạy mượt mà trên máy tính của bạn, đặc biệt là những ứng dụng sử dụng các tính năng của Microsoft Windows API, DirectX API, và Microsoft.NET Framework. 

Bạn cần nó vì nhiều ứng dụng phụ thuộc vào nó để hoạt động, và nếu bạn không có nó, bạn có thể gặp phải các lỗi như thiếu file DLL hoặc không thể khởi động ứng dụng. Ngoài ra, nó cũng giúp bạn tiết kiệm dung lượng ổ cứng, vì bạn chỉ cần cài đặt một lần cho nhiều ứng dụng sử dụng chung.

Có rất nhiều bản [Microsoft Visual C++ Redistributable](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170) khác nhau, để cài đặt nó một cách đơn giản và an toàn thì bạn có thể sử dụng winget.

- Đầu tiên hãy cài chắc chắn rằng máy tính của bạn sẵn sàng để sử dụng winget theo hướng dẫn sau: https://learn.microsoft.com/en-us/windows/package-manager/winget/

- Tiếp đến hãy mở cửa sổ dòng lệnh với quyền admin (hãy chắc chắn điều này).

- Cuối cùng hãy thực thi câu lệnh sau trong cửa sổ dòng lệnh:

	``` powershell
	winget install -e --id Microsoft.VCRedist.2015+.x64;winget install -e --id Microsoft.VCRedist.2015+.x86;winget install -e --id Microsoft.VCRedist.2012.x64;winget install -e --id Microsoft.VCRedist.2012.x86;winget install -e --id Microsoft.VCRedist.2013.x64;winget install -e --id Microsoft.VCRedist.2013.x86;winget install -e --id Microsoft.VCRedist.2010.x64;winget install -e --id Microsoft.VCRedist.2010.x86;winget install -e --id Microsoft.VCRedist.2008.x64;winget install -e --id Microsoft.VCRedist.2008.x86;winget install -e --id Microsoft.VCRedist.2005.x64;winget install -e --id Microsoft.VCRedist.2005.x86
	```

	