alias gs='git status'
alias gl='git log --decorate --all --oneline --graph'

alias sourced='source ~/.bashrc'
alias typo='nohup typora ~/Desktop/Notes/0_DailyPlan.md &'
export ROSCONSOLE_FORMAT='[${severity}] [${time} ${node}]: ${message}'

export https_proxy=http://127.0.0.1:12333 http_proxy=http://127.0.0.1:12333
export ALL_PROXY=socks5://127.0.0.1:1080

# Install Ruby Gems to ~/gems
export GEM_HOME="$HOME/gems"
export PATH="$HOME/gems/bin:$PATH"
