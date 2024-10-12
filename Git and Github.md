## Git and Github:

Git គឺជា​ Version Control System. វាមិនមែនជា Language​ ឬ Framwork​ វាគ្រាន់តែជា System​ មួយ ដំណើរការរបស់វាយើងត្រូវប្រតិបត្តិដោយសរសេរ Command Line. 
យ៉ាងណាក៏ដោយកម្មវិធីជាច្រើនតែងមានភ្ជាប់នូវឧបករណ៏សំរាប់ប្រើប្រាស់ Git ដោយមិនចាំបាច់ប្រើ Command Line.

ដើម្បីប្រើ​ Git បានយើងត្រូវមាន Git System នៅក្នុង Local Machine របស់យើងសិន។

Repository​ ឬ Repo គឺដូចទៅនឹង Folder​ មួយដែរដែលវាក្ដោបក្ដាប់កូដ ឯកសារ រូបភាព...ដែលចាំបាច់របស់កម្មវិធី។

### ខាងក្រោមជា Command Line ដែលត្រូវប្រើប្រាស់ជាមួយ​ Git & Github:

`git init ` សម្រាប់កំណត់ folder​​ ណាមួយជា Repositry​ របស់ Git។

`git status` សម្រាប់បង្ហាញអំពីស្ថានភាពរបស់ Git។

### git add សម្រាប់ treack file ឬ folder ចូលទៅក្នុង stage។

`git add .`  សម្រាប់​ Add​ File or Folder ទាំងអស់។

`git config --global user.email` your@yourdomain.example.com

`git config --global user.name` "Your name"

`git commit` សម្រាប់បញ្ជូន file​ ឬ folder ទាំងអស់ដែលនៅក្នុង stage ចូលទៅក្នុង repo​ របស់កុំព្យូទ័រ ហើយដាក់ `-m "Yor command"` សម្រាប់សរសេរពាក្យនៃកំណែថ្មី។

`git log` សម្រាប់មើលថាក្នុង repo បច្ចុប្បន្នបាន commit អ្វីខ្លះ។

`git remote` សម្រាប់ឆែកមើលថា github មានឈ្មោះអ្វី។ បើមិនមានទេយើង add ដោយចុច add ហើយដាក់ឈ្មោះរបស់ github​ ដែលយើងចង់ដាក់ និងមួយទៀត Link របស់ Repo នៅក្នុង Github.

`git push -u origin master` ដើម្បី push file ឬ folder ទៅក្នុង Repo (master)។

`git pull origin master` ដើម្បី pull file or folder ចេញពីក្នុង Repo (master)។

`git clone` [link] សម្រាប់ទាញយកនូវ folder នៅក្នុង Repo របស់ Github មកប្រើនៅក្នុង Local Machine។

### + Github branch សម្រាប់ធ្វើការបែងចែក​ Code ជាក្រុម

`git checkout -b` [ឈ្មោះ branch] សម្រាប់បង្កើត branch។

`git checkout` [ឈ្មោះ​ branch] សម្រាប់ផ្លាស់ប្ដូរទៅ branch​ ផ្សេង។

`git branch` សម្រាប់មើលថាយើងកំពុងស្ថិតនៅ branch មួយណា។

`git merge` [ឈ្មោះ branch] សម្រាប់merge branch ណាមួយ ទៅកាន់ branch​ បច្ចុប្បន្ន (master)។

`git branch -d` [ឈ្មោះ branch] សម្រាប់លុប branch។

### + Gitignore ប្រើសម្រាប់លាក់ file ឬ folder នៅក្នុង Github Repo
`touch .gitignore` នៅក្នុង root project របស់យើង

`.gitignore` ឈ្មោះ file ឬ folder នៅក្នុង Github Repo



