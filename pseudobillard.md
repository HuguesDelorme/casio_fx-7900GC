Mcl:.3🡪R:Lbl 0:Range 0,1,1,0,.65,1:Plot 0,.65:Plot 1,.65:Line:Plot 1,0:Line:Ran#(.6)🡪F:F<.08⇒Goto 0:F+R🡪G:Plot F,F:Plot G,F:Line:Plot ◢
-X+Y🡪P:Y>X−.35⇒Goto 1:Plot 1,1+P:Line:X+Y🡪A:Plot A−.65,.65:Line:1.3−A🡪B:F−B🡪X:Plot X,F:Line:X⩾F⇒X⩽G⇒Goto 2:X<F⇒Plot 0,B:X>G⇒Plot -B,0:Line◢
Goto 3↵
Lbl 1:Plot .65−P,.65:Line:Plot 1,.3−P:Line:F+.7+P🡪X:Plot X,F:Line:X⩾F⇒X⩽G⇒Goto 2:Plot .7+P,0:Line◢
Goto 3:Lbl 2◢
"GAGNE":5+S🡪S◢
R−.05🡪R:R<.1⇒.1🡪R:Goto 0:Lbl 3:"PERDU":S−5🡪S◢
Goto 0
