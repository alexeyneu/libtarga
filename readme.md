## example
```C++
	BYTE *trr;
	unsigned char* targaimage;
	int wdt=512, hgt=512;
	trr = (unsigned char*)tga_load("161208ap5410_fpx.tga", &wdt, &hgt, TGA_TRUECOLOR_32);
```
produce block of RGBA bytes