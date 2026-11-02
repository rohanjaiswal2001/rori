# RoRi · sugar free & alcohol free

Nightly check-in dashboard for Rohan & Riya. Two tabs, same format:

- **🍬 Sugar**: 🌿 No sugar · 🍯 Healthy sugar (still counts) · 🍰 Slipped
- **🍸 Alcohol**: 💧 Dry day · 🥂 Had drinks (how many + which: 🌵 tequila, 🧊 vodka, 🥃 whiskey, 🍷 wine, 🍺 beer, 🏴‍☠️ rum, 🍸 gin, 🍾 champagne, 🍹 cocktail, 🔥 shots)

Each tab has a together-streak counter (numbered: Streak #1, #2…), per-person streaks, a calendar (tap any day to log or fix it), streak history and notes.

Static `index.html` on GitHub Pages; data in Supabase table `habit_log` (`habit`, `day`, `person`, `status`, `note`, `drinks`, `drink_types`). Start dates and milestones are constants at the top of the `<script>`.
