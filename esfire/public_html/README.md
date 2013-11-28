esfire
======

The idea to open firebug using esprima powaa combined to node to debug javascript with external tools
(why not xdebug?) wouldn't be like opening js to the json world in live?

Firebug is great but I did not manage to export dom nor give the possibility to communicate to third party tools.
Today, export is mainly limited to the console logs and diff of the dom is not there.


Javascript has always been a pain to debug async stuff - I mean when timer or ajax is in the place then trace is a pain
and reserved to people who know how to reach the core of firebug. I don't want't to blame the authors here, firebug is
great but lack an thrid party connector to interopate with. I assume this will change with Esprima entering into the dance and 
opening ECMASCRIPT to the world. 

I create this project having in fact not many time to involve in it however I think I am not the only one have 
this in mind and have done a piece of this puzzle with the knowledge on board like others did I mean http://spy-js.com/
I would like to thanks specialy esprima, esmorph and escodegen (あらがとうごさいますコステラタイオンさん！）authors.

I created a github but it's a pain to update this and from netbeans, so I gave up and send this by mail.
Please feel free to integrate.

Greetings from france, 

Cheers
             luluboy

 
My issues is now to make esmorph working with node the git version of esprima is incompatible and I dunno how to generate
the package to make nodejs happy (node:true missing somehow..). The current esprima node 1.0.4 provided with npm crashes as well.
I tried with 1.1.0dev too same problem. If someone has an idea...