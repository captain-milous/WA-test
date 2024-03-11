# WA test
 
## Autor
Miloš Tesař C4b

## Nalezené chyby

### gruyere.py

na řádku 682 "except IOError, ex:" změněno na "except IOError as ex:"

na řádku 719 "print 'mkdir: ', directory" změněno na "print ('mkdir: ', directory)"

### gtl.py
na řádku 187 "xrange" is not defined

## Security issues
Žádné jsem nenašel.

## Řešení problému
Na vyřešení security problémů bych si v reálné situaci zaplatil firmu, která tomu rozumí mnohem více než já. Firma by měla zároveň za celou security zodpovědnost, kterou bych si dobrovolně na triko nevzal.

## Závěr
Až na pár syntaktických chybiček jsem žádné velké security issues nenašel a lépe bych ho nevymyslel. Ale věřím, že tam určitě nějaké jsou. Protože v licenci se píše: "This application is a small self-contained web application with numerous security holes. It is provided for use with the Web Application Exploits and Defenses codelab. You may modify the code for your own use while doing the codelab but you may not distribute the modified code. Brief excerpts of this code may be used for educational or instructional purposes provided this notice is kept intact. By using Gruyere you agree to the Terms of Service". Díky této informaci vím že bych tuto aplikaci pro svůj web nepoužil. Ale i přes to věřím že vývojářský tým od Googlu je velmi sofistikovaný a že jejich kód je přímoúměrný jejich zkušenostem, které s mými zkušenostmi nemohu porovnávat.