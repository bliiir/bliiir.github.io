**Music Journal**  
Rasmus Groth,  
Utterslev, Denmark,   
20180428

# Music theory

Taking the Music [Theory for Electronic Music](https://www.udemy.com/music-theory-for-electronic-music-complete-parts-1-2-3/learn/v4/overview) course on Udemy. I am trying to work through the material with all the stuff I am learning including coding in such a way that I have a kind of first hand understanding of it rather than have just listened to the lecture as I find that despite thinking I understand the lecture, I never really do unless I resolve all the little "what about ..." myself. In this case I discovered the nature of the Temperate vs Just Intonation tuning systems and also the ratios between the notes in the minor and major scale.

This way of studying is incredibly slow, but I am not studying to get a degree or certificate, but simply to understand more about the subject. I am also not publishing these notes because the material isn't out there already, but more as an exercise in writing about topics that interest me so that I might at some point be able to produce material that is helpful for others like all the many many resources I have been so lucky to have available to me.

Right, lets get to it

## Octaves
Octaves are distinguished by *one* wavelength of the root note coinciding with *two* wavelengths of the octave.

> That's: 1:2

The frequency of the root node being half that of its octave. The octave is also the note with which the scale "starts over". This is if course just a made up concept. The fact that we think c4 sounds like c5 is simply due to the 1:2 relationship. They are not *really* the same note.

This image shows the root node (c4, or middle c) as green and the octave note (c5 or the c higher than middle c) as reed
![image](https://www.dropbox.com/s/9hh3uv0p9fnq37u/Screenshot%202018-04-28%2018.15.01_merge.png?raw=1)

## Fifth

### Perfect fifth
Perfect fifths are distinguished by *two* root node wavelengths co-insiding with *three* octave wavelengths. Like this:
![image](https://www.dropbox.com/s/q18c87ljc957e1s/https://www.dropbox.com/s/q18c87ljc957e1s/Screenshot%202018-04-28%2018.59.37_merge.png?dl=1)

> That's: 2:3

When run through the oscilloscope at the same time it looks like this:

![image](https://www.dropbox.com/s/arrsa2ihi94pl7c/Screenshot%202018-04-29%2014.09.10.png?raw=1). There is a clear patter, but if you look close, you can see that it changes over the entire series I've plotted. That is because normal western instruments are tuned using the [equal temperatement](https://en.wikipedia.org/wiki/Equal_temperament) method which compromises ther relationship between the weavelengths of the notes in the scale in order to simplify the instruments rather than the [Just Intonation system](https://en.wikipedia.org/wiki/Just_intonation) method.

### Diminished fifth
If you are in a major scale and you want to play a harmony of the 7th note in the scale, the perfect fifth will be the sharp of the 4th note and outside the scale.

Example:
![image](https://www.dropbox.com/s/7z82oshdsdjkudv/Screenshot%202018-04-28%2022.16.35.png?raw=1)

We are looking at a C major scale with the root + fifth harmonies along the scale. Notice the 7th step (B) has the fifth (F#) outside the scale.

To play inside the scale, we need to move the fifth one half tone down - or diminish it. Like this:

![image](https://www.dropbox.com/s/qrk334eyjw078mu/Screenshot%202018-04-28%2022.19.10.png?raw=1)

The F# in the 7th step of the scale is now an F and no longer a perfect fifth, but now within the C major scale

Using a Diminished fifth does screw with the cyclicality of the waves. Take a look at this image:

![image](https://www.dropbox.com/s/e8xjh0gvqgq1tar/Screenshot%202018-04-29%2012.58.00_merge.png?dl=1)

As mentioned above, the root(green) and the perfect fifth(red) have a 2:3 wavelength relationship. The root and the diminished fifth do not have that kind of relationship - in fact, it is hard to spot a precise cyclicality at all. There is one close to 5:7, but it isn't a true relationship.

Here is a graph of both notes run through the oscilloscope:

![image](https://www.dropbox.com/s/uza98zxjv0pktvi/Screenshot%202018-04-29%2014.08.21.png?raw=1)

Again - there are clearly patterns, but not as simple ones as the perfect fifth.

## Third
This one is a bit more tricky because the third has a lot to do with what kind of scale we are in.

<figure>
  <img src="https://www.dropbox.com/s/i0bf9glym752ve4/Screenshot%202018-04-28%2022.40.45.png?dl=1" alt="my alt text"/>
  <figcaption>The C major scale is on the left and the C minor scale on the right</figcaption>
</figure>

#### Major third
In a major scale the sequence is ```2, 2, 1, 2, 2, 2, 1```, where 2 signifies two half steps or a whole step, and 1 signifies a half step. Another way to remember it is ```W W h W W W h``` where ```W``` signifies a whole step and ```h``` signifies a half step.

In this case, the third is an E as can be seed from the figure above.

It takes *four* wavelengths of the root tone and *five* of the third for a repeateable cycle to complete - and it looks like that isn't a completely precise relationship either. That is because the major and minor scales use a compromise called [equal temperatement](https://en.wikipedia.org/wiki/Equal_temperament) to simplify the relationships between notes so as to be able to create an instrument such as a piano. In the [Just Intonation system](https://en.wikipedia.org/wiki/Just_intonation), the cycles fit perfectly together,

![image](https://www.dropbox.com/s/vhlk0jc35856kr7/Screenshot%202018-04-29%2012.34.57_merge.png?raw=1)

> That's: 4:5

#### Minor third
In a minor scale, the sequence of steps is ```2, 1, 2, 2, 1, 2, 2```. Another way to remember it is ```W h W W h W W```

In this case the third is a D# as can be seen from the figure above.

Here is a [link](https://www.dropbox.com/s/3mudnk4ltjszrao/20180428_major_minor.mp3?dl=0) to an audio clip of the two scales

There seems to be no real regularity about the cyclical harmony as can be seen from this image showing the root C in green and the minor third D# in red.

![image](https://www.dropbox.com/s/2wi8t295jbp7mt3/Screenshot%202018-04-29%2013.54.04_merge.png?raw=1).

However, when I put the two notes at the same time through the oscilloscope, I get this pattern:

![image](https://www.dropbox.com/s/tz7mj3mf8ea7wt5/Screenshot%202018-04-29%2013.55.06.png?raw=1) which does show a clear pattern, but while it looks like the patterns repeats every 5.x root note wavelenghts, it still has some irregularities.

I guess this is why we feel it has a darker feel than a minor third.

Here is a screenshot of the oscilloscope rendering 300, 500, 800, 1300 Hz:

![image](https://www.dropbox.com/s/bpp8x55xgf71pab/Screenshot%202018-04-29%2017.50.24.png?raw=1)

![image](https://www.dropbox.com/s/3s054gac0d2zxv8/Screenshot%202018-04-29%2017.52.26.png?raw=1)
It is clear that there is perfect periodic regularity between all the notes

---

## Chords

Here is an image of major chords with perfect fifths with each note in the C major scale as the root with all the notes as reference on the left and right.

![image](https://www.dropbox.com/s/53nugxsxuanqbln/Screenshot%202018-04-29%2018.03.15.png?raw=1)

If we [play the chords](https://www.dropbox.com/s/09na3p0ziop5tju/20180428_c_major_scale_chords.mp3?dl=0) it sounds pretty awful. That is because several of the notes in those chords are not in the C major scale.

| # | Chord     | Scale compliance |
| :--- | :--- | :--- |
| 1 | C major | OK |
| 2 | D major | 3rd, F#, is outside the scale |
| 3 | E major | 3rd, G#, is outside the scale |
| 4 | F major | OK |
| 5 | G major | OK |
| 6 | A major | 3rd, C#, is outside the scale |
| 7 | B major | 3rd, D# and 5th, D#, are both outside the scale |
| 8 | C major | OK |

We can fix that by moving the thirds down to be minor thirds and fifths down to be diminished fifths. Lets try it:

![image](https://www.dropbox.com/s/wtj8d8mnsk8hq72/Screenshot%202018-04-29%2018.18.30.png?raw=1).

| # | Chord     | Scale compliance |
| :--- | :--- | :--- |
| 1 | C Major | OK |
| 2 | D minor | OK |
| 3 | E minor | OK |
| 4 | F Major | OK |
| 5 | G Major | OK |
| 6 | A minor | OK |
| 7 | B minor, dim 5 | OK |
| 8 | C Major | OK |

Also [sounds](https://www.dropbox.com/s/gpemtno9yxf05nn/20180428_c_major_scale_chords_fixed.mp3?dl=0) better.

## Seventh
Ok, cool - now lets add the 7th to the mix and see how that fares. Lets start out by naively making a C major 7th and then copying it out with each note of the C Major scale as the root of each chord. Looks like this.

![image](https://www.dropbox.com/s/2zrjf7a34e9eqkb/Screenshot%202018-04-29%2018.33.40.png?raw=1)

Again, we can see that a lot of the notes are on the dark stripes indicating the black keys on the piano.

| # | Chord     | Scale compliance |
| :--- | :--- | :--- |
| 1 | C major | OK |
| 2 | D major | 3rd, F# and 7th C#, are outside the scale |
| 3 | E major | 3rd, G# and 7th D#, are outside the scale |
| 4 | F major | OK |
| 5 | G major | 7th, F# is outside the scale |
| 6 | A major | 3rd, C# and G#, are outside the scale |
| 7 | B major | 3rd, D# 5th, D# and 7th A#, are all outside the scale |
| 8 | C major | OK |

Also [sounds really intense](https://www.dropbox.com/s/d8qv1r2gvc7gx13/20180428_c_major_scale_chords_7th.mp3?dl=0).Lets fix that - just like before, we move the 3rd's and 5th's down and now also the 7th's.

Looks like this:

![image](https://www.dropbox.com/s/a4if1txocprfvmy/Screenshot%202018-04-29%2018.41.58.png?raw=1)

| # | Chord     | Scale compliance |
| :--- | :--- | :--- |
| 1 | C Major, 7 | OK |
| 2 | D minor, dim7 | OK |
| 3 | E minor, dim7 | OK |
| 4 | F Major | OK |
| 5 | G Major, dim 7 | OK |
| 6 | A minor, dim 7 | OK |
| 7 | B minor, dim 5, dim 7 | OK |
| 8 | C Major | OK |

Cool - now we can make a chart of all the chords in all the scales (I am conveniently going to avoid talking about the 9th etc for now)

| Major scale | minor scale | Chord | 3rd | 5th | 7th |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 |   | Major | - | - | - |
| | | | | | |
| | | | | | |
| 2 |   | minor | dim | - | dim |
| | | | | | |
| | | | | | |
| 3 |   | minor | dim | - | dim |
| | | | | | |
| 4 |   | Major | - | - | - |
| | | | | | |
| | | | | | |
| 5 |   | Major | - | - | dim |
| | | | | | |
| | | | | | |
| 6 | 1 | minor | dim | _ | dim |
| | | | | | |
| | | | | | |
| 7 | 2 | minor | dim | dim | dim |
| | | | | | |
| 8 | 3 | Major | - | - | - |
| | | | | | |
| | | | | | |
|   | 4 | Major | - | - | - |
| | | | | | |
| | | | | | |
|   | 5 | minor | dim | - | dim |
| | | | | | |
|   | 6 | minor | dim | - | dim |
| | | | | | |
| | | | | | |
|   | 7 | Major | - | - | - |
| | | | | | |
| | | | | | |
|   | 8 | Major | - | - | dim |

I was going to make a table with all the root notes, but thought better of it. I will not remember anyway, so better to move on or actually make some music...
