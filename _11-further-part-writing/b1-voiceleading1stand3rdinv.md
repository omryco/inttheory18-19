---
layout: chapter
title: Lesson 11b - Voice-leading for First and Third Inversion Chords
abc: true
---

First-inversion and third-inversion chords are used to make smoother, more melodic bass lines, but in doing so, we put tendency tones -- and all of the accompanying expectations -- into the bass. Even though this seems more restrictive, first- and third- inversion chords actually allow more freedom in part-writing because:
- they remove the potential objectionable parallels that come from having the root in the bass.
- the upper voices have one less tendency tone to distribute and resolve correctly.

## Resolving tendency tones

Use the voicing and voice-leading guidelines discussed in the previous topic to harmonize the following progressions as a four-part chorale. Assuming that the progression follows the circle-of-fifths, what inversion should follow a first-inversion chord? What about the chord following a third-inversion? As always, make note of any difficulties that you encounter for the class discussion.

{% capture ex1 %}X:1
T:First- and third-inversion chords
T:in circle-of-fifths progressions
M:3/4
L:1/4
Q:1/4=70
K:C
V:1
[cE]xx| [cE]xx|| [cE]xx|]
V:2 clef=bass
[C,G,] [B,,] [C,]| [C,G,] [B,,] [C,]| [C,G,] [F,] [E,]|]
w:C:I V6 I I V6/5 I I V4/2 I6{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

### Conclusions

With first and third inversion chords, we place either the chordal third or chordal seventh in the bass. Both of these chord tones are tendency tones, especially when part of circle-of-fifths progression--chordal thirds like to resolve up by step and chordal seventh should resolve down by step. 

For first-inversion triads and seventh chords, the bass note should resolve up by step to the root of the following chord, meaning that the chord following a first-inversion chord will likely be in root position assuming that the progression follows the circle of fifths. For third-inversion seventh chords (there are no third-inversion triads), the chordal seventh in the bass should resolve down by step, and if it is a circle-of-fifths progression, this means that the bass will resolve to the chordal third of the next chord making it a first-inversion chord.

Of course, these guidelines assume that we are harmonizing circle-of-fifths progressions. If you do not have roots that are separated by P4/P5, you will need further guidelines which functional substitutions can be used to explain.

## Function over form (Part 2)

When harmonizing the the root-position deceptive progression from the previous topic, we discussed that you should treat the vi chord in a deceptive progression as a *functional substitute* for tonic. Because the vi chord acts as a replacement for a I chord, we double the scale degree that works best for a I chord, `do`, rather than the standard doubling of the root, `la` or fifth, `mi`. In the deceptive progression, it is correct to break standard convention and double the chordal third of the vi chord. Now that we are looking at first inversion voice-leading, we have another *functional substitution* to discuss.
- vii<sup>o</sup> is a dominant function, so therefore functions as V<sup>7</sup> chord without its root

Because of this, the vii<sup>o</sup> chord must follow different *doubling* rules in order to avoid poor voice-leading. With this in mind, try to harmonize the following progressions; first a simple I-V<sup>6/5</sup>-I progression, and then with an added root-position vii<sup>o</sup> chord. You will discover that:
- the two chords have all but one pitch in common.
- resolving a root-position vii<sup>o</sup> is extremely difficult and will require one voice to make consecutive jumps of a P5 to avoid issues due to tendency tone resolutions.**

{% capture ex2 %}X:2
T:Voicing a viio using functional substitution
M:4/4
L:1/4
Q:1/4=70
K:C
V:1
[cE] xx2|| [cE] xxx|]
V:2 clef=bass
[C,G,] [B,,] [C,2]|| [C,G,] [B,,] [B,,] [C,]|]
w:C:I V6/5 I I viio V6/5 I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

Because the root position vii<sup>o</sup> triad is so difficult, it is rarely used. It is not possible to resolve a root-position vii<sup>o</sup> triad to a I chord without creating at least one unacceptable part-writing error. A root-position vii<sup>o</sup> must either pass through another chord or be inverted to resolve directly to I.

As a general rule of thumb, any diminished chord (including the ii<sup>o</sup> in minor) will typically need to have the chordal third doubled, because the tension of the diminished fifth and its tendency tones.

## Function over form (Part 3)

The pre-dominant function presents an issue that the functional substitutions in tonic and dominant functions do not. To this point, we have considered the circle-of-fifths as the voice-leading foundation for diatonic harmony. In this case, the ii chord would be the "primary" pre-dominant function, and in many ways, this is true. The IV chord, however, holds a special place in harmony because of its role as the *subdominant* -- the opposite pole of the dominant -- as well as the high frequency throughout history of the I-IV-V-I progression.

Generally speaking, root position ii chords and root position IV chords are equally strong and follow standard doubling conventions. When the ii chord is in first inversion, however, it becomes a functional substitution for a root-position IV chord. This means that a ii<sup>6</sup> chord most often takes its doubling from a root-position IV chord. (In the same way that a vii<sup>o</sup> chord takes its doubling from a V<sup>7</sup> chord.) Try this on the following progressions. (Make sure to consider the common direction and motion for upper voices tend to do when a root position IV chord moves to a V chord.)

{% capture ex3 %}X:3
T:Using functional substitutions for pre-dominants
M:4/4
L:1/4
Q:1/4=70
K:C
V:1
[cE]xxx| [cE]xxx|| [cE]xxx|]
V:2 clef=bass
[C,G,] [F,,] [G,,] [C,]| [C,G,] [F,,] [G,,] [C,]| [C,G,] [F,,] [G,,] [C,]|]
w:C:I IV V I I ii6 V I I ii6/5 V I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

## Passing chords

When a chord is inserted between two other chords to create a bass line with stepwise motion, we call this a *passing chord*. To this point, when we have discussed a chord's function we have only discussed tonic, dominant, and pre-dominant. We now add *passing* to that list. You can consider *passing* a function that replaces a chord's standard function (i.e. tonic, dominant, and predominant), and instead extends the function of the chords on either side. Harmonize the following progression that uses the IV<sup>6</sup> as a passing function. What does this say about the function of the IV chord--is it still a pre-dominant? Does it change the function of the first V chord?

{% capture ex4 %}X:4
T:Passing chords
M:3/4
L:1/4
Q:1/4=60
K:C
V:1
[dG]xx|]
V:2 clef=bass
[B,,B,][A,,][G,,]|]
w:C:V6 IV6 V{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

## Conclusions

Your first thought about this progression is probably along the line of "V doesn't go to IV." And you would be right, because V to IV would technically be a *re*gression, not a *pro*gression. (We will discuss this more in the next topic on second-inversion passing chords.) However, in this case, the IV chord is not functioning as a pre-dominant chord; instead it connects the two inversions of the V chord with the smooth voice-leading that comes from passing motion. A listener will hear this progression as an extension of the dominant color, not as an alternating dominant - pre-dominant - dominant pattern. Any inversion of a chord can be classified as a passing chord as long as it creates stepwise motion in the bass voice, and many first- and third-inversion chords consistently function this way. 

In the example above, this passing IV<sup>6</sup> chord allows the composer enough space to fix a voicing error on the V<sup>6</sup> chord. You hopefully noticed that the V<sup>6</sup> chord has a doubled third, and if it were to resolve directly to a I chord, it would create parallel octaves. So the IV<sup>6</sup> chord bridges the gap between the two inversions of the V chord, allowing the V<sup>6</sup> to fix its doubling issue before resolving to a tonic chord.