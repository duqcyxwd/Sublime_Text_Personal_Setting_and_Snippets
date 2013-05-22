Sublime_Text_Personal_Setting_and_Snippets
==========================================

Sublime_Text_Personal_Setting_and_Snippets

This is a folder for my personal setting and snippets for Sublime Text 2

I found a minor bug with `toggle comment` for ruby. I am using **Sublime Text 2** for windows version. 
`ctrl+shift+/` is the short key for **toggle comment**, you can select a paragraph and press `ctrl+shift+/`, it will automatically create a `=begin` and `=end` at beginning and and end of your code. When you press `ctrl+shift+/`, it will delete `=begin` and `=end` automatically.(just like  `ctrl+/`)

before:

    def initialize(point, guesses)
      @correct_point = point
      @guesses = guesses
    end

after:     

    =begin
    def initialize(point, guesses)
      @correct_point = point
      @guesses = guesses
    end
    =end


Sometimes it is not working. It will create multipy  `=begin` and `=end` instead delete the old one. If someone have the same bug, you can download [Comments.tmPreferences](https://github.com/duqcyxwd/Sublime_Text_Personal_Setting_and_Snippets/blob/master/Ruby/Comments.tmPreferences) and paste it to `X/Package/User/`. 

(I am using windows and my directory is `C:\Users\UsersName\AppData\Roaming\Sublime Text 2\Packages\User`)

There are also some snippets and personal setting for sublime thatI am using. You can find it out from my [github](https://github.com/duqcyxwd/Sublime_Text_Personal_Setting_and_Snippets)
