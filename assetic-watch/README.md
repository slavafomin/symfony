assetic-watch script
====================

A very simple shell-script to recursively and efficiently watch for asset changes and to trigger automatic recompilation.

Installation
------------

1. Place **"assetic-watch"** inside your **"Symfony/bin"** directory.
2. Open **"assetic-watch"** with your favorite text editor.
3. See comments in **"configuration"** section for configuration details. Update and save the file.
4. Do **". ./bin/assetic-watch"** from inside your Symfony directory. Watch will now run and will monitor your assets.
5. Use **Ctrl+C** to terminate watch execution when you've finished.

Requirements
------------

* **inotifywait** must be installed, [see](https://google.com/?q=install+inotifywait "Google it!")

---
Slava Fomin II <<s.fomin@betsol.ru>>  
Feel free to contact me.  
From Russia with Love.  
Let's make this World a Better place!