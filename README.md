# DAT 학술트랙 데이터셋 (공개)

한국외대 DAT 학술트랙 미니 캐글 대회용 **train/test 데이터**입니다.
정답(answer)은 포함되지 않습니다.

## 코랩에서 불러오기
```python
import pandas as pd
base = "https://raw.githubusercontent.com/nepersoned/dat-datasets/main"
train = pd.read_csv(f"{base}/finance/train.csv")
test  = pd.read_csv(f"{base}/finance/test.csv")
```

| 대회 | 폴더 | 비고 |
|------|------|------|
| 금융/시계열 | finance | |
| 이미지 | image | train은 용량 커서 `train.csv.gz` (pandas가 자동 해제) |
| NLP | nlp | |
| 제조공정 | manufacturing | |
