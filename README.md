# Malicious-URL-Detection
With the rapid growth of the internet, malicious URLs have become a major entry point for cyberattacks such as phishing, malware distribution, and website defacement. Traditional rule-based and blacklist approaches struggle to detect newly evolving threats, making intelligent and adaptive detection mechanisms essential for modern cybersecurity systems.

This project focuses on detecting and classifying malicious URLs using a combination of deep learning and machine learning techniques. A large and diverse dataset of over 650,000 URLs is used, containing benign, phishing, malware, and defacement samples collected from multiple reliable public sources. The URLs are processed at the character level to preserve sequential patterns that are often indicative of malicious behavior.

Deep learning models such as LSTM, CNN-LSTM, and Transformer are employed to learn temporal and spatial dependencies within raw URL sequences. In parallel, traditional ensemble models like XGBoost and CatBoost are used on engineered features to provide comparative baselines. Among all models, the hybrid CNN-LSTM architecture achieves the highest performance, demonstrating its effectiveness in capturing complex URL structures.

The project includes complete data preprocessing, tokenization, feature extraction, model training, evaluation, and performance analysis. The results highlight the superiority of sequence-based deep learning models for malicious URL detection and showcase the potential of CNN-LSTM architectures for real-time cybersecurity applications.
