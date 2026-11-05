# gh-metrics/metrics

The maintained fork of lowlighter/metrics, through `gh-metrics/metrics@master` (it has no release tags; `master` is its default branch). Every image also has `user: RottenSea`, `config_timezone: Asia/Shanghai` and, unless it sets its own, `base: ""`. The images have no background of their own and grey text, so they read on the dark theme as they are; the terminal template is dark in itself.

## Classic with every plugin

Every plugin that had data on the first run. The options are the same for all three; only `config_display` changes.

### Classic, every plugin with data

`base: header, activity, community, repositories, metadata, plugin_isocalendar: yes, plugin_isocalendar_duration: full-year, plugin_languages: yes, plugin_languages_limit: 8, plugin_languages_details: bytes-size, percentage, plugin_lines: yes, plugin_achievements: yes, plugin_achievements_display: compact, plugin_activity: yes, plugin_activity_limit: 5, plugin_activity_days: 0, plugin_habits: yes, plugin_habits_facts: yes, plugin_habits_charts: yes, plugin_followup: yes, plugin_followup_sections: repositories, user, plugin_reactions: yes, plugin_reactions_details: percentage, plugin_repositories: yes, plugin_repositories_pinned: 6, plugin_introduction: yes, plugin_people: yes, plugin_stars: yes, plugin_stars_limit: 4, plugin_stargazers: yes`

![Classic, every plugin with data](classic-all.svg)

### Classic, every plugin with data, large display

`config_display: large`

![Classic, every plugin with data, large display](classic-all-large.svg)

### Classic, every plugin with data, two columns

`config_display: columns`

![Classic, every plugin with data, two columns](classic-all-columns.svg)

## Templates and base sections

### Classic, default sections

`base: header, activity, community, repositories, metadata`

![Classic, default sections](classic.svg)

### Classic, default sections, large display

`base: header, activity, community, repositories, metadata, config_display: large`

![Classic, default sections, large display](classic-large.svg)

### Classic, default sections, in-depth commit analysis

`base: header, activity, community, repositories, metadata, base_indepth: yes`

![Classic, default sections, in-depth commit analysis](classic-indepth.svg)

### Base section: header

`base: header`

![Base section: header](classic-header.svg)

### Base section: activity

`base: activity`

![Base section: activity](classic-activity.svg)

### Base section: community

`base: community`

![Base section: community](classic-community.svg)

### Base section: repositories

`base: repositories`

![Base section: repositories](classic-repositories.svg)

### Terminal template

`template: terminal, base: header, activity, community, repositories, metadata`

![Terminal template](terminal.svg)

### Repository template, design-system

`template: repository, repo: design-system, base: header, activity, community, repositories, metadata`

![Repository template, design-system](repository.svg)

## Calendars

### Isometric calendar, half year

`plugin_isocalendar: yes`

![Isometric calendar, half year](isocalendar-half-year.svg)

### Isometric calendar, full year

`plugin_isocalendar: yes, plugin_isocalendar_duration: full-year`

![Isometric calendar, full year](isocalendar-full-year.svg)

### Calendar, current year

`plugin_calendar: yes`

![Calendar, current year](calendar.svg)

### Calendar, two years

`plugin_calendar: yes, plugin_calendar_limit: 2`

![Calendar, two years](calendar-two-years.svg)

### Calendar, full history

`plugin_calendar: yes, plugin_calendar_limit: 0`

![Calendar, full history](calendar-full-history.svg)

## Languages

### Languages, most used

`plugin_languages: yes, plugin_languages_limit: 8`

![Languages, most used](languages.svg)

### Languages, with size and percentage

`plugin_languages: yes, plugin_languages_limit: 8, plugin_languages_details: bytes-size, percentage`

![Languages, with size and percentage](languages-details.svg)

### Languages, top four and the rest as other

`plugin_languages: yes, plugin_languages_limit: 4, plugin_languages_other: yes, plugin_languages_details: percentage`

![Languages, top four and the rest as other](languages-other.svg)

### Languages, every category including data and prose

`plugin_languages: yes, plugin_languages_limit: 8, plugin_languages_categories: data, markup, programming, prose, plugin_languages_details: percentage`

![Languages, every category including data and prose](languages-all-categories.svg)

### Languages, recently used

`plugin_languages: yes, plugin_languages_limit: 8, plugin_languages_sections: recently-used, plugin_languages_details: bytes-size, percentage`

![Languages, recently used](languages-recent.svg)

### Languages, most and recently used

`plugin_languages: yes, plugin_languages_limit: 8, plugin_languages_sections: most-used, recently-used, plugin_languages_details: percentage`

![Languages, most and recently used](languages-both.svg)

### Languages, in-depth analysis with lines

`plugin_languages: yes, plugin_languages_limit: 8, plugin_languages_indepth: yes, plugin_languages_details: lines, bytes-size, plugin_languages_analysis_timeout: 15`

![Languages, in-depth analysis with lines](languages-indepth.svg)

## Lines of code

### Lines of code, in the base section

`base: repositories, plugin_lines: yes`

![Lines of code, in the base section](lines.svg)

### Lines of code, per repository

`plugin_lines: yes, plugin_lines_sections: repositories`

![Lines of code, per repository](lines-repositories.svg)

### Lines of code, history

`plugin_lines: yes, plugin_lines_sections: history`

![Lines of code, history](lines-history.svg)

### Lines of code, every section

`base: repositories, plugin_lines: yes, plugin_lines_sections: base, repositories, history`

