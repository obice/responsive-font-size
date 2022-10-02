<h1 align="center">Responsive Font Size </h1>
<p align="center">Control font size at a specific breakpoink.</p>


<p align="center">
<a href="https://www.npmjs.com/package/responsive-font-size"><img src="https://badge.fury.io/js/responsive-font-size.svg" alt="Version Status"></a>
<a href="https://www.npmjs.com/package/responsive-font-size"><img src="https://img.shields.io/npm/dt/responsive-font-size.svg" alt="Downloads"></a>
<a href="https://www.npmjs.com/package/responsive-font-size"><img src="https://img.shields.io/npm/l/responsive-font-size.svg" alt="License"></a>
</p>

------

__Install using npm__
```
npm i responsive-font-size
```

__Default sizes__
```
text-xs: .75rem;
text-sm: .875rem;
text-tiny: .875rem;
text-base: 1rem;
text-lg: 1.125rem;
text-xl: 1.25rem;
text-2xl: 1.5rem;
text-3xl: 1.875rem;
text-4xl: 2.25rem;
text-5xl: 3rem;
text-6xl: 4rem;
text-7xl: 5rem;
```

__Responsive__
Add size prefix before the class name {screen}:{size}

`Breakpoints/screen`
```
sm, md, lg, xl
```

__Usage example__
```
<p class="text-base sm:text-sm md:text-base lg:text-xl xl:text3xl">Hey there!</p>
```

__Customizing font size and breakpoints__
Edit the variable.scss file to change the default font size and breakpoint values, located inside the src folder and run the command below to rebuild.
```
npm rfs-build
```


------

Made with <span style="color:red">♥</span> by __[Obicerj](https://twitter.com/Obicerj)__
