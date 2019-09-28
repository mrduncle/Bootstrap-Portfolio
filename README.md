# Bootstrap-Portfolio

Web page showing profile, portfolio and contact pages of Duncan Campbell

Spent too much time getting the look of the pages right in full screen without fully realising the implications of shrinking the screen. 
As a result I chose margin/paddings on one column that were not repeated (or symmetrical) in order to make spacings correct in the small
screen view. For example I could make the separation between two successive rows look right by having the bottom padding or margin a 
certain size without applying that same bottom padding or margin to the second column. This was due to the row container for the two 
columns. If I had applied the same bottom padding or margin to the second column, when shrinking to the small screen (and in a manner 
"breaking" the row container), the two columns on the same row now become two separate rows with a gap between them.

The same argument applies for the left hand padding or margin for the two columns when in full screen where they must have the same 
overall left side effect so that when they go to small screen, they align to the left hand side instead of having an offset.

Next time, do small chunk of css/bootstrap satisfactorily in big screen until it works....then test the small screen vesrion straight 
away, then move onto the next chunk of css.