The given codes are implemented in python v3.6

| RegEx expression| Illustration |
| ------------- | ------------- |
.*H.\*H.\*  | aHbHc <br> abHcdHef
(DI\|NS\|TH\|OM)*  | DI <br> NS <br> TH <br> OM <br> DINS <br> DINSTHOM <br> THOMOMTHDIDI
F.\*[AO].\*[AO].* | FaABAv <br> FaOBOv
(O\|RHH\|MM)* | O <br> RHH <br> MM <br> ORHH <br> ORHHMM
.* | *blank* <br> AB <br> AAAAAAAA
C\*MC(CCC\|MM)\* | MC <br> CMC <br> CMCCCC <br> CMCMM
[^C]\*[^R]\*III.* | RCIII <br> crIII <br> RRCCIII
(...?)\1* | AB <br> ABAB <br> ABC <br> ABCABC
([^X]\|XCC)* | x <br> XCC 
(RR\|HHH)*.? | RR <br> HHH <br> RRHHH <br> HHHHHHRR <br> RRA
N.*X.X.X.*E | NaaaaaXAXAXaaaaE
R*D*M* | blank <br> R <br> RDM
.(C\|HH)* | ACCCCHHHHHH
.*G.*V.*H.* | aaaaaGaaaaaVaaaaaHaaa
[CR]* | C <br> R <br> CCR <br> CRRC
