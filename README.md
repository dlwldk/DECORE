# DECORE (Deep Compression with Reinforcement Learning)
강화학습을 활용하여 딥러닝 모델을 효과적으로 압축하는 프레임워크

## 프로세스
1. **모델 사전 학습**:
    - structured pruning 기반 사전 학습 수행
    
2. **데이터 준비**:
    - 딥러닝 모델 로드
    - 가중치 및 파라미터 추출

3. **모델 압축**:
    - 강화학습 에이전트 설계
    - 압축
    - quantization 및 pruning

4. **학습 및 최적화**:
    - 압축률과 성능 간의 트레이드 오프 최적화
    - 압축 모델 미세 조정
  
5. **평가**:
    - 모델 성능 평가
    - 압축률 측정

## 환경 및 라이브러리
- Python 3.9+
- PyTorch >= 1.12.0
- CUDA >= 11.3 (GPU 사용시)
- pandas >= 1.4.0
- numpy >= 1.21.0
- scikit-learn >= 1.0.0
- matplotlib >= 3.5.0
- tqdm >= 4.64.0
