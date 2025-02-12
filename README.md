
---

### 🇬🇧 English Version  

## 🔄 AutoPlay Button Presser for [Pony.Town](https://pony.town/)  

This JavaScript bookmarklet automatically clicks the "Play" button on [Pony.Town](https://pony.town), making it easier to enter the game without extra clicks.  

### ⚠️ Warning  
I have nothing against the game’s rules, and all further actions in the game are performed by users independently, without my influence or the script’s interference. I am not responsible for your account, any penalties, or other consequences of using this script. Use it at your own risk.  

### 📦 Installation & Usage  
1. Open **Pony.Town** in your browser.  
2. Copy the following code:  
   ```javascript
   javascript:(function(){setInterval(function(){let body=document.querySelector('body');if(!body.classList.contains('playing')){let b=document.querySelector('.btn.btn-lg.btn-success');if(b){b.click();console.log("Clicked Play!");}}else{console.log("Game is already running, not clicking.");}},5000);})();
   ```  
3. Add it as a **bookmarklet** in your browser:  
   - Create a new bookmark.  
   - In the URL field, paste the copied code.  
4. When **Pony.Town** is open, simply click the bookmark, and the script will start working.  

### ⚙️ How It Works  
The script checks every **5 seconds** whether the game is running. If it's not, it clicks the "Play" button.  

### 📝 License  
Use at your own risk. The author is not responsible for any penalties in the game.  

---

## 🔄 AutoPlay Button Presser for [Pony.Town](https://pony.town)  

Этот JavaScript-букмарклет автоматически нажимает кнопку "Play" на сайте [Pony.Town](https://pony.town), упрощая вход в игру без лишних кликов.  

### ⚠️ Предупреждение  
Я не имею ничего против правил игры, и все дальнейшие действия в игре выполняются пользователями самостоятельно, не зависят от меня и от работы скрипта. Я не несу ответственности за ваш аккаунт, возможные санкции или иные последствия использования данного скрипта. Используйте его на свой страх и риск.  

### 📦 Установка и использование  
1. Открой **Pony.Town** в браузере.  
2. Скопируй следующий код:  
   ```javascript
   javascript:(function(){setInterval(function(){let body=document.querySelector('body');if(!body.classList.contains('playing')){let b=document.querySelector('.btn.btn-lg.btn-success');if(b){b.click();console.log("Нажали Play!");}}else{console.log("Игра уже идет, не кликаем.");}},5000);})();
   ```  
3. Добавь его как **букмарклет** в закладки браузера:  
   - Создай новую закладку.  
   - В поле URL вставь скопированный код.  
4. Когда откроется **Pony.Town**, просто нажми на закладку, и скрипт начнет работу.  

### ⚙️ Как это работает?  
Скрипт каждые **5 секунд** проверяет, идет ли игра. Если нет, он нажимает кнопку "Play".  

### 📝 Лицензия  
Используйте на свой страх и риск. Автор не несёт ответственности за возможные санкции в игре.  

---
