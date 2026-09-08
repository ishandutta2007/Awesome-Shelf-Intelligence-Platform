# Awesome-Shelf-Intelligence-Platform

rm *.py

mv "$loops_path\sheet_outputs\$real_repo_name.txt" "$loops_path\sheet_outputs\_$real_repo_name.txt"

(Get-Content -Path "../$repo_name/README.md") -replace "GitHub Stars", "GitHub_Stars" | Set-Content -Path "../$repo_name/README.md"

(Get-Content -Path "../$repo_name/README.md") -replace "Github Stars", "GitHub_Stars" | Set-Content -Path "../$repo_name/README.md"

git add README.md ;git add assets ;git commit -m "final readme";git -c http.sslVerify=false push;git status

gh-browse-or-reload
