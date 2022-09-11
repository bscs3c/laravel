1. Download and install XAMPP. Got to thi link: https://www.apachefriends.org/download.html.
2. Download nad install Composer from https://getcomposer.org/download/.
3. Go to Drive C:/xampp/htdocs. Create a new folder. Name it mylaravelapp.
5. Open your Visual Studio Code Editor.
6. Click terminal in the file menu of your VSCode.
7. In the terminal, type cd C:/xampp/htdocs. Then press enter.
8. Enter this command: composer create-project laravel/laravel mylaravelapp .
8. Close the terminal.
9. Open the mylaravelapp folder.
9. Open the terminal again.
10. Run php artisan serve.
11. Open your browser and enter this url: http://127.0.0.1:8000 .
12. Go to C:/xampp/htdocs in the file explorer. Click the mylaravelapp folder. Right click and click Git Bash.
13. Type git init . Press Enter.
14. Type git checkout -b 'groupname' . Press Enter.
15. Type git push https://github.com/bscs3c/laravel.git .