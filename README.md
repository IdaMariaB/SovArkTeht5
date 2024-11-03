# SovArkTeht5
TuotekuvastoApp
Ohjelman keskeiset osat on HomeController.cs, product.cs, product.cshtml ja products.json.
Product.cshtml määrittää mitä tietoja tuotteesta näytetään ja miten tuotteen tiedot näytetään sivustolla.
Tuotteelle määritellyt ominaisuudet se hakee luokasta Product.cs. 
Product.json -tiedosto puolestaan pitää sisällään olemassa olevien tuotteiden tiedot, jotka näytetään verkkosivuilla.
HomeController-luokan metodit hakevat mm. product.cshtml:n määrittämän näkymän verkkosivuille sekä
Product.json:n avulla näytettävien tuotteiden tiedot.
