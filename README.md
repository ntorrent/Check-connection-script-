# Check-connection-script-
És un script en llenguatge Bash el qual comprova si un equip (host) està actiu o no.

# Requirements / Installation 
* Sistema operatiu Linux
  * Qualsevol distro
    * 3r nivell
* Terminal (per exemple, bash)
* Fitxer de l'Script (checkconnection.sh)

# Usage
Primer de tot, cal donar permís d'execució a l'script *checkconnection.sh*
```bash
chmod u+x checkconnection.sh
```
Una vegada l'usuari té permís d'execució, ja podeu utilitzar l'script seguint la sintaxi següent:
```bash
./checkconnection.sh <HOSTNAME> <N>
```
On `HOSTNAME` és la **IP de l'equip que volem comprovar**

On `N` és **el temps en segons cada quant comprovarà si està actiu l'equip**

# Demo

Podeu veure el resultat de la demo de l'script realitzada a classe [en aquest enllaç](https://htmlpreview.github.io/?https://github.com/ntb-cicles/Check-connection-script-/blob/main/exemple-execucio-correcta-script-ex4.html).

Per a realitzar la demo, s'ha utilitzat un equip el qual s'ha connectat i desconnectat de la VPN per comprovar que l'script funciona.


