#uv init sclass (buat folder baru namanya sclass)
#cd sclass (masuk ke folder = change directory)
#cd .. (utk keluar ke folder lebih luar)
#git branch -M main
#git add . (add semua file python)
#git commit -m "first commit" 
#git remote add origin https://github.com/JenniGwen/sclass.git
#git push -u origin main

#cd sclass/
#cd . (beda sm cd ..)
#uv add django

###django
cd src
cd sclassdev
uv run django-admin startproject sclassdev
uv run django-admin startapp app_landing
uv run django-admin startapp app_blog
uv run manage.py runserver


abis itu open linknya Starting development server at http://127.0.0.1:8000/
delete semua di app landing kecuali main.py, views, apps
bikin folder baru disana templates\app_landing dimana isinya ada index.html

#kalo ada file innt py di folder itu artinya satu module

// XXS SCRIPT //
belajar cybersecurity
1. create CRUD App
2. Basic Security
3. Penetration Testing
4. Load test
5. deployment: docker and kubernetes

#basic view app_landing
- create templates/app_landing/index.html
- bikin basic html with ! enter
- app_landing/views.py -> bikin function render
- app_landing/urls.py -> bikin path untuk manggil html
- sclassdev/settings.py --> mendaftarin app_landing dan app_blog
- sclassdev/urls.py -> bikin path untuk manggil views render app_landing

task-> bikin view render untuk app_blog