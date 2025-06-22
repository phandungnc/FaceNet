# Thực hiện huấn luyện mô hình FaceNet
- Sử dụng môi trường thực hành: Google Colab
- Ngôn ngữ: Python 3.11
- TensorFlow version: 2.15.0
- TensorFlow Addons version: 0.23.0
- NumPy: 1.23.5
- OpenCV: 4.11.0
- scikit-learn: 1.6.1
- Ngoài ra còn có các thư viện khác được import trong code
### FaceNet ver1
- Bộ dữ liệu sử dụng: Yale
- Được tải từ trang web https://vismod.media.mit.edu/vismod/classes/mas622-00/datasets/YALE.tar.gz hoặc sử dụng trực tiếp file YALE.tar.gz
- Code thực hiện: FaceNet_ver1.ipynb
- Thực hiện đánh giá trên bộ dữ liệu LFW: phần dữ liệu này đã được tải lên và đặt vào đúng đường dẫn trong Google Drive ở phần so sánh các mô hình trước đó
### FaceNet ver2
- Bộ dữ liệu sử dụng: Train_LFW, đây là một phần nhỏ được chọn lọc và tách ra từ bộ dữ liệu LFW
- Code thực hiện: FaceNet_ver2.ipynb
### FaceNet ver3
- Bộ dữ liệu sử dụng: Train_ver3, cũng được tách ra từ bộ dữ liệu LFW nhưng số lượng lớn hơn, gần gấp đôi so với ver2
- Code thực hiện: FaceNet_ver3.ipynb
### Thực hiện tối ưu ver3
- Bộ dữ liệu sử dụng: vẫn sử dụng bộ dữ liệu Train_ver3
- Ở phần này, giữ nguyên bộ dữ liệu huấn luyện, thực hiện thêm kỹ thuật tăng cường nhằm làm tăng độ chính xác mô hình so với ver3 trước đó
- Code thực hiện: Nang_cap_ver3.ipynb, Nang_cap_ver3tiep.ipynb do trong quá trình thực hiện Colab hết hạn và cần chuyển đổi gmail
