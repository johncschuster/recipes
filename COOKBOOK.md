# 📖 Family Cookbook Contributor & Style Guide

Welcome to the **Schuster Family Recipe Vault**! This repository serves as our single source of truth for family recipes, fully integrated with our Home Assistant Kitchen Tablet.

---

## 🛠️ How to Edit & Add Recipes in Obsidian

1. Open this repository (`github.com/johncschuster/recipes`) as a **standalone vault** in Obsidian.
2. Duplicate the template in [`templates/Recipe Template.md`](file:///Users/johnschuster/Github/recipes/templates/Recipe%20Template.md) into the `recipes/` folder.
3. Fill out the YAML frontmatter at the top of the file:
   - `title`: The official display name of the dish.
   - `servings`: Number of portions (integer, e.g. `4`).
   - `prep_time`: Active prep time (e.g. `"15 mins"`).
   - `cook_time`: Total cooking time (e.g. `"30 mins"`).
   - `tags`: List of tags for category filtering (e.g., `Dinner`, `Italian`, `Breakfast`, `Quick`, `Dessert`, `Healthy`).
   - `source`: Family member name or original URL.
   - `image`: Relative image path (e.g. `assets/images/lasagna.jpg`).
4. Write out the **Ingredients** as Markdown check-lists (`- [ ] 1 lb Italian Sausage`).
5. Write out the **Instructions** as numbered steps (`1. **Heat Oven**: Pre-heat to 375°F.`).
6. Save the file, then commit and push your changes to GitHub!

---

## 🖼️ Adding Recipe Images

Place image files into `assets/images/` and reference them in your recipe frontmatter:

```yaml
image: "assets/images/lasagna.jpg"
```

---

## 🚀 Automatic Sync to Home Assistant

Once committed and pushed to GitHub, changes automatically sync to Home Assistant so they appear instantly on the kitchen tablet!
