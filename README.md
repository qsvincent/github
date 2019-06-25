# test
测试库

配置用户名和邮箱
git config --global user.name "qsvincent"
git config --global	user.email	"962739337@qq.com"

通过git地址下载项目"https://github.com/qsvincent/test.git"
cd /c/github
git clone "https://github.com/qsvincent/test.git"
ls

上传修正的代码test.txt
git add test.txt
git commit -m "注释"
git push origin master
