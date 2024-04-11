# Sentiment-Analysis
Trong thế giới mạng xã hội ngày nay, Facebook là một trong những nền tảng quan trọng nhất cho việc chia sẻ thông tin, giao tiếp và tương tác. Với hàng tỷ người dùng trên toàn thế giới, Facebook chứa đựng một lượng lớn thông tin được tạo ra mỗi ngày, bao gồm cả hàng triệu bình luận được đăng trên các bài đăng.

Bài toán Sentiment Analysis (phân tích tính cảm xúc) trên các bình luận Facebook là quá trình đánh giá và xác định tâm trạng hoặc ý kiến của người dùng đối với một chủ đề cụ thể. Mục tiêu chính của Sentiment Analysis là phân loại các bình luận thành các phân nhóm như tích cực, tiêu cực hoặc trung tính.

Trong dự án này, chúng ta sẽ tìm hiểu cách thức xây dựng một hệ thống Sentiment Analysis để phân tích các bình luận trên Facebook. Chúng ta sẽ sử dụng các kỹ thuật và công nghệ Machine Learning và xử lý ngôn ngữ tự nhiên (NLP) để tự động phát hiện và phân loại tính cảm xúc từ các bình luận này.

Điều này sẽ cung cấp cho chúng ta một cái nhìn sâu hơn về cách mà cộng đồng reagiert với các bài viết trên Facebook, từ đó giúp chúng ta hiểu rõ hơn về cảm nhận của họ đối với các chủ đề cụ thể.

## Models
[Visobert](https://huggingface.co/uitnlp/visobert)
[CafeBERT](https://huggingface.co/uitnlp/CafeBERT)

## Training hyperparameters
- learning_rate: 5e-05
- train_batch_size: 3
- eval_batch_size: 3
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 1

## Training results

## Framework versions
- Transformers 4.38.2
- Pytorch 2.2.1+cu121
- Datasets 2.17.0
- Tokenizers 0.15.2

## Link Demo
[Toxic_Comment_Classification](https://huggingface.co/spaces/DuongTrongChi/Toxic_Comment_Classification)
