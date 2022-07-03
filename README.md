# manifest
manifest

1. ./manifest/repo init -u ssh://git@github.com/egyeom/manifest.git -b master

# 여기서 master는 manifest main branch

# 현재 manifest branch name : master

2. ./manifest/repo sync -j4

3. ./manifest/repo start master --all

# sync로 내려받은 레파지토리의 branch를 master로 변경


# 2022-12-14
# REPO_URL = 'https://gerrit.googlesource.com/git-repo' => REPO_URL = '/home/gyeom/study/manifest/clone.bundle'