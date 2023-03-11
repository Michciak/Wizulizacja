    Przedstawienie rankingu brytyjskich uniwersytetów - Projekt   h1 {font-size: 34px;} h1.title {font-size: 38px;} h2 {font-size: 30px;} h3 {font-size: 24px;} h4 {font-size: 18px;} h5 {font-size: 16px;} h6 {font-size: 12px;} code {color: inherit; background-color: rgba(0, 0, 0, 0.04);} pre:not(\[class\]) { background-color: white }    code{white-space: pre-wrap;} span.smallcaps{font-variant: small-caps;} span.underline{text-decoration: underline;} div.column{display: inline-block; vertical-align: top; width: 50%;} div.hanging-indent{margin-left: 1.5em; text-indent: -1.5em;} ul.task-list{list-style: none;} code{white-space: pre;} if (window.hljs) { hljs.configure({languages: \[\]}); hljs.initHighlightingOnLoad(); if (document.readyState && document.readyState === "complete") { window.setTimeout(function() { hljs.initHighlighting(); }, 0); } } .main-container { max-width: 940px; margin-left: auto; margin-right: auto; } img { max-width:100%; } .tabbed-pane { padding-top: 12px; } .html-widget { margin-bottom: 20px; } button.code-folding-btn:focus { outline: none; } summary { display: list-item; } pre code { padding: 0; } .tabset-dropdown > .nav-tabs { display: inline-table; max-height: 500px; min-height: 44px; overflow-y: auto; border: 1px solid #ddd; border-radius: 4px; } .tabset-dropdown > .nav-tabs > li.active:before { content: ""; font-family: 'Glyphicons Halflings'; display: inline-block; padding: 10px; border-right: 1px solid #ddd; } .tabset-dropdown > .nav-tabs.nav-tabs-open > li.active:before { content: ""; border: none; } .tabset-dropdown > .nav-tabs.nav-tabs-open:before { content: ""; font-family: 'Glyphicons Halflings'; display: inline-block; padding: 10px; border-right: 1px solid #ddd; } .tabset-dropdown > .nav-tabs > li.active { display: block; } .tabset-dropdown > .nav-tabs > li > a, .tabset-dropdown > .nav-tabs > li > a:focus, .tabset-dropdown > .nav-tabs > li > a:hover { border: none; display: inline-block; border-radius: 4px; background-color: transparent; } .tabset-dropdown > .nav-tabs.nav-tabs-open > li { display: block; float: none; } .tabset-dropdown > .nav-tabs > li { display: none; }

Przedstawienie rankingu brytyjskich uniwersytetów - Projekt
===========================================================

#### Michał Koziński

#### 02-02-2022

Przedstawienie danych
---------------------

* * *

### Główny ranking

Pierwszym przedstawionym zbiorem danych pochodzących z rankingu _“The Complete University Guide”_ z 2022 roku, jest zbiór 130 Uniwerystetów z Wielkiej Brytanii, w którym zostały one zestawione ze sobą w kilku różnych kategoriach. Dane pochodzące ze strony są wynikami procentowymi uzyskanych punktów w poszczególnych kategoriach.

* * *

Wyświetlię tylko 15 pierwszych linijek i dodam poniżej przewijaną wersję dla zachowania przejrzystości dokumentu.

#### Zbiór przedstawiony jest w domyślnym sortowaniu według _całkowitego wyniku_.

var dest = document.getElementById("419c4af0-9991-4b13-839f-afc60d659ff7"); var template = document.getElementById("5afeebae-e2b0-4a92-b811-a7bc11256378"); var caption = template.content.querySelector("caption"); if(caption) { caption.style.cssText = "display:block;text-align:center;"; var newcapt = document.createElement("p"); newcapt.appendChild(caption) dest.parentNode.insertBefore(newcapt, dest.previousSibling); } var fantome = dest.attachShadow({mode: 'open'}); var templateContent = template.content; fantome.appendChild(templateContent);

University

OverallScore

EntryStandards

StudentSatisfaction

ResearchQuality

GraduateProspects

University of Oxford

100

96

NA

83

90

University of Cambridge

99

99

NA

83

90

London School of Economics and Poli…

96

85

80

84

91

University of St Andrews

95

100

86

78

80

Imperial College London

90

93

80

84

95

Durham University

89

88

80

78

85

Loughborough University

87

72

84

74

83

UCL (University College London)

85

89

79

80

85

University of Warwick

84

78

81

81

84

University of Bath

84

81

81

79

88

Lancaster University

82

69

81

79

78

University of Edinburgh

80

90

77

79

80

University of Manchester

79

79

79

79

81

University of Exeter

79

76

81

77

80

University of Southampton

78

73

81

79

80

University of Glasgow

77

95

81

77

78

University of Bristol

77

79

79

79

82

University of York

76

72

81

79

80

University of Birmingham

75

73

78

77

83

University of Leeds

75

76

79

78

80

King’s College London, University o…

75

80

77

81

85

University of East Anglia UEA

74

64

81

78

77

Heriot-Watt University

73

82

80

76

78

University of Nottingham

73

70

79

77

84

Cardiff University

73

69

79

82

83

University of Sheffield

72

72

81

79

79

University of Essex

72

56

81

76

71

University of Dundee

72

86

82

76

81

Swansea University

72

63

82

77

80

University of Strathclyde

72

95

80

76

81

University of Liverpool

72

67

81

77

78

Royal Holloway, University of Londo…

71

63

81

77

71

Harper Adams University

71

58

83

67

70

Queen’s University Belfast

71

70

79

75

83

University of Surrey

71

66

79

74

84

University of Reading

70

60

79

76

77

Newcastle University

70

69

79

77

78

University of Stirling

69

78

81

74

71

University of Aberdeen

69

87

81

74

75

University of Leicester

68

63

79

73

74

University of Sussex

67

66

78

75

71

Queen Mary University of London

67

70

77

80

79

University of the Arts London

66

66

78

78

57

Ulster University

64

61

81

73

75

Nottingham Trent University

64

58

82

65

68

University of Lincoln

63

57

83

63

70

Aston University, Birmingham

63

60

80

76

80

SOAS University of London

63

71

78

70

64

Northumbria University, Newcastle

63

66

80

68

74

University of Kent

63

60

80

74

69

Oxford Brookes University

63

55

79

67

76

Coventry University

62

55

82

67

76

University of Huddersfield

62

58

80

66

70

City, University of London

61

64

77

74

75

Bristol, University of the West of …

61

59

83

67

76

Manchester Metropolitan University

61

61

81

69

64

Arts University Bournemouth

61

69

84

58

57

Keele University

61

59

81

72

75

Aberystwyth University

61

57

86

71

63

Edge Hill University

60

62

80

56

69

St George’s, University of London

60

70

77

75

89

Brunel University London

60

57

78

67

74

Cardiff Metropolitan University

60

60

82

75

68

Goldsmiths, University of London

60

60

74

73

60

Robert Gordon University

59

72

84

59

76

Bangor University

59

57

82

75

70

Sheffield Hallam University

59

55

80

69

75

Bournemouth University

58

53

80

68

78

University of Plymouth

58

62

82

68

75

University of Chichester

57

58

83

63

66

University of Hull

57

59

81

68

72

University of Chester

56

56

82

52

66

Liverpool John Moores University

56

67

81

70

66

University of Portsmouth

56

54

81

69

69

University for the Creative Arts

56

63

81

68

53

Liverpool Hope University

55

55

82

55

58

Edinburgh Napier University

55

69

82

63

72

Glasgow Caledonian University

55

79

81

67

72

University of Roehampton

55

49

80

71

57

University of Hertfordshire

55

50

81

65

69

University of Brighton

55

53

78

71

75

Birmingham City University

54

57

80

66

70

University of Salford

54

61

80

63

70

Norwich University of the Arts

54

61

81

67

53

University of Bradford

53

59

79

74

73

Kingston University

53

56

80

68

69

University of Worcester

53

55

83

52

70

Queen Margaret University, Edinburg…

53

74

80

66

68

University of Central Lancashire

52

59

80

63

69

University of Northampton

52

51

80

52

67

University of South Wales

52

55

82

63

65

University of Sunderland

51

56

80

53

61

University of Greenwich

51

55

80

58

71

University of West London

51

55

84

48

66

Teesside University, Middlesbrough

51

55

82

64

74

University of Derby

51

56

82

52

65

Staffordshire University

50

55

83

55

64

University of Gloucestershire

50

55

81

59

62

Falmouth University

49

59

82

51

59

University of Cumbria

49

58

81

53

72

De Montfort University

48

51

79

67

68

Buckinghamshire New University

48

50

82

55

70

University of Wales Trinity Saint D…

48

65

84

60

53

University of the West of Scotland

48

64

81

59

70

Bath Spa University

48

50

79

63

60

University of Winchester

47

52

80

58

63

Middlesex University

47

50

79

65

59

London South Bank University

46

51

80

63

70

Abertay University

46

67

85

54

62

Leeds Beckett University

46

50

82

54

67

York St John University

46

52

83

51

64

St Mary’s University, Twickenham

46

50

82

50

69

University of Bolton

45

53

84

51

59

University of Westminster, London

45

57

80

68

61

Royal Agricultural University

45

55

80

35

71

Plymouth Marjon University

44

55

84

NA

67

Anglia Ruskin University

44

52

81

59

73

Canterbury Christ Church University

43

47

79

60

69

London Metropolitan University

43

46

82

61

56

Solent University (Southampton)

43

53

82

41

61

Newman University, Birmingham

42

49

84

53

60

Bishop Grosseteste University

40

50

82

49

68

University of Buckingham

40

58

83

NA

71

University of Wolverhampton

40

51

80

58

64

Leeds Trinity University

40

49

81

50

64

University of Suffolk

40

53

79

NA

74

University of East London

37

46

80

68

57

Glyndwr University, Wrexham

36

49

83

54

63

Ravensbourne University London

33

54

76

NA

70

University of Bedfordshire

30

50

79

63

66

Data source: [https://www.thecompleteuniversityguide.co.uk/league-tables/rankings](https://www.thecompleteuniversityguide.co.uk/league-tables/rankings)

* * *

Od teraz będzmy wyświetlać już tylko po 5 linijek.

### Zestawienie w różnych kategoriach.

* * *

Przedstawię teraz ranking w kilku przykładowych sortowaniach.

#### Sortowanie według poziomu _satysfakcji studentów_.

var dest = document.getElementById("033c3b3d-e0a5-490a-b440-a5bd0f4a98fc"); var template = document.getElementById("1e736924-bbdc-404a-81b1-3582788aa1cf"); var caption = template.content.querySelector("caption"); if(caption) { caption.style.cssText = "display:block;text-align:center;"; var newcapt = document.createElement("p"); newcapt.appendChild(caption) dest.parentNode.insertBefore(newcapt, dest.previousSibling); } var fantome = dest.attachShadow({mode: 'open'}); var templateContent = template.content; fantome.appendChild(templateContent);

* * *

#### Sortowanie według poziomu _perspektyw absolwentów_.

var dest = document.getElementById("8a885ccd-8b10-41b2-b3d9-fca9330ad038"); var template = document.getElementById("9b73f5dc-efd3-4b30-a0f2-4cf0fc06883d"); var caption = template.content.querySelector("caption"); if(caption) { caption.style.cssText = "display:block;text-align:center;"; var newcapt = document.createElement("p"); newcapt.appendChild(caption) dest.parentNode.insertBefore(newcapt, dest.previousSibling); } var fantome = dest.attachShadow({mode: 'open'}); var templateContent = template.content; fantome.appendChild(templateContent);

* * *

### Rankingi dla poszczególnych przedmiotów

* * *

Nazwa uniwersytetu

Całkowity wynik

Próg przyjęcia

Satysfakcja studentów

University of Cambridge

100

93

NA

University of Oxford

97

91

82

University of St Andrews

97

100

88

Imperial College London

95

88

81

UCL (University College London)

94

83

81

University of Warwick

94

84

80

* * *

##### Z tego samego źródła jesteśmy w stanie pozyskać rankingi danych uniwersytetów na poszczególnych kierunkach.

##### Do przedstawienia w projekcie wziąłem rankig dla kierunku _Computer Science_.

\\\[\\\\\[1in\]\\\]

* * *

Nazwa uniwersytetu

Całkowity wynik

Próg przyjęcia

Satysfakcja studentów

97

University of the Arts London

80

42

88

109

University of Bolton

78

50

88

66

University of Buckingham

84

65

86

13

University of Aberdeen

91

73

85

24

Loughborough University

89

67

85

41

University of Wales Trinity Saint D…

86

72

85

* * *

##### Dodatkowo do wglądu uniwersytety posortowane względem satysfakcji studentów.

##### Ponadto widać ich pozycje w rankingu ogólnym dla tego kierunku.

* * *

\\\[\\\\\[1in\]\\\]

* * *

Nazwa uniwersytetu

Całkowity wynik

Próg przyjęcia

Satysfakcja studentów

3

University of St Andrews

97

100

88

1

University of Cambridge

100

93

NA

2

University of Oxford

97

91

82

4

Imperial College London

95

88

81

9

University of Edinburgh

92

88

79

8

University of Glasgow

92

87

79

* * *

##### Tym razem ranking dla kierunku _Matematyka_ posortowany względem _Progu przyjęcia_.

##### Tutaj również widać pozycje uniwersytetów w rankingu ogólnym dla tego kierunku.

\\\[\\\\\[1in\]\\\]

\\\[\\\\\[1in\]\\\]

* * *

Druga część zbioru
------------------

Wróćmy teraz do rankingu ogólnego i poszerzmy go na podstawie rzeczy także dostępnych na stronie. Oferuje ona możliwość pobrania rankingów z poprzednich lat w formacie _csv_, z czego skorzystam do rozbudowania naszego zbioru danych.

* * *

### Wykresy pozycji

Teraz nasze dane możemy wykorzystać przykładowo do przedstawienia jakie pozycje na przestrzeni lat zajmowały konkretne uczelnie. Jako pierwszą próbkę wezmę uczelnie, które w ostatnim roku zajęły 5 najwyższych lokat w rankingu ogólnym.

![](data:image/png;base64,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JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1JFJSbiIIAoGmj9SQSEm5iSAIBJo+UkMiJeUmgiAQaPpIDYmUlJsIgkCg6SM1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)

Jak widać wykres nie jest zbyt spektakularany, a wynika to z tego, że uczelnie które wziąłem do jego wygenerowania, od lat zajmują wysokie miejsca w rankingu.

* * *

Sprawdźmy zatem uczelnie z dalszych pozycji, by zobaczyć czy w ich sytuacji wykres będzie wyglądał podobnie. Naszym zbiorem będą teraz uczelnie, które w 2021 roku zajęły odpowienio miejsca 50,51,52,53 i 54.

![](data:image/png;base64,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)

Jak widać, tym razem wykres wygląda o wiele ciekawiej, po czym możemy wnioskować, że w środku stawki walka co roku jest zaciekła.

* * *

#### Wykres satysfakcji studentów

Tym razem wykorzystajm nasze dane do zestawienia, jak wyglądała na przestrzeni lat satysfakcja studentów w trzech przykładowych uczelniach. Do naszego zestawienia wziąłem _“University of St Andrews”_, _“Loughborough University”_, a także _“University of the West of Scotland”_, które zostały wybrane losowo, a w rankingu ogólnym w 2021 roku zajmowały odpowiednio miejsca 7, 3 i 109.

![](data:image/png;base64,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m95VEeBndEZCCMePH5/pj9RtzgrNS7nRinN2SufrCc5xOS/R5lZcZOezjhL+QptbbpG9ouaxXLjslL42R+Vq/n7Wy11eca7K1c7nS3NXcaGVmLMU4U1vlirOGecz0+XCIk0iptADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAECPAAAAGSAAA8AAAAZIMADAABABgjwAAAAkAGt8/0AJte399HP9vT09YUQQtjStXPnzp1dW+b5MQEAAMDcW8gj8D2P/ub9e0fSewihr2fvo/c/2jOfDwkAAADmx8IN8D2PPtoTQtiy85HHv/Od73znO48/snNLCKHn0fv39k31swAAALDILNQA37d3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P33huglhq73Jzu3K5hc+mSxed1fzh8rmpvqsPPow8/hDEo8si9+cxyX1XFPMS7iynu6292snzt+instHHfA1EOABAMYdXUz+2BLl3XPkPvb7VcWmm599j7vGmwQ/PJOq2LTnce2TzpeuX23u6onzt3HxqAO+BgI8AMCEuF05bG8x+f0lyttZz4Mr7kmeJ/Fwv1WaVeG14vthPSFef9o9k7agK5dav6yYu9qvp72wvXe7+tZLz2U/7J8zRx3wVRLgAQCmJXld5sl2+bA4TrL8jJnWSV7u75eX97y9Ok7y4bL4IcRJVr7uRPe36HCq+ltw6agD3r2orut71wAAAACc4Ao8AAAALIAADwAAAAsgwAMAAMACCPAAAACwAAI8AAAALIAADwAAAAsgwAMAAMACCPAAAACwAAI8AAAALIAADwAAAAsgwAMAAMACCPAAAACwAAI8AAAALIAADwAAAAsgwAMAAMACCPAAAACwAAI8AAAALIAADwAAAAsgwAMAAMACCPAAAACwAAI8AAAALIAADwAAAAsgwAMAAMACCPAAAACwAAI8AAAALIAADwAAAAsgwAMAAMACCPAAAACwAAI8AAAALIAADwAAAAsgwAMAAMACCPAAAACwAAI8AAAALMD/A/0Q5jEJM7EIAAAAAElFTkSuQmCC)

Jak widać zajmowane pozycje w rankingu pokrywają się ze średnią satysfakcją studentów.

\\\[\\\\\[1in\]\\\]

### Źródła

* * *

##### Strona z rankingiem z obecnego roku i z rankingami z poprzednich lat (do pobrania):

[https://www.thecompleteuniversityguide.co.uk/league-tables/rankings](https://www.thecompleteuniversityguide.co.uk/league-tables/rankings)

* * *

##### Strony z rankingami dla poszczególnych przedmiotów:

* * *

_Computer Science_:

[https://www.thecompleteuniversityguide.co.uk/league-tables/rankings/computer-science](https://www.thecompleteuniversityguide.co.uk/league-tables/rankings/computer-science)

* * *

_Mathematics_:

[https://www.thecompleteuniversityguide.co.uk/league-tables/rankings/mathematics](https://www.thecompleteuniversityguide.co.uk/league-tables/rankings/mathematics)

* * *

// add bootstrap table styles to pandoc tables function bootstrapStylePandocTables() { $('tr.odd').parent('tbody').parent('table').addClass('table table-condensed'); } $(document).ready(function () { bootstrapStylePandocTables(); }); $(document).ready(function () { window.buildTabsets("TOC"); }); $(document).ready(function () { $('.tabset-dropdown > .nav-tabs > li').click(function () { $(this).parent().toggleClass('nav-tabs-open'); }); }); (function () { var script = document.createElement("script"); script.type = "text/javascript"; script.src = "https://mathjax.rstudio.com/latest/MathJax.js?config=TeX-AMS-MML\_HTMLorMML"; document.getElementsByTagName("head")\[0\].appendChild(script); })(); Footer © 2023 GitHub, Inc. Footer navigation Terms Privacy Security Status Docs Contact GitHub Pricing API Training Blog About Wizulizacja/Projekt.html at main · Michciak/Wizulizacja