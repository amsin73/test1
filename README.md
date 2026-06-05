Отлично! Давай развернём твой сайт на **GitHub Pages** — это бесплатно и просто.

## 📤 Пошаговая инструкция:

### 1. **Создай репозиторий на GitHub**

1. Зайди на [github.com](https://github.com)
2. Нажми **"+"** → **"New repository"**
3. Название: например, `studaktiv-portal`
4. Видимость: **Public** (публичный)
5. Нажми **"Create repository"**

### 2. **Загрузи файлы**

**Способ A: Через веб-интерфейс (проще)**
1. В созданном репозитории нажми **"uploading an existing file"**
2. Перетащи все файлы:
   - `index.html`
   - `raspisanie.html`
   - `news.html`
   - `styleindex.css`
3. Нажми **"Commit changes"**

**Способ B: Через Git (правильнее)**
```bash
# В папке с проектом
git init
git add .
git commit -m "Initial commit: СтудАктив портал"
git branch -M main
git remote add origin https://github.com/ТВОЙ_НИК/studaktiv-portal.git
git push -u origin main
```

### 3. **Включи GitHub Pages**

1. В репозитории перейди во вкладку **"Settings"**
2. В левом меню найди **"Pages"**
3. В разделе **"Build and deployment"**:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (или `master`)
   - **Folder**: `/ (root)`
4. Нажми **"Save"**

### 4. **Подожди 1-2 минуты**

GitHub соберёт твой сайт. Обнови страницу Settings → Pages.

Ты увидишь сообщение:
```
Your site is live at https://твой_ник.github.io/studaktiv-portal/
```

### 5. **Готово! 🎉**

Твой сайт доступен по ссылке:
```
https://ТВОЙ_НИК.github.io/studaktiv-portal/
```

---

## 🔧 Как обновлять сайт:

**Через веб-интерфейс:**
1. Открываешь файл на GitHub
2. Нажимаешь ✏️ (Edit)
3. Вносишь изменения
4. Нажимаешь **"Commit changes"**
5. Сайт обновится автоматически через 1-2 минуты

**Через Git:**
```bash
# Вносишь изменения в файлы локально
git add .
git commit -m "Обновил страницу новостей"
git push
```

---

## ⚠️ Важные моменты:

✅ **Имена файлов** должны быть маленькими буквами: `index.html`, не `Index.html`

✅ **CSS подключается правильно:**
```html
<link rel="stylesheet" href="styleindex.css">
```
(без слэша в начале, иначе не найдёт)

✅ **Все файлы в одной папке** (корень репозитория)

✅ **GitHub Pages бесплатный** для публичных репозиториев

---

## 🎨 Кастомный домен (опционально)

Если хочешь свой домен (например, `studaktiv.ru`):
1. В Settings → Pages → Custom domain
2. Впиши свой домен
3. Настрой DNS у регистратора домена

---

**Скинь ссылку на свой репозиторий, когда создашь — помогу проверить!** 🚀
