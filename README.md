# Lúa Khỏe AI — EfficientNet-B0 browser pilot

Gói thử nghiệm chuyển mô hình EfficientNet-B0 đã huấn luyện sang ONNX để nhận diện trong trình duyệt. Không huấn luyện lại, không thay mô hình.

`lua-khoe-browser-source.zip` chứa đúng 8 tệp nguồn/mô hình được chọn, không chứa secrets hoặc ảnh người dùng. Workflow thủ công sẽ giải nén, kiểm tra checksum, xuất ONNX và so sánh logit với PyTorch trước khi tạo artifact.

Đây chưa phải website hoàn chỉnh. Tiền xử lý Canvas còn phải đối chiếu với Pillow; chưa nghiệm thu trên điện thoại hoặc ảnh thực địa. Bản backend/giao diện đầy đủ đang được giữ riêng, chưa có trong gói thử nghiệm này.
