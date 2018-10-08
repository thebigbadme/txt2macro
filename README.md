# txt2macro
translate Strings of text into macro sequences for your Corsair Scimitar mouse

Although the products offered by Corsair have a decidedly "gaming" bent,
having use of 12 macro buttons is particularly useful under alternative contexts.
In particular, much the way code-completion speeds up the process of coding,
some aspects of coding can be sped up further by use of hot-keyed insertion of code.

Using the "ckb-next" utility allows for all manner of customization, however, sequences
of characters must be format in a slightly cumbersome manner.
Example: NetBeans allows use of the string "psvm" to be used in defining a main method
under Java. In order to execute this sequence from one of the macro buttons requires
the string to be put together as "+p,-p,+s,-s,+v,-v,+m,-m,+enter,-enter"
In order to streamline the process of converting an ordinary string into such a format,
I whipped up this little bit of java code, in hopes that others may also find use.
