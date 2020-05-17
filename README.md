Если хотите посмотреть изменения:
 * Установите Хромиум `https://chromium.googlesource.com/chromium/src/+/master/docs/get_the_code.md` (это может занять несколько дней)
 * Загрузите мой файл в папку src
 * Выполните в консоли команду `git apply FinalDiffEvelina.txt`
 * Соберите проект: `ninja -C out/Debug -j 2000 chrome` (примечание: маломощным компьютерам здесь прописать вместо 2000 10)
 * Запустите `/out/Debug/chrome.exe`