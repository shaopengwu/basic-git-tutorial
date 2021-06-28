# Method 1: Add each file individually
git add source-code/index.html
git add README.md

# Method 2: Add all files in current directory
git add .

remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From github.com:zachgoll/basic-git-tutorial
 * branch            master     -> FETCH_HEAD
   29d0b59..91b8897  master     -> origin/master
Updating 29d0b59..91b8897
Fast-forward
 README.md | 15 ++++++++++++++-
 1 file changed, 14 insertions(+), 1 deletion(-)

The line was added by another contributor to the project and will create a merge conflict.


# Reference
- [Basic Git Tutorial](https://zach-gollwitzer.medium.com/git-crash-course-a-simple-workflow-for-small-teams-and-startups-c491919c9f77)
