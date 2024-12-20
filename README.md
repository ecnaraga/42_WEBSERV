# 42_WEBSERV

Goal

    - Mandatory : Write a mini http server in C++98. Implement the followings :
      - Return the right HTTP response status code
      - Default error pages if none is provided
      - Has to be abble to serve a static website
      - Upload files
      - Implement GET POST and DELETE methods
      - Server should never die
      - Listen to multi ports
      - Multi server block in configuration file possible
      - Directory listing
      - CGI
    - Bonus : Support Cookies and Session management, handle multiple CGI
    
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
