# git_ftp_test


서버정보 설정

server: ${{ secrets.FTP_HOST }}

username: ${{ secrets.FTP_USERNAME }}

password: ${{ secrets.FTP_PASSWORD }}


git -> Settings 들어감

좌측메뉴 : 시큐리티 =>  Secrets and variables 선택

actions 클릭 : Repository secrets <= 여기에 키 등록

New repository secret 버튼 누르고

Name * =>    FTP_HOST  FTP_USERNAME   FTP_PASSWORD 

Secret * =>  111.111.22   계정명        비밀번호

각각 등록

