# inotify for php5 and php7

more detail [php.net inotify](http://php.net/manual/en/book.inotify.php)

## inotify_add_watch
```
int inotify_add_watch ( 
	resource $inotify_instance , 
	string $pathname , 
	int $mask)
```

## inotify_queue_len
```
int inotify_queue_len ( resource $inotify_instance )
```

## inotify_read
```
array inotify_read ( resource $inotify_instance )
```

## inotify_rm_watch
```
bool inotify_rm_watch ( resource $inotify_instance , int $watch_descriptor )
```

###contact
更多疑问请+qq群 233415606 or [website http://xingqiba.sinaapp.com](http://xingqiba.sinaapp.com)