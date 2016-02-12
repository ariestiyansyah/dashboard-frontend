# EdX Learning Dashboard

Submitted to [EdX Learning Dashboard Challenge](http://databits.io/challenges/edx-learning-dashboard-challenge)
*- Siyuan Guo, Jan 2015*

## Overview

- `D3.js` is the only dependency for visualizations
- `Progress` is a donut chart showing section-based progress of current student (in comparison to peers)
- `Timeline` is a line chart showing time-based progress of current student
- `Leaderboard` is a bar chart showcasing the top performers
- Implicit cues rather than explicit verbal suggestions are used to guide and encourage students.
  - in `Progress` chart, a smooth colorful ring looks better than a gray rugged ring, and student can achieve a beautiful ring by making more and balanced efforts;
  - in `Timeline` chart, x-axis punchcard be a perfect green line if the user stay active everyday;
  - `Leaderboard` directly shows the behaviors that are praised.
- Visualization logics and data logics are separated. JS scripts contains minimal codes for data manipulation, they simply read and show all JSON data generated by `csv2json.py`.

## Style

- mimicking the native style as in EDX course page
- rich and meaningful animations
- responsive design (though hover effects are limited on small touch screen)
- tested working on latest Firefox, Chrome, Safari and IE (there might still be minor style conflicts with certain browser)