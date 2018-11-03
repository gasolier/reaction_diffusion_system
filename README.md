# Reaction-Diffusion System (Gray-Scott Model)
This simulation was written in Haxe using the Kha framework before being exported to HTML5. If you would like to know more about the simulation please go to Karl Sim's [excellent tutorial and writeup](https://www.karlsims.com/rd.html) or visit the  Wikipedia page on [reaction-diffusion systems](https://en.wikipedia.org/wiki/Reaction-diffusion_system).

# The Slightly Technical Stuff (The Tools)
As mentioned above, this simulation was written in [Haxe](https://haxe.org/) an "open source toolkit based on a modern high level strictly typed programming language, a state-of-the-art light-speed cross-compiler, a complete cross-platform standard library, and ways to access to each platform's native capabilities". In order to provide the framework for the simulation I used the [Kha](http://kha.tech/) framework which is a low-level SDL implementation that through Haxe is able to be compiled to a slew of different platforms. In this case I decided to use HTML5 because the web is a wonderful platform. The other upside of targeting the web was that it allowed me to use Haxe as the backend of the simulation - where I ran the actual simulation that is - and use regular HTML and JS to easily build a UI.
