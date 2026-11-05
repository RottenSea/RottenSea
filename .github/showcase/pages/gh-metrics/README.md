# gh-metrics/metrics

The maintained fork of lowlighter/metrics, through `gh-metrics/metrics@latest`. Every image also has `user: RottenSea`, `config_timezone: Asia/Shanghai` and, unless it sets its own, `base: ""`. The images have no background of their own and grey text, so they read on the dark theme as they are; the terminal template is dark in itself.

### Classic template, default sections

`base: header, activity, community, repositories, metadata`

![Classic template, default sections](classic.svg)

### Classic template, header only

`base: header`

![Classic template, header only](classic-header.svg)

### Terminal template

`template: terminal, base: header, activity, community, repositories, metadata`

![Terminal template](terminal.svg)

### Repository template, design-system

`template: repository, repo: design-system, base: header, activity, community, repositories, metadata`

![Repository template, design-system](repository.svg)

### Isometric calendar, half year

`plugin_isocalendar: yes`

![Isometric calendar, half year](isocalendar-half-year.svg)

### Isometric calendar, full year

`plugin_isocalendar: yes, plugin_isocalendar_duration: full-year`

![Isometric calendar, full year](isocalendar-full-year.svg)

### Calendar, current year

`plugin_calendar: yes`

![Calendar, current year](calendar.svg)

### Calendar, full history

`plugin_calendar: yes, plugin_calendar_limit: 0`

![Calendar, full history](calendar-full-history.svg)

### Languages, most used

`plugin_languages: yes, plugin_languages_limit: 8`

![Languages, most used](languages.svg)

### Languages, with details

`plugin_languages: yes, plugin_languages_limit: 8, plugin_languages_details: bytes-size, percentage`

![Languages, with details](languages-details.svg)

### Languages, recently used

`plugin_languages: yes, plugin_languages_limit: 8, plugin_languages_sections: recently-used, plugin_languages_details: bytes-size, percentage`

![Languages, recently used](languages-recent.svg)

### Languages, most and recently used

`plugin_languages: yes, plugin_languages_limit: 8, plugin_languages_sections: most-used, recently-used, plugin_languages_details: percentage`

![Languages, most and recently used](languages-both.svg)

### Languages, in-depth analysis

`plugin_languages: yes, plugin_languages_limit: 8, plugin_languages_indepth: yes, plugin_languages_details: lines, bytes-size, plugin_languages_analysis_timeout: 15`

![Languages, in-depth analysis](languages-indepth.svg)

### Lines of code, compact in the base section

`base: repositories, plugin_lines: yes`

![Lines of code, compact in the base section](lines.svg)

### Lines of code, repositories and history

`plugin_lines: yes, plugin_lines_sections: repositories, history`

![Lines of code, repositories and history](lines-history.svg)

### Achievements, detailed

`plugin_achievements: yes`

![Achievements, detailed](achievements.svg)

### Achievements, compact, every rank

`plugin_achievements: yes, plugin_achievements_display: compact, plugin_achievements_threshold: X`

![Achievements, compact, every rank](achievements-compact.svg)

### Recent activity

`plugin_activity: yes, plugin_activity_limit: 5, plugin_activity_days: 0`

![Recent activity](activity.svg)

### Habits, facts

`plugin_habits: yes, plugin_habits_facts: yes, plugin_habits_charts: no`

![Habits, facts](habits-facts.svg)

### Habits, charts

`plugin_habits: yes, plugin_habits_facts: no, plugin_habits_charts: yes`

![Habits, charts](habits-charts.svg)

### Issues and pull requests on own repositories

`plugin_followup: yes`

![Issues and pull requests on own repositories](followup.svg)

### Issues and pull requests opened by the user

`plugin_followup: yes, plugin_followup_sections: user`

![Issues and pull requests opened by the user](followup-user.svg)

### Notable contributions

`plugin_notable: yes`

![Notable contributions](notable.svg)

### Notable contributions, in depth

`plugin_notable: yes, plugin_notable_indepth: yes, plugin_notable_repositories: yes`

![Notable contributions, in depth](notable-indepth.svg)

### Comment reactions

`plugin_reactions: yes, plugin_reactions_limit: 100, plugin_reactions_details: percentage`

![Comment reactions](reactions.svg)

### Pinned repositories

`plugin_repositories: yes, plugin_repositories_pinned: 6`

![Pinned repositories](repositories-pinned.svg)

### Featured repositories

`plugin_repositories: yes, plugin_repositories_featured: design-system, RottenSea.github.io`

![Featured repositories](repositories-featured.svg)

### Introduction

`base: header, plugin_introduction: yes`

![Introduction](introduction.svg)

### Followers and following

`plugin_people: yes, plugin_people_types: followers, following`

![Followers and following](people.svg)

### Recently starred

`plugin_stars: yes, plugin_stars_limit: 4`

![Recently starred](stars.svg)

### Starred topics, labels

`plugin_topics: yes, plugin_topics_limit: 12`

![Starred topics, labels](topics.svg)

### Starred topics, icons

`plugin_topics: yes, plugin_topics_limit: 0, plugin_topics_mode: icons`

![Starred topics, icons](topics-icons.svg)

### Stargazers, classic charts

`plugin_stargazers: yes`

![Stargazers, classic charts](stargazers.svg)

### Stargazers, graph charts

`plugin_stargazers: yes, plugin_stargazers_charts_type: graph`

![Stargazers, graph charts](stargazers-graph.svg)

### Code snippet of the day

`plugin_code: yes, plugin_code_languages: typescript, javascript, plugin_code_load: 400`

![Code snippet of the day](code.svg)

### Repository traffic

`plugin_traffic: yes`

![Repository traffic](traffic.svg)

### Discussions

`plugin_discussions: yes`

![Discussions](discussions.svg)

### Gists

`plugin_gists: yes`

![Gists](gists.svg)

### PageSpeed of www.rottenth.cafe

`plugin_pagespeed: yes, plugin_pagespeed_url: https://www.rottenth.cafe`

![PageSpeed of www.rottenth.cafe](pagespeed.svg)

### PageSpeed of www.rottenth.cafe, detailed

`plugin_pagespeed: yes, plugin_pagespeed_detailed: yes, plugin_pagespeed_url: https://www.rottenth.cafe`

![PageSpeed of www.rottenth.cafe, detailed](pagespeed-detailed.svg)

