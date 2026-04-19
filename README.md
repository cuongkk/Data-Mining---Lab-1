# Khai thác dữ liệu và ứng dụng — Lab 1

## Cấu trúc thư mục

- `docs/` — chứa `Report.pdf`
- `notebooks/` — các Jupyter Notebook:
  - `01_EDA_image.ipynb`
  - `02_preprocessing_image.ipynb`
  - `03_EDA_tabular.ipynb`
  - `04_preprocessing_tabular.ipynb`
  - `06_temporal_preprocessing.ipynb`
- `README.md` — tài liệu tổng quan (file hiện tại).

## Lưu ý quan trọng về cách chạy (Colab / Google Drive)

Nhóm khuyến nghị chạy các notebook trên Google Colab bằng cách lưu các notebook vào Google Drive và mở bằng Colab. Lý do:
- Dataset ảnh có kích thước lớn, nhiều máy cục bộ không đủ tài nguyên để xử lý.
- Colab cho phép mount Google Drive, sử dụng runtime có GPU và dễ lưu/chia sẻ kết quả.

Link Google Drive:
https://drive.google.com/drive/folders/120mvzOAyvNwa2f8BWuBUFNoxExIrRcEU?usp=drive_link

Hướng dẫn nhanh:

1. Follow theo link GG Drive ở trên để tới folder chứa các Colab Notebooks.
2. Mở notebook trong Colab và sử dụng trực tiếp tài nguyên tính toán có sẵn. 

Ghi chú: Vì khuyến nghị chạy trên Colab, file `requirements.txt` được nhóm loại bỏ.

## Ghi chú về dữ liệu

Do kích thước dữ liệu lớn, nên ưu tiên xử lý trực tiếp trên Colab/Drive và lưu đầu ra trên Drive. Vì thế, nhóm không đặt thư mục ``data/``. 