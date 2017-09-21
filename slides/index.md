- title : The marvels of F# type providers
- description : A dive into the world of F# type providers
- author : Alexander Mogilka
- theme : moon
- transition : default

***
## The marvels of F# type providers
<br />
Alexander Mogilka
<br />
[@alxmglk](http://www.twitter.com/alxmglk)

***
## The era of rich information spaces
<img src="images/modern-enterprise-application.png" style="background: transparent; border-style: none;"  />

<small>Most modern systems integrate with a bunch of external information sources</small>

***
## Adapters for an external data source
* hand-written static library
* generated static library
* dynamically-typed information representation

***
## The traditional bridging mechanisms are deficient
* hand-written libraries do not scale to information spaces with large metadata-size
* workflows involving code generation are clumsy and do not integrate well with explorative programming
* dynamically-typed bridging mechanisms discard the benefits of strongly-typed programming
