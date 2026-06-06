# Hi, I'm Thái Viết Lập (Lap Thai)
### AI Engineer | LLM & RAG Specialist | K28 CNTT - Văn Lang University

Thế mạnh của tôi là tối ưu hóa mô hình qua **Fine-tuning** và xây dựng kiến trúc **RAG** (Retrieval-Augmented Generation) để giải quyết các bài toán dữ liệu lớn.
Tôi tập trung vào việc nghiên cứu và triển khai các hệ thống AI thực chiến. Thế mạnh của tôi là sự giao thoa giữa **Xử lý ngôn ngữ tự nhiên** (NLP) và **Thị giác máy tính** (Computer Vision), từ việc tối ưu hóa mô hình qua **Fine-tuning** đến xây dựng kiến trúc **RAG** (Retrieval-Augmented Generation) để giải quyết các bài toán dữ liệu lớn và xây dựng các hệ thống phân tích hình ảnh y tế và công nghiệp chuyên sâu .

---

## Kỹ năng chuyên môn

- **LLM Tech:** LangChain, RAG Pipeline, Fine-tuning (LoRA, PEFT), Prompt Engineering, Vision Transformer (ViT), Segment Anything Model (SAM).
- **Models:** Qwen, Flan-T5, LLaMA, GPT, YOLO (v8/v11), ONNX Runtime.
- **Backend/AI Ops:** Docker, FastAPI, Flask, ChromaDB, Qdrant,PostgreSQL.
- **Data/CV:** Tesseract OCR, Selenium, OpenCV, Cvat.ai.

---

## Dự án trọng tâm

### [Chatbot Tư vấn Tuyển sinh Đại học Văn Lang](https://github.com/lap2004/admission-consulting-system)
*Hệ thống RAG hỗ trợ giải đáp thông tin tuyển sinh tự động.*
- **Demo:** [https://vlu-chatbot.vercel.app](https://vlu-chatbot.vercel.app/)
- **Công nghệ:** RAG, PostgreSQL (Vector DB), Tesseract OCR để xử lý file PDF/Web, Docker.
- **Giải pháp:** Xây dựng pipeline xử lý dữ liệu từ nhiều nguồn (PDF, Web crawling) và cung cấp câu trả lời chính xác dựa trên ngữ cảnh thực tế của trường.

### [Chatbot Voice AI Bác sĩ](https://github.com/lap2004/ai-medical-chatbot)
*Trợ lý ảo y tế tương tác qua giọng nói.*
- **Demo:** [https://kltn-vlu.vercel.app/](https://kltn-vlu.vercel.app/)
- **Công nghệ:** Speech-to-Text (STT), Text-to-Speech (TTS), LLM Inference.
- **Tính năng:** Cho phép người dùng giao tiếp bằng giọng nói, chatbot phân tích triệu chứng và đưa ra lời khuyên y tế sơ bộ nhanh chóng.

### [COVID-19 Radiography - Hệ thống sàng lọc bệnh lý hô hấp](https://github.com/lap2004/COVID-19-Radiography)
*Phân loại tự động tổn thương phổi (COVID-19, Lung Opacity, Viral Pneumonia, Normal) từ ảnh Chest X-Ray.*
- **Demo:** [https://huggingface.co/spaces/lap2004/COVID-19-Radiography](https://huggingface.co/spaces/lap2004/COVID-19-Radiography)
- **Dữ liệu:** 21,165 ảnh từ bộ dữ liệu chuẩn quốc tế COVID-19 Radiography Database trên Kaggle (tỷ lệ 80% Train / 20% Val).
- **Công nghệ:** Mô hình siêu nhẹ YOLOv8n-cls (~1.44M params), ảnh chuẩn hóa 256x256. Huấn luyện bằng GPU Tesla T4.
- **Kết quả:** Đạt Top-1 Accuracy 94.99% sau 15 epochs. Đường loss hội tụ lý tưởng (Perfect Convergence). Tốc độ suy luận siêu tốc 0.5 ms/ảnh (~2,000 FPS), tối ưu cho thiết bị phần cứng hạn chế.

### [A Transformer-Based Multimodal Cross-Attention Framework for Pill–Prescription Matching](https://github.com/lap2004/PIMA)

*Hệ thống AI đa phương thức hỗ trợ nhận diện và đối sánh thuốc từ ảnh thực tế với đơn thuốc y tế.*

- **Công nghệ:** ViT-B/16, Faster R-CNN, PP-OCRv3, R-GAT, Multimodal Cross-Attention, PyTorch.
- **Dữ liệu:** Bộ dữ liệu VAIPE gồm ảnh viên thuốc và đơn thuốc thực tế.
- **Giải pháp:** Kết hợp thị giác máy tính, OCR và Graph Neural Network để học mối quan hệ giữa viên thuốc và thông tin kê đơn.
- **Kết quả:** Đạt **83.47% Top-1 Accuracy**, cải thiện hơn **33%** so với mô hình PIMA gốc (49.89%).
- **Nghiên cứu:** Được phát triển trong khuôn khổ bài báo khoa học về Multimodal Medical AI.
---

## Định hướng & Mục tiêu
- **LLM Engineering:** Phát triển các hệ thống Agentic RAG (AI có khả năng tự suy luận và thực hiện hành động).
- **AI Deployment:** Tối ưu hóa việc triển khai mô hình LLM trên các thiết bị phần cứng hạn chế.

## Kết nối với tôi
- **Email:** [lapthai03@gmail.com](mailto:lapthai03@gmail.com)
- **LinkedIn:** [linkedin.com/in/lap-thai-912210317/](https://www.linkedin.com/in/lap-thai-912210317/)
- **GitHub:** [github.com/lap2004](https://github.com/lap2004)

---
*“Biến những dòng code thành giải pháp AI mang lại giá trị thực tế.”*
