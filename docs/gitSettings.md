## 전역으로 사용할 설정은 config 뒤에 --global 추가.

# 커밋의 사용자 이름/메일 설정

- `git config --global user.email [gitlab 메일 주소(회사 이메일)]`
- `git config --global user.name [gitlab 사용자 이름]`

# git 대소문자 구분하도록 (\*)

- `git config core.ignorecase false`

# git message 보기

- `git config commit.template .gitmessage.txt`

# rebase: true

- `git config pull.rebase true`

# origin/master 로 (local)master 재설정(pull error 무시)

- `git reset --hard origin/master`

# 폴더 및 파일 명의 대소문자만 변경할 경우

- `git mv {as-is} {temp}`
- `git mv {temp} {to-be}`
