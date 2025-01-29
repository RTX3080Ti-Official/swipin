## Devlog #1

First devlog! Please read [swipin/devlogs README](../README.MD) to know what I will put in my devlogs and what it is!

## State of the app

The app has really evolved from just a video player, I managed to put text on a video player (using RelativeLayout), now, things are still not there/broken.

![image1](/image1.png)

As you can see in the image, it's very broken, there a gap at the bottom (from a stupid video control thing that is just here for some reasons)

## Problems/Compiler errors

For some reasons, this code:

```
videoview1.setOnClickListener(new View.OnClickListener() {
	@Override
	public void onClick(View _view) {
		if (videoPaused == 1) {

			videoPaused = 0;

			videoview1.start();

		} else {

			videoPaused = 1;

			videoview1.pause();

		}
	}
});
```
does not work.

It should pause the video when you click on it (just like TikTok).
But well, it dosen't work.

Also, first pre-release version is coming out on **February 17th**! So get your calendars, and mark that date!
