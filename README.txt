ГлазОК: сборка APK через GitHub (без Android Studio)
1. Создай аккаунт на github.com и новый репозиторий (New repository, Public).
2. Загрузи ВСЕ файлы этой папки: Add file -> Upload files. Должны попасть
   package.json, capacitor.config.json, папка www и папка .github/workflows/build.yml.
   Если скрытая папка .github не загрузилась: Add file -> Create new file,
   в имени напиши .github/workflows/build.yml и вставь содержимое файла.
3. Открой вкладку Actions, дождись зелёной галочки (5-10 минут).
4. Открой запуск, внизу в Artifacts скачай glazok-apk, внутри app-debug.apk.
