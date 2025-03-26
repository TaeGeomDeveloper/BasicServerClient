# filepath: /home/jun/jun/BasicServerClient/client/Dockerfile
FROM python:3.10-slim

# 작업 디렉토리 설정
WORKDIR /app

# 의존성 파일 복사 및 설치
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# 애플리케이션 코드 복사
COPY run_client.py .

# 컨테이너 실행 시 기본 명령어 설정
CMD ["python3", "run_client.py"]