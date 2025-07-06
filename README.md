<table>
  <tr>
    <td>
      <img src= "https://github-readme-stats.vercel.app/api?username=configbast1&show_icons=true&theme=tokyonight"/>
    </td>
    <td>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=configbast1&layout=compact&theme=tokyonight" />
    </td>
  </tr>
</table>

## 📌 Что я здесь выкладываю 

Разработка телеграм-ботов (Aiogram)  
- Мини-скрипты для автоматизации и парсинга  
- Связка Python с SQLite и файлами

🔹 Учебные задачи по курсу **C++**  
🔹 Практические проекты с ООП: классы, структуры, шаблоны 
🔹 Отдельные проекты по работе с файлами, массивами, перегрузкой операторов 
## 📚 Закреплённые репозитории

✨ **Примеры моих учебных проектов:**
- [cpp-practice-IT_Step-](https://github.com/configbast1/cpp-practice-IT_Step-) 
- [C-_Structures_Practice](https://github.com/configbast1/C-_Structures_Practice) 

мне типо создать репозиторий name: Update README

on:
  schedule:
    - cron: "0 */6 * * *" 
  workflow_dispatch: # Можно запустить вручную

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout repo
        uses: actions/checkout@v3

      - name: Generate README stats
        uses: lowlighter/metrics@latest
        with:
          token: ${{ secrets.METRICS_TOKEN }}
          user: configbast1
          template: classic
          base: header, activity, community, repositories, metadata

<!--
**configbast1/configbast1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

