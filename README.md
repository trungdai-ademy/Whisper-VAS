# Whisper-VAS

Phần mềm nguồn mở tích hợp trong **Vietnews AI Studio (VAS)** — Vietnews phân phối lại đúng bản VAS dùng (mã băm SHA-256 khớp bản phát hành VAS đã ký),
kèm mã nguồn tương ứng và giấy phép. Bộ cài VAS tải từ đây trước, lỗi thì tải từ nhà phát triển gốc.

| Phần mềm | Phiên bản | Giấy phép | Bản phát hành |
|---|---|---|---|
| whisper.cpp (CPU) | 1.9.2 | MIT | [whisper-cpu-1.9.2](../../releases/tag/whisper-cpu-1.9.2) |
| whisper.cpp (GPU NVIDIA, kèm thư viện CUDA của NVIDIA) | 1.9.2 | MIT + NVIDIA CUDA Toolkit EULA (thư viện phân phối lại được) | [whisper-cuda-1.9.2](../../releases/tag/whisper-cuda-1.9.2) |
| Mô hình Whisper large-v3-turbo (tiếng Việt) | large-v3-turbo | MIT (OpenAI Whisper) | [whisper-model-large-v3-turbo](../../releases/tag/whisper-model-large-v3-turbo) |
| Mô hình Silero VAD (chỉ dùng khi điều tra) | 5.1.2 | MIT | [whisper-vad-5.1.2](../../releases/tag/whisper-vad-5.1.2) |

Mỗi bản phát hành: tệp chạy gốc (không sửa), `nguon--…` mã nguồn tương ứng (theo danh mục `nguon/<id>.json`), `giay-phep--…`, `SHA256SUMS.txt`.
Bản phát hành do GitHub Actions tạo (`.github/workflows/publish.yml`): tải từ nguồn gốc, kiểm mã băm ghim, sai là không phát hành.

Bản quyền phần mềm thuộc các tác giả / cộng đồng của từng dự án. Yêu cầu mã nguồn: support@vietnews.com.vn