![Lines of code, every section](lines-all.svg)

## Achievements

### Achievements, detailed

`plugin_achievements: yes`

![Achievements, detailed](achievements.svg)

### Achievements, compact

`plugin_achievements: yes, plugin_achievements_display: compact`

![Achievements, compact](achievements-compact.svg)

### Achievements, compact, every rank

`plugin_achievements: yes, plugin_achievements_display: compact, plugin_achievements_threshold: X`

![Achievements, compact, every rank](achievements-compact-every-rank.svg)

### Achievements, detailed, without secret ones

`plugin_achievements: yes, plugin_achievements_secrets: no`

![Achievements, detailed, without secret ones](achievements-no-secrets.svg)

## Activity and habits

### Activity

`plugin_activity: yes, plugin_activity_limit: 5, plugin_activity_days: 0`

![Activity](activity.svg)

### Activity, ten events with timestamps

`plugin_activity: yes, plugin_activity_limit: 10, plugin_activity_days: 0, plugin_activity_timestamps: yes`

![Activity, ten events with timestamps](activity-timestamps.svg)

### Activity, pushes, pull requests, issues and releases

`plugin_activity: yes, plugin_activity_limit: 8, plugin_activity_days: 0, plugin_activity_filter: push, pr, issue, release`

![Activity, pushes, pull requests, issues and releases](activity-code.svg)

### Habits, facts

`plugin_habits: yes, plugin_habits_facts: yes, plugin_habits_charts: no`

![Habits, facts](habits-facts.svg)

### Habits, charts

`plugin_habits: yes, plugin_habits_facts: no, plugin_habits_charts: yes`

![Habits, charts](habits-charts.svg)

### Habits, graph charts

`plugin_habits: yes, plugin_habits_facts: no, plugin_habits_charts: yes, plugin_habits_charts_type: graph`

![Habits, graph charts](habits-charts-graph.svg)

### Habits, facts and charts over 30 days

`plugin_habits: yes, plugin_habits_facts: yes, plugin_habits_charts: yes, plugin_habits_days: 30`

![Habits, facts and charts over 30 days](habits-all.svg)

## Issues, pull requests and reactions

### Issues and pull requests on own repositories

`plugin_followup: yes`

![Issues and pull requests on own repositories](followup.svg)

### Issues and pull requests opened by the user

`plugin_followup: yes, plugin_followup_sections: user`

![Issues and pull requests opened by the user](followup-user.svg)

### Issues and pull requests, both sections, in depth

`plugin_followup: yes, plugin_followup_sections: repositories, user, plugin_followup_indepth: yes`

![Issues and pull requests, both sections, in depth](followup-indepth.svg)

### Reactions, with percentages

`plugin_reactions: yes, plugin_reactions_details: percentage`

![Reactions, with percentages](reactions.svg)

### Reactions, relative, with counts and percentages

`plugin_reactions: yes, plugin_reactions_display: relative, plugin_reactions_details: count, percentage`

![Reactions, relative, with counts and percentages](reactions-relative.svg)

## Repositories, people and stars

### Repositories, pinned

`plugin_repositories: yes, plugin_repositories_pinned: 6`

![Repositories, pinned](repositories-pinned.svg)

### Repositories, featured

`plugin_repositories: yes, plugin_repositories_featured: design-system, RottenSea.github.io`

![Repositories, featured](repositories-featured.svg)

### Repositories, most starred

`plugin_repositories: yes, plugin_repositories_starred: 4`

![Repositories, most starred](repositories-starred.svg)

### Introduction

`base: header, plugin_introduction: yes`

![Introduction](introduction.svg)

### Introduction, without its title

`base: header, plugin_introduction: yes, plugin_introduction_title: no`

![Introduction, without its title](introduction-no-title.svg)

### Followers and following

`plugin_people: yes`

![Followers and following](people.svg)

### Followers and following, identicons, larger

`plugin_people: yes, plugin_people_identicons: yes, plugin_people_size: 40`

![Followers and following, identicons, larger](people-identicons.svg)

### Recently starred

`plugin_stars: yes, plugin_stars_limit: 4`

![Recently starred](stars.svg)

### Stargazers, classic charts

`plugin_stargazers: yes`

![Stargazers, classic charts](stargazers.svg)

### Stargazers, graph charts

`plugin_stargazers: yes, plugin_stargazers_charts_type: graph`

![Stargazers, graph charts](stargazers-graph.svg)

## No data yet

These were empty on the first run: no code snippet, no notable contributions, no discussions, gists or starred topics.

### Code snippet of the day

`plugin_code: yes, plugin_code_languages: typescript, javascript, plugin_code_load: 400`

![Code snippet of the day](code.svg)

### Notable contributions

`plugin_notable: yes`

![Notable contributions](notable.svg)

### Notable contributions, in depth

`plugin_notable: yes, plugin_notable_indepth: yes, plugin_notable_repositories: yes`

![Notable contributions, in depth](notable-indepth.svg)

### Discussions

`plugin_discussions: yes`

![Discussions](discussions.svg)

### Gists

`plugin_gists: yes`

![Gists](gists.svg)

### Starred topics, labels

`plugin_topics: yes, plugin_topics_limit: 12`

![Starred topics, labels](topics.svg)

### Starred topics, icons

`plugin_topics: yes, plugin_topics_limit: 0, plugin_topics_mode: icons`

![Starred topics, icons](topics-icons.svg)

