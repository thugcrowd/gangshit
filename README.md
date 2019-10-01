# gangshit

![Gangshit](https://pbs.twimg.com/media/Dce__UgVAAAAoFy.jpg)

This is a collection of figlet fonts based on graffiti handstyles by a number of artists. 

You can test these [here](http://patorjk.com/figlet-editor/#/edit) by selecting "Import" and pasting the contents of any of these files into the test box. 

Currently, gangshit1 only supports uppercase, and gangshit2 supports both upper and lower case. These are both test fonts I made using generic hand styles. More to come soon!

## Adding To Existing Figlet Frameworks ##

You can use these fonts just like any other figlet font.

### Pyfiglet ###

You can install pyfiglet to render figlet fonts with Python

Usually they're stored here on Linux systems
    /usr/local/lib/python2.7/dist-packages/pyfiglet/fonts

Usage:

    >>> from pyfiglet import Figlet
    >>> f = Figlet(font='gangshit1',width=200)  
    >>> print f.renderText('SUP')

                      ..
         .            do,              ...';ccc;.
        ;o'           'ld:.     ''   'co:.  .':dxl,
        ;xl.          .ox:.   .oxl. .cdloxl.    .lxx;
       .;dxo.          ;xx,   .lkx; oxo..cxo'    .oxd
     .,;codxxo,        'dkl.  .oxxc.xxd' .:xd;   .odd
    .oo. .':dxd,       .okd'  'dxxo.xxl. .:xx;..lc,
     lxo:'...,'.       .lkx,  :xxxx,:lc'  .:xdl:'
    c. ':lool:,'.      .lxx; 'dxxxxc       .cxd'
    oc.   ..,:lddc;.   .oxx;.lxxddxo.       .okl.
    dx,        .,lxd:. .oxx::xxd;:xx;        ,dx:
    cxc           'lxl.'dxxddxx; .okl.       .lkd'
    'dd'           .od'.cxxxxx:.  ;xx;        :xx:
    .:xo'           co. .':cc,    .cko.       ,dkc.
     .:xd;.        .c'             .ox:       'dxc
       'lxdc,.. .....              .cl'        ...
          ';cllc:,'.

The python figlet library by default uses a width of 80 columns, so make sure to specify the width when printing large words.

## Future Features ##
* Multiple fonts with different sizes
* Engine for combining specific characters for custom fonts using the glyphs in this collection

## Contact ##

If you want to contribute to this project, you can get at me on twitter. [@dmxinajeansuit](https://twitter.com/dmxinajeansuit)

