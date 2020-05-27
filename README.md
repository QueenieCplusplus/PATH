# PATH
for Mac

    $ which < app name >



finder/
cmd + shift + G

    /usr/local/bin
    /usr/bin
    /bin
    /usr/sbin
    /sbin


    [ Read 5 lines ]
    ^G Get Help  ^O WriteOut  ^R Read File ^Y Prev Page ^K Cut Text  ^C Cur Pos
    ^X Exit      ^J Justify   ^W Where Is  ^V Next Page ^U UnCut Text^T To Spell

add path in line

ctrl + X

Y


     $ sudo nano /etc/paths
     

envpath

    ✗ printenv
    TMPDIR=/var/folders/81/ncqxl7t95_363jgkl65d573m0000gn/T/
    XPC_FLAGS=0x0
    LaunchInstanceID=3168675C-C44D-44B4-AB4B-6EE11623CD63
    TERM=xterm-256color
    LANG=zh_TW.UTF-8
    SSH_AUTH_SOCK=/private/tmp/com.apple.launchd.Ln7DSnngmB/Listeners
    SECURITYSESSIONID=186a7
    XPC_SERVICE_NAME=0
    TERM_PROGRAM=Apple_Terminal
    TERM_PROGRAM_VERSION=433
    TERM_SESSION_ID=523D8AF0-6E73-472D-AF3F-E40EF65CEEFE
    SHELL=/bin/zsh
    HOME=/Users/pintred
    LOGNAME=pintred
    USER=pintred
    SHLVL=1
    PWD=/Users/pintred
    OLDPWD=/Users/pintred
    ZSH=/Users/pintred/.oh-my-zsh
    PAGER=less
    LESS=-R
    LSCOLORS=Gxfxcxdxbxegedabagacad
    PERL5LIB=/Users/pintred/perl5/lib/perl5
    PERL_LOCAL_LIB_ROOT=/Users/pintred/perl5
    PERL_MB_OPT=--install_base "/Users/pintred/perl5"
    PERL_MM_OPT=INSTALL_BASE=/Users/pintred/perl5
    _=/usr/bin/printenv
   
環境變數下的 path

    PATH=/usr/local/opt/python@3.8/bin:/usr/local/opt/python@3.8/bin:/Users/pintred/perl5/bin:/Library/Frameworks/Python.framework/Versions/3.8/bin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/Applications/VMwareFusion.app/Contents/Public:/usr/local/go/bin
    
增加 path 於環境變數

    $vim ~/.bash_profile
    
    esc
    
    i
    
    export PATH=$PATH: < dir >
    
    or 
    
    export PATH= < dir >:$PATH
    
    esc
    
    :wq
    
    $source ~/.bash_profile
    
Ref doc
    
https://www.opencli.com/linux/set-path-var

https://www.brilliantcode.net/466/os-x-uninstall-python/
    





