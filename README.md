Если хотите посмотреть изменения:
 * Установите Хромиум `https://chromium.googlesource.com/chromium/src/+/master/docs/get_the_code.md` (это может занять несколько дней)
 * Загрузите наши файлы в папку src
 * Выполните в консоли команду `git apply FinalDiffEvelina.txt` и/или `git apply max_pinned_tab.txt`. У Максима дифф с коммитом 102ca0c7a1e88, у Эвелины -- e034ec3ee599415d7e631ae3089b0b7ce988fef3
 * Соберите проект: `ninja -C out/Debug -j 2000 chrome` (примечание: маломощным компьютерам здесь прописать вместо 2000 10)
 * Запустите `/out/Debug/chrome.exe`