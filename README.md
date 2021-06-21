입력순서
git init 로컬저장소 초기화
git branch -m main 저장소> -> 브랜치 기본경로 생성
git remoten add origin 깃허브 소스 주소 ->원격저장소 연결

git add . 업데이트할 파일 등록
git status 업데이트 대기 등록된 파일 확인(new 초록색으로 보임)

git config -- global user . email 깃허브 계정이메일주소 -> 인증(처음에만 하면 됨)
git commit -m "첫 업로드" -> 변경사항을 반영

git push -u origin main 깃허브에 업로드


// 다음 업데이트 부터는
git add .
git commit -m "업데이트 설명글"
git push -u origin main
