# It excludes directories inside the paranthesis from included in
# the search result. -prune option removes whatever is there with
# -path option.
find . -type d \( -path ./.tox -o -path ./.git \)  -prune -o -print
# To copy blog content to git repo.
find . -type d \( -path ./.\* -o -path ./theme* \)  -prune -o -exec cp -r {} ../test \;
# find files {} in last 60 minutes.
find srch_dir -amin -60 {accessed}
find srch_dir -mmin -60 {modification time}
find srch_dir -cmin -60 {creation time}
