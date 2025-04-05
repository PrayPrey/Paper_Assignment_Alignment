사용법 (2025/04/03 기준)

0. 파이썬 최소 3.9.0 이상
1. 가상환경 생성 - requirements.txt 내용 설치 (pip install -r requirements.txt
2. .env 파일 생성 (.txt 파일로 생성 - .txt 확장자 제거 - .env로 이름 변경)
   <예시>
   OPENAI_API_KEY= <your-api-key>
3. graph.py와 app.py 의 경로를 동일하게 설정
4. streamlit 구동 (인터페이스)

- 로컬에서 구동 시:
  > > cd 저장한폴더 --> conda activate 가상환경 python=<3.9.0버전 이상> --> streamlit run app.py - 구동
- 자신의 컴퓨터를 서버로 활용하여 다른 사람도 구동할 수 있게 만들 시 (자신의 open api 사용, 연구실 내에서만 가능)
  > > cd 저장한폴더 --> conda activate 가상환경 python=<3.9.0버전 이상> --> streamlit run app.py --server.address=<your-ip-key> --server.port=<port_id>
  > > ++ (port_id는 보통 8500번 대를 주로 사용합니다.
  > > ex) 8500, 8501....

++) 추가 사항

- 자신의 ip 주소 번호는

  > > cmd 창 --> ipconfig --> IPv4 주소
  > > 에서 확인가능

- 예상되는 비용은 문서당 80 ~ 90 원 입니다

- 과제 목적 및 진행상황 예시는 과제*목적*진행\_예시.txt 참조하시면 됩니다.

######################### REAEDME.md #####################################

### license : Creative Commons Attribution-NonCommercial-NoDerivatives (CC BY-NC-ND)

### https://creativecommons.org/licenses/by-nc-nd/4.0/

### Made by Woo Yoon Kyu

### IIPL, Chung-ang University
