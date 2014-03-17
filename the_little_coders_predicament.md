# The Little Coder's Predicament (En español)

<!-- NOTA: la forma que me resulta útil para traducir es
usar estos comentarios HTML para enmarcar el párrafo en inglés y
luego escribir el texto en español abajo.

Al final de esta primer parte del texto hay un ejemplo de esto -->


> Esta es una traducción del texto  [The Little Coder's Predicament](http://viewsourcecode.org/why/hacking/theLittleCodersPredicament.html) escrito por **why The Lucky Stiff**, un artista admirable a quien  extrañamos mucho...

<!-- Okay, then, children of the modern age (where we live in a world so tied together with wires that Pangaea ain't goin' nowhere!), you tell me if this is a predicament or not.-->

Veamos entonces, niño de la era moderna (!en la que vivimos en un mundo tan interconectado de cables que Pangaea no se irá a ningún lado!), decime vos si esto es un dilema o no.

<!-- In the 1980s, you could look up from your Commodore 64, hours after purchasing it, with a glossy feeling of empowerment, achieved by the pattern of notes spewing from the speaker grille in an endless loop. You were part of the movement to help machines sing! You were a programmer! The Atari 800 people had BASIC. They know what I'm talking about. And the TI-994A guys don't need to say a word, because the TI could say it for them!-->
En 1980, podías levantar la vista de tu [Commodore 64](https://es.wikipedia.org/wiki/Commodore_64), horas después  de haberla comprado, con una brillante sensación de poder lograda por la secuencia de notas musicales escupidads desde el speaker en bucle infinito ¡Eras parte del movimiento para ayudar a las máqunas a cantar! ¡Eras un programador! Gente. La [Atari 800](https://es.wikipedia.org/wiki/Atari_800) tenía BASIC. Hay perosnas que saben de que estoy hablando. Y la [TI-99/4A](https://es.wikipedia.org/wiki/Texas_Instruments_TI-99/4A), amigos, no es necesario decir ni una palabra de  la TI ¡Porque podía decirla por si misma!
<!-- The old machines don't compare to the desktops of today, or to the consoles of today. But, sadly, current versions of Windows have no immediately accessible programming languages. And what's a kid going to do with Visual Basic? Build a modal dialog? Forget coding for XBox. Requires registration in the XBox Developer Program. Otherwise, you gotta crack the sucker open. GameCube? GameBoy? Playstation 2?
-->
Las computadoras antiguas ni se comparan a las de hoy,tampoco las consolas. Pero, lamentablemente, las versiones actuales de Windows no tienen lenguajes de programación inmediatamente accesibles. Y además, ¿que puede llegar a hacer un chico con Visual Basic?, ¿crear un dialogo Modal?. Olvidemos codear para XBox, porque requiere una registración en el programa de desarrollo de XBox. Es mas, tenés que descifrar absolutamente todo. ¿GameCube? ¿GameBoy? ¿Playstation 2?


## Coding Just Isn't Accessible

Yes, there are burgeoning free SDKs for many of these platforms. But they are obscure and most children have no means of actually deploying or executing the code on their own hardware! This is obvious to us all and likely doesn't seem such a big deal. But ask yourself what might have happened had you not had access to a programming language on an Atari 800 or a Commodore. You tell me if this is a predicament.

It turns out, most of the kids in my neighborhood are exposed to coding through the TI calculator. A handful of languages are available on the TI and its processor is interesting enough to evoke some curiousity. But this hasn't spread to its PDA big brothers, where young people could have more exposure to programming. And undoubtedly the utility of a language on the Palm, Pocket PC and others would be useful to many.

So what's the problem here? We have no shortage of new languages, but they become increasingly distanced from the populace. Are the companies behind these platforms weary of placing the power of a programming language in the hands of users? Is there not a demand any longer? It's got to be some kind of greed, power, money thing, right?

Perhaps this is just another reason to push Linux and BSD on consumer systems. Still, are scripting languages easily accessible to beginners on those systems? OSX has made several scripting languages available (including Ruby and Python), but most users are unaware of their presence.

I should mention that Windows is equipped with its own scripting host for developing in JScript and VBScript. But the use of the scripting host is (I believe) under-documented and limited for beginners. Try doing something useful in a script without using Server.CreateObject. Let's not let kids touch the COM objects, please!


## The Christmas List

I'm thinking a toy language for consoles and desktops alike could be monumental. I'm ot saying it needs to be cross-platform. A language for GameCube that took advantage of platform-specific features could be more appealing to GameCube users than a language that used a reduced featureset, but could execute on a handheld. Really, we live in a world where both choices should be available.

As for essential features:


#### 1. Transportable code.

On my TI-994A, I could make a little, animated Optimus Prime from pixels. Insert cassette. Record. Pass around to friends. Receive high fives from friends. Put on wraparound shades. Thank you, TI! Thank you, Optimus Prime!

A little language for the consoles could be wildly popular if combined with the good ature of sharing code. This could be done by trading memory cards, but would be more effective if code could be easily obtained and posted on the Web. Learning would accelerate and collaborative development could take place.

A suitable language should give coders access to I/O devices, to allow experimentation with network devices and the ability to enhance one's connectivity with others. For the consoles, games could provide hooks for user mods. This has long proven a successful staple of the desktop gaming world.


#### 2. Simplicity.

You've got to be able to write a single line of code and see a result. We need some instant results to give absolute beginners confidence. Simple methods for sending an e-mail, reading a web page, playing music. Demonstrable in a one-liner.

Admittedly, as our systems have grown complex, it is difficult to balance simplicity and capability. Most users will be unimpressed by code that emits beeps and bloops from a PlayStation 2. If Ruby were available on the PS2, then I would hope that I could hear rich symphonic sounds from a wee bit of code.

Orchestra.play( "A:2", "C:4", "E:1", "G:1" )

Access to the graphic engine might require more complex code. But simple drawing methods could be provided for beginners. Or images could be stored alongside code and accessed programmatically.

ImageLibrary.load( "GolfingOldMan" ).drawAt( 12, 10 )

The trick would be to uncover what small applications might entice novices and still provide the ability to write large applications that would drive developers to master the language and not limit their growth.


#### 3. Sensible environment.

Considering that many won't want to purchase a keyboard for their gaming unit, let's make sure that a reasonable environment is provided for entry of text. Controllers could be worked like the Twiddler. Or code could be transferred via IR, TCP/IP. (Dare I say cassette? :D)


#### 4. Give it away!

It used to be that programming was practically an inalienable right for users. Include a language with the system, situated in a friendly spot. Each of the game consoles I've mentioned has launchers. (With the exception of Game Boy and its successors.) Provide a development prompt from the launcher. From desktop software, provide shortcuts for both the command prompt and a development prompt.


Remember, we're looking for a language that requires no system hacks. No obscure links. No warranty violation. We've become so used to these techniques that it seems to be an essential part of getting our way.

And in many ways it is essential. Tinkering with hardware is learning. Lobotomizing and renovating is meaningful, magical. On behalf of those who prefer to code, I make these wishes. Not to take away jobs from the Phillips screwdriver.


## The Ultimatum

My challenge is to Sony, Nintendo, Microsoft, Apple, and to those who manufacture and develop our interactive technology. Let us interact with these machines more deeply. Provide us a channel for having a dialogue with the entertainment boxes we nurture and care for. I swear to you, the relationship between the public and your product will assuredly blossom. That box will become more of a chest for our personal works.

In addition, if your developers start putting out crap, then you have a whole world of people to pick up the slack.

My challenge is for you to bundle a useful programming language with your product. Ruby, Squeak, REBOL, Python. Take your pick. It will be inexpensive to add any of these languages to your systems. And people will seriously pray to you. You know how geeks get when they pledge allegiance to something. But, yes, Ruby is preferable.


> Escrito por *why the lucky stiff*, el 10 junio del 2003.
