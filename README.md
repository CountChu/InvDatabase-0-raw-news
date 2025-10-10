# Push the news to GitHub

## Step 1

```
git init
git branch -m main
git add .
git commit -m 'Init commit'
git remote add origin https://github.com/countchu/InvDatabase-0-raw-news.git
``

## Step 2

Manually create an empty YaijaBridge in GitHub

## Step 3

```
git push -u --force origin main
```

# Clone the repository

```
git clone https://github.com/CountChu/InvDatabase-0-raw-news.git 0-raw
```

# Auto Upload News

Refer `InvNews/news-nuc.sh`