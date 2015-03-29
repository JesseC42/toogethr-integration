
## Search

### Parameters

* `frmAddress` an formatted address, e.g. "Voorstraat 20"
* `frmLatLng` comma seperated latitute and longitued coordinates, e.g. "52.013397,4.356209"
* `toAddress` ,e.g. "Zoetermeer"
* `toLatLngString` comma seperated latitute and longitued coordinates, e.g. "52.061806,4.483128"
* `group` a string to identity the group, e.g. "Huishoudbeurs"

### Examples

```
https://m.toogethr.com/query/search?frmAddress=Voorstraat 20&frmLatLng=52.013397,4.356209&toAddress=Zoetermeer&toLatLngString=52.061806,4.483128&group=huishoudbeurs
```

Returns a list of all offers and requests (max 100) fitting the search parameters

```
https://m.toogethr.com/query/local?geoLocationAddress=Voorstraat 20&geoLocationLatLng=52.013397,4.356209
```

Returns a list (100-200) of items in range of 5km

```
https://m.toogethr.com/query/recent
```

Returns a list of all recent offers and requests


## Example JSON responses

```JSON
{
    "status": true,
    "data": [{
        "id": 123456,
        "frm": {
            "name": "Rijswijk, Nederland",
            "longitude": 4.346102500000029,
            "latitude": 52.0463661,
            "shortName": "Rijswijk"
        },
        "to": {
            "name": "Delft, Nederland",
            "longitude": 5.017101899999943,
            "latitude": 52.1319071,
            "shortName": "Maarssen"
        },
        "departureTime": 1427123727000,
        "estimatedDistance": "66,5 km",
        "estimatedTravelTime": "44 min.",
        "polyline": "yht|HczoY{CbGkBiDcApAM@KKcCmEQKW@{@p@QDUEWYZo@hCcDnBiBnAcAd@s@|@{A^Kd@?p@UzA}@bDmA~C}@tIeB`Dm@NFX?NJR`AC~@_@hBa@r@c@^e@Rw@Ay@]i@s@oA_DOOaByEyE_MmAyCs@cAiE}JqHmNuCyEaGwIeGgIcAsAIi@cB_CoB}C{AgD}BsGiAcCaA{AmAuAgC_CeGaF_DeEuC}FeAoCiCcG}@wC]cCGiCLeCj@iD`CaKtIs\\dFaTrB}JpAaICc@d@oCfBgLnCwSbBaNhBoRj@iIpAyWlA{a@vBmx@`AmWpB{m@bH}{B`@oVbByj@~@kS`Ae\\nBey@|Ayg@l@_O`Bu[`BqTv@yIlD}[`A_H|AsIfFmT|EeUxN{|@jBcMtCoUdD{[vCoTrCcPxEcVvGy_@hHkf@pFo[`DeRdCaRfDi\\jCyRnBuJnLoi@hEoU|D{V|Iop@vAaLnAcNf@sLLkLIeb@s@wyBm@{\\cAsU_BsUwAiOeD{WcEkWkKqn@{Jyk@uNsy@{DyPwBoHqG_QwDeKyFoN}Uwl@_LiX{DaIqEwH_F}GwT_Y{p@i{@{MkRaPyV_HqLqCwFmCsG_EsLmDgN_DcQsAeK_AsKe@eHa@_KKcGA_Tn@g]pBy{@nCioArB{|@nC{lA^sWCaL]uOoAcS_A_JeCqRcRkuAeAkKi@sHq@uPOuU`@auE?aa@QkO_A}Zu@mNaBsTqBqRoB}OaDgSaH}]gFkToMgg@_FmSqAuGmBaM}AuOy@iP[{POqbDGkvACml@TwTh@gNn@mIjBmQn[scCrAcMhCq[xAcS|AgTtOknB~Dwe@^oDl@{CtBuO|DuWbLet@\\}@^o@^Uf@E`@Fb@Zj@lALlBUfBUh@a@^k@NaAGWFsBo@}C_AcDeAcAi@cD}CaByAwBgAmAWuAIsC@uAGqCk@eBMeDeAsDkAeFuAqJ{B_KyCgEw@{B_@oBKeHKiOb@gMtByGvB{GxCoEdCuUvPkSlOyJnHoDfDyMpN{CvDmH`LiD~EcEvHaJvReChG_AzB{Mbb@kT|r@oCtFaDrEqA|CmAbDMFOD[YgBaB{@o@mAw@sCiB}DeCs@q@_@]Ia@L{@|@oCtCyFj@y@`@M\\Xv@vA^dAHl@DhAM~@oBxE}GxN{AbDiB~CcDdEsFzFwDxEm@j@s@t@cC~AmDrDk@l@kDjEqA|BwHjJcH~HoHtImEpGkDfFALr@vBd@vA]l@G^ThAhAlDdAhDrAl@rAh@v@k@n@i@z@?nAuAl@w@X_C^gBGu@",
        "icon": "/public/images/duimpje.png",
        "traveler": {
            "id": 1,
            "gender": "FEMALE",
            "profileImageUrl": "https://toogethr.com/logo.png",
            "publicName": "Ella",
            "ageRange": "35-39"
        },
        "typeString": "Requested",
        "oc": "RideRequest",
        "departureTimeAsString": "16:15",
        "url": "https://m.toogethr.com/request/######",
        "objectKey": "RideRequest_######",
        "passengerPrice": 0.0,
        "inPast": false,
        "passengerPriceAsString": "EUR0.00",
        "departureDateAsString": "Today",
        "shortestDistance": 46.28112582311881
    }, {
        "id": 234567,
        "frm": {
            "name": "Tu Delft, Stevinweg, Delft, Nederland",
            "longitude": 4.3737672,
            "latitude": 51.9972121,
            "shortName": "Delft"
        },
        "to": {
            "name": "Nieuw-Vennep, The Netherlands",
            "longitude": 4.63180060000002,
            "latitude": 52.2640283,
            "shortName": "Nieuw-Vennep"
        },
        "estimatedDistance": "42.7 km",
        "estimatedTravelTime": "33 mins",
        "polyline": "mak|HgtuYq@uDG]rA{@tA_AUsAe@qC|@i@lDyBWcBbDmBdB}@lCmAnBoAtA}@fAs@Ic@_CwO}@kHOwEGeCOsDa@yCy@gBa@_@m@Q}@Hq@h@]n@Y~@s@~AYZoJlFq@^iLrE}FxB_@`@{DhBkC~A_EhDuB~BgApAoD`EwUvYc@h@Y\\{R`VkBdCsErFk\\~`@{SrVyJvM{VnZwChDqEpDyDpBwCz@aIjAiIhBmD^}G@cJ?kCYiD{@uBgAcCiBcCqCkJkN_@m@eG{I{EwHuFuIeB}BaC}DkBmDgCgFoAoByAeBeB_BwC{BgImHmKcLcAkAgA_AsKiMc@i@yAeBc@m@e@m@}@_AoIyJwBqCsBuCqAkA}D_F_DwEiCqEQ]}BiE_CqFkD_KeFmPq@_CmEuN{C_LCMMa@{CqLK]kAkEgCmI_B{E{D_JuBgEcBuCUc@s@oA_BoCuP}TgCqDqGaKuCgFwA{CgFmKwC_Hc]{v@kGeOoMm\\_L_Y}KeYcFwMsIiToEaKoFsKyB}DgGaKmAgBo\\_e@_Yo`@yIqNuIkPyLiVuHwNgJ}QuAcCUg@wHcP_GwJmC{FaEaLeBeFiBeGOm@KWIQsCgHeEyL{C_HgQwa@aDsGeAyAuDsEuGaH_EeE_BwAiEcF_A}AwBuCmDcHyCgHqA{DkAiEoCqLiDwPMeAgAsHaIw_@o@_Cy@oCuMw_@Sg@iFiOaCyHiAsEkAaFmFaPaEsKqNe]qJwR_GwJaD}E{C_EeGsH}EuFeDuDsEaGoEwGsHcNgDkH}B_G{CiI{BcIcNmg@mFwQyMsb@aHqU_C}HeC{GyBmFkE{IwFyJ}HwKiD}DiIqHwEwE_]a[uF_F}NcMSSgM_Me@]{IgIIQuFaFmBkBwBiBoFgEkMaKiFkDeKiGcOsHsBcA}BqA{FsCoF}BuCqBkBeBgEiE}CqEeX_d@[k@a@o@sGsIqGqI}CgFaCuDI]k@cAeC{EmA{C_AmDy@mF}@uHk@_Dk@{BgByEgAwBo@_A}NoU}AaCKQEHKXuDrIkAdCsFfMcEbJoDpIaBnD}BbF}HbRm@zAcN~[_EjJaBnDkE`KcF`LkA|CmA|EY~Ae@rDU`DM|FBlFP~C@\\L~@F~@yExAc@@KYMIOBKFIj@BT}@xAgA~B?LcCnFYd@{@`B}BqDkDqFcAmBwG}JG?}AcCuGmKwC}E}GwKoDyFUj@u@~A]t@",
        "icon": "/public/images/autootje.png",
        "traveler": {
            "id": 2,
            "gender": "MALE",
            "profileImageUrl": "https://toogethr.com/logo.png",
            "publicName": "Bartledan",
            "ageRange": "25-29"
        },
        "typeString": "Offered",
        "oc": "RideOffer",
        "departureTimeAsString": "17:00",
        "url": "https://m.toogethr.com/ride/######",
        "objectKey": "RideOffer_######",
        "passengerPrice": 2.0,
        "inPast": false,
        "passengerPriceAsString": "EUR2.00",
        "departureDateAsString": "Today",
        "shortestDistance": 34.411607856620996
    }]
}
```