#Modular Scale

Modular Scale is a Stylus-based mixin that calculates the incremental values of the modular scale in proportion to a set size and ratio. It was inspired by and adapted from Tim Brown's [modularscale.com](modularscale.com), Scott Kellum's [sassy modular scale](https://github.com/Team-Sass/modular-scale), and Cory Simmons's [Jeet](https://github.com/CorySimmons/jeet). I think it's valuable enought to be a seperate module.

## Usage

1. Set the value of `modular-scale` to one of the following ratios:
	````
	double_octave
	major_twelfth
	major_eleventh
	major_tenth
	octave
	major_seventh
	minor_seventh
	major_sixth
	minor_sixth
	fifth
	augmented_fourth
	fourth
	major_third
	minor_third
	major_second
	minor_second
	````
	`modular_scale = golden`

2. Use the `ms()` function to get a value in pixels:

	````
	height: ms(0) // 16.618px
	````

3. use the `msem()` function to get a value in ems

	````
	height: msem(0) //1.03em
	````
