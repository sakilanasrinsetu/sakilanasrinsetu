### Hi, I am Sakila Nasrin Setu 👋

<!-- **sakilanasrinsetu/sakilanasrinsetu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile. -->

<!-- Here are some ideas to get you started: -->

- 🔭 I’m currently working on Python and Django
<!-- - 🌱 I’m currently learning Vue JS -->
<!-- - 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...  -->

<!-- ![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=sakilanasrinsetu&hide=contribs,prs) -->
<!-- [![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=sakilanasrinsetu)](https://github.com/sakilanasrinsetu/) -->
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=sakilanasrinsetu&show_icons=true&theme=radical)


<!-- [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=sakilanasrinsetu&layout=compact)](https://github.com/sakilanasrinsetu/) -->




<!-- ![Harshal Jadhav Medium](https://mediumblog-cards.vercel.app/getMediumBlogs?username=harshalrj25)](https://medium.com/@harshalrj25) -->
<!--  
 git branch statble
 git checkout master
 git merge hotfix 
 git branch -d hotfix

def post_json_response(request):
    post_qs = Post.objects.all()[0:1]
    post_list = list(post_qs.values())
    return JsonResponse(post_list, safe=False)

def post_response(request):
    # response = requests.get('https://api.covid19api.com/countries').json()
    response = requests.get('https://127.0.0.1/post_json_response/', verify=False)
    # requests.get('https://google.com', verify=False)
    # r = requests.post(url, data=json.dumps(payload), headers=headers, timeout=5)
    # time.sleep(5)
    print('sleep')
    context= {
        'response':response
    }
    return render(request, 'dashboard/check.html', context)

python manage.py makemessages --all
python manage.py compilemessages

-->
