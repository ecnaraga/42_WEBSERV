# 42_WEBSERV

Goal

    - Mandatory : Write a mini http server in C++98. Implement the followings :
      - Right HTTP response status code
      - Default error pages
      - handle pipes
      - handle environment variables and $?
      - handle SIGINT, SIGQUIT and EOF like in bash
      - implements builtins (cd with relative or absolute path, echo and option -n, export no options, exit no options, env no options, pwd no options, unset no options) 
    - Bonus : Implement && and || operators, and wildcards for current directory
    
Launch

    - Compile with the makefile
    
    -  launch ./webserv <configuration.conf>
    
Authorized functions

    - send, recv, write, access, stat, open, read, close, kill, fcntl, signal
    - fork, dup, dup2, pipe, execve, waitpid 
    - opendir, readdir, closedir, chdir bind
    - socketpair, htons, htonl, ntohs, ntohl
    - kqueue (kqueue, kevent)
    - socket, accept, listen, connect
    - getaddrinfo, freeaddrinfo, setsockopt, getsockname, getprotobyname
    - select, poll, epoll (epoll_create, epoll_ctl, epoll_wait)
    - strerrorr, gai_strerror, errno
    - Everything in C++98

