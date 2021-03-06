Name
====

HTTP.Request.Provider - Cross-platform HTTP request implementation


SYNOPSIS
========

        new HTTP.Request.Provider.XHR({
            method      : 'POST',
            url         : 'http://my.host.com/some_url',
            
            query       : 'some text'
            
        }).THEN(function (res) {
            var status  = res.status
            var text    = res.text
        
        }).CATCH(function (e) {
        
            var status  = res.status
        
        }).now()
        

        // or
        
        var req = new HTTP.Request.Provider.NodeJS({
            method      : 'POST',
            
            postBody    : 'some text'
        })
        
        req.setHeaders({
            'X-My-Header' : 'value'
        })
        
        req.request('http://my.host.com/some_url').THEN(function (res) {
            var status  = res.status
            var text    = res.text
        
        }).CATCH(function (e) {
        
            var status  = res.status
        
        }).now()


DESCRIPTION
===========

`HTTP.Request.Provider` is a stub for Joose-orientied JSAN modules.


ISA
===

None.


DOES
====

None.


TRAITS
======

None.



ATTRIBUTES
==========

### attributeName

> `AttributeType attributeName`

> Attribute description


METHODS
=======

### methodName

> `method signature`

> Method description


EXAMPLES
========

Our class can be used like this:

        // then instantiating it
        var instance = new HTTP.Request.Provider({
        })

and like that:

        // then instantiating it
        var instance = new HTTP.Request.Provider({
        })


GETTING HELP
============

This extension is supported via github issues tracker: <http://github.com/SamuraiJack/Module-Stub/issues>

For general Joose questions you can also visit [#joose](http://webchat.freenode.net/?randomnick=1&channels=joose&prompt=1) 
on irc.freenode.org or the forum at: <http://joose.it/forum>
 


SEE ALSO
========

Web page of this module: <http://github.com/SamuraiJack/Module-Stub/>

General documentation for Joose: <http://openjsan.org/go/?l=Joose>


BUGS
====

All complex software has bugs lurking in it, and this module is no exception.

Please report any bugs through the web interface at <http://github.com/SamuraiJack/Module-Stub/issues>



AUTHORS
=======

Nickolay Platonov <nplatonov@cpan.org>





COPYRIGHT AND LICENSE
=====================

This software is Copyright (c) 2010 by Nickolay Platonov <nplatonov@cpan.org>.

This is free software, licensed under:

  The GNU Lesser General Public License, Version 3, June 2007
