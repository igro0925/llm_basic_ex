# llm_basic_ex
생성형 ai api 활용 실습

# 콘다 가상환경 만들기
```
주피터 랩에 가상환경 연동하기
- Jupyter 노트북에서 파이썬 코드를 실행할 수 있는 파이썬 커널

pip install ipykernel
- jupyter lab에 가상환경

(llm_env) 등록하기
python -m ipykernel install --user --name llm_env

새로운 가상환경 만들기
conda create -n llm_env python=3.10
conda activate llm_env

llm_env 가상환경 활성화
 conda activate llm_env
```

# openai gpt 모델 api 사용방법 실습
## 라이브러리 설치

```
pip install openai
pip install --upgrade openai
pip install python-docx
```

# google llm모델 api 사용방법 실습
```
pip install google-genai
```

## 오디오 파일 생성 문제 해결
```
Windows에서 FFmpeg 설치
1. Chocolatey 설치
Chocolatey가 설치되어 있지 않다면 다음 단계를 따라 설치할 수 있습니다:

1) 관리자 권한으로 PowerShell을 엽니다.

2) 다음 명령어를 실행하여 Chocolatey를 설치합니다:
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
    
3)Chocolatey 설치가 완료되면, 다음 명령어로 FFmpeg를 설치할 수 있습니다:
 
choco install ffmpeg
```