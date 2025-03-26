FROM python:3.10-slim

# 작업 디렉토리 설정
WORKDIR /app

# 필요한 파일들을 컨테이너로 복사
COPY requirements.txt .
COPY run_client.py .

# 의존성 설치
RUN pip install --no-cache-dir -r requirements.txt


# 클라이언트 스크립트 실행
CMD ["python","run_client.py"]