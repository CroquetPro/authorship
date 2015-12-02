# authorship
fix authorship

git filter-branch -f --env-filter "GIT_AUTHOR_NAME='Ben Rothman'; GIT_AUTHOR_EMAIL='croquetpro@gmail.com'; GIT_COMMITTER_NAME='Ben Rothman'; GIT_COMMITTER_EMAIL='croquetpro@gmail.com';" HEAD
