# moggle-preview-hompara135
AI윰합학과 학술동아리 Moggle 사전미을 위한 레포지터
import pandas as pd
train = pd.read_csv('train.csv')
test = pd.read_csv('test.csv')
submission = pd.read_csv('sample_submission.csv')
submission.head()
submission.to_csv('submission.csv', index=False)
