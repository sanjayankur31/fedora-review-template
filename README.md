fedora-review-template
======================

Just a checklist I use when I review packages

Based on templates other Fedora contributors have put together:

 - https://fedoraproject.org/wiki/User:Kevin/Review_Template?rd=KevinFenzi/ReviewTemplate
 - https://fedoraproject.org/wiki/User:Gholms/review_template


Add this line to your `~/.vimrc` and place the `fedreview.vim` file in `~/.vim`:

```
 autocmd BufNewFile *.fedreview 0r ~/.vim/fedreview.vim
```
