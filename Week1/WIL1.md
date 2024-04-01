#1주차 수업

##깃의 상태는 크게 4개로 나뉜다.
###Working Directory
    현재 파일이 있는 컴퓨터 내의 디렉토리

###Staging Area
    편집하고 있는 파일을 추적할 수 있고 커밋 전의 파일들이 있는 저장소

###Local Repository
    커밋을 한 파일들이 모여있는 저장소, 다른 의미로는 깃허브에 전송되는 파일들이 모여있는 저장소.

##파일의 깃 상태변화 명령어
###git add <file_name>|<.> 
해당되는 파일을 staging area에 올리거나 현재 있는 모든 파일들을 staging area에 올린다.

###git coommit -m "<commit message>"
staging area에 있는 파일들을 커밋하고 커밋 메시지를 남긴다.

###git push -u origin main
커밋된 파일들을 git hub에 올린다.