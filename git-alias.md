# Example aliases
# alias zshconfig="mate ~/.zshrc"
# alias ohmyzsh="mate ~/.oh-my-zsh"
```
alias plo="git pull origin"
alias puo="git push origin"
alias sts="git stash"
alias stp="git stash pop"
alias gulp="./node_modules/.bin/gulp"
alias cm="git commit -m"
alias st="git status"
alias lg="git log --all --graph --decorate --date-order"
alias dp="git diff --word-diff --unified=10"
alias nb="git checkout -b"
alias find="git grep"
alias goto="git checkout"
alias add="git add"
alias diff="git diff"
alias gcm="git checkout master"
alias box="~/Desktop/bin/mount.sh"
alias radhe="cd ~/1conf; vagrant up; vagrant ssh;"
alias gr="git grep"
```

# font color
color='\e[0;36m'
colorGreen='\e[1;34m'

# font color
color='\e[0;36m'
colorGreen='\e[1;34m'

# font color : white
NC='\e[0m'

# To extract ones digit of second from system clock
a=`date|cut -c 19`

# Array containing quotes- you can edit it to your favorite quotes
```
var=(" Ever tried. Ever failed. No matter. Try Again. Fail again. Fail better.
\n \t\t\t\t\t\t\t-Samuel Beckett " "Never give up, for that is just the place and time that the tide will turn.
\n \t\t\t\t\t\t\t-Harriet Beecher Stowe " "Our greatest weakness lies in giving up. The most certain way to succeed is always to try just one more time.
\n \t\t\t\t\t\t\t-Thomas A. Edison" "Life isn't about getting and having, it's about giving and being.
\n \t\t\t\t\t\t\t-Kevin Kruse" "Strive not to be a success, but rather to be of value.
\n \t\t\t\t\t\t\t-Albert Einstein" "You miss 100% of the shots you don't take.
\n \t\t\t\t\t\t\t-Wayne Gretzky" "People who are unable to motivate themselves must be content with mediocrity, no matter how impressive their other talents.
\n \t\t\t\t\t\t\t-Andrew Carnegie" "Design is not just what it looks like and feels like. Design is how it works.
\n \t\t\t\t\t\t\t-Steve Jobs" "Only those who dare to fail greatly can ever achieve greatly.
\n \t\t\t\t\t\t\t-Robert F. Kennedy" "All our dreams can come true, if we have the courage to pursue them.
\n \t\t\t\t\t\t\t-Walt Disney " "Success consists of going from failure to failure without loss of enthusiasm.
\n \t\t\t\t\t\t\t-Winston Churchill" )
```

# Welcome message ! Edit it with your name
echo -e "\n${color}${var[$a]}${NC}"
#end of code

# GRE Vocabulary List
gshuf -n 1 gre
# fortune | cowsay -f $(cowsay -l | tail -n +2 | tr ' ' '\n' | gshuf -n 1 gre) | lolcat



source ~/.zsh/zsh-autosuggestions/zsh-autosuggestions.zsh
