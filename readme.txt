git init .

git rm -rf .git

git rm --cached file_name
git rm -r --cached file_name

. -> all file in directory

# pushing project to git
git remote add origin https://github.com/NdagiStanley/new-repository.git
git branch -M `main`
git push -u origin `main`


How to see git show
git log
git show commitId

* Commit လုပ်ပြီး မှာ ထပ်ပြီး ပြန်ထည့်ထာဆိုရင်
git diff

Commit ပဲ ဖြစ်ဖြစ် add ပြီးသားဖြစ်ဖြစ် restore လုပ်ရင် ရတယ်

push မလုပ်သေးပဲ နဲ့ ခနန commit လုပ်ရင် commit id အများကြီးထွက်လာမယ် အဲ့ ကြောင့် --amend ကို သုံးရတယ်

Github ပေါ်ကို တင်တော့မယ် ဆိုရင် github မှာ repository တစ်ခုေဆာက်မယ်
git branch
git branch -M main

How to create tag , you can create two
git tag tag_name
# git tag -a tag_name -m "Any comment"
git push origin tag_name

Creating branch
git branch ( for local )
git branch -r ( for remote server )
git branch -a ( all branch local and remote )
git checkout branch_name
git checkout - ( switch origin/main to other branch , otherbranch to main)
git push -u origin feature-a
