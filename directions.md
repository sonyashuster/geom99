
# Directions API
Toronto to Winnipeg, via Thunder Bay - avoiding toll routes

### URL:
https://maps.googleapis.com/maps/api/directions/json?origin=Toronto&destination=Winnipeg&waypoints=Thunder+Bay%2CON&avoid=tolls&key=AIzaSyCLpFK8iab0VpFvlmHeV6kSISa9hWxLq-I

### Response Code:

```json

{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJpTvG15DL1IkRd8S0KlBVNTI",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJjekWTHchWU0RdIsdjzRXBT0",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJESsa-ftz6lIRZMq5xvoaKis",
         "types" : [ "locality", "political" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 49.8951374,
               "lng" : -79.3827656
            },
            "southwest" : {
               "lat" : 43.6168422,
               "lng" : -97.13836839999999
            }
         },
         "copyrights" : "Map data ©2021 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "1,398 km",
                  "value" : 1397657
               },
               "duration" : {
                  "text" : "14 hours 36 mins",
                  "value" : 52563
               },
               "end_address" : "Thunder Bay, ON, Canada",
               "end_location" : {
                  "lat" : 48.3808589,
                  "lng" : -89.24768189999999
               },
               "start_address" : "Toronto, ON, Canada",
               "start_location" : {
                  "lat" : 43.6533096,
                  "lng" : -79.3827656
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 131
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 22
                     },
                     "end_location" : {
                        "lat" : 43.6521792,
                        "lng" : -79.38231689999999
                     },
                     "html_instructions" : "Head \u003cb\u003esouth\u003c/b\u003e on \u003cb\u003eBay St\u003c/b\u003e toward \u003cb\u003eAlbert St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "e`miGhmocNdA[fBg@r@U"
                     },
                     "start_location" : {
                        "lat" : 43.6533096,
                        "lng" : -79.3827656
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1079
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 231
                     },
                     "end_location" : {
                        "lat" : 43.6431829,
                        "lng" : -79.37793119999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eBay St\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "cyliGnjocNHEBCDEBC@C@C@CBC@IBIBKLq@BGBCBE@CBCBCBCDADChBm@hBi@VIlA_@n@U`@MJC|Ag@b@MfA]pBo@`@M`@MBA`@M`@MHC`@OjAa@~B{@TDJEXIb@ORG`@OLE`@M`@M`@Mb@M`@MTITGLEDCPGVILE@?DCLEJG@?LIPK\\KDCDCNEHA"
                     },
                     "start_location" : {
                        "lat" : 43.6521792,
                        "lng" : -79.38231689999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 157
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 36
                     },
                     "end_location" : {
                        "lat" : 43.6423392,
                        "lng" : -79.37949549999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eLake Shore Blvd W\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{`kiG`oncNRf@Tf@~@vB^x@DJBDHPHR"
                     },
                     "start_location" : {
                        "lat" : 43.6431829,
                        "lng" : -79.37793119999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 138
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 20
                     },
                     "end_location" : {
                        "lat" : 43.6417833,
                        "lng" : -79.3810117
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "s{jiGzxncN@VBV@LBLBLDNFRPd@~@hC"
                     },
                     "start_location" : {
                        "lat" : 43.6423392,
                        "lng" : -79.37949549999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "13.5 km",
                        "value" : 13537
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 519
                     },
                     "end_location" : {
                        "lat" : 43.6157944,
                        "lng" : -79.53737529999999
                     },
                     "html_instructions" : "Take the ramp onto \u003cb\u003eGardiner Expy W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "cxjiGhbocNRh@Rd@Rj@N\\BHp@fBHRLZDLJZTp@@FHV@DBLNj@Nl@Nh@?@?@FZNt@DPV|@H`@Jp@Nt@Hj@BLFZNjAJ~@Lz@ZxCB\\Lv@PdBPjBPfBPbBJjAHv@Fn@?@J~@JfALpAJdA\\vDJbAJfAHr@?FBT\\nEHx@H`AFx@H`ADp@Bb@@x@@p@Af@@pAAxA?p@An@Ap@A`AExAExA?RExAAvA@p@?H@|@Bx@@l@Bl@@^FrADp@n@jNFfBBx@@d@Bt@@v@B`A@v@?v@?d@?t@?zA?x@?z@?x@@Z?`@@Z@\\@\\@XD|@B\\BXD^BZDZDZDZDZD^FZTpAVpATnA\\rBXzARdAj@`D@B`@xBDPd@dCdA~FZdBLn@VzA`@|BLp@Lp@FZX~AF`@Hf@Lp@PbATjARdAP~@F^PbALl@DXBHNv@F\\N|@Ln@Jl@~@fFZfBLl@Jj@VxADRDVJx@@@BVDZBVB^D`@@ZBX@P@h@@b@@f@@Z?f@?\\A^?XCb@Cn@AVAPC\\Gt@Iz@Ip@AFYbB]~Aa@vAK`@IRw@`CIXUr@Yz@O\\Uv@W|@sBhGmAvDGR{@hCsCxIcA|CCFM`@Ut@Of@Mb@Wz@Mf@Md@Sv@Kj@Qt@WfAOv@Mt@Q`AOx@UrAQlAEZOfAOlAABQ~AQ`BKlAMzAKnACb@?BEf@?BIhAGpAEbAGpACt@E`ACnA?PCp@?LEfCA`B?X?N?|@?R?L@b@?J?d@?ZBrA@d@@Z?RD`AF`BHrAHdAF|@Fp@JjAP`BFj@Hp@Fl@L`A@BHr@Hh@Hd@@HFb@Jj@ZfBPx@Hd@BHH`@DPZpAXjAPp@t@nCj@jBTr@n@nBt@xB`AxCr@tBVn@L\\LXLVl@nARb@p@vA^t@f@`ANZh@~@d@~@FJf@bALXNZHRXl@^~@d@hA\\z@Pf@Zt@FLJV\\r@@?\\p@l@dAd@v@j@|@V`@`@l@bA~Al@`AV^V`@HLLNLPT\\JNLNX^Zb@n@|@p@`ALN`@j@\\f@l@|@Zf@\\j@\\n@JRLZVl@Tl@JZHXHVHZPp@Nr@H\\ZhBfA~GZtBd@zCLt@FZNbAV|AXbBRxADNj@|DzAvJl@|D\\vBtBjN`ApGv@jFJl@lAhIjBfNBTdBzMp@`G@BBH@D@HFf@LhAJx@`@fD?F`AjIFj@~CbXv@zGNvADb@LdAz@xHr@dG\\xCRdBv@`Hl@hFf@lEhArJBXFd@V~BrApLn@nFNtADXHx@p@`Gn@~FFh@ZnCZlC`@jDP~Al@xE"
                     },
                     "start_location" : {
                        "lat" : 43.6417833,
                        "lng" : -79.3810117
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.5 km",
                        "value" : 1482
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 60
                     },
                     "end_location" : {
                        "lat" : 43.618718,
                        "lng" : -79.5524746
                     },
                     "html_instructions" : "Take exit \u003cb\u003e139\u003c/b\u003e for \u003cb\u003eON-427\u003c/b\u003e toward \u003cb\u003eAirport\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-401\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "uueiGrsmdNCHAH@TBx@Bf@RrBB\\NxB\\nELdCTpD^nFJnAB~@NfCJrBHnA@\\BZD~@BhADxABr@@X@f@?`@?B?d@A^AXALAXGf@CRCTGVIb@ELIZQh@ENIPKTIPU^OTORURMLQNQN]Ri@\\w@b@yAx@yAx@u@`@k@VKFUJQHs@Xq@XC@ABCBAB"
                     },
                     "start_location" : {
                        "lat" : 43.6157944,
                        "lng" : -79.53737529999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.8 km",
                        "value" : 2820
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 98
                     },
                     "end_location" : {
                        "lat" : 43.6430853,
                        "lng" : -79.56211789999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eON-427 N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_hfiG|qpdNm@TYJ[Jg@Pa@Nk@P]Ls@Vy@Xg@Pw@VGBaCx@eCz@c@NQFs@Ve@NMDOFMD[JaDfAwE~AMDODUHSFaAZcA\\eAZq@R_@JIB_@JSF_@LGHGBEBC@ODYJ[HMDkA\\iA\\sCx@qA^{Bn@gBf@i@NMDoAZk@NwBj@E@gCl@}@TqBd@o@NqAZu@PE@oAXeBb@K@y@R[Hg@LiBb@gDv@s@POBE@y@RIB_@JKByCv@kAZkA\\qCx@yBp@yC~@YJi@P"
                     },
                     "start_location" : {
                        "lat" : 43.618718,
                        "lng" : -79.5524746
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.9 km",
                        "value" : 2851
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 99
                     },
                     "end_location" : {
                        "lat" : 43.6674328,
                        "lng" : -79.57317350000001
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eON-427 N\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "i`kiGfnrdN{LbEqNxE]NuBt@eC~@}Aj@aC|@}DzAoAh@UHiCdA{B|@sCjA{@\\iCdAaBp@wCjAcBr@mAd@gC`ASFMFq@TuBt@e@PaBj@eA\\c@Nc@LC@u@VmA^eAZu@Vi@NiCx@g@NOBUBi@PYHy@VKBgCx@KBgBj@gCt@sExAqDdAi@V"
                     },
                     "start_location" : {
                        "lat" : 43.6430853,
                        "lng" : -79.56211789999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.2 km",
                        "value" : 4162
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 158
                     },
                     "end_location" : {
                        "lat" : 43.701249,
                        "lng" : -79.5608678
                     },
                     "html_instructions" : "Take the exit onto \u003cb\u003eON-401 E\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "mxoiGhstdN[EI@I@MBoCn@k@LSDyA\\aATMFODODGB]LSHOFWLULOJA?MHOJOJSNUPQLQP]XKHQNo@j@KH[Vk@f@o@h@_@ZGFURi@b@}@t@EDOLWPWPMHMFULQHKDMFIDODUHGB]HUFUFc@FG@E?UBG@M@a@Bc@@c@?]?u@EMASCUESCMCYGQE{@WeA]uBs@_Bi@QGsAg@yAi@{Ak@UKqCmAwB_Ac@O}@]y@[i@SSCQ@AAUIqAk@uAk@a@Sq@[uAo@aAg@_Ae@eAi@gAi@qAq@c@UcBy@wBeAGCeAi@oDeB{@]GC}Au@w@_@u@a@m@Ym@YYOYOMEMG_Ai@GEiAq@UMkAw@aBgAmA_Ao@g@_Aw@s@m@kC{BaAy@q@m@_BuA{@u@sAiAYYa@c@y@q@_@[oAeAQOeA}@k@g@{BmBuAmAm@g@e@]i@e@y@w@MIk@g@QOs@q@}BmB"
                     },
                     "start_location" : {
                        "lat" : 43.6674328,
                        "lng" : -79.57317350000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.2 km",
                        "value" : 3200
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 142
                     },
                     "end_location" : {
                        "lat" : 43.7149303,
                        "lng" : -79.52766220000001
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e at the fork to stay on \u003cb\u003eON-401 E\u003c/b\u003e, follow signs for \u003cb\u003eIslington Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWeston Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBlack Creek Dr\u003c/b\u003e",
                     "maneuver" : "fork-right",
                     "polyline" : {
                        "points" : "ykviGlfrdNOYGIEGOMGGa@_@SQaA_AUUmAmAe@g@KKm@m@AAi@k@{@{@sAyAi@i@yAyAkAmAi@k@}@aA}BcCKKi@g@g@i@{@{@[[g@g@OOm@m@c@c@c@g@[]QWA?QWEIU[O[GIACCGKQM[KUi@mAc@wAIWI_@S{@Q}@G]Ig@U{AU}ASqAYqBG]WaBCQKcAOgA_@gC]{Bg@iDWeBMs@c@qCSwAc@sCIm@s@{Ec@kCMw@UiBOeACKQgAGe@Ii@SmAOgAEYi@mDQqAAEM}@Ku@M}@U_BW}A?ASsA_@gCc@cDEi@c@wC_@oCg@wDIm@Im@]iCq@cF"
                     },
                     "start_location" : {
                        "lat" : 43.701249,
                        "lng" : -79.5608678
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "83.8 km",
                        "value" : 83778
                     },
                     "duration" : {
                        "text" : "46 mins",
                        "value" : 2780
                     },
                     "end_location" : {
                        "lat" : 44.4213825,
                        "lng" : -79.6546853
                     },
                     "html_instructions" : "Take exit \u003cb\u003e359\u003c/b\u003e to merge onto \u003cb\u003eON-400 N\u003c/b\u003e toward \u003cb\u003eBarrie\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "iayiGzvkdN?m@SgBGs@Gm@Ea@Ca@OsBCa@AKAEEw@Ec@Co@CWGqAC{@C_@Ak@?c@?I?_@Bi@BY@KDc@b@_EBWLgA?M@KHgA?E@WBU?[?U?U?KC_@COCWAKCQCMAC?AAA?AAAGEGQMYMQOOSQSKSISESAC?U@M@UDA?UFSHWHOHOHQJOJmCfB[TKHKHGBC@S@m@b@gBxAc@Zc@\\wC|BQLSNUPc@ReAr@g@Ze@Xw@d@ULQJg@TMFg@TUHSHe@Nk@PUFUFe@Ja@JoAPUDwLfB_ALgFt@_G|@q@J_ALuCb@oC`@eAP{BZoFx@oAPsEp@A?eIlAwARqDh@C@iC^kJtAwDj@wLfBqC`@c@F{LhBkBX_@FA?{Cd@y@LYDaEl@cEl@uMlBqARsGbAUBSD]F[H}BZcGz@{B\\wAR]F_KxA_G|@eC\\qDj@yEp@gDf@{B\\sHfA{C`@E?oC`@sCb@gC^c@NMBG@IB}@LqJvAuARuARkHfAcKzAYD[Di@HoBXyCb@I@kANiBTwARiBTsANiFn@yALiBVc@FG@uCd@mCh@kAPwEv@cC`@qAR_BVsEv@a@Fo@JuCd@OBo@JuCd@aANyCb@_IhAeDd@_BRQ?uEr@q@JiDj@aBXgDj@kK|AyATqG`AiJtAuInAsARs@LmBVkC^wDh@sC`@yDj@eDf@kEp@eC^qC^oBVm@L{BVoALuBPgBL[BqH^YBiBHA?c@ByCLsCNU@kFRc@B_ERyBJgDNa@@A?oCLkBH_@BaGV]BE?qDNU@E@oBJwADgLh@gBHsMl@kJ\\kCJcDLm@B_CNoCPwCN_ABg@ByAFu@Du@DoDXgFb@_CV}JxA}ATkEr@yAP[DoBXQB{Ep@_BVqEt@gG~@}C`@_D`@u@L_@FA?a@Fa@FC?aAN_El@sNvBE?qB\\yAT{Dj@MBUDy@J_BT_@F_@FcDd@eEl@M@c@HiAPy@NYDWDC?iAPiAPsC`@eEp@M@A@c@FaH`AcC^cFv@eEj@gDf@c@HmHhAsC^uBZwAR_Gx@cC^a@Fy@L}Et@_Fr@[FiDf@{Cd@kDd@SDC?_@F{Et@c@Fs@JyATc@Fq@JoBXuAPqAPgCb@y@JyDj@OB_BVc@HmC`@_JrA_AN_HbA}Dl@gEl@m@JgDd@yB\\_Eh@cEl@cAP{IpAa@FQDaANaEl@sC`@cBVoBXgC^sCb@gHfAaDb@mAR_@Fy@JoCb@m@HiBVeAP}Cd@cEl@mEl@y@JgEf@i@LeEd@mC^}Fz@eEn@]D[FgC^W@y@LoDh@qDh@G@c@FmC`@aF|@YDaEb@{Fz@_ANi@H}B\\{AXo@JuBZk@H_C^cC`@}@NSD_AP{@N_APeAPo@LOBuAVcANu@LyJxAiHdAmJrAyCd@qDl@{P`CWJ_@Fa@FoC`@iDd@K@wBZmC`@g@He@FcAPkANeAPoAR_@DaBXgAPu@JkAPu@JyCd@]DmCb@yAR{Cd@{@L}Er@w@L{@NM?cANaAN}Dj@qCb@_CZcBVgBXaBVSB_BTuAT_@DoARiBXYDc@Fk@H}@Na@FkBXa@Fuf@lHsEp@uCb@G@eC^uARw@LeDf@{B\\oDh@kDf@c@Fi@HiDh@YDmDh@o@JmBX_C\\yFz@oAPa@Fo@JaC^qDh@kMlBwFx@kAPiG~@uEr@eNrBeC^_ANMB_ANg@J}@Po@No@LcB`@iBb@IBaB^cCj@uBf@gB`@aN~CeGxAmGvAwGzAy]fIaBb@uKdCcCf@_QjCuF|@gV|DyCf@mE~@wWpE{GhAuBPuLbCkFv@gBVkB\\c@FC?_@Ja@L_APuCr@aAZSFeBh@oAp@s@^wDrBaB|@iBlAuB|AiClB}EbE]X}@v@}RbP{BlB}@t@kHfGSPiEzD[ZqFzEUPSNIFwCdCiEjDWRA?uAjAcBvAkDrCOLMJkA`AOL{AnA]X{AnA]XwCdCGDeJxHyBfBwJ~HkMrKgHzF]XyCbC]Xg@`@uClBuC~AqB~@UJKDoCfAkA\\aA\\qBd@KBc@Fm@JaPjCwDj@E@]DgC^iCb@_Fv@kIpAqS~CuGfAkGdAy@LyB\\yLlBqCb@_a@lGeMlBuGdA{HlAc@H_JvAeEj@eG`AyHpA}AVaC^a@FMBa@FuCd@a@F]FuEr@_JvAiBXI@YD{B\\eEp@}JzAaInA{@NuBZoAReNvBc@FyLlBQBuEr@m@Jm@JmDj@_s@xKcK~AuEt@mFx@qDj@oDj@aJvAsFz@C?c@HsEr@G@mAN_AL_CTqDXeAFuBJA?kCJe@@cDJuADsDJsDLgXv@uIXqIVeBHsBFmBDyELeFNqDJsCJqBDaENwBHuAD}ADaELy@B}CJcELg@@{FPuM`@m@BA?i@@oCHgAB}@BI?kBBcABC?eENiCNy@Fc@Dc@Do@DoBTaCZmC`@_Dl@qB`@_Cj@o@PE@]JwA`@yDjAyBx@wBx@_Bp@gEnBkEpBsNnGg@TyDbBuJhEa@Pa@PcAd@cAd@mIpDqElBgBv@iAh@c@T{ErBeF~Bc@TA?uDdBmAd@k@V_FxByAn@}FfCwDbBGDcA^uAh@kC~@sBp@aBf@}A`@sA\\w@PaB^iB\\wCh@eDh@mDn@YFc@FeARQBQBkCd@]FsCd@wB^kCd@}Dp@{Ex@mCd@q@Lw@Lc@H}Ch@cIjAwBb@_APcGz@uHvAmGfAiHrAwM~Bq@JwCf@_Dh@{@N{Bb@uB^cDl@gARaAPwCf@cEt@aDh@mF|@kJ|AyB`@aEt@mDl@eAPqDp@cBXg@HqAVmDj@cFz@wDp@s@LoBZMBy@NgCd@_C`@yB^uAVeAPsDn@kCd@iB\\kCd@kBZoBZ_Ej@gHtAkARkARaBXeBXeCb@sB^uDp@eDh@qCf@OBa@F_BXqF`AmHnA}Dr@a@HyCf@aC`@kDl@OBwCd@eCf@aCb@sEv@wDp@sCf@aDh@sB^qHnA_Fz@_Dj@I@UDaHlAo@Ju@LWF_@F[DqEx@c@H_@FG@m@Jc@HG@a@H}Dp@oARsDp@_@FK@uB\\w@N_APkARc@Hi@J_ANc@H]FwB`@mARu@NG@[DuAVu@Le@HaBXkARk@J{AXeBXeDj@cBXuCf@iBZ}@Pk@Ju@JuAP{ALiAHgADeAD_A?y@?k@?K?c@AE?u@Ao@CU?gDIaACy@Cs@CaAC}BGu@AE?]A]AmACa@Ag@AcACqBEC?eCGaBEsLYcBEyBEyDKiEIqDIsDIqAG_BCU?_EKiAEkCEkISgDGqDIeBEkAEmBEgBEo@?gB@oBF}@DaAHcANgANuC^A?eEl@uATmHlAy@LkAP_C\\_G|@mC`@{@N{@LiDj@I@qCb@_Ft@KBoJtAmAPoAR{AT{@LuATqB\\SDcGbAe@FkLlBgCb@eFt@aANeAPyB`@m@H_Ej@aEp@oAVoAZk@NqBl@gA`@qAf@aAb@OHsCxAgAp@kAr@iAx@_Av@}ApA_CxBmBnBkDdEuAfBa@h@w@`AUZqDpEqB`Cy@`AMN?@iAtAaBnBwE|FaCtCgArAo@v@QRmBxBmCzC{@~@cBhBUTm@p@mBtBoB|BeAnAe@j@Y\\[^wDtE[`@IJEFYZkB`Cy@bAY\\cCvCuAxAo@l@y@v@qBzAw@`@iAl@eAb@yAb@s@Nu@JC?sCTcEESAsAQcASu@OsAa@cA]WMIC_CcAsAk@qAi@mBy@yAo@qAi@sD}AuGqCaCcASImCgAwEoBmF}BaAc@QKu@]m@]o@_@o@a@w@g@u@g@kA{@oBwAkCmBoDkCWS{AgAu@k@}EqDyEmDsOcLeBqAyBaBqB}As@m@q@k@[We@c@a@_@CEaAaAa@e@IIw@}@QSIMW[W[AAe@q@sAmBc@o@aA{AqDsFeF}H_FoHmIkMs@kAcBmC[i@[m@g@aAYo@Wk@_@{@Qg@Oa@i@yAWw@YeAOg@Qu@ESm@gCCOMg@O{@QcA_@_C}AaJkCeOeByJQmAE]G]iDyRgAsGgCqN}@oFw@oEWyAg@_D[cBSkAQaAMq@O}@Qy@U}@Ok@GUQk@Qk@Sm@Uo@i@oA_@}@a@w@a@y@S_@IKg@y@c@o@QUSYe@k@wA_B[W?CaCeBsA{@k@c@"
                     },
                     "start_location" : {
                        "lat" : 43.7149303,
                        "lng" : -79.52766220000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "138 km",
                        "value" : 138096
                     },
                     "duration" : {
                        "text" : "1 hour 14 mins",
                        "value" : 4422
                     },
                     "end_location" : {
                        "lat" : 45.4374529,
                        "lng" : -80.1244863
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e at the fork to continue on \u003cb\u003eON-400\u003c/b\u003e, follow signs for \u003cb\u003eOntario 69\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eParry Sound\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSudbury\u003c/b\u003e",
                     "maneuver" : "fork-right",
                     "polyline" : {
                        "points" : "s`cnGxpdeN[_@YQmCiBqBoAe@Ys@a@_Ak@eAi@s@]iAo@y@c@s@m@QQe@g@]c@a@i@k@u@a@k@IMOSOQa@a@UOYS]O[K[KUESEo@Ea@@e@B[DSBg@NIBYLc@V_@VUV]`@[d@i@z@Yl@]r@w@pB_AbCmA`DaA`Cc@lAa@|@i@hAc@t@Ub@QZg@v@g@p@a@j@UX[\\_@b@_@\\]\\yAnAoIfH[V_Av@yAnAm@d@gBzAqExDg@d@{JlIaFbEwCfC{@r@wCbC_@ZsC`CmCvByAhAkElDyBhByBhB{BfBwDxCyBjBa@\\sDzCwDxCqB`Bs@j@cJpHmVbSiGbFmGdFmEpDeBvAeAx@kB|AcAv@w@p@qAhAUP{CnCuDdDMLOLqCbCMNiA`A}@x@wBlBGDyBrBi@b@sAlA}BtBaDrCi@b@qBjB{@t@oAhAgFtE_DnCeA`AuBlBGFoBfB}ArAIHi@d@i@d@aBxAcBzAkJnIcDrC_CtBYToCfCqF~EyClCyArAEDaElDyDjDiBfBeD|CqAlAaA`A{KfKyGjGi@f@}AzAwBpBeB|ASTkBfBcA`A{MdMuBnBQNgF|EQPqCjCu@t@eC~Bw@v@oCdCqAlAGDsClC}AxAkCbCeBdBiG`GqChCgGzFuBnB]\\yApAy@v@]ZiAfAiAbAmAfAcC`CkFbFmFdFaLhK]Z[X_@\\MLONs@t@qCfCuBpBgC`CUTKJsCjCeAbAoPvO}BvB}AxAa@`@yHlHi@f@eIpH{AtA_At@o@b@m@^m@\\m@XiAd@g@P_@Jy@Tga@`K}Cv@kFpAi@LeAVa@JkBb@cAV_AV{G`B_ATmCn@sCt@qARmANq@BC@}@Ds@@uAAsAImAKaAMuA]kA]}@[o@[ICgAi@{AaAw@k@{@s@gEyDy@y@[WoCgCOOmC{Bg@g@sE{DcA}@sAoAeBaBcCyBg@e@_BsAwDkD{@y@{DkDwDgD_CuBoCgCuAmAgCeCm@i@AAi@o@mAsAcAoA{@kAgCuDgB}CkAaCgAyBCEiAoC}@gCeAsCI[Qm@So@[iAc@aBk@cCMo@Qo@_@yAkB{H?AOm@{CmMyD{OMm@yC_MQs@A?Qu@q@wBmAmD?AeAeCmByDeBsCqCuEwCwEsAwBOWYc@oAsB_BiCq@gA}BsDYa@?AyBkDaC{DWc@cDkFWa@sCuE{AiCaB{CsAwCaBsDyA}CcCqFsAyCqAqC_AqB{AgDkAiCcAyB_BkDqE}JcCoFUg@o@uA}@gB[k@wAgCgBqCw@gAoBeCIKu@aAmAyAy@aAaBqBeAqAyBmCsDmEuCqD}HqJuBgCmCcDgAmAcC_C_BwA{@o@WUKI_C}AwDcC}B{A}BuAaSgM_@U_@UqLuHkG_E_C{A{CkBCC{BwA_@UcG{D}GgEGE_DqBwCkBwCiBeDeB_A_@{B{@wAg@}Ag@sHaCa@O{QgGmPqFA?i@QkHaCyAg@YKaEoA{FqBmFcB_EsA]MmJaDkJyCAAy@YmE{A_EqAsHcC_Cy@a@MeBm@eMgEuHiC_D_Ae@QaA]qEyAoC_A_FaBgCw@k@S}Ag@gC{@YI{DsAYKsViIkDmAeDcA_AYa@OgEyAwJaDGCyGyBaBe@w@SkAUaAQkAQqBSoBEoAEoCDaCNkBRy@JiDn@cCd@kDp@oATcCf@k@Lu@LoThEaJdByGrAe@FkEz@_Cb@iBZeBVy@Lc@FaBPyBR{AJuBLiKj@sETuDPkET{G`@qCLs@BkG\\M@}Jh@oFXgBNeAPw@PODi@LkAb@_Ab@i@Xa@R[Re@\\_@Vk@f@}@v@u@v@{@dAw@dAg@x@u@vAg@dAaAvBO\\qElK}BtFiBlEUf@aBrDIRgC~FQ^g@dAS^e@|@yA~Bk@~@_@j@aAnA{@fAg@j@g@j@mAnAy@r@CBYVUTaBlAc@Z]VC@oCfBkAv@qChBiCfBC@yAbAcBfAcBhA{BxAqCjBkAv@_DtBgEpC{DhC]VyDbCeAt@_@V}JxGyA`A{JrGwMxIaN~ImBpAsD`CkCdBa@XeG~DeFdDoFpDmAx@eAn@s@d@_BhAe@\\gAz@w@r@MLeAdAa@f@mA~A]d@}@vAc@v@Ud@[n@u@~Aq@dBKZc@jAUt@_@pAy@vCa@zAo@zBmAlECHi@jBW`Ay@pCIX}@bDGVwAbFUz@Y`AK^w@dCa@jA_@|@_@x@o@tA{BxDiA|A]b@_AbACBSRw@t@i@d@g@^s@j@g@\\SLg@\\s@`@_Ab@c@RoAd@qBf@qB\\y@Je@D[Bm@DS@s@BK@_AAm@AyAGaAGw@Kk@Kc@KMCm@Ou@Uu@Ug@Qc@SUMe@Wg@Y?A_@SCA[SKGcBaAwDyBgDmBgAq@gAo@_GkDUOs@c@kC{AIGsKmGsCcBkC}AkHgEoDuBQKOKcC{AeB_AoAs@WO]O_@SiEgCWOwBmA_Ag@]QUKUI}@]k@QWGYIc@K_@I]Gw@Os@Ke@CqAGkBAk@@_ADY@e@Fu@NQB}@P{@RaAZiBr@y@^_@RSL}@l@c@ZA?iA~@{@r@w@n@y@p@gA|@UPiA~@q@h@_@XKHoB`BUPIF{BjB_@X]ZIFqAfAa@Z]Xc@\\g@`@w@n@WT{BhBUPoDxCq@l@OLOJ}AnAMJOLoC|BgElD}GrFcFfEiBxA_@X{DbDyD|C]XkB|AcCrBaBrAsB`BYVc@ZIHIFIHCBa@b@s@x@SVe@v@]h@]h@e@z@]n@KV[n@c@dA{@|BSp@Sr@]lAYpAu@jDwAfMEd@u@jHc@hEAJa@hD?@CRYzBm@lEQjAOfAADSzACRSvASxAi@bEw@nFUfBw@bFWxAYrAe@lBKf@Ox@g@zBI`@Md@Qr@Mr@IVq@jCSp@Wv@Ur@c@nAc@hAc@bAS`@IRe@`AOZCBMVa@t@Wb@?@_@j@c@r@_@l@A?o@z@a@f@s@|@q@z@IHs@t@y@v@iA`AWR]XEDoAx@u@f@}A~@}At@kCdAA?y@VKBcBb@oCd@A?sAPqAJqBJu@?{@?aAAkACe@Ec@Cw@GoBUyC_@eBSaEc@}BYkHw@}BYuEi@yFo@qDa@c@G}AQgEc@aBSc@GsEk@c@EgAOUCaBQWAo@EeBCmB@q@Bw@F_AHo@FKBm@Hm@JaCb@qDn@aKjBoDp@iB\\s@LsB^yAXgARyBTk@BM@M@Y@_BBQAw@CiBMkBWgAWQC_@OgDuAA?o@_@_BeAc@YUOiBiAUQYOs@e@s@a@ECYO_@S_Aa@w@[]K[Kg@Mo@Oi@Me@Ic@GWCA?m@GE?k@Eq@C_@@K?G?{@AA@oADQ@I@[B]DMBi@F_ARwA\\aAZq@XgBv@yAp@a@Pi@T]NsAn@w@\\s@ZeBt@eBr@YLg@Ri@VWLMFoAl@e@RMFmGtCaCbAiGpCmGpC}CtAmJnEcAb@_@R}Ar@eChAmHbDeBt@wObHA?gDzA_@PsB|@_A`@aA\\aAXsA\\e@He@H]DQ@OBe@B_@Be@?m@@m@A_@AUAUAKAo@Gw@IkAQKAUE_IoA_AI[GwASk@I{@My@Ka@C[C]Aa@Ae@Ay@@O?U@u@De@Bg@Fy@Le@Hs@P[JWFGBm@RMDe@Pq@\\iAn@ULMJYP}@r@a@\\g@f@q@p@cAfAsGjH_DjDyB`CA@_CjCiAhAGH{@v@u@n@{@p@y@h@mAt@_Ab@i@T_A`@aE`Bi@Rg@Ti@Ta@RYNc@XmA|@]Xu@n@WVq@x@{@fAQZm@|@w@pAkDvF[h@sBhD}CfFYd@yCzEyA~B_CzDYb@_@n@}BvDcA`BMT[`@GHA@s@~@w@|@cA|@y@p@UPkA|@kAn@}Ar@}B|@gC`AeBp@cA`@gC`Aa@PcA^_DlAkCbAgA`@iA^cAXwA\\ODiB`@eATeATi@L[HiB`@qEbAi@LyInBmOhDs@Ns@JkAHeCLeA?e@As@AgACkD@wNSaHK}EGoHKoCCgACS?O?gAAwEEc@Aw@As@?SAO?c@?w@As@AwJKQAgA?C?}ACIA{@AC?G?WAK?mAAu@?y@?y@@qCFY@gADc@BU@M@_BFu@FsAHqR`Bc@Da@BeAJqCTc@Dc@BkGh@O@{It@K@cBNoK|@kCT{CV_BLcALk@Fe@Hs@L_@JcKnCQFgHhBeCn@uBh@c@HkANe@De@BiAD{@@OA_BEq@E{@Im@KqAWmAY{@Y_Ac@cAc@yAw@qDqBiH_EgDiBIEaCsAyC_BAAaB}@aAg@wAw@IEaB_AsC}AcDeB_@U_A_@i@UcA[_@Iy@Ok@Is@EsBGW@]?aAF{@F[DaAP{@VE@s@VqAl@u@`@m@`@i@\\a@\\aA~@g@l@oAbBc@j@e@p@aA`Bo@dAa@n@oA~AOTmAhB[`@SV[\\i@h@]Z[VONoAz@w@b@g@Ra@N{@Z}@V}Cv@g@LqEjAIB_B`@c@JeAVuA\\yA`@oD|@uCr@cDv@uCr@KDmDz@a@JkCn@oEhAkCn@sBf@M@cG`ByA\\WDk@JQBe@Fa@FG?[@}@FQ?a@@k@@O?k@?}@Ay@Cm@Gi@G}@My@Og@Kc@KOEw@W}@[c@S]O}@c@_Am@o@_@y@m@k@c@i@e@eA}@iA_Ak@e@o@k@kA}@a@[qA{@aB_AmAm@mAi@mAa@iBc@oAUAAc@GE?]E_AGsAGkBEeBCG?_ECgBCmBAuACaCCuAAgAAC?}@AiBAwCEwAC}@?wAEu@?]?uACwAAK?iAAwBCa@Aq@?I?eACgAAS?oCCgBCuAAEAmAEi@Cm@Eq@GGAg@Gk@IqAU}@QKCYGk@O{@Wm@Sc@Oi@Sy@]{@_@oAo@kAq@mAy@uAcAACu@o@iA_AgCcCg@g@u@q@q@q@q@q@u@s@AAwBqB{AuAeA}@w@k@e@Ye@Wc@Ui@Wo@Ws@Ug@Mi@Mk@Ik@Gc@Ei@E_AAg@Ak@@U@e@BUBW@e@FqB\\sATwAVeBZcDn@eDj@i@JgB^gBZ}Dr@{@PeBf@k@RmAh@_@Rk@\\g@Zc@\\WP]Zu@r@a@d@_@d@_@h@k@z@m@x@}@vAy@tA[h@m@|@aArA_@f@a@d@c@b@q@n@aAv@o@`@gBdAoCxAeExBcCpAi@V{C~AwIpEgBbAoB`AyAv@m@\\oBbA_Af@SJgAl@}C~A_CnAOHCBcAh@iHrDkAl@mAn@iAb@o@VgAZWH{@N_@F_@Dq@Hq@Fk@@}@@w@?s@EUA]Ce@Gc@Ei@KaBYq@IGCy@MsAUA?gBYqDm@s@KsGgAuCg@YGkB[a@GiB[kB[A?]GwAUsAUEAa@ECAKAu@IA?e@Ee@Co@C}@AsAA}CBoEBiBBaGBeFDU?}SNk@?iFDgEFyBHaBBiLb@gHVcGVwK`@mI\\_J\\yHZaCHoFR_FRiBHG?E?eFPc@@s@BK?qGXI@aK\\eAFeBJwCRkBRcCT_@BoLvA}En@uEl@sGv@kJjA{BRsEl@k@Hc@FaBTaH|@{Ft@_@DmLxAmC\\kM|A}Df@gPtBiFn@aI`A_Ef@{BXkBTaCX{BXaALyFr@}@J{@F{ADeAB}@A{@Em@C{@Ie@Im@Kq@Kw@Q}@Y{@WoAe@yEeBYKkCcAcCaAeAc@uAi@cBq@sAa@gA]w@SoAWiASeAK_BMgCGU?A?a@?u@?{BJ{CR_AHw@F{@FwD\\kGf@A?w@H{DZqBPeAHc@DuBRoBNw@FK@mANqANo@Hm@Ji@Jk@Ji@Jc@Ja@Hs@PmAZiA^k@NYLcA\\sAf@KDw@ZwAh@MFgCdAaC`AkBt@QFyCfAe@P_A^gAd@{PxGqEfBgBr@aC~@_@Na@PmAb@_A^eBp@aC~@kAd@a@NkFpBeA`@cBv@y@b@GBm@\\a@T[Ro@^]Va@TIFaAp@{AhA_@Vc@^_At@KHkAdA{AvAeAfA_BjBkAtAg@n@cDxDu@~@EDUXoB~B[^[\\EFwEvFGFSVGHo@t@uAzAs@t@qAlA_At@oAz@s@`@CBOFQJm@\\QH]P]Pg@TaA\\A@iA^[HQFG@IB_@J}@Pi@Jo@Lo@Ho@FaAFsADkAD_FBc@?c@@cC@o@@oCBQ?wAFc@Ba@@}@HeAL_@FOBeARA?u@Pu@Pq@TsAd@g@Pu@XqBz@aDzAcBv@cAd@cBv@iCjAa@RgCjAyDhBcCbAaCx@y@Xe@Pm@Nu@TgB`@u@P_ANWD]Hm@Hu@Lm@HgANmC`@k@FwAPIB{@LyB`@gC\\gAPwFx@eC^k@HeDf@yARc@FA@sEp@c@Fc@Fa@FaBR}CZgL~@a@BA?eBNa@Bq@F_BPWB[DE@k@H_@Hm@LuA^s@Ro@Tw@Zo@Xy@b@q@`@w@f@s@h@cAz@q@t@y@x@s@x@w@bAcArAi@r@oAfBkBrC}A|Ba@l@_AtAu@fAgA~A}BfDsA`Bw@~@cAjA_BzA_@Vm@f@OHy@h@eB|@C@cBp@eAZa@LwA`@A?e@Hi@Hm@HG?o@FoAFw@@a@?m@@o@Ci@COAoAM_AMmASqA[_AW_AYAAuBm@wC{@{@Wu@SoB_@s@IOAEA_BQuAEYA]Ao@?w@@I?g@Bg@D}@FaAJ{@PsAVq@ReAZi@Rm@TA@c@Ri@Xq@Zm@`@UPSPu@j@kAz@aAt@m@b@y@n@UR_At@wAjA_Av@sAhAcA|@{@r@a@X[R{AlAcAt@]RuFtEcBvA{@r@aEdDa@Zk@d@KFQPcDhC[VYT}BdB}AdAgAn@iAj@eBt@uAd@uCt@_BVE@aALuAJs@DoAD_A?C?oAAsACcAEcBK{BKuAKeDOqAIk@EoCOmBKgBI[Cy@EgBKuAGsAKYAy@CeBE_ABqAD_AFaAJaAN}@NaAT}@Tu@VYJaBv@kAl@_@Vm@^cAv@iA~@q@n@_AdA{@~@GH_AhAiAfBk@`Au@tAu@zAu@xAGJuAfCsAjC_B|Cm@lAUb@Uf@Wf@Wj@m@jAk@nAUb@S`@Q\\Wf@OXQ\\Ud@Yf@Ub@Ud@o@nAo@lAUd@eAvB}BpEGLuApCqD~G]t@e@|@_@r@g@z@_@l@EHKNOVi@v@[f@Y\\m@x@q@t@e@d@]\\_@\\]XwAjAe@Z]TC@]Ta@Va@RYNu@`@w@^a@Re@T{Ar@a@Ra@Re@Rq@Z_@PCBQHi@X{@d@]R_@V[RYRm@b@IFQLe@`@]X[X_@^EBYZq@t@aAdAq@hAk@z@g@v@]h@a@t@Wf@Uf@Q^Q\\MXKVKVQf@Sj@Un@Qp@i@~AOf@Qj@Mh@Mj@S|@Q~@Q`AMt@Kl@Kt@YvBs@zGALi@|EGb@In@I`AIv@KdAKz@K|@QhBMnAMnAGl@UzBW~BUzB[xCIx@Ef@UtBIbAK|@?@[lDIb@ALE^OpAQdBCPEd@K~@W`C]bDEb@MfAg@pEGh@MlASxAMv@Mz@Y|Aa@nBQv@Op@Qp@Of@Md@IVIZITIZIVQf@O^w@pB[p@ITeArCm@|AgA~C[hAK\\i@`B[hASz@WdAWpACJUvAUbBUtBOpBIrAAVAVC|@IxC@~ABlBJfEBl@RdILvE^dJN`ELxCFdB@b@B`A?^FbD?x@AbBAh@?p@EjAE`BCj@EfACn@AFCv@Cb@WjGIdCK`D?DM|DAr@E~@Ar@CxAElACdC?f@Ap@ANCdACtAInDGlCGbDIpDShIGnCCt@ALOfCObBC`@UfB[pBa@xBADI^GVi@bCY~@IXENQj@Sd@M\\O^IRKZGJQb@c@z@a@t@_@v@Wd@Wd@k@~@u@fAe@n@UXa@`@q@v@]\\A@a@^}@v@k@f@iAv@WLSLKF]Pe@R_@NC@y@ZG@a@Na@NkE`BeBn@eA^a@NcA^C@gEdBa@NcAb@GB_@NYLcAd@a@R]NA@i@ZWNkAt@s@h@]X_@Xe@`@MLGDy@z@STGHYZAB]`@q@z@[f@_@h@]h@OVWf@U`@]r@CFa@|@O\\EJSh@GNWr@Yz@Sj@Qj@CH_@lAKXcBjFOd@O^IZM`@Qj@Oj@W|@Y`AADQp@Qd@Ul@Sh@c@tAy@xB{@xBeA`CaAtBs@rACHqB`D{CrEm@|@gBbCW\\}B~CY^SXuDbFwAnBcArAmB`CGDyB~CqD`FiBhCcC|CqBfC{@~@aBxBs@bAc@p@MRSZ{@zAU`@[n@[p@EHs@zAa@fAWt@Sp@Qf@CHSb@Qf@Qb@Wx@Qf@Of@Qd@Ol@Qh@Qp@YlAUbAQx@M|@Mz@QdAG\\MbAKd@Ih@Gb@AHG`@Ox@Kr@Ip@Kz@Iz@Kz@SvAQlAWlB?DYhCGf@MbAIr@[hCq@`Gw@dHUpBUrBgAbJu@jGgApI]pC_@vCKx@YzB]`DQzAAJIn@EZQzAa@`CYrAOt@Kn@Ih@SbAY`Ba@bBg@nBe@rAIX[~@g@nAKTiAxB{AhCaBdC[n@KPk@t@WXKNMLY\\GFUTQRq@l@cAz@mA~@KFYRg@X[T{@d@A@_@Ty@^GBIDkAd@w@VKB_AXA?SFKB_@H_@JA?cCj@iCp@A@a@J]Jw@TQFa@LWHKBo@RsAh@s@ZaB~@wA|@k@`@_Ap@aA|@_A~@g@f@_AjAo@`A[p@gAdBcB|CqAzBiApBg@~@u@rAA@Wd@cAfBaAfBoCjFMRm@nAa@v@q@tA[r@}@|AcAlBm@pAYl@s@xAw@xA{A`C]d@a@h@a@f@a@b@s@p@cAz@w@j@w@d@y@d@{@b@mAj@qAl@_A\\}@V_AReBTeAFsCZwBT}ATa@Hw@Tk@Ls@Ty@\\a@Pa@NiAj@w@h@k@b@g@^aA|@gAlAq@z@qA`Bo@|@k@|@k@`Ag@dA_A|BKVs@pB{@rCq@hCo@`C}AxFg@bBSt@c@hBI\\Ib@u@pCe@vAi@|Am@`By@jB[p@k@fAi@bAi@z@CFiAbBkClDg@r@g@p@]\\uFdH[`@[`@{EdGg@j@e@h@GHWZUZUZmBjCe@j@e@j@i@p@eB|BaCzCmCjDyDdFgQzTY\\MNABIJiDhEw@bA}@dAgAnAkAhASR_@ZMLkAbA]ZMLoBvA]XuCvB}AdAa@Xq@d@aC~AaC~Ai@`@_BhAgBhAc@VuAn@C@]Ny@\\mA`@a@Na@Lc@LUHKBiB`@g@L]FG@o@HO@yALsAFm@F_AFuAHkAF_CNkBNiBRcALqATgBZaATeBb@aAXkBl@_A`@u@ZuB|@oCzAqBjAgCfBaClBwCrC[\\_@XkAjAkArA_AdA]b@iEdFABgBrBoEfFa@d@kCzCa@d@aBlBe@f@MN?@UTQRkAlAQR{CpD{DvEgLxMkE`FoAvAUXuB|BsAdBqAdBoAlB{@tAcAnBi@dAq@xAa@~@c@fAk@bBa@hAc@tAi@hB]rAc@jB[zA]fBSjAQfASpASzAMxAOxAQ|BKrAEbAIdBGnBAn@GvEAvFCtKArHCxSAr@?lFAlCA|DAxGApFEzECxAEdBCt@ItBIxAKzAEr@Gx@S|BK`AGj@_@xCU~ACN{@bF}@`Eg@|B_AdDkAvDyBjGqA|DuChI"
                     },
                     "start_location" : {
                        "lat" : 44.4213825,
                        "lng" : -79.6546853
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "140 km",
                        "value" : 139876
                     },
                     "duration" : {
                        "text" : "1 hour 23 mins",
                        "value" : 4976
                     },
                     "end_location" : {
                        "lat" : 46.43584629999999,
                        "lng" : -80.9684821
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-69 N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "aoitG`i`hNQj@Sj@CHqKl[Qj@_EpLO`@cLrXkClFiE|GmBbC]\\iAlAaA`AoBjBk@f@MLqJzIqI|HeBxAgAbAy@x@w@~@W`@A?W`@KN_AnAUXeAjAQVa@l@sCrCCBsBjB]Xa@^qBtBuA`Bs@~@wAlBSXaH~J_JpMOT[`@iBjCkFxHoAfBoAfBeBfC_IdLY`@yB~CuCbEc@n@wDrFs@dAoAhBwArBmIxLY`@A@mAdBgBjC[b@aAvAsGjJY`@oAhBY`@s@bAcCnDoAhBY`@mAhBiBjCoAfBiBhCoAfBW^u@fAkAdB_DxEaCjD{AzBCDiAnBYd@GJgCpEYh@cJjPWd@_BvCYd@{K`ScHfM_BtCyB|DWd@aElHo@jAwBxDi@`AwDzGyB|DwBzDcHdMo@jA{EtI{AlCcHdMkAvB{DjHWd@OXiB~CaA`B{BlD{BfDm@~@Y`@kJnNmAjBy@jAgNzSYb@}GdK{CtE{CrEYb@mAhBiC|DeA|AkIfMoFbIm@x@yIfNCDU\\yHdLY`@wDtFYb@qBvCcA|AuJ|NiI~LoEzG{CrEYb@m@~@oFdIs@dAoEzGuDvFsH~KYb@Yb@aLtP}A~BaGbJmAhBYb@Yb@{CrEcGbJQVoDrFGHYb@qGnJg@v@gBjCgBlCY`@Yb@[b@KP{EjHYb@Yb@mAhBQVGJiBjCk@|@cCbEWb@Yd@Wb@A@yArCADUf@Yn@{@rBk@rASh@Yp@c@jASj@w@vBWp@Qj@eBtEk@|AWz@}@|BgAvC{@`CeEhLaBlE_AfCc@lACD}BlG{@~B}@~B}@`Ce@pAcBtEaAlCgA|CSh@q@nB_AfC{@~BqApDeBxE?@iA~CYt@Ul@g@~AK^oB~GIZq@fCOl@?@mFtROp@Oj@yCvKcDfMQl@q@fCaAtDwAdFsCtKA@{A|FsAbFOl@y@xCYfAa@zAIXGR_@xA]nAU|@Of@Qp@W~@Ux@M`@I\\Uz@W|@U~@Y~@U|@U|@YbAa@|Ac@~A]nA]pAUz@W~@e@fB_@vAENU|@Sr@Y~@Sx@Mb@IZYbA_@xAa@zAW~@_@zAk@zBo@bCc@dBa@bBSbASdAS`ASfAQ`AYdBYbBa@fC]dB_@`Bw@bCaAjCYl@aAvBi@dAGNmBzDmAfCgBpDo@nAe@`Au@xAoAjCWl@Wj@O^q@hBADMf@Ql@Qn@Sx@YnAMb@CLm@zD_AzGKt@_ApFOp@{@~C[|@Ul@Yr@qAtCUd@ADoB`DKN[`@gAzA]`@iCfDu@`AsAdBoAbBa@j@eBxB[`@iB~BoD~EcBpB]`@QTgBpBQPgHvG}AzAuDhDqFdFoBfB_A|@cDxCON]ZuClC]\\OLsCjCm@j@IHSRg@b@SPeAbAWTsBhBIJ]^oBdBo@j@a@\\iA`Ao@j@iBbBqBhBi@d@C@_BtASRaCtB{ApA?@GDqB`BA?gBvAeAz@{D`Dw@p@o@f@yAnAKHw@f@]Re@Vc@TUJw@^MD]LC@k@PuAZm@Lk@J}@PE@_APOBu@NI@YFeAR}@PG@I@}@P]FC@k@Ja@H[Fc@Hk@L}@Pg@J]FG@QD_APWDgEr@iB\\oB^c@HkCf@gAXaAPuAVcEv@qATi@HeAReATq@LyA`@e@NqAh@q@Z_@Ra@Tw@b@i@^}@r@w@p@qBlBGH{AvAwAvAaBzAmBhBEBWVqBjBmAjAkCfCkBhBeB`ByAvA{AvAq@p@WREF_@XUTsBbB_BjAs@f@aAl@iBbAOHcAf@i@V_Bp@_Cx@eAZ}@VwCt@a@Jo@NiCn@aCl@_@HsEhAYFgHdB[H_E`AuD|@mCn@oAZeAVE@[HmAXoBf@u@PoAZYFeAVIBYFeAVa@JiAV]JkAXkAXcDt@q@PWFkCl@oEdAeATm@NuBf@m@Nc@La@Je@N_Bh@C@eAd@]Ra@Rk@^SLOJMLm@d@ONURo@l@a@`@]^WZy@bAoAfBgBjCQVYb@[b@mAhBY`@gBlCY`@oAhBYb@Yb@W^A@Yb@Yb@wDvFmAlBEFSZcCnDmAhB}CpE{A|BYb@s@dAu@dAwIpMo@~@{CrEYb@Yb@Y`@wDvFYb@ORILYb@wDvFgBjCYb@sIjMkErGsJrNaCpD[`@eG`JcAxAABY`@Yb@SViCxDeHlKm@|@oN~ScCnDYb@Y`@s@fAY`@mAhBgBjCoDjFg@p@IJc@j@QVEDUXIJw@~@QR]\\CDg@h@sApAGH_Az@u@l@kA|@_@XMJi@^c@Xk@\\m@^kAn@WLqAp@mB`AeB|@cErBa@RaAf@cCnAe@Vu@^cBx@a@Ra@RmJvEmKlF_@RcHlDsIhEaAf@iIdEmHnDmB`Aw@^u@`@e@Rq@Xw@Z_Bx@sBbAo@\\mAl@aAf@w@`@GBeAf@u@^cAh@mAl@}@d@uBbAwAr@iCpAcCnAiCnA{@b@OHa@RC@gAh@WLWLGDg@VkB~@}@b@{DnBkAl@a@ReAh@gCnAuDlB}@b@OFy@b@eB|@mCrA_Bv@}Ax@e@TeBz@qCtAs@^aAf@eB|@uCzAaB~@KFa@Ty@d@gB`Ao@ZoCzA}@f@qGlDaLfGqEbCuBjAIFw@`@sBjAoAr@A?]TaB~@_HtDu@b@oDlBwBlAwJnFyHfE}DvBsFzC}@d@o@^}DtBWNcGdDcB~@aAh@g@XsBhAy@b@gDhB}@f@yC`B{F|CwAv@_@RaAh@WL_DdBYNu@b@m@Zy@d@o@^g@ZsQvJiAl@oAr@oFtCaAh@kLlGSJ_FjC}IxEa@R{C`Bw@b@u@^g@VWJEB]Ni@Tm@T}@\\u@Ti@Nq@Ra@Jk@NC?[HE@WDc@J]Fa@F]FUDE?]DI@i@Fi@Dc@D]BWBy@FoCPG@yCRqBLkGd@k@Hu@DqAJkBNyALi@DqAJe@D]DUBYDQBSDOBMBQDYHYHQFODWHOFSHSHQHSHOFOHUJWNMHSJSLMHOJSN_@Zc@ZGF_@\\]\\[ZYZA?Y\\A@SVW\\SVQXORQXQVQ\\U^QZSb@Uf@Ud@[v@Sd@Ob@Sh@K\\Of@Of@Oh@Kf@Mb@Kd@Kf@Id@Id@I`@Ij@G`@Gd@EXCR?@C\\Gh@CX?FGv@Gx@KxACh@Er@Gt@Q`Dk@jJO`CEp@S|CWtEO`CEp@Et@Cf@C\\KxAI`AIt@Gn@Mz@CTE^Ib@Il@Kf@Kh@Mh@]|A]pACH]dAYx@[x@Sj@]v@_@r@Wh@a@r@_@n@[f@_@h@Y`@MP{@dAwAdB{@bAuAbBKLeAnAiAtAaAjA_AhAoA~AWZ[^GHST[`@C@kB|BuAbBsBdCmAxAuDrEmGtHoA|ASTGH_AhAg@n@m@p@YZWXUT[VWTUP[T]Ry@b@[PYL}@`@uBbAa@RiFbCa@RA@kD`BsCpAsBbAgAh@aChAcChAyCtAiBz@aCfAkDbBwCtAgBx@w@^gD|AULKDgD|AWLkB|@a@PeBx@uCtAuAn@cAf@e@Ti@XQHqB`AcAd@[NEB_@Py@^gAd@e@TSHcGrCGB_@RaDzAmEvB_@PeBx@ULsAn@GBc@RgBx@cElBaAb@_@Pc@ReClAcD|AA?cBx@{CxAk@XiEnBiAh@cGrCa@PmCnAmErBSJw@^wBbAkGtCsJrEaAb@sB~@u@Vk@PYHc@JmD~@a@J{A`@}ElAeAXuIvB}MhDkAZ{UhGkCp@ODSDiItBkItB{Ct@sKlCuA\\wDbAwBh@cFrAkCr@A?kD~@_B`@I@a@LoG~AaIpBkCp@{@RsCt@c@LmD|@c@LA?gCn@eAVwFtAcAVkCp@mD|@a@Jc@Ju@RkFrAWFu@Ra@JGBkFrAc@Lc@JoEjAwDbAqCp@c@Lg@L]Da@HeAPu@FS@c@Bq@@gA?m@Am@CA?a@Gc@EI?YESCs@Ka@IEAiAYYGoCs@oCu@YGa@Ma@Kc@KQGOE{Aa@MCcAYc@Ma@KOEwAa@c@MgBe@UGwCy@iBg@cAYa@Mc@Ma@Ma@KKE{Aa@c@K]KqDeAa@MMEUGa@MeAYw@SME}C{@OEa@IQEQCc@Ia@EA?[CEAc@AUAM?o@@i@@e@DYBe@FWD_@HA@mA\\}ClAqBz@sBx@eIfDwB~@aC`AeBt@a@NoH~CcA`@a@Pa@P_@Na@Pa@PiDvAeBr@a@PeCdAcA`@aDrAi@Ta@PoHzCa@PcA`@a@PgDvAcBr@c@Pa@PoAj@k@TIDa@NYLg@LC@e@JQBQDYDE?UBW?Y@I?_@?e@Ci@ESEOAm@Mk@MiCy@GCw@Us@UUG[IUGq@MA?MAOCSC]EE?QCQAc@C}ADsBPk@Dc@DwA^wAd@}An@kFjCwCxAoAr@a@Pm@XiB~@sCrAOHuCzAk@ZaD~AiBhAo@b@yDfCcD~BSNkBpAuBzAgBlAmAz@o@d@_BhAw@j@eBjAaBhA}CtBIFu@d@QJy@^yA^_APo@JA?wAJwABcF[WC_EY}AMuFa@cF]{F_@iBMkBMaAIiE[QCc@COA{BQwBGuBCcGM{FDE?wFAu@CkBEsDKgACgAEkAC]CgAIoCSmCSgAGsDY{CSaCQsDWaIk@gAIiBMgAIeBKsCUoCS[CsBMiBMuDUa@CgAKc@Cc@EeAIgAIgAKgAIiBOA?eAIgAI}@GeAUc@KmAW}@Ua@Ma@K_D_Ao@WgDyAi@U}Aq@aAc@iDyAaAc@OGQIa@Sa@QaAc@aAc@cAc@cAc@cBu@aAc@cBy@cAe@_@Qa@SqD_BcBu@cAe@s@WcAa@{@_@mBq@eA_@gBe@iCu@kCu@C?cB]gASiB]cAQe@IeASeAQkB[]GCAc@Ec@EgAKc@Cc@Aw@IiBQG?mBIY?}@AyCBiB@A?oCNk@DYBsDXk@DaBRmCXc@FkBRgALs@HkGr@cAJe@FyFl@gALeALA?iBRc@Dc@Dc@Dc@FeAJc@Dc@FA?a@DeALgAJc@DkBRg@F]DgAJmCXkBRqD^mCXc@FM@UBgALa@Fc@Fc@Dc@Fc@Dc@Fa@DeCXQBy@NM@E@G@w@NsE|@UDgCv@YHwAd@MDy@VKDcAb@[LiA^cBv@eCjAaCrAy@d@}@r@]X}@r@{BfB_@X_@X]X}@r@_@X]X_@X]X_@X]XKHSN}@t@]Z]X_@Z{@t@_@X]Z]X_@Z]X_@Z{@t@_@X{AnA{@t@_@Z{@t@}AnAqAfAsAfA_EjDqAhAcDlC{AnAw@n@aA|@}AvAYZkCpC{A`ByA|AoA~AeBxBwBlCoBbC{@fAKNoCpDm@v@mBfCqAbBmBfCgCfDmBfCkBdCmBfCy@hAuAbBcGrH_IbKkJtLqAbB[`@_EfF[`@SVwFrHiG~HoIvKqCpDmBlCqA|Aw@`AsA`BiCdDY`@i@n@i@p@w@~@w@`A_BlBQPuAzAy@z@]\\]^ABYXg@f@o@n@]\\]Z]\\{@x@wAvAGFqAnAi@h@m@l@kAhA[X{A|AKJuCnCiAhAqErEg@f@cCbCaE|D[ZqBtBCBmErEGBGDOLWRoBjBMLeAfAmAhAUT}B|Bk@j@gBfBA@w@x@yAvASRe@f@{@x@{@z@uCpC_A|@uAzAa@d@a@f@STSVORIJs@|@cAtAOVg@z@ILCFKNa@p@OT?@[f@}AtCyB|DyB~Do@jAILMVKPaCfEaCdEGLOVEFCDaA~AILg@x@[d@{@tAGFyApBGHABk@x@c@n@Yb@QR}AlBaBhBqD`E?@IHMNEDuDvD_CxBOJ?@IHoAfAa@XqAfAkA~@y@j@A@}@p@_@VIFSNA?IFA@sAz@sMrImDxBA?KFSL?@KDeF`D[RSLA@IFaKvGSLA@IFUNiBlAuEzCKFiAt@i@ZA@IFULIFuBnAKHcAl@qD`C?@KFGBkAx@KFSL?@KF_DhBmCfBu@d@GBKHi@\\a@VKFq@b@uAv@aAb@ULsAn@KDSHA?[NiA`@KDSHA@mDrAqHxCA?sAf@q@VyBx@qBx@qChA{@Zi@Ta@NiC`AoKbEqChAaE`B_DpAIDiG~Ba@Ni@R_Bl@eBn@?@a@NUFeA`@yAn@ULc@Pi@Rg@RwAl@gBn@kAd@eAd@w@Zc@TaAf@mAv@aB`AyAbA]TyAlA{AlA?@{@p@{GzFqAdAEBWTEBw@n@EDuAhA]XGFqAhAg@b@oAhA]XeB~A{AnAQPcKtIeCtBeBxAkA~@WT{@r@{ArAcElDqNxL_KtI[X}ApAuFvEMJaCtBGFoDzCuD`DsBfB_EfDo@h@{AtAKJi@h@gAhACB_AfAcBvBw@fAGHmAfBmAlB]h@o@lAA@Ud@_BzCWd@?@gDlGYj@y@zAKRs@pAe@t@cA~AyAtB{ApBCDuAzACBaBfB{AtAyAnAQNw@n@]VeBfAa@T[Pc@Ty@b@o@\\{@^c@R[LeAb@}FbCgMnFsElBa@PeBr@oCjAYJcC`AC@a@PcA`@gDvAkAd@_E`BaA^g@R]NaBp@iAb@oAb@qCv@KBeATgB\\SBi@HuAPuANqCTaAFsAJe@@aAFqBJuALcDR}DT}AH]BI@{@HS@S@U@yBP}AJu@Fm@DiBVk@FsAVeATKBwA\\_AVg@PUJs@TaBr@uAl@A?aBz@}@f@iAt@cBhAkBvAs@n@sAjA}@z@cAbAONcAfAY`@Y\\s@fAKN}@pAg@v@s@jA}@zAs@tAe@|@CF[n@[n@g@hAWl@Wn@MXUp@i@tAWv@m@lBw@hCgKz^iDzLu@~BeBpFeAxCUr@cBlEmCpG]x@mAhCc@|@{@hBw@|A[r@aBdDcAtBcArBuAnCiCnFoFnLcAxBUf@gCpF}CzGUf@cAxBMZcAxBuDhIc@bA{@fBQ\\c@~@KXQVyAbDiEhJe@bA_@~@]p@uBvEuArCUf@q@rA}@`BKXOXYh@a@t@m@bAwArBSXi@l@g@j@eAtAaAxAc@h@_@d@g@d@c@`@kB|AmA`Ag@^q@d@y@h@_B|@o@Z?@y@^s@^YJg@Rc@PWJA@c@N}@Z{@Xi@LSFWFi@NSD]DoAJo@Fo@F{BV_@Dg@Da@Be@BW@_BHi@@YBO@m@Fg@Fk@Ji@Fk@Ho@De@BaAFa@@g@BwBFU@oADsADm@@i@BeA?sB@cABU@aAFi@DWBWDqAVaAJsAFgBHeAFm@Fc@D_ALoAPgAVy@VaAVkC~@}Al@[LwB~@{BjAMHULA@QJe@XQNSLQLSLOLe@\\y@n@QLABC@KHSPa@^a@b@SRc@b@QRQPSXaBdBGHIJA@q@v@MNQT{@lAQRo@`AILKLINw@pAS^_CjE]n@_BxC{ApCCFYf@Wd@_BxCoCdFaBzC_BvCiAtByExIi@~@_@p@Wd@oH`NoEhI{IjPWf@cDbG}BhEyFlKuBzD}CzFWf@uAfCMTm@hAKPi@bAk@~@Wd@cBhCa@j@q@`A[`@e@j@m@t@eAhAa@b@eB`BSTeBxAsAbAOLa@X[RQJe@\\m@\\a@TQJe@VUJOHC@QJoAj@YJwAh@UHq@TqA^MDE@uA\\QDUFUDKBA?a@FMDUB[FmAPK@WBc@DiBPgADq@@yB@eBAuAGe@CgBQI?sBSc@IWCqAUWGgAWcDaAc@MOE_DoAwDoBkC}AUOmEmCaAk@sBkAa@WoBkAeBcAQKQMaB_A{@g@iQmKoAs@qDwBMISM_B_AcI{ESMeBcAmAq@{@c@c@SYMuAi@OGg@Qy@Ws@QSEeB]qBWmAKeAEcBEiGM{FKuEIe@Aa@AmCEuAA}A@qADy@FsAPyAT}@T}@V_AZ{@\\KFYJ_Ad@C@kAr@kAv@m@d@WTm@h@k@h@u@v@[^e@h@s@|@OPm@z@eB|BmCrDaBzBQTm@x@KLUZQVcF|GeBdCwAfB[b@aErFSXC@W^ABEDeBhCcC`D_BnB[^YZk@h@u@r@EBu@t@u@n@WRc@Zc@Vo@ZoCjAuBn@iB`@q@JaALgAJaAFs@@q@?_AAs@CeAGs@GWEmI}@{AWsC_@sBY}Ek@a@G{C]_Fi@wBSeSaCi@G{Fq@qAO_Eg@}@Kc@Gy@MkBW_AOQEq@Om@OOG[Ig@Sa@OWKOGQISKe@Uk@]q@a@g@]c@YKIs@k@WWe@c@sDyDmAsAA?m@q@cAiAAA[]yAaBy@y@_BaBg@i@c@a@UUCAy@q@c@[e@]UOmCuAWMq@[oA_@i@QICq@Qu@Qu@MGAmAMcAI_AEeA?i@?_@?g@BY?I@k@Bu@HiANu@Lc@Lm@Lm@Pa@NmAd@uGzCMFa@RgI~DeAj@WLsExB}E`CaLrFy@d@aAj@eAn@{CrB]VA?u@h@}CbC_CrBKHiB~A_A|@g@f@w@x@GHu@z@y@dAeApAo@x@s@`Aw@fAq@`A_AzAsAtBw@lAk@z@u@jA}@pAk@|@m@x@]h@o@|@Yf@a@n@kAhBk@`A}@pA_ApAuA`Bw@`Ai@p@{@lAq@|@m@z@u@t@gAfAQPUPGF_@ZsAdAcBvAcBlAyAdAmAz@q@d@cCjBw@p@KH_Ax@m@h@UPoBpAq@b@s@f@yAfAuBzAqA~@m@d@e@d@c@b@gAdAa@^u@r@m@n@e@b@IHs@t@o@n@i@h@[Ze@h@SX{@hAgA~AmAfBo@dA{@zAm@`A?@Wb@ABm@hAA@cApBYh@Ud@EHk@fAu@jAg@hAo@tA}@rBm@|AcAjC_@`AqBlFaAbCs@`Bu@hB}@nBe@fAq@vAu@|Aq@rAu@vAS`@U^CD_AfB}CpFq@hA?@W^W`@EHaAzAi@v@m@|@QVqAjBoBjCo@|@yAdB{BlCi@l@sEtEGF]\\_GxFKJ}AvAwFhEoHzF[VA@yDxCmEhD]XyDxCa@Z}AjAkAz@aBjAeDzBi@Z}@j@w@d@iCtAs@`@s@\\cD`B{@`@oAh@}An@kAb@mBv@gFfBiCz@gC|@mL~Ds@TwG`CyLfEKBa@NA@gCz@eA\\a@NmBn@aBf@_@LeA^mFlBmDpAqGzBa@Na@Lc@NkDfAa@Na@NcBj@iBr@uBx@SFkDjA_DdAMFWJq@XiB`A]P]PaAj@o@b@MHkCnB_CxBA@sBvBaBrBaAzAeAhBu@|AmAtC_@|@u@zBOh@Of@a@dBs@fD]rBGf@KdAKt@@b@_@rDCj@UnDQpCk@xIOxCa@`Ia@dII~AKlBEr@SzD@tAIp@ALIh@Mt@YbBMj@GVQv@Ol@A@Sv@Ux@[`A]tAk@pBELUr@Ob@Yl@Wh@QZEHQXWb@{@pAMPw@jAm@bAa@v@Q\\Qb@Wr@Ob@CHSt@Qt@GRIb@Kj@CPE`@CNI|@Ef@Ef@?JCj@?FCr@?BAz@?f@?N?b@@n@Bl@B|@?BFfAJlBHdADr@FjABZDp@NpCZnFXpF@DDxABz@@\\@~@BpBD~F@lBBbDBfF?~C@nC@tA?tBB|C@dELzY@bC?tA@lD@z@Af@A\\Ar@A`AGxA[nGAVc@nICh@IbBK`Bs@pNa@lH]lGIfBaAdRYfFk@|KQnDOrC[xFm@fLg@hJStDYbGIxAe@hJg@zJIjBU`EWbFUnEMpCKfBUpEGFCBAFCFCx@C`@MpDAh@AfACrB"
                     },
                     "start_location" : {
                        "lat" : 45.4374529,
                        "lng" : -80.1244863
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 623
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 43
                     },
                     "end_location" : {
                        "lat" : 46.4356975,
                        "lng" : -80.9685966
                     },
                     "html_instructions" : "Take the \u003cb\u003eON-17 W\u003c/b\u003e ramp to \u003cb\u003eSault Ste. Marie\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "aolzG~cemNCLELCPCf@Cb@Ib@GTIXGLMNML_@Te@?WASCUGOGIGYQIIKKIKIMSa@IUGQESEYAMAU?U?QB]F]HW?CFONWHMJKNKRKBALCRAV?J@LBJDPJRRJJPRf@p@~@vADDDBJD"
                     },
                     "start_location" : {
                        "lat" : 46.43584629999999,
                        "lng" : -80.9684821
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "32.7 km",
                        "value" : 32717
                     },
                     "duration" : {
                        "text" : "19 mins",
                        "value" : 1157
                     },
                     "end_location" : {
                        "lat" : 46.3769284,
                        "lng" : -81.347385
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eHwy 17\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-17\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "cnlzGvdemN@B@@NTVd@zB|DfAlBXf@Vd@d@|@h@fALZTh@d@lAVt@Vz@Pt@VdA`@lBt@rD`@zBZfB@Jl@xDDPJVZhCb@bEZ|C|@`JZ~Cl@jGLlAt@nH?@XnC\\lDD`@^rD^rDFj@X|Ch@vFPhBf@~EJjAHv@HhABr@F~ABpAA\\?rCEjBGlAMtBGp@Gr@?BW`CCNOdAc@|Bc@bBKd@gAzEmAhFOn@s@xCSbAoCtLu@hDeAxEI`@CDKb@GZGXgAtEe@~BUbAIh@]jB[pCOfBIz@GtBAZ?TCdA?rA?h@BxB@XZ~Gl@tGl@dFVzBJx@P|Af@fEd@~EPvCBXBr@HnBDxB@V@t@@x@@`C?R?xDC`BCZUbGCp@C`@APQpBk@bFe@hDSnACFKf@m@`DWrA_@xA[fAWx@e@bBk@~AWr@Qb@Q`@Sh@k@tAYh@[n@S`@_@p@OZEF[j@cD|FaBvCsH`NaA`ByBxD{B|Di@~@w@xAu@rAk@jA_AtB[z@{@`CKZOf@s@nCCJg@bCMn@e@hDc@bEMbBGvAGvAEhAE`FFzD@t@B~@Dx@JrBPdCD^ZzCPlAJn@Hh@@D^rBVdAn@xBj@jBh@zAb@hAd@`Ad@fApAlCZp@Vd@|A`DpB`E~AdDfCjF|A~CJTpCxFZn@d@~@dBlDz@fB\\v@|A~CVf@jAdCtFhLVh@fA~Bz@dBZp@Vf@`C|EpF~KVf@zA|CN\\nB`EzA|C`BfD`C|ErAfCjAfCf@hAP`@Vp@\\z@d@nARj@n@lB~@`D|@fDXlAr@fDz@nEpAfJZpDX`DBl@Fv@JrA@XJ`DD`BBz@HtD?xB?zAApACtA?JElBO`E?^GhAE|@EfAEz@MzACb@Er@I~@yBrM_@hBQv@y@xCqCtJiAnF}@rEw@rD[xAcDxOMp@Mn@I^uClNgAjFm@zCq@pD_@xBSvAIn@Gx@IjAADCl@E|@Cl@EfAC~@?t@AJ@tBBlA@|@DjAD|@Dz@HlAL|ALhAX~BXdBPdAjBpL~@|FdAtGbArGbBfKRpAPdAHh@ZlBfA`H`@hC\\`CRrAJz@NvAThC@NTbDLpC\\hHVdEPvBHz@RdBVpB@LH`@RhAj@~Cp@bDh@fCt@tDZ|AhGrZvEhUzFnYh@lCd@rC\\rBXtBXpBXtBBZP|AVtCN~ARtBl@vHNbCNxBNfCBn@@BRjEHrBLjDHdDBr@JzDJnDXtJPlG@h@HvDNrEHbDD~ABrAHnD@?PhEDv@DjAHjANvBNnB\\nDD`@P~ANpAXzBNfAVjB\\rBFd@BJ`@zB|@rEVjA`@dBd@nBPn@`@xAxA~E?BRj@DPr@pBTr@Xv@`@dAPd@p@`Bv@jBtAxCnAjCP^dCdFBHrC|Fz@hBlAdC|@lBTf@zA`DTd@?@Tf@?@`@z@HTLVFP`AhCb@jABFLd@Vr@Lb@Pl@Pl@h@lBHXNl@FRb@dBXxAThAV~AhAlGzClQfApGxCfQfBdKJn@PdAfAnGr@`EJp@~@zFj@jDd@nCt@fEd@lCd@nCt@dEbA~Fr@hEjA|G|CtQd@lCb@nCJj@Hf@R|A@LJp@BTHv@H`APpBT`ERbFBhCBpB?n@?V?tBC|AAjAANAb@Cv@IzAE|@O|AMtBe@nEk@pEQfAAFWvAYtAQx@ERg@xBMl@CFy@tDCJK`@}@zD_BbH]|ACDKf@On@k@hCABOl@m@lCaBpHOn@y@pDa@fBS|@y@lD_@fBU`AUhAYtAa@~ACLK^]rAi@rBYlAG\\a@lB?BYvAWxAIb@[fCQ|AIt@Q|BCVCd@Ez@KrBAj@G|ACpB?^?RAdB@t@?l@@D@pABhA@VFvALrBD\\Dp@@LT|BNzANnAR~ATxAVpAd@nCPdAJn@`@rCDVh@lDVfBf@dDh@lDJn@lApH`ChOhDzTt@~E|@tFh@dD\\tBFZbAbGPjAV~ApBvM|@`GHb@p@dETjAJh@VrAXpAd@jBZtAh@pB\\nA`@lAHXdBdEz@zBlAlCz@hBBDXb@p@rAhAnBjAfBnAfB~ArBpB~BbBtBnClDRTZ`@fBxBb@h@Z^Z`@xAfBhC|C`BpB~EjG`BrB`BrBpBjCtBhCpA`B`BpBbChCtBfC~@lArA`BpDrERVFHrA~AFHlAvA`CzCpGfIbFnGfApArBhChAvA"
                     },
                     "start_location" : {
                        "lat" : 46.4356975,
                        "lng" : -80.9685966
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "269 km",
                        "value" : 269006
                     },
                     "duration" : {
                        "text" : "2 hours 54 mins",
                        "value" : 10462
                     },
                     "end_location" : {
                        "lat" : 46.5207121,
                        "lng" : -84.27651059999999
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eHwy 17\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "y~`zGbdooNf@p@n@~@PZXb@DFXf@N\\FLPb@Tf@b@jA`@nARr@^tAVnAPrAJz@P|ADf@@JH`AXrDLbB@HDj@PzCL`B?HDd@@LTfCd@vFRdDPlCHhAFbALrAXvCFVXjEFr@?HFl@LrAPxBRvCN`BDr@N`CFbANrBJdAZ`Ev@hKPhC^pFPxBLdBVnCNbB@?ZjELdBXtDBV\\|ERhCLlBThC?BFp@NnBDh@LdBFr@@PB^B^@RDp@Dr@Bb@@NB\\BT@RB\\Dd@JnAHrA`@zERfCDt@NdB?HDh@@JHv@J`ABPJfARxAXpBBTRtAL|@Jl@Jr@PhA`@xBf@rCf@jC?@t@zD^tBH^Lx@Jf@RpA\\nBBNH^\\vB`@`CJj@Ln@XbBX|AN|@P`AXbBTnAh@dDd@pC`ApFRfA`@zB`AjFLj@F^FXDTJn@Z~AHd@@Jh@|CJl@PbANbAF`@Fh@Hj@Ht@Ht@BVB\\HfAFbABXDr@?FBn@@R@f@@|@BxABfBDhBBp@D~@DzA@^FlCFvBH|C@d@?LF|BB`ADxADnANnEDj@F|@Fp@BPB^Ff@Hr@DZFl@Jt@BTDX?@Jl@TrAN`ABLF`@@DLn@Z~AFVJb@Tv@l@nBx@zBh@vA`@dA`@`Ah@dA\\r@j@dAdAhBFJPXjAlBVb@PXz@tAVb@lAlBVd@TZv@pAXb@Vb@r@hAjBzCdAdBXb@jI|MlClElAlBdBpCx@vAFHf@dAb@~@^~@@B^`A`@fATt@HXNl@L`@XhAZ`B\\fBPfA`BlJb@fCF^Jp@r@`EX`BFb@j@|CJn@nAjHJh@p@`E~@rFd@nCJp@X|AbArFJl@?BNl@Ln@P~@XnA\\zALf@f@`Bh@jBtAhEdCxHnD`LBFLb@Rj@nBjGPj@v@dC\\dApAdEb@vARl@rCdJPj@Pj@hArDPj@d@xAp@xBrGrRl@hBr@rB`@rAtA~DvE~MPj@nAnDPj@Rj@bArC|@lClAnDlAnDd@vAr@pBXz@Pj@Rl@d@vAd@vARh@Pl@Vx@d@zAH\\Lf@b@bBRx@Pz@\\bBP|@@DX~AHf@@FJj@TbBHd@\\jCFr@d@bF@JD`@LvBLnBNpDF`C@p@BpABhB?f@?`@AfD?x@Ar@?FElBAd@A|@Ch@Cp@?@]tHUnEMnCEr@Cp@Ex@QzDiAhU?DEr@E~@KfCIbBE|@Er@Ep@Q`EEz@E|A?t@A~A?pAB|ABr@@`@DxAHhA@FJ|AP`BPtAPhA?@b@dCJb@R|@V|@\\jARn@DJL^Rj@nA|C`AbCfBnEBDRh@tAfDRf@nAzC\\z@zCrHl@zAN^BHdAbCP`@Th@vAjDPd@Th@bBfEf@tAbAfDNp@d@zBLr@DTPfAHp@Jv@LjA@HFr@HdADj@Bt@DfAHvB?vCAjAE`BAl@?DI~AGx@?@Ep@Iz@MlAK~@AHGf@]|BwAlJ?BKl@In@W`B_@~BQbAc@pCYlB[pBYbBu@jDk@vBSl@Qh@i@zAWl@Yn@IRg@hAe@x@e@x@u@fAa@l@s@jAS\\S^CDc@z@e@bAQ`@KTIRQf@A@a@rA_AvD{@fE}@lEgAnFCJs@dDCJiAjFc@nBKf@_@bBWtAU~ACNQzAMtAIlAEn@G~@Cf@EhAA`A?NAr@?t@@nCB|@Br@?NJlBLlBNzAFf@PrANdAP|@^vB`AdF`AjFbAnF^pBLn@DRFZlA`HjA~F~@hF|@`Fb@`ChBlJb@bCPz@bApFNp@fC~MLn@~CpPd@bCfA~FJj@Z~ALp@z@rEtB|KpA~GnEpUJn@Jf@\\fBHd@BH\\tBPpAPvALlAF|@HhADdAF`BBpA?hBAx@?TA\\Ar@?@Cp@AVAZEl@Gv@CXCVGr@?@KfAEXG`@QjAIb@Mn@Id@a@hBMf@Mh@q@tDEVEXMz@OdAMbAKnAO|BEp@Er@CvAC`B?lB?FDpCHfCPxBLdBTzBLhA`@`C`@jB^zAlEhNzHlV@DNd@|HrV@Fz@jCbGnR|@nC`EnMd@xAjHfUPj@Pj@jApDbAdDnA~DPj@j@hBrAbEBF~@dCx@rBlAnCtDnHbAnBVf@rGdM`@t@tBbEVf@pDbHjA|BzN`YnCnFh@bAlAnCt@jBf@zAhAtDNl@l@`CNx@XvA\\rB`@fCl@|DhBzLDZJn@XrBl@lFFd@h@tF^nDb@hELnARxBv@lHNvAJ~@Hp@XjC@HHp@Db@RpA^xBZpAb@`B\\~@z@pBv@|An@pA`CxEdAxBnAzC|AxD`B~DrCdHXr@dDhIlA|C\\dAJZLd@@FTx@Tx@RbA?@VpALt@Jr@@DHp@Fd@N|AHtAHnADlA@pB@pA@`B?n@?hDA|N?`U?r@AhO?zC?r@AfO?r@?rM?|C?r@@dHDjBDdAL~BBRFp@?@NzAJx@\\jCr@~Eh@fDLz@\\`Cn@dE^~BZvBVbBBNvBpNpBvMN`Ad@|CXrBZ|BHv@BVD`@\\dEj@zGt@zIDX`AhL^nEBXR~BhAdMZrDj@bGdA~LTnCPvBJ|AJbAJrAFp@TjCHvA@ZHtALlF@|@DbEBbE?X@Z@xE@xCB`G@rD?T?V?jA?|@Cx@GnBEt@AZCVO~CSxCOtCe@rHMpBANSvCE~@IlAQ|BGtA]`GCXEv@Cd@c@dHk@~JkAbQSxCUbDSvCEr@MdBCd@a@|FUfDGr@MdB?@En@OdB?FGj@StBE^MrAKbAIp@KlACVQbBGr@ABEl@EXEn@CZANCZA`@Cd@Cv@?|@?V?h@?l@@f@BZ@T@\\B\\Dn@BV@FDd@?BD^Ff@Hl@F^DTLj@HZH^Tt@\\hAvB`HrCbJPj@bCvHlAzDPj@f@~AzAtEJVX~@Rl@DJJ^FRTt@DNNl@@@ZlARz@H\\R~@Pv@VvA@FTvA?@Jn@Hh@PxABPD^Fn@HbAFt@B\\^pFPhCBV^dFnAvQDr@f@pHF|@^tFZjEDr@LdB^~FDp@LfBF|@^rFDr@Fp@RxC?Fb@rGP|BLnAJ~@Lt@@HJd@BLT~@DNPj@Pl@hApDRj@d@vABJL^x@bC`ClH@F~A|EPj@x@bCPj@hDlKHR`A|CRj@hDlKTr@`@nAPl@BHVbANz@Lv@Jz@Ht@B`@@RHpADr@@ZJ~C@RV|HD|AJ|CHxCRfNHzE@r@Bv@@r@DlCPhL?@@p@?@NhJ?@?NNvI?B@n@?B?JH~D@r@?B@n@@r@?BJrF@~@@@DxC@l@?FDlBBn@Dz@FdAH~ABXFt@F|@d@pGVlDLxA?H@@Fv@Hv@Fb@@@BTRpAJh@Ll@?@Pz@Hb@Ll@@@Z|A?@Lj@@@XtAjArFNp@\\zA?@\\zA?@z@zDR`Ar@dD@JFZDR?DJp@Hp@z@pK~@~K\\lEf@`G~@pLbA|KJpAFp@H|@Hl@Jt@Lh@Jj@V~@Ld@Vr@b@`AZn@NVJRPVb@p@f@l@HHHHRPJFNNt@f@\\R~@`@\\Nh@N\\F@@^FB?d@Dl@FfBLfBNvGf@b@DnCT^DTB\\Dd@Hb@Jh@Lr@Rp@T^Pf@T`@T^TNJr@f@d@^h@b@b@b@\\^DFTXZ^BB|@pA`@r@BDTb@@@Xj@Rb@Xp@d@jAX`AV|@Tz@Lh@Pr@d@xBd@|Bl@lC^jBl@lCLn@Nn@vAzGLn@Nl@vA|GNl@x@|Dl@lC\\~ALl@z@|DlAvFb@bBr@lCbAtD|BtI~AxFz@|CZdADRj@hBVr@HZb@hATn@HVNZDLTh@Xj@Vf@zAtCHNLTzHpNZj@l@dAnEdI`BzCbBzCFJ~@bBnAdCBFd@~@f@hAf@lAx@pBl@`BHTPh@@@Z`Ad@zAl@tBb@bBVfAR|@ZvALl@FXThAJj@b@bCBJdAnFZ~AvBtLvCdPJn@Lp@x@tExE`XLn@VtAbAzFf@pCjE|UHd@X~ALp@bC`NZ~AJp@Z~AJn@dCbNlDxRLn@hBbKLn@pCrO`FtXf@nC~BzLDXTjADRJn@DTLp@Lx@Jt@Hf@Jx@Fh@F`@BZ?HFh@Df@LlBFv@Dx@NxBNzBFz@RdDXtEHpADp@`@lGZdFTrDNvBLpBJlBBVBZV~DVvDNlCHtAF~@HfABXBh@LpAHbAFn@J~@BRHh@Hh@N|@l@hC|@jDNl@dCnJfDjMNl@`@zAlAlEfAbElBdH`ApDH^v@tC\\vARz@R`AVvABPHn@DXLz@P|AR`CJ~AHjCH|DLrEPzGNvFLzDZ|GHnANvBVtC@F`@dELdAbBvOD^TtBZpC?BZvCRhBh@`F\\hDPbBHp@NvAlAxLTrB~@vIZrC^lDDXD`@D^@DFp@Hp@ZvCD\\t@fHp@nG\\xCv@lHdC`Ul@tFx@zHhB~PXhCXlCHr@XbCXbCJbAH|@HdAHxAC~EEtAC~@SzECjACnA?F?P?X?N@j@@j@@\\PlCd@bFr@pGd@lF\\zDb@zEJhAN~ABZH~@Dv@Ft@Bp@Dl@?FBh@@^BnA?rA@pB@`@?bBBnB@t@B~@Bv@Bf@Dn@Db@HdAJlANdB^xDBRFr@NbBH|@h@|FTjCHz@DZ`A`Ld@jFz@xJx@`Jx@`JpAxNhAfMhBpSd@bFRvBT~B`@vGVxEDbAd@~LHdBt@~SBr@DjA@Zb@zKV`GT`GPlEt@hRPbENhEDnA`@hKDdAz@pUj@bOh@lNnA`\\RxEn@|OPnEL~DBj@h@vMBp@Dr@Bp@v@nR\\dJNbER|EF`BNrDLzCBjADfA@dB?tA?VAbCG`CAVGzAOpCYlDGn@W~B]xCy@hG_@tCsB|O_@xCaBzMSvBM~AKrAKfCGlCExD@`A?r@?r@?bABhGFpN@vC?B@r@DbG@r@@r@@r@?r@@r@F`G@lDHbO?r@@fB@nEBzC@fB?r@@zCBlEBf^?vH@~E?tH?|B?vI?r@?vH?r@Ar@?fB?r@?fB?r@?r@?nE?@?z@Ah@Ab@Ab@Cf@Eh@Ej@Gr@Iv@[tBGd@Kl@Kb@_@lBGNa@zAc@vAg@dBy@zC[lAKh@EPG\\ETEZEREZEZCTIf@AHIp@AJGd@Gn@SbBShBOrAI~@Ip@APE^Ip@QlBAVC^AR?JCr@Ab@?j@@nA@d@@`@Bv@DfAHfAFj@BTLvAFh@Jx@d@tCt@~EV`BJp@lBvLb@rCPdA`BnKLv@Jz@TdBLpAFn@Dv@HtADhBDtCB~B?d@?nA?jBAvG@jK@f\\?rM?jA?n@@jJ?jJ?r@@fA?nA?lC?hL@zC?r@?r@?r@?bG@bT?xC?zC?zC?r@?r@?fB?r@@bG?|@DdE@pABdCLpPT~XBnE@r@DlE?r@LrMH~KDnGBlCPnM@|@@r@D~G@dCFfCB|@BfAHxAJpAPzABRFf@RpATtAp@tD\\jBX`B^rBJh@Ln@BLzBjMLn@X~At@`Er@`EhB`KJn@`ApFZ`B`Hd`@PbAjAlGLn@BPNr@v@dDT|@Lh@b@rAZz@Tl@HPb@~@f@`Al@dA@BV^p@hAlEnGpBpCb@j@^h@zBjDT\\b@n@l@~@NRVf@Zl@Vh@N\\JZDLHTHTHZLf@DXFXLt@@PD\\BRBZFz@Bv@B|@?dAAt@Ad@C^AXCVCXCXE\\G\\Gf@GXKl@a@|AOl@a@|AqAxEoA~EmAvEaBtGi@tBc@dBaAvDiBlI_E`Qy@dDA@[pAm@dBe@nAaBnD}BrEwA|C_@dAYx@Sl@W`AOl@Ol@gAjEwAlGmAzFs@vCiA|Ei@vBc@nBA@Ml@Sx@[pAWfA[tAOl@Ib@I^GXGZGZEVEVEXGb@Gd@C\\E\\E\\CZATC`@C^C`@A`@C\\Ch@Ah@Cd@Cv@EdAGnAAVCr@IhCMvCEpAIlCE~@ElAEdAElAAh@Ad@Cd@IvC?HCr@Aj@ClAAp@Av@CpA?fAAz@AjAAjA?Z?dA?`@?fB?pC@dDD~K?r@@pD@dEBrN@vH@jA?nA?zB?^@tB?v@?z@?n@AZ?RAr@Cj@Cr@Cf@?HEx@EfAE`AANEbACdAE|@Cp@Cv@EpACv@Et@Q~EKtCKnDCh@Ab@A^AX?VAZAp@Cz@An@ElCEdBG~DEvBAb@CtBAd@Ar@AZC~ACnAAfAA`@AT?f@Av@Ah@?d@AH?j@?p@?|@Ar@?`@?n@?n@?v@@`A?~A?bA?F@jA@dABnG@pABvFB`HDbH@r@?rADvG@fBFrM?r@DvHFfO@r@@zB?rA@r@DjJBjFBbF@hB?J@zA?r@@hBBrE@hC@zAB|D@tC?n@@X?tA@zA?v@@lB@`B?r@?fBDpB?|@@l@Br@@l@B\\Bl@Fl@Fz@\\xE@PT|Cf@|Gf@|GTxCHtARvCBl@Fp@Bl@@\\@\\?b@@j@?`@?j@?f@?\\?f@?@Ad@Ap@Ah@AX?JARCXA`@C^C^AZE^Ef@ANIjAG~@KlAQxBIjAM`BGbASfCMjB_@~FCb@Ej@Ab@Cl@A^ANAf@Ab@?l@A`@?`@?@@l@?D?f@?t@?x@?v@?h@?H?x@?~@?fA?bB?bA?hA?`B?DAjA?hA?l@?t@Af@?\\AFAp@Ap@El@Cj@Cd@Eh@Ef@AJCZEb@CVIt@In@CHCTEZENGd@Mh@AFKj@Mj@]vAU~@WdAK\\YlAc@dBa@`B{AbGOl@Ol@aAxDyBtIg@pBi@xBMb@Op@Qp@I`@Mj@I`@G^Kn@Ij@Ih@It@A@C\\CJ?FGh@Ir@El@Ex@Ev@Cj@Cn@ChAAh@?X?BAz@Aj@?P?B?n@?B@z@DhA?TBl@?BFhA@FBr@Bf@B~@@ZBhA?L?P?x@AdAA|@GzAA`@C^CXCd@Gr@Ed@Gb@In@EZCNO`AQjAq@hFEVc@tCk@bEKn@EZa@tCGf@E\\CLGj@Gh@AJGd@AJEr@Gn@Iv@Gr@El@Gp@Ex@GfAE~@AJE~@Cn@Cx@C~@?JCr@?ZC`A?HAhAA\\?r@?HApB?rA?P?t@?z@?|@@p@AnE?~D?lH?V?vB?hAAfACl@?XEbACZAPAXC\\C^AXEXIv@Gf@MbACPETEZKd@Ot@WdAQv@Ol@AF[rASv@Kf@YlAEL]|ACJq@rCSfAMl@G^G`@G`@G`@Gd@Gd@Gh@Eh@Eb@SjDC^AVAb@An@?b@A`@?ZAf@?|@?|@A~@?pA?r@?D?pAAtEAdB?rAAhE?ZAtC?lB?NAtEApA?`@A`F?|AAlD?|B?xAAhGCnH?pCAnB?~A?L?fBAP@R?d@BnA?FDz@FzAL~A@TJ`AH~@@HLlAN|ABRLvAH~@VlCR|BFp@NdBLnAJfAFp@N~ANbC@ZDp@Br@?BDzA@xA?TAd@?L?dACtAATMjDG|B?h@Ar@?J?f@?\\?|ADjAHhBLzBRbDHhADr@D|@VtDRdDPfCLtBBXTrDLdBF`ANhC@JFhADr@Bt@@~@@pBAj@?p@A|@Cz@C`AKjBKzAM`BQbCu@tIKrAOjBWhD_@dEi@xG[jDa@tEk@lHSdCUzDWzGQvFGdBEpAG`BA|@CbA?r@?j@?H?f@?J@`@?P@j@?F@x@Bt@Bh@?@Dr@@PL~AHhABLFl@NdAPnA@@TrAPv@Ll@Nt@Tz@XdAPt@J`@`@fBNp@FZJn@Jv@L|@NrAJjADj@d@`GN`BH~@NpBDd@J|ABb@Dv@Bv@BbABdA?`CAhDC|CEbHIrOAzAG`JExFCnEAdA?zB?`@?r@?R?r@B`ADzAFnAF`ALnBP~BDb@\\zEB^HbALdBDh@NhB?DDp@Bj@B`ABnABjBDlL?r@?~@F`G?r@DrELxCH`BDv@Br@DpAF`B@pA?~ACjB?LGxAA\\ATK`BY~DGbAKbBA@GhCEvB?fBBvBDlAB|@@TJtBNrBBPB^RpBh@dFbApJnBrRZtCRtBB`@Dr@HfAFpABVHbCBp@@^DvBF`G?R?zC@d@GjG?DCr@ObG?zBA|BBnBDbBDlA@JBf@B`@PdBJ`AD\\LdAHp@?@^rCHn@hAzIh@fEJn@^tCHp@~@hH@Lf@vD^lCLjAHz@BZFh@Dn@Bl@DbA@ZD|A@tA?H?~AAp@Ar@CpDApACr@AnAIjEKjJKxI?PGxC?ZEdC@dBBbB@f@Br@F|@@FDj@@TDZLpABPHp@F\\BRJn@Lp@RdAFVRx@^hA^hA\\z@HRJT|@vB@BRh@Th@L^Zz@Rn@ZnA@B\\xA?@Nl@?@`@xBDVHn@BNJ|@J~@Bf@HbARzCJdBDr@JzAF|@Dp@F|@HbAHhA?@Fp@BVBXF^V|BFh@NbATfBDXJn@ZzBp@zEHn@\\|BNfAVjBj@dEjAlIHj@x@vFfAzH|C|TDVJ|@`AhIHp@^|Cv@rGp@bG`CpSR~APzA\\vCbBrNvBbRXdCZdChBrOl@lFB\\Hp@BRRfCL`BDr@Dp@HlBHhBBfABpABrBBrA?X@X@dBBhBHjJ@dADnEHvID`F@pBB~BBvBBjC?NBz@Bj@B`@?DBl@@BFjAJfA?JR`CTjCNdBBTFp@PtBD`@Fr@H|@ZlDf@xFr@~Hd@rFJvAFlAD|@@h@@t@@|A@z@GxHMjIAn@At@I`GCt@ElCIpECtAIvBG|@Er@AXUrDe@lIAVKdBEr@KhBK`BGr@GfAQvCSpDYjE?FGtAC|@ANAh@?z@AjA@hBBfADdBFbAH`BBXNhCZfFN`CFtADt@@T@\\@b@@dA@p@A|@A~@CjAMdBGv@Ej@QnAYfBa@~BOx@Mz@E`@Gd@Gj@?BCZARCVCXAb@Cl@Aj@A\\?DAj@?n@?D?l@?D@n@@zA?N@r@BxC@r@FlGFnE@x@Br@B|@Bf@Bd@Dj@Dv@LnAPdBL|@NdATpALr@VdAf@rBZfATp@f@vA@@Rh@HPJTP`@hA~BjAzBh@fAVd@jAzBXh@~@jBjA~Bn@lAf@dAXr@BDVn@Vp@Vr@Rl@Ld@FTL^Pt@Pr@RbAVtATfALr@@HPx@TfANr@VbAX`ANd@Vt@^bA`@bAFL`@z@Tf@n@tA`AnBl@tARd@@BPd@Tl@Pd@`@rAV~@^zAXnAVtAV|ABLL~@JdAHfAF`@HtAHpAFrAT|FV`GZtHFdBDr@LxCXhHPlE@d@HbBD~ABn@Bb@@j@@LBtA@l@?rA?r@CnEMnREvHEtEAv@AvA?r@Ar@GvHAt@AbBAr@EhEAx@?r@CnAC~B?@Ap@CbAGlAIzAG`AGh@Ix@K`AIt@o@hFWlBe@rDu@bG_AnHaAxHCXi@dEIr@Id@Iv@EZKv@Kt@e@bDa@rCKn@[zBCVOrAQjBQrBGbBEpACbAAnAApB@P@vABnADhAFvA@DJ`BLhALxARxA@HPbAhA~FLr@h@nCpApGNx@Ln@Z~AF\\j@lCP`Av@~DLn@Z~ALn@Jh@t@tDt@vDh@vCNdAFb@Hn@Hv@J~@F~@HhAFjABtABrA@tA?bACfAAj@?@Cx@Cp@Aj@A@Ex@IxAEp@ObCa@dGOdCMhBS|Cw@bMQlCQdC]nFC`@a@~FOzBIdAUhDUhDAJWdDMrBCn@G|AAPGpAEfAGzAClAAd@A\\CvBAzD?vAA`CArD?tCAbCCnI?f@?fDAvBA|C?vA?h@Ar@?r@AzCCfOAvCApEAjJ?fA?f@?D?Z?d@@j@@bB@`A@~@@p@@r@@|@DxBDrB@`A@F@r@BtAHlD`@bTDjB@R?L@b@@\\BX@VBh@Fp@BZBb@Ff@D^D\\Hr@Hn@BNDTHj@F`@H^F\\H^H`@Lh@J`@Pn@Vz@J\\HVXz@HRHTHRFPHPvAjDR`@lBtEXr@P`@Rj@HVL^Rn@L`@Jb@FRBLJ`@DNNp@Lp@Lp@Hd@H`@?DHh@DTBXFb@Fp@JbAFx@Fn@Bn@F`ABv@@^?J@n@@`@?`@?l@?nAArACp@Aj@Cn@Cf@El@APIfACZC`@EZC\\G`@Ir@Ip@CPEREVG^Kf@S`AS~@Kb@Qr@]pA]pAUx@k@rBmChJs@dCaB|F_@fAWv@Y~@sAvEc@xAM^Kd@aAjDa@tAW|@iBhG[fAM`@KZGRo@hBa@hAWl@CFO\\[x@y@dBi@lAwAbDo@xAkAlCoHzPgC|FYp@c@dAc@jAKVKXGTM`@GRGVMf@I\\GXEXI^Ij@If@E^Gb@Gn@Gt@ANAH?BCZAVCd@Af@AX?LAd@A`@?n@BrA?\\Bj@@f@B\\?FDj@?BH~@BZFd@Hl@Hj@N|@Lr@Jb@Lb@HZ@DXbAz@vC`@pATv@Nj@Lh@Jd@Px@RnAHb@D^Ht@HdAHdA?HB\\?T@H@d@@v@?F?j@?n@Af@Al@Aj@Cj@Ex@E\\ANGp@O|AqAlKeAtI]lCWxBmA|J[hCYfCIp@_@~C{@bHGj@WlBE^CZE`@Eb@Ep@Ej@Ch@Cn@AZA\\A\\Ab@?^?X?h@?x@@^@\\@^@\\B^@^Bf@B\\BZD^B`@J~@?BHt@LrA@JVvCDl@Bb@Dl@Bv@@`A?X?^A^?j@Ct@C`@C\\C^C`@WfDWvDm@fIa@pFEr@Q|BKpASrCSlCU`D[bEEp@y@vKCZ?HEh@_@|EUhD_@dFM~AGt@C^EXE^AJAHEVKp@GXI`@Md@CFENIXIRGPIRKRMXS^QZORKNMNQTWVMLQLKJIFSJOHOJc@RUHMDODUFQDUF[D_@FA?k@F]De@DUBO@Q?[@]A_@CQASCWEYISGWKWMIEIGSM]S_@YWUkAaASQSOYQUMUMQKSKSKUIAAUIYISGYGUGWCCAWCSC]Ce@A[?a@?_@BY@WBOBUBYFYFUFWHSFOFWLa@R_@T_@X_@ZONMLSTUX[b@OTMRMTOZO\\MXIPIVMb@M^GTIXEREPIb@E\\GZE`@Gl@Gx@Cb@AZA\\A`@?V?L?^?d@@h@@~@@r@@z@?X?b@Ar@AXAZAVCXCd@Gj@KlAMdAGr@Iv@Eh@En@Er@AVAX?\\AV?h@?\\@`@@j@@Z@`@B`@Bh@LtBHrAPvCPzC?HN~BL~BLzBF|@NhCTtDDz@p@lLHtABTFhAFnAFpA@p@Br@@H@p@B~@JdENzHLnFXpM?@@j@?D?h@@p@?j@Ap@?b@Ap@C`AAXA`@A`@Ad@C`@C`@Et@Cf@Gx@Iz@M|A[rDs@tHU`CGv@APCPCX?DC\\Er@EbAC\\A\\Av@CfA?h@A`@?L@bA@r@@p@?VBp@Bb@@ZDn@FpAL`BJxAJrAJnA^rENlBFj@?DTrCPtB\\vEZpD?@D^@P@NBd@Dt@Dz@@n@@l@@X@d@?`A?hA?p@C|@CdACx@Ev@Ev@Gx@Gv@Iv@Iv@Gh@G`@Id@Kr@Id@Kf@G\\Kb@Kd@Kf@CDMj@M`@Oh@Wz@_@nAg@zAcAdDwApEeAdDQf@qBvG_CnHQj@CFI\\Ot@Mp@I^[bAOb@Qj@aBjFuCfJ]hAQj@sCdJABgAlDwBfHuBzG{A~Eg@|AcBrFOd@g@xAm@~Ao@fB{@lB_AjBkAfBEFcAtA_AnA]d@qBdCeAlAoAfAu@l@GF_Aj@{@^WNgBl@u@T}AXcARcIdAG@gAXqAh@kAj@sAx@}BvBsA~A{@jAg@p@{G~K{@pAYb@u@hAaBnC_@l@u@rAk@nASb@m@tAYv@c@pA}@|Cg@zBUjAI`@GVOz@Gd@WhBs@vG[pCKbAg@nEc@~DIp@MbAMrA{@~HiAbLi@~EGf@CRG\\UlAY|Ak@fC_A~Ci@|A}@`CUf@cA`Cg@pAgAhD_@nAQr@W`Ay@fEc@|Bg@pCCPKf@cAtEk@|Cc@~Bq@pD_@fB]vAQp@k@fBk@zAGNm@vAg@fAk@fAu@lA{@nAIJyBxCcAtAoBhCY^eCzC}AfBGHcFxFsB`CaBvBGJw@lA_A|AINu@xAc@~@Uf@{@jBaBjDKTq@|A}@lBIRKRWf@S\\]j@MRKN[`@W\\aAjAgCtCA@Y^[^KLUXeA`BQXg@~@Yj@e@fAg@lASh@ADm@jBUx@Qp@Mf@]~AAHMn@ALIb@UzAShBKp@Ip@?D{@dHIp@OtAc@nDy@hHWfCIn@StB_@hE]lEMnBC~@CpACrACbBAfB?t@AbE?fC@lC@vE@`EAlCEdCEbBKbCM~AGt@G|@ShBOnA]|BqBrMAHw@hFQdAe@zCWzASbAMr@I\\Sz@[jAYbA[~@ITm@~AYn@g@fAaAhBA@Yb@Yb@q@bAcAnAQREDWVWXcA|@e@^k@b@IFyA|@mAl@a@Re@TaErBo@\\uAp@cDdBw@`@oCtAa@Ps@^aEtBkExBoAn@SJqKpF{EbCm@\\iAh@gDbBuAz@s@b@MJ[RoAbA{AtAk@j@y@~@m@r@m@v@{AzBq@jAw@xAi@dAo@rAEJM\\Sf@c@lAg@tAUv@[dAYbAWfAUbAWpAQz@W|AAFKn@E\\U`BMfAAHAJQnBIlAGz@MdDEfACz@?dAAx@?L?dB@pA?fB?hA?tA?zB?r@?r@@xE?lHBxM@jO@tJ?r@?zC@xQ?T@hG@jR?|L@zM?`GCfCEjAG|ACZQxBSzB[tB[jBWjAS~@K\\Sx@s@~B[z@o@~Ac@`Ae@~@{@zAuBdDgLjQy@nASZYb@mAjBmAjBaD`FaCrDaCrDYb@Yb@mNjTg@v@}AdCYb@S\\ADMRGJILMXOXO\\MVEJQ`@Qb@_@~@Sp@Ut@Qj@ADM`@Mf@EPERIXERMt@Op@Kp@ERIh@Kv@Ip@?DGj@Gd@Eh@Ch@GrAAZAVCj@C~@AbAAjA?z@AvH?r@?fB?nE?jJ?fA?^?tB?d@?`ABxADbBF|AJ|AHpAJbA?BPvALz@Lz@Lp@P|@z@hEP|@P`ADXHd@L~@NrA@LFx@H|@FrAFdA@^Bf@BvA?z@@x@Ap@?JAn@E~AQnGAFAj@OlEIvCGjBSnGO`EMlEQ~F]jLCr@ElAElAIzCCp@KzCCn@GjBCr@EdBOnEMrDCr@QbGCp@KzCGjBK|CAj@I`Cu@pWK|CGxBGnBEdB_@|LG`CEvACn@Ad@AX?R?XC`B?D?z@?b@?n@?xAB|I@fK@xH@lB?hE@~K@lO?jE?H?h@?vAMpQApAC`C?XA^Aj@Aj@Aj@Cl@Cn@?BCn@Ep@Gp@?@Gt@Eb@AJCXGb@EZE^Ij@Mx@SfAKn@e@pCMp@Y~AKp@Y~AKp@i@xCSlA[jBUpAm@lDi@~CiAvGi@~CYdBMl@[lBQnAUdBKdAEb@C`@E`@C`@C`@A^Cn@Cb@A`@AZAv@?r@Aj@?v@?~@?dG?lC?pC@nH?zQ@XIbE@nF?lA?rNAr@?n@?B?pD@dA@~@?\\BzA@v@@v@@n@BjAFrAD~@F|AFnAHrAHtAJnAJ~AHx@HdAN|ALpAPtALjAF^Fd@R~ABLRpATxAN|@@JThANz@P~@XvAPx@DNLh@Nr@Pt@Pp@J`@J^Lf@J`@JZNj@J^Rt@Nf@Rj@Pj@d@xARn@Xt@Xt@x@tBXr@Zx@@?Xt@Vl@LVTf@\\r@\\t@^t@DHVf@b@x@f@~@pBhDdBtCDFRZnAtBfAhBVb@Xb@Xd@nArBxBrDfBvCzCbFdBtCNXXb@jEhHbBpCVd@j@~@h@|@Vd@T`@Rd@Zn@Zr@Xr@@BPd@Tp@Nf@@BPj@?@Nd@Lh@Nl@Px@Ll@H\\DXDPDZ@FDZBLD\\Hh@D`@D^Fh@BRBTFx@@RDf@Dx@?DDr@Bt@@n@@h@?H@b@?j@?Z?L?|B?rH?X?n@?B@fA?h@@T@b@Bv@Dp@Br@HhAFt@Fn@@HBVHn@F`@D`@F\\DZHd@@JPz@Hd@Ll@@@Rz@H\\DRRp@X~@?B\\|@HVTh@DJf@lAP`@P^DFVf@Xj@j@hATf@|A~CTd@j@fAXn@Vf@Vd@dAvBl@lABFj@fAt@zANXJPJRjClFf@bAp@tAbBfD|A`DbBjDjCjF~@jBtC~FzAzCbAtBbDtGVf@Tf@R^jCnFtAjCbAvB`@~@DHN^@DVn@Vt@Pf@^pALd@VbATdANt@PbAF\\TbBF\\@PTxBLbBL~BD|A@~@?D?r@@~@?vC?lB?vAAzJ?`C?fK?~A?`NApU?jNArI?pR?bJ?x@AfQAzQ?bEAnN?fF?r@AfX?fK?xC?nRBrG@bC@nD?p@@pEFbT?l@AfDGpBI~AEn@KtAQdBw@fIMrAGr@_@xDK`Ae@dFi@nFe@nFe@rEM|AQrA]fCSjAEROz@q@~Ck@zBc@|A[`Ac@lAe@rA_@|@oA|CUf@Sh@[t@u@lBUp@Mb@YbAa@dBQdAId@Kt@Kz@Gt@InACp@ATCf@AfA?xBDtAD`ADt@B^BVLnARxAZdB?@Nn@?@Nl@Vz@\\fATn@Rn@vAdEp@lBFTlAlD`BxEbAvCHVRh@~@jC`@lAdBbF`@pAz@dCbEtLpCdIhAbEZtAXtAZfBRzABR`@fEHhADp@H`BD|A@jB?`@?`C?xD@pC?dG?zB@zE?zA?vB?pC?nDAbE?tB?fD?pA?xD?`CAh]A|DA|AGdBGhAAPGdAI|@OtACPQnAOfAOt@SfAWdAIZa@zAg@`BWv@Wl@GP_A~BMRe@`A]j@CFi@z@m@|@s@|@]`@]^SRCDSNg@f@YT]ZmA`AyCdCiFfEyCdCuC~BsAfAo@j@u@p@u@v@g@j@c@h@m@|@gAbBq@pA}@lBm@xAENg@xAm@jBIV]jAcAhDGRoCxIyA~Ei@fB}@vC]~@Up@Ob@g@rAg@jAGN[t@]v@]p@Yp@S`@CFS\\MVQZi@bA{@vAcA~A[d@o@|@[`@[^[b@q@x@aAlAs@z@IJQRaAlAiAtAKLk@r@a@f@{AhB}@dAGHe@l@QTYb@a@l@i@~@Wf@_@t@]r@Q^o@rA]|@Up@CHYbAWfAQx@CJIb@I\\O`AQhAMbAADYtCI`AInAIjBIhBEhBKxCCj@YzJCr@Cz@QxFQfGE~@EdBCr@C|@ExBCx@?z@?HAr@?PApB?pABpC?v@BzB@~BD`GFvJBbGHfLBfEB~CBbB?r@BzCBnDBzBLzORjWJhMBxEBnCFbG?r@FvHHjJ@r@JhO@r@@b@BjFBbD@j@?r@DbG@rA@nADvHBzC?r@BpB?h@@r@@fB@dA@`@?r@@r@@r@BzCDnEBdDDjE?x@B`B@r@@r@@bABlGB`B?^?j@CjACnAEbAGt@Gr@K`AWtBABOnAMfAEr@Gp@GbBAt@AZ?V?l@@~A?L@r@@l@HrEFlDDxBBdAHnFJpF@r@PxJDlCFnDFdDL~GVvOHxEDpCFbD@j@@r@JbGHlEL~GBjA@d@BxB@xB@pAAx@An@Cd@Cz@EfAG|@Gz@IbAKfAOjAQpAQ`AGXETO|@s@pD_CnLUfA_@pB{AxH}@rE]jBKb@oAtGQx@i@nCId@a@pBIf@G^Ox@Ij@M|@Ip@Ir@Gn@Gt@Ep@?BCf@Er@?DC^A`@At@Az@?d@Al@?xAApD?dE?^?rE?N?bG?F@dF?~C?`D@tC?@?lE?nE?fA?fD?dH?nC?xC?|C?R?bE?j@?r@?X?lA?TA\\?X?^Af@Af@Cf@Cp@GhA?FIbAGv@Ix@Kz@AJGh@AFIf@AHId@Kr@Ml@Ml@Id@GPI^U|@YbAOb@M^M^KZMXWr@}@vBk@xA[v@i@rAIRa@bAwAjDs@dBq@`BcAdCw@nBm@zA_@|@Sh@aC|FcAfCu@hBsAdDiAnCaAbC]z@a@`ASh@]v@kAxCKTIRg@pAA@c@nAO^Qh@Uv@Oh@Qp@CHK^CLIXEREPU`AI^Id@Id@GXETCPG^Kn@Kn@?DIj@AJIj@It@Ix@Ej@Eb@CXC\\Cd@AJEl@Cd@?RATC\\?LE`AA^?XAVAfAAdBAjA?BAvDApBA`A?r@CnEM~XAzCAt@?z@A~A?r@Ad@?L?r@Ar@?r@?r@AfDAf@?bA?`@Ax@?~@?xE?h@?`@AnA?h@EtJ?h@A~@?r@AzCAdA?n@@bABhCD`ABt@JtABZDh@Ft@TvBP`BD`@v@lHV|B^jDZpCZzCJz@@V@R@R@X?@?`@BlC@`CBjF@rA?`ACrAG|AKnAGb@O|@k@xCShAo@`Dq@lDId@qArGw@~DgAxF]~AUz@Yz@eA|Bi@`AW^Y\\UVWTg@`@OLu@f@wGdEwArAs@x@]j@y@xAi@pA]dA]xA]fBOjAIdAG|AGbEHp_@@vH@zCBjJ@nE@pEBjJ@zC?tBA`DCpAEr@Gp@QtACNId@S`A]vAi@~Ai@nAo@fA}@lA_C`CmAdAa@`@eAdAe@h@c@j@_@n@g@~@a@`AUt@Wz@CLQt@Qt@Il@y@vIaBfQ{AhPkBpSaAjKy@`Ja@rEgAzLcBdRaB`RAHs@jHi@pDa@pBMh@YfA]jAi@`Bc@nAg@fAc@z@y@zAgAhBg@t@m@t@a@f@k@l@y@x@k@f@m@b@e@\\m@`@iCnAeBp@wAb@_Cp@mD`AqEnAsA`@aEdA{MjDgBd@eAXsFvAmBf@oCx@{@V{@XmBp@uAh@uAl@yAt@}@n@e@ZMHoA~@_@\\gA~@q@n@WTeAhAUX}@hASX[^_@d@k@|@g@v@o@bAo@hAa@x@_@r@ABWj@_@z@a@dA[z@eBjFGNcEzMq@tBuAlEY`ASv@UhAS`AMdAIr@En@IvAGvAADq@`Ti@nPe@dOCz@CbA?nA?r@?~C@jEFtMLvUDxHHxP@`CAhACz@GbAC`@IbAKhAGd@_@tCi@~De@vDm@tEe@rDKp@iAnIWlBM|@YhDEl@Cr@Ax@?T?TD~BDdAHp@Ff@Jn@Ll@Pv@XdAtBtHnB~G`@jBP~@TzANtAJxABtABt@H~CBbBLbGNpF@PDl@?BFn@N~@BNRdADXDRPv@Pf@Xv@j@bAFHHNJPf@r@\\b@|@~@nDvD`BlB`AhAl@x@\\f@d@~@f@pA^nA\\fBPrAN~ADf@BXBdB@tBCnA?TArGAfDExSC`L?r@CbGAzCAvHClJAzCEvP?BC|PIvZCtMExJ?d@?zC@h@?nF@dD?TAnC?rBAtDAlACvEA|F?NAzAA`D?bFAfI?zH?p@?lRAnJ?hMCNAR?ZAf@Cz@ErAErAGlBEhAA\\ExAG`BCzAAr@ALAbAA`AAp@?lBA~G?zD@|A?bI@pEA~D?rA?v@?`FA~B?pE?dE?H?nE?vJAlH?fC?nDAhDA~D?t@AhE?|C?tB?r@@bE@rC?xFApy@?tMAxU?zC?zC?fE@lIA~@?z@?|B?zDAfC?tAAvJ?zD?zB?vIAjDAx@A|@AbACz@Ct@A^AZEx@G|@Gz@Ix@Iz@QzAKt@O~@Ox@EZMn@GZKb@On@G\\IVMh@ELUv@Sp@Wx@Wn@Un@M\\Uj@O\\EJQ^u@zA_@p@[f@QXQXGJORm@|@_@f@QROPQRSTMNCBKJOPQNUTURIFQNQNi@^e@\\KHi@Zc@Vg@VQJWJQHQHg@RQHC@ODSHWFQF{@T_@Ha@Jg@Hi@J{@Hm@Fe@Bi@BY@g@@W?U@{@?i@?k@?K@iA?eA?M?mB@w@@aA@iB@yDBU?sG@I?sB?E?eF@g@A_E@yJ?iF?gA?_H?uI?yA?sTAyH?cGAmG?}@?aF?sD@c@?_H?aE?_CAgA?wDAwA?_C?kF@wB@y@?aA?iA?uECuBAaDCwCAwBA{@?kE?qA?uB@uF?wJ?iJ?gH?}CAeA?{AAyBAkCAiGAe@?}H?cS@cF@yHAkFAgA?qB?]?qD?gA?cD@kB@{B@o@?wFBgGBk@@m@?qCB{@@eABiA@K@cCFkBDeABqCHsBFsCFeGPeEHiDDoB@gG@gD?kH?sCA_ECo@?yHEuECaBAkECqFAqECqGC_H?iJ?}F?iE?Y?yC?}A@i@?s@Ac@ASAG?OAi@EMAYC]E]Gi@Iy@Sm@Oe@Qi@Qg@Si@Wc@Sg@[w@e@g@]g@a@_@[c@a@a@_@c@e@kAuAw@_AuBoC}BwCCCmCoD{CyDo@u@k@m@c@c@e@c@s@m@UOKGg@_@UOSMc@YQKYMg@WMG{@_@g@Si@Qm@Qq@O_@Ii@Kc@GCAi@Gg@Ek@Ek@Cg@Ay@?cAAmA?o@?u@@e@@eA@a@@}@@k@?g@@c@?y@?gBCu@A]?}@?aA@sA@mB@G?aB@oB?mA?wA?_AA_AA}@A{@EcAE{@Gc@CGAi@Eg@Es@Io@ImASi@IkAUKCoAUkA[oA]g@O_AYo@S]Me@Q{Am@KEc@Sc@Qu@_@_By@SKaB}@wAy@c@Yk@_@e@]mA{@o@g@kCwB}AuA}BsBmAiAs@o@eDyCqCgCgC_CuBmByCmC{AuAkAeAqAkAqDgDgAaAwEgEoEaEa@_@u@m@k@e@eAs@e@[cAi@g@Ug@W_A_@i@Qc@Oi@Mg@Mk@MuAUo@Iy@KiBS{H{@_CUeD]KA_Ec@}AQ{@IkBS{C[_@EkC[iAMuBScCYc@EA?cAKk@Ei@CWAU?a@AW@W?S@a@BS@YBk@Fc@Hk@Le@Jo@R_@Lc@NKFc@R_@Pu@b@]Te@\\UPYTUP[Zc@b@c@f@e@h@Y^{@lAABkAbBq@`ACDmAhB{BbDeFjHaCdDgH|Ju@bAqFvHy@jAaGlImBnC]d@}@nAiAbB_@j@QX[f@OXy@tAk@jAWh@i@hAe@fAKVYr@Wn@Wt@KVKZSn@IXK\\_@jA?@Oj@c@|Aa@xAOl@q@fCoApEy@`DOl@k@vBU`AQl@Sx@m@|BCLK`@[nAe@dB?@q@dCSp@U~@]lAIX}@dDy@`DiB~GCJeA`EeAzDGTg@pB]pAi@nBU|@YfAq@dC{@dD{@`DeA|D]pAg@jB[rASv@Ov@GZOv@Mz@Mv@Kx@E\\Iz@E\\C^Iz@Ex@G`ACv@A\\Ab@A^AXA`A?V?b@?`A?V?^@^?^BtBBbCBtB@`A?f@?lAAxACx@C~@Ez@G`ACXIz@Ix@Kz@Kx@E\\G\\Mx@S|@WnAW`AEN]nA_AbDi@fBm@lBaA~C_@lA_AvC{@dCw@|Bm@dBm@fBw@`CcA~Ca@nAc@nAa@pAwA~E}AjF}AjFmAfEaCdI}D`N{F|RaFzPkBlGe@`BwCxJoBtGkBfGcBdF}FhPcCnGaDpI[r@Sh@u@fBk@pAqCtGeAdC}BdFUh@s@fBUh@kBtEuAbDUh@Yr@}@pBuBhFi@xAYz@Un@o@tBiAbECJi@|BmAbGaA|E_@lBk@vCm@tCeBnJ_A`Fu@xDu@nDmAdGcB~I{@hEm@nC_@hBMn@GZgBnIgBhHABiBpGwGlUwE~O}AhF}AnFwAzE[lAMd@AFw@pDW~ASxAMjAEXQbBOtBKtBGtBCrACxA@rA@xABrBN|FLpFVvJb@`Pf@tQPxG@^\\~KTbITtKBx@JzGBdDDdG@zF@r@Jd]?T?dJBhIBjEDjCDdC@l@Bv@FfBJtC@XP~CVjDV`DLrAXbCNrA`@nCb@hCf@pCBHv@rDf@nBVbATz@bAhDx@jCh@~APb@Zz@hArCLXjB|DXf@`@n@l@x@Z^h@h@b@b@FD\\X\\VtAv@p@XdA^l@Ll@Jn@DnAD^?b@?`AEjAErEUz@GhH]zAI`BID?v@E~CQd@Cr@Gj@KZGB?b@Mf@Q^OlB_AfDgBr@a@JD@?LAHBHBFDDHLRNXHJf@`BRl@FLJZBDDFLLtBjGh@`B\\bAbA|C^jA`Pve@hBpFt@|B`@lAVt@t@|BHTRj@J\\r@pBv@~BnB~FlDjK|FdQ|@lCpEzMlB|F~CbJVv@zAvEzDfLnAvDp@pB|I~WtEbNVx@Z|@Tr@Pd@t@xB\\dA^jAp@vBX~@xAjEbAzC~@fC^dAZ`APl@"
                     },
                     "start_location" : {
                        "lat" : 46.3769284,
                        "lng" : -81.347385
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 339
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 31
                     },
                     "end_location" : {
                        "lat" : 46.522362,
                        "lng" : -84.2798272
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eS Market St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ma}zGdgkaOYTWVm@h@gA`AED[XSVQVQV[|@CLI^I\\Kp@Gx@?BCf@?n@BbA"
                     },
                     "start_location" : {
                        "lat" : 46.5207121,
                        "lng" : -84.27651059999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 547
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 40
                     },
                     "end_location" : {
                        "lat" : 46.5219033,
                        "lng" : -84.28691500000001
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eMcNabb St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wk}zG|{kaOl@fJNvBJrABh@Bj@Bh@@Z?T@^?t@@x@?`A?`E?~E?n@"
                     },
                     "start_location" : {
                        "lat" : 46.522362,
                        "lng" : -84.2798272
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.9 km",
                        "value" : 1859
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 122
                     },
                     "end_location" : {
                        "lat" : 46.5383852,
                        "lng" : -84.2872646
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eHwy 17\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{h}zGfhmaOS\\KVGLEHGJGFGDEDKDWRI?iC@kAAuA@oC@mD@{E@uD@qC@eE@sC?oB@oA?{B@eB?yB@aB?q@?k@?S?UCSCYCYI]Ia@Ky@Yq@S_@IOEWEWCWAUAa@?g@@i@@y@Bm@BU@kCHyBF"
                     },
                     "start_location" : {
                        "lat" : 46.5219033,
                        "lng" : -84.28691500000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.9 km",
                        "value" : 1920
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 120
                     },
                     "end_location" : {
                        "lat" : 46.555625,
                        "lng" : -84.28851739999999
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eBlack Rd\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "}o`{GjjmaOwAF{ADYCY?k@DkBH_BFyCJ}CJqAD}BJqCHoOb@oCHc@@kBF{@B{FN{FPmIVc@@sDJyCL}@DgAFc@Bm@@"
                     },
                     "start_location" : {
                        "lat" : 46.5383852,
                        "lng" : -84.2872646
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1246
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 78
                     },
                     "end_location" : {
                        "lat" : 46.5637513,
                        "lng" : -84.27857610000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eOld Garden River Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "s{c{GfrmaOg@e@USSOUQAAWOUMYM{@[UIWEWEYEk@I_@Ee@Ka@Ia@Mi@Sa@O]Qe@Ue@]c@[OKIGq@m@UUWWi@q@u@aAGIm@}@m@aAi@{@MQeA_BgAyAc@o@[a@GMEGKOKQGQISISGUWmAQu@]kBMo@UoA_AaECKa@mBMg@Mc@"
                     },
                     "start_location" : {
                        "lat" : 46.555625,
                        "lng" : -84.28851739999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.6 km",
                        "value" : 2593
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 171
                     },
                     "end_location" : {
                        "lat" : 46.585682,
                        "lng" : -84.282698
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eLandslide Rd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "mne{GbtkaOIQO]OYQYSW_@WMIKECAOGOEOGKAOA{@@i@@aABgABgABgCFG@_@?C?E@Q@Q@]Bk@FaANmCb@C?aC^K@mCb@[ByBXWDy@LWFSBQDQFC@EBGDKHMNMNGJGFOVw@hAA@IJKLCBIHMLED[TyAdAkCjBmBtAo@^_@NMDE@G@IBI?Y@i@DS?Y@o@ACAc@CA?a@GGAYGSGOE_@OcAe@cAc@cAe@[OUGq@UUGOCE?aACc@?c@Ac@AQ?s@AsDGgAAOAS?SAO@c@@c@@Q?{AAk@Bi@JYFMHOPUZOTGNOXIJ[`@o@n@IH_@VIDWLaAd@k@ViChA"
                     },
                     "start_location" : {
                        "lat" : 46.5637513,
                        "lng" : -84.27857610000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1421
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 106
                     },
                     "end_location" : {
                        "lat" : 46.5969432,
                        "lng" : -84.28143659999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eFifth Line E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eLandslide Rd\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Landslide Rd\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "owi{GzmlaO{@yD}@oDi@{BGUEQEKGIGIGIIGIECCOEQEA?KAU?qCHkABkABc@@W?o@Bc@@gAD{FJgABM@aCHc@@wBHgDHcBDyBD[Bm@D}@L_ARiAb@SFiAbAk@d@IRAN@V"
                     },
                     "start_location" : {
                        "lat" : 46.585682,
                        "lng" : -84.282698
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1114
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 84
                     },
                     "end_location" : {
                        "lat" : 46.5976235,
                        "lng" : -84.2940735
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eSixth Line E\u003c/b\u003e",
                     "polyline" : {
                        "points" : "{}k{G~elaOADAJAJ?N@lDBxC@T@T@^^~AH|@@b@@z@BV`@z@f@dA|@zBl@rAx@tBRt@J`@Hd@Ff@Ab@Ad@Cb@QhBEf@?@Gd@ERCPKd@Yr@]|@_@|@a@j@EFwAlBw@~@i@bAG\\GLIVGROn@Mr@Mj@[dB"
                     },
                     "start_location" : {
                        "lat" : 46.5969432,
                        "lng" : -84.28143659999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "51.5 km",
                        "value" : 51521
                     },
                     "duration" : {
                        "text" : "32 mins",
                        "value" : 1922
                     },
                     "end_location" : {
                        "lat" : 46.9316981,
                        "lng" : -84.51848079999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-17 N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cbl{G|tnaOMLMRGNKJQJSDC?I?UAE?E@C@EBgA[g@KqAMgAGm@Ak@@gAFkEToMx@a@DaHh@_AHk@FcBZ}Ah@qBfAkAx@o@l@sA~AgAvAKLs@~@mBdCkAtAcAhAA@_BbBuG|GuDxDgBhB{@x@kCnC{EpDwElDkDpCmBvAWTkFbE}DzCgAv@w@h@eAl@]Rc@T_@NsAf@C@]HaAXk@LUDC?wARs@FWB_BDI?[?WA{AGYAEAwBYi@MaAWKC}@Wi@SQIq@Yq@[c@U_@S]QeAi@cD{A{CyAs@_@SKwDqBkHuDeAk@cAg@_Aa@iA_@{Aa@uAYsASeAMi@CoAAk@AuABu@F]@o@D_C^aB`@oBn@oAh@q@`@aAl@w@f@a@Xu@l@m@f@aFtE{EhF_@\\sBrByAvAmEnEgDdDcCbCeCdCmCjC{EzE]`@iCdCEFqBnByAxAiDjDwCvC{FrFmFdFeKhKmFjF}AzAmClC]\\]Z]\\kBvAu@d@OJoAn@c@R{Aj@cAZOFmBh@gD~@sBj@gFtAcCn@i@NwBn@UHSJIDIDQJe@XoAz@}@t@oAjASRQTu@dA]h@m@fA_@p@MZEJO\\s@`B{ApDgAnC_A|Bm@xAgBlEkBpE_A|BgCfGIPkA~B[b@IL}A`CCBc@f@m@p@EDs@p@i@f@cBnAgCxAs@\\cBp@cAXgAV_BR}@FO@uHVuGBgDFeGNcCDM?mFJgABc@@gA@wHNiKTkBBkABuCHmFJkCDoABu@@yABW@sABW@K?uBD}BFsABmCDuBDy@@eAByCHoCF_CDeDFU@}BDkCFoCDwBDmDHaFJgDFuCFiCFcEHk[j@{CFoA?y@FiALqANyBZsEx@sB^oGjAeCd@_B\\}Bf@oAToJhBgGlAqE|@aGlAgARmCf@sEx@a@H_BZI@gARa@HmCf@oDp@C?qB`@cB\\mAVoBf@cBh@iA^y@Z}Av@_Bt@EDm@ZeBdAGFaBhAyAbAo@b@sA`AcDxB{CzBcCdBk@^_@T_BdAsBxAw@l@UPqBvAuA~@{@j@c@ZaElCy@h@ED_BfA_@V}CvBcBnAuBzAaAp@q@d@{@h@q@b@SLk@XYNc@P[Lw@VWFG@SDQBYD]DWBs@FgAB{@Cq@G_@Cc@Ge@K}Ac@sAg@wD{AcDeAiBm@wAi@uBm@mFyA{A_@_@Ic@K_AQi@Io@Go@G_@Ac@Ag@C_@@e@?]@g@BO@c@Dc@FQ@u@LI@UDA?c@Hq@LeCh@}@Rk@LsBd@uBb@gCh@mAVeARA?a@JeARw@PmATaB\\sDv@eCf@{Ah@MDk@X[LeAh@oAx@A?oAbAsApAsAxASVoAbBA@cAdB}@fBy@nB_CzFSd@_AbC}B`Gy@zB_AbCm@vA{@zBw@pBoCzGkFzMcAdCiArC_CzF}CzHwCnHQb@O\\m@|Ay@vBi@zAs@fBk@nAS`@_@p@u@pAq@`Ae@l@WXm@n@eB|AONsCrB}DpCyB|A}@l@m@`@{@j@o@\\cAb@m@RUH{C`A[HyBn@QDKDi@R[NQHA@YNi@^[TA?m@f@k@f@]\\oAvAo@z@o@x@mA~AcB|BcBzBaBpBw@fAgAtA{@jAm@p@m@l@a@\\_Ar@e@^o@b@u@d@yBhAy@Z]JUJqA\\A?}@Pe@HC@kCTmDZi@DeBNS@c@D{AJoDTiFf@iBPYBm@FkBPSBwDX{DXA?wAJ{AF}@@mACk@EaAISCuAS_B]m@OkAYkGyAsD{@a@IkASo@K{@GiAAU?[@{ADu@NODs@Pm@Nk@N_KfCmCn@eAVC@wAV_@B]@c@?a@CKAc@EC?WEWGQGMEc@OQIKESOA?_@W]YIGQOACWUEGY]{@eAkBcC?A[a@u@cAi@s@m@{@eB_CaBuBgAsA{AaB]]gBmBsB}Be@g@y@eAGGo@aAw@sAqBkDAE}B{DKQMSaBwCYe@aBsCs@mAWe@kAoBAAcEiHACYe@uCaFGKOYWe@kAwBo@gA[m@k@eAwAsCeBiDUg@o@oAKUu@{A_@u@{CiGUg@MUeGcMqAgCoCiFsAeC{@eBiA}BeAwBgDaHe@_AYg@Wi@Wc@AAQ[Q[MOCG[a@SUY[UUSOMMQMKISKUQSK[MWK[KQGa@KOEUEWCOCOAc@EU?]?Q?S@Q@O@k@HSBWFSDUFa@N[L]P_@RYR]VYVWVQPMNOPU^QTQVWb@MTOVIPQZWf@e@r@[f@o@~@[b@w@lA[f@[f@ORQV]b@Y`@GFW^c@j@UZ[\\CBKLOLQNOJUPYPy@b@UH[LI@YJ]F_@F_@FM@Q@W@Q?U@SAQAS?QCWCUESESEUEUISGSIm@Yk@[e@Y?A{@q@_@_@EEi@q@k@{@g@_Ae@aAeAkCi@wAYu@c@kASi@Sk@}@aCM]EKwA{D}@cCu@qBUm@cAqCa@cAgAwCcAoCoAiD_BmEISaAkCgB{EM]k@yAe@qAs@mBs@iBEKw@uBAE_@_A[u@Sa@Yk@[i@Yc@Yc@_@e@W[OQ]]MKYY]Yc@]aAi@y@c@GC[MaA[e@Ki@Km@Kq@Eu@E}@@A?c@@U@y@JaAP{Fz@kE|@KBWDm@L_AX_A\\IDy@d@w@j@CB]\\KHQRUXEDa@j@QZKP[h@y@xA_@r@y@rA}@lAk@j@YZ_Ar@m@Zq@Zo@RQD[Hq@Jw@H}DRgCNgIZC?mCP_@D[Dk@Hc@Ha@J{@Xm@TeCbAeBp@oBx@kCbAaAb@gC`AiCbAmBv@mAd@w@^k@\\w@f@g@b@i@f@e@f@u@z@a@l@[h@g@z@qAjCaBbDyChGiBxDs@|A_@z@e@lAENO^Wz@Ut@[pAo@lC{@rD_D~M}@pD{@nDe@nBMf@Y`Ay@pBO\\MRMVa@j@SZe@h@[\\e@b@_@ZYRm@`@y@l@iAv@yA`AYR_BfA_BjA{@n@_ChBcCnBwDvCuB`Ba@\\_@XGFe@d@a@`@[\\e@j@_@l@c@r@Yh@OXYl@g@jA]bAk@`BkAjDe@tAeD|JuCrI{@dCk@zAq@`Bw@hBi@fAa@z@q@nAcCnEWd@wAfC[r@a@|@]~@c@vA_@vACP]bBi@lCCNS|@y@pEMr@[|AMr@[bBY`BOj@WjAi@nBe@jAo@vAa@x@o@jAaA~AS\\EFw@pAQ\\Yd@[h@m@hAm@lAWf@CFWf@Q`@Sd@Wl@O\\q@hBc@nASh@Qb@k@|A{@`CUj@oAjDg@xA}@`Cg@vASh@i@xA_A`CSd@CHS`@Wf@[j@[d@]h@MRkCzCa@`@qCxCaBhBcE`Es@v@A@q@~@a@n@e@|@Q`@Qb@Od@Qd@i@jBq@bCIZc@zAy@tCADy@|C_AbDs@hCeA|Da@vAq@jCaAjDCJi@lBIZi@nBIZKb@WdAYpAABYrAYvAWvAe@tCYrBa@`DcC~Qy@lGe@tDqBnOYlB}@fHa@|C_AlH?@_@rCW~BGx@APEp@EpAErCG`E?@Ap@Cx@ChAIlAEn@?@Gr@?@SjBGh@]vCIr@w@`Hq@`Ge@vDIp@Gf@c@xDEZ]rCa@pDg@fESzAQhAQz@ADKf@a@vAg@hBaApDgAdEYbAy@tC]nAkAhEIZYhA_@bBYzA[hBO`AOfAEXIr@WlBSlBKrACZMfBGlAIrBAd@Ct@AHEbCAlB@jE@vADtBFjBHxBHlAJzAl@zFx@`IRdB@JVhBb@|C`@~BdBvI`AxDz@dD^xAPl@d@fBpBzHbAvD`@zA\\pAb@fB`@zAXrAh@fCj@bDTpANfA^nCh@nE`AjIv@vGxCdWx@rGjAtK|@hHjA`LTxBThDHlBBvD"
                     },
                     "start_location" : {
                        "lat" : 46.5976235,
                        "lng" : -84.2940735
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "571 km",
                        "value" : 571233
                     },
                     "duration" : {
                        "text" : "6 hours 2 mins",
                        "value" : 21723
                     },
                     "end_location" : {
                        "lat" : 48.716271,
                        "lng" : -88.6212393
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-17 N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "cjm}GnozbOAvBCbAExAAl@CPE|@GhAKjA]rEi@nHk@dIi@tH_@lE[hFQhBUfBYbBSt@_@nAa@`Am@nA{@rAiBtBOPoC|CeFzFmCxCkAfAi@n@a@d@gArAs@`AoAfBwAzBU^kAtBaAnBcAzBcA`CmA~CkAnDu@bCm@zB{DvPy@`EKb@a@xBq@zDo@rEqApKOrAy@lIc@`Fe@jFS|CKjBElBExBAdB@zB@bBFpDDhD@bD?H?h@AzACrBKjEC|@G~BErDExCC`C?dDB~EDhJ@bDBxDFfELhHNvGDfBN|FBfAPxELfDLzCXxHT~G@PNpDDrAFjBHxC?HL|FDfG?LTvVH`MDfGB|EJxKBbCBvD@`A@bC@~BAr@?xAG~AIvAUrBa@pCYvAe@nBgAvDmEfMaCnHcGtQg@vAeFvOyDnLuDhLiHlTk@fBQj@mCjIaEzLeDbKiAlD]dA_B~Eq@zB{@jDOn@Ox@_@lB[lBYpBa@|Co@`Ho@lH]jDi@bG]zDcApJe@hE[xCIl@]fC]`CIb@]rB_@tBm@xC_@lBQ|@Mn@Mn@y@lFkExS[xAaB`Ia@pBs@`DgEjSiCbMu@tD{@fEyA`H_DnOMh@aDrOk@nCcBfIEP_C`Lq@fDk@~C[dCCXQzAMjBKrBEfACbBCzDErIIzLCxBA`C@vBDbCBbADbBNxDJrCDfARzFL|CR`GFbAJdDNtD^vHPhDd@nM?F~@pWLzCRdGZdINdERdGTbGh@|NNbEtA|`@HvBRvFRpF`@hM@XPpEBr@f@dONnDVhIN`ETjGDtABfADhC?r@?`ACzAAv@E`AEp@G|@Ef@Gf@MdAQ`AKj@CNMj@Sz@_@rAM`@Sl@oAlDuBbGmAnDq@lBo@fBaBrEwAzDkBnFqApDqAnDYx@eAzC{@fC_A|C}AfF_A|CSp@s@`CQl@uAtEsAnE_A~Cg@bBQh@s@bCw@hCs@~Be@xAYx@M^[x@Wp@O^KVYp@k@pAUj@EFQ^a@z@q@nA_@t@]l@_A|AcA|Aw@fAw@dAkAxA_AnAkBdCMN{BvCQTqCrDw@dAs@|@sBlCyBrCaAnA_@d@_AnAi@p@i@r@m@x@iAvAo@t@KL_@`@[Z_@\\k@f@MJs@h@m@b@c@XWLSJmAl@mD~AyB~@kBz@uAn@iAh@KDiAf@wAd@u@TiAR[F[DI@c@F_@Bm@Bm@@u@Ag@?iACw@GqAIaCMwBQgCQa@EaAGi@CcAGkAIaBIqAIwAIkAKkAIs@K[Ea@Eo@Ok@Qo@Sq@]o@_@a@W_@Ye@_@YUUWCC]]_@_@w@{@cAcAiAmA_AaAy@{@wA}AIIcAeAIIgAiAQQcAgAcB_BMOeAcAy@y@u@w@g@i@e@k@CE_@k@]g@[i@[q@Wk@EKSe@]aAIYSi@o@sBa@kAa@mAWw@Si@Um@[u@[s@Yk@Ye@q@iA[g@Wc@ACi@}@g@{@}AgCuA}Bg@{@s@kAi@{@c@s@kAoBy@sA_B_Ce@m@QSOSY[WUg@c@e@_@m@a@e@W_@Q[Ou@Y[Mw@QcAQ_@C_@CoACiA@gAJwAVu@T}@\\q@XaAh@_Ar@EDm@j@wAbBaEhGsBfDwBhD]f@uBjD_BfCgC`EoBbDU^}AdCc@p@mBxC[b@[`@w@z@o@l@e@\\WP_An@mAj@uAh@o@Vi@TuAj@{DrAgLbF_CbAqAd@g@P_B\\gBT}ALoBDkAEk@Ae@A_BU}AY{@WcA]CA_A_@yAy@gBeAc@U_Ai@cBaA_DiBcAk@c@WmAs@yBqAq@c@k@a@m@e@c@a@g@m@y@gAeAeBMUoBgD{AkC_@s@Wg@gEmHi@cA}BaEcByCgB{C{B{DmAoBgBsCeCyDmAkBQYwAsBSWeBsC{@sAmE_HACc@m@a@g@{@_Ai@g@KKw@m@{FyD}@o@_CaB_Ao@eAy@{@w@aAeA{AuBCCcAeByAoCMWuBgEKWk@gAsAoCoAeCMY}CkGiFkK{AgD_@{@e@}Am@uBg@{Bm@wCEUoDcQcAaF_@aBCK]oA[_Ac@oAUi@Wk@_AcBsAkB{@_Ac@]}BiB}FeEoA_AmA}@}FgE_GkEaEwC_D{BOKOK}C{B_@Y_CaB]Y_CaB_@Y}CyBg@_@wAeA}@q@{@o@y@q@k@i@WU][g@k@QSqA_BAAmBaC}C{D}BsCo@aAi@w@e@w@[m@k@kAiA}BwBsE}@gB}@kByAiCc@s@aAiA{AsAAC]S_BgA_@WQMmAw@kBkAkBiAKIiAw@uA}@a@WcAo@{AcAqBoAo@a@aBeAk@_@sA_AyAcAeBuAwAqAIGw@w@WWiAmAMM_BmBkB{BqBaCgBqBs@o@s@e@}@c@}Au@i@OOEs@OgAKg@C[?i@AE?q@Ai@?g@AE?q@A}@Aq@CQAA?u@E{BMYC}ACcAEQ?s@CcACi@AQ?_BEcCCg@Ca@Ek@GKCo@O_A]_Aa@[OWOIEg@]m@_@KG_@UOK[Si@]IG_@UA?o@_@_@UWQWSECa@Ws@c@c@WuBkAi@[k@c@g@a@OO][c@a@[]g@i@[a@CCo@{@g@u@u@mAOW_@q@w@eBEGk@qAWi@gAcCsAsCeAaCUi@cA{BaA{BkAiCu@_BoAoC_@y@Uk@u@cBw@gBYm@q@}AMYKWe@cAQ_@AA]s@Wg@OUMSYa@SWSWAASS]]_@YIGEESMUOs@_@i@Q{@WEA{@Om@G]@Y?Y@a@BY@[BC@q@Js@R]L[NKDWN[POLQLg@`@A@UVWVWXMRORMPQXMPMRKNOVKNILKNINGHGJEDMRKPGJGHEFEFEHOVOROTMRORMTKPIJCDCBEFGLKNILKNKNGJCDGJGHCDA@EFQVKPcCrDOT_AvA[d@i@x@cCtDw@jAABSZSZMPOVCBGJk@z@]h@c@p@c@r@ILMRQ\\w@nAq@hA[b@[h@W^SZKLABINQTMPMPQVU^U\\m@`AS\\QXQXS\\u@pA_A`BgApBk@dAc@n@WZEFUXMNCB_@`@e@`@k@b@CBQJSLYNc@T]LeA\\}@RK@q@Je@Dc@BU?uA?K?iB?iAAW?iA?sBAqEAiAAm@?uAB_A@m@?q@@u@@{CAY?_@@qA?_D?gB@}@?sCBU?}AE[Ag@EYEOC]IA?QGOEMEu@Ya@QCCQGIGAA_@U_@UIEUSCA[USO]Yi@g@?A[]GG[_@]e@a@m@SYU_@S[y@sA{@}Ao@gAcBoC{BkDuBgDEGWe@Yc@U_@qAsBq@kAKOcBoCOWYc@MQa@k@c@i@u@y@kAeAQQ}AqAYUCCuBcBoBsBoAsAc@o@_@i@_AeBOU_@i@Uc@IUISiAeC{@yB}@uB_@w@{@aBe@y@]e@w@gAGI[a@oBcCKMGG}@s@]Y}AoAGEaCmBaAu@{AeAsCoB}AgAMIqByA}BcB[UaBoAUQaGmEaBkAqAaAo@c@qGyEuB{AMIq@g@_@YYUc@[_@Y_Aq@o@e@mDgC_@WoFyDMK_Aq@}BeB_Aq@UQgCkB[UaD_C]W_CcB_@Y_Aq@}BcBUOiAy@_@Y}AiAyIqGcAs@_Aq@SOKG_@YiAy@SO_@Y]W_Au@?Ay@u@_@]]]]]QQi@k@]a@e@m@OQ[a@i@s@_AwAACWa@IMi@}@a@s@e@}@kAcCSc@_@}@_@aAIQ_@cASk@[w@K]{BeGg@uAi@wAg@uA}@cCSi@_@cA]_Ai@uASk@g@wASe@Uo@g@wAcBuE{BmGuAaEKWSk@eAqCK[Sk@Qg@i@yAKWISSk@Us@Qc@Oa@q@{AGMeAqBe@u@s@}@u@{@OOQQk@e@_Am@MIQK[O}@_@m@SSGOCu@SiAMg@Aa@AK?u@AQ@c@@{@@m@Hc@DYDoANaAL_Hx@oFt@u@HkANu@F_AJyAJcADK@w@BaA@m@@i@@cACa@C{@Em@Em@CeCMoCKkBIaDUOAkBKc@C{@GwBKc@Ca@Ae@EmCOaCMoCKoCQYAaDSsBIy@CgAAeA?wA@cAFoAHaBL_CTA?c@BwALu@Fc@D{ALO@c@DkBNeBLuEZmAFuBP{DZaCR{AH_@@A?c@?m@Ac@Cg@Gg@Gk@Kk@OQESI_@M_@QCA[QKE_@SUQOKoA_AyAqAMKQO}@s@ECWW]]YW_@e@ECW[CE]a@UYMQKQYc@[a@sA_Ck@eAu@sAkAuBiAsBACUa@We@GKQYCGQYS_@GIMSSYSYSWGGQSa@a@_@]YUIGOI[SUK_@Qa@OAAc@MYGc@Kk@IYEGAWCi@Ia@I_@IICMCQEUIUI]QSK[Uk@e@?AUUGGW]Yc@ACWg@GKO]EKM]ACKYEOEOI]CGESI]EWCMCQEUAIAGCWCSAMC_@Aa@A]?[?Q?A?S?S?K@M@o@Be@B_@BY?CBWDU?ADYDWDYJe@L_@H]Na@Ne@Vg@FONWRa@`@w@\\o@JS^u@~@gBdBaD|CeGr@wAfBiDf@aAvDiH`@w@`ByCTc@BCVe@R_@LWP_@N[N_@N_@Pg@Ne@Nk@R}@F]DWLo@Fm@Da@F{@DeA@eA?m@Cw@?KCc@AQAUGy@Gm@E[Iq@?CMm@G]Mo@Me@KYEMIYUk@AAWi@KUa@y@q@kAYe@_@q@u@wAIQISKUGMQc@Me@Oe@Mk@Oq@G[G]Im@Gm@Gw@Cq@AYA[?I?k@Au@?E@i@@_@@_@?ADq@?ADq@Fe@D_@NaABOLo@No@Pm@?APk@Pm@Rm@BG`@oAd@yAPm@d@yARk@p@uBj@kBRo@Nk@ZmADOVgATgABMTsA@GJg@Jq@DWr@oFRwARsATeBHq@Hq@Js@BUD[Jq@Hq@Js@Hq@@GR{Af@yDBOJq@VsBX{BL_AJq@@EFm@Fq@BMDy@D}@?W@c@?O?_@Aa@A_@Ca@Aa@Eg@CWAEEa@G_@Ia@AOMg@Mi@K_@GSAEIUGMCIQa@MUS_@OYQYEGOSKMQSa@a@e@a@o@c@_@ScB{@CA}@e@a@SaAe@a@Sa@Sa@SGEWKa@QiAg@mAo@{@g@[UOMMKWSc@g@EEe@i@MOKMOSMQe@u@MSc@u@?AWe@Yk@Se@Q_@[s@Ui@aA{BUi@k@sAaA}Ba@aAi@oAm@wAk@eAk@{@MSYc@GI_@e@]_@OQMKa@a@k@c@_@YAA}@g@A?_@Sa@SUKoAi@a@QeBs@eCgAa@Oa@QcAc@a@Qa@Qk@UWKkEiBiDwACA]Oa@Oy@_@qEkBeAc@cAc@{@]qAi@s@Yk@YCA[SGEWQEEYS?Aa@_@c@c@k@o@_@e@KMOSe@o@OSe@o@mCwDu@gAi@y@Ye@Sa@Ye@Qc@GOMYAEQc@[{@K_@K_@Ka@Ke@Oo@Ms@Io@Mq@MeAIy@I}@KgAC_@Ec@COIq@?AKq@?CKk@CMIc@I_@U}@W{@Qk@y@wBq@wAS[Ye@ACW_@CCYa@Y]AAY]EGWW][CEYUYUECm@a@QKa@UGCWMcAa@MEw@Wa@Ma@OQGQEa@Oa@Mc@Ma@MGC{@YaA]C?eCy@kBk@o@S}Bs@}@Yi@Oa@MkBk@yAe@sA[o@M}AQUAq@Cq@Ag@?oABaABK?c@@U@mAD{CF]@c@?}ABuAB_A@_ABkBBgABc@@A?mCDgABsBDkFJ_DFu@B_BDsABY?{BD]@eABiBDyAB}ADC?]Bc@DYBm@Ja@HMBUD_ARi@Py@VIDa@Pa@POFs@f@[TUPg@b@g@`@q@t@MLi@r@]d@W^u@fAwDrF}BbDmA~Ac@d@WX[Va@^_Al@e@^KDe@Xk@\\OHIBc@Ny@RiB`@ODyAXa@Hc@Ha@JmAX}Bf@G@a@JeATG@[HiARe@LOBMBa@JeAXcAVe@Ja@JqEdAC?_@J{@TIBa@N_A^m@VYNOFOJo@^g@\\IDe@\\e@\\QNQLIFa@`@QNs@v@o@p@ABk@x@_BxBQX[b@i@r@wB~Cs@dA[b@oAjBY`@yBbDaAtAY`@u@fAY`@kBjC[b@wCdEsDzFuEfGsC|DuAtBSXYb@Yb@q@dAA@aB`CGLU\\CF[h@Yf@[l@e@dAa@bAUp@ITQh@W`AI\\Ol@Op@?BMl@CPO~@OrAe@|De@hEIn@[|CUxBMhAQhAMt@I`@Ib@Kb@K\\Uz@s@hBq@hBwAjESj@[|@cB`GW~@Ol@s@nC_@zAYfAGTQl@Ol@GPYjA]rA}@jDYfAOn@ENK\\KXGPKXGPUh@?@Uf@S^CFWf@A@mAjBe@l@q@t@YXCBy@n@A@]VKHcBv@SJi@Nm@Rm@NkAZwF~AoGbBgAXc@Js@ReBh@sBv@cAf@iEbC_@T]PkH`ESJyFzCyLlGiDhBcDbBaCrAsCrAwEpC{AnA_@Vy@~@qAtAsBnCsChDkBzB[^[^]^iD`Eu@z@{CzCsDfD]ZKHgGnF}DjDoAfA}GnGgE|D{ArA]\\]ZiBbBcEzD{@x@aFxEONeExDkAbA]ZsBhBcA|@{@v@]Z_@Zg@b@mEvDiB|Ak@f@oAhAg@f@s@`Ai@t@a@x@ABWf@Sb@Wp@St@Qj@Oj@Sz@G`@CNUpA?@W`BGf@y@fGQtAqAnJUdBUbBUdBUbB_@pC[|Ba@vCWbBa@vCGd@M|@Ip@WdBIp@UbBWdB]lCy@dGU|AWdCCXGr@Ef@G~@?@Ep@A`@EvC@`D@TDt@F|ARpBHp@Dd@L~@Jr@BNF^Jp@VbBLp@?@Jn@Jp@Jp@Jp@z@vFJp@H`@LbAVbB?@Hn@PlADT?BR`BFr@Fb@DbADv@@f@?HEdBMlBCPOnA]nCAFOr@[|A?BMl@?BER_ApFG\\g@`DEd@Gr@Ir@Gr@APA`@At@?BAn@EhBAr@At@?t@E|C?LEzA?BGdB?DGj@Ir@?BOzAQt@?DMh@IZGRSj@ABKVy@xAy@|@[^UTg@^_An@_@XC@{@l@_@V{B|Ag@Z}@h@s@b@kBpA}ClBGDYNiDtBoDzBqChBSN_@X_@VkAx@QR]^wAzAA@aDjE[`@u@dAu@dA[`@EFSXu@dA[b@u@dA[`@u@dAYb@u@dAu@dAu@dACBW\\kBjC[b@Y`@KNqBjCMJ{@v@_@ZURi@Va@Pa@Pc@R_@Lc@La@L?@wBR{BH}BMWGa@IoAY{@WgBi@c@Ma@MeA]cA[w@Uo@SgBi@c@Ma@Oa@Mc@McA[c@Ma@Oa@Ma@Mk@QYGiBe@a@Ki@M]Ga@Gm@K{DQQ@c@B{@Dm@Fc@BWB{@PUFa@Lu@ROHiCdAaEdC_@TCB[RaAj@_@V_@Ta@V_BbAa@T_Al@[PCBaK~G_@V_@V_An@QJMJ_@X_BjAUPyBvAqAv@IFwAt@OHuAj@KDUHa@NsC`AaCj@c@JIBYDeAPc@HiBX_@FC@eALc@FgANa@FoC\\eALkBV}@JgLnAc@DgALeAJc@FgAJc@FeAPiBZc@Fa@HkCz@_Ct@mBz@a@RYL_B|@kAp@a@TEDw@n@yD~CoHfGc@`@_@ZwDdDaDjCkCvB]X_@XkB|AOL]\\wAxAg@d@oCpDmAnCWf@CHO`@mArDQj@g@xAUn@eArDu@hCeAxDuArEu@hCQl@Ql@Ql@Ql@Ql@Ql@Ql@KZW~@c@zA}B`IGPIZoDjLaAbDITIVe@xAQf@?BsAlDiAnCCFWf@i@nAA@Uh@wAhDUh@Uh@Uh@Sj@k@rAYp@sCzGUh@Uj@wAfDk@rAi@rAQ`@gAdCUh@qDlIoBnEO\\{CvHk@rAUj@gBjDi@|@Wd@o@bAuBdCGFs@p@}@x@uCnCkF|EaA`A]\\oFjFOPw@t@wGrG]\\gAdAQPyAtAyBrB]Z]Z]\\{@x@sEhE{AtAyAtAmBhBeAbA]\\{@x@]\\yAvAsDnD]\\yAvA{@x@]\\C@w@v@yBrBgBdBgApAsAbBw@~@A@s@dAu@dAiDbF}B`DgClDu@dAQXgEpGoDtF[d@uBdE}@~BsAjDmC`IqBdH_BzFgBvGQl@Ql@Ol@Md@aCjIc@zASt@oAvDO\\k@tAQb@aJ|OiGlKqDfGGJQVYd@kAnBYb@Yd@s@hAYd@Yb@]l@{CpFKRUh@cAzBOZELQl@Sl@Ql@IVY`Ae@zAY`AYhAs@jCcAzDaAnDABMh@Qn@a@zAOn@_AnD}@pCSl@e@xA?@m@nAUf@Wh@a@|@KPYd@kApBWd@GHm@|@Yb@e@p@OR[^]`@[^?@]Z]Z]\\[X_@\\}ApAiBdA}C|AID}Ah@a@LcBd@g@Hc@Hc@Hg@H]Dc@Fc@F_ALi@Hc@Ha@HgAP]Hg@NcA\\OFsAt@a@RA@]T_@V_@V_@VIFSRiAbAgAz@GF_@Z{EfEWVkAfA_FtEEDuBbB[X}CjBGBwBt@s@PgDr@wCRYByBEoBOcCa@eA[kCs@eI}BqJoCKCcGgB_LaDGCgBi@cD_AoA_@iCu@wBm@SGiCw@sBk@_HsBMCa@MgGcB}C_AoGmCa@Q_@OcCuAaAu@}EoDoCsBgFcEGGWOaBkAoAq@s@Wa@O?Aa@K[ImAW{AYA?a@AgACMAaBF_@Dc@Da@Dc@D?@eAVYFIBa@Ni@PYNa@PSH{B|AkAjA]\\_@`@s@~@[b@SXEF{@xAMXWf@Wf@}A`Dq@vAS`@Wf@Uf@gAxBUf@Wf@]r@eFdKi@dA]p@Wf@eAvBMTiCpFi@hAg@x@u@~@a@f@MLMRKLe@d@g@`@g@b@[PcAj@_@P]LOFuBf@sBPcB@kAIMAUCuASu@S]KkAk@[U_BeAuBiB_DoC][QOcEsDGGsAkAkB_Bo@g@cEkDqBmAiAa@a@Qa@Oq@Wu@Si@M}AWmAOyAGcB?{@Dc@Bc@BsDRgADiBJc@BoCNsDRkBJ_@@e@BI?Y?Y?w@GYEc@GeAQkBWICWEc@GaFq@gEo@yCe@cAMs@Ey@CY?}@?uBLc@BWBI@mB\\}Ab@w@Tu@ZUHKFaAj@YNcBrA_Ar@_@XGDu@n@]Z{BlB]X]Z_@Z]Z_@XOLML{BlB_BtAwC`C]ZC@mAz@aBjAoAr@k@Xm@TeAZ}@Ru@La@HqDn@a@HOBoHtAaSnDmCd@WDKBc@Ha@Hc@Hc@HoDn@eARiB\\gARa@H_C`@kIzAkBX_@FuCXiDPoBHwNp@iK`@MBgHj@eAF{@D{CZm@Na@J[Je@Pe@Ni@XEBYPSLKH_@VYPED_@X[VA@eAz@i@d@g@l@[`@MLgApA[^]^[^GHqApAyApA_@ZWPaAl@eBx@mBp@_AZE@eARI@YDa@Dy@HM?c@BoBHkBEgBOOAu@Oc@KQCq@Uc@MKEoBs@m@Yo@[QM_BgAkAy@OM_@W_@W_@W_@W_Ao@w@i@GEa@UaAk@WQi@WgAi@_A[[KEAc@Gc@IQCOAc@EWAKAc@?OAS@c@?Q@kAH}AT}@RUF}@\\i@TmAj@aAd@a@RcAd@_@Pa@Ra@Pa@R[LEB[NE@c@LcAPI@YDYDc@BqA?E?gAG]Ea@GIAYGoDq@gASeAUC?_@GiB]w@M_IyAwAWMAYEI?g@CeAAm@Ai@@g@?_@Dg@Fi@JE@a@Lm@Py@VUHqAd@a@NiC|@a@Na@La@NeA^]LC@gBn@a@Ng@P[Ja@Nc@La@La@NMBUHKBUBc@FOBSBWBK@WBK?o@?WAc@AEA]CWCg@Gu@OsD{@QEkCo@c@Ka@IoCo@_@Ic@IiAUoBc@WIc@Ma@MSGMEc@Oi@Y[S[UAA[WKIQQYYCCc@e@UYCCW][a@?A[_@c@i@q@u@y@_A[_@GGkFiGyBaCII{@w@][MM]Ys@e@_@SIGWM_@USKo@YaAg@a@QcBy@a@ScBy@a@QcAg@aAe@a@SeCkAa@ScBy@a@QcAe@mHmDiFcCoHgDcAe@aAe@cCgACAa@Qc@Q_@MWIcAWo@KGA[G{ASM?a@CiAAkB@C?_@BeAFA?iBRgFj@u@Hu@HwARkAP_@FGBm@HgBf@q@Xa@Pi@VkAt@KH_@X_Ap@}AjA_BjA}DvCSNk@`@_BhA}CxB{EvDmA~@uEhDYPsAx@MDeAXa@Lu@Rs@Hc@Dy@HsACm@CYEaAMaB_@}@]wAq@qAk@QIqGmC}Au@uHeDwLkFeBu@qCiAqAa@ICgA[mB[k@G}@Mk@E_BAc@?e@AoDb@yA`@uLdDgBf@qBh@yEpAsCx@i@Nc@Jw@TqA`@{Bp@uCv@kBf@cAPYDs@Ja@Da@DA?wAFq@@qBCk@Ae@Ai@EiAIeAOs@MgCk@{Ae@qC_AiAa@oFkB{@[cBm@aDmA_Bo@kDmAmCcA}CoAi@ScA_@gAa@y@WUKYI[KGAa@KYIg@Kg@Ia@I}@KgAIgBKq@AW?sAAiCLaTbCm@D{@HyBTwAL}@DmBDsBByBEoCEaQUoFKiDGU?gAAuEEgAAcCAcAAwBCA?eGGsDEgAAc@Ac@?m@AeCE}@Ak@@eADiAHE@]BWBm@HA?a@Ja@JA?oAb@SJQFmAn@YNGD_Al@_@TIDu@l@QNKJ{@r@A@]\\]\\WVa@f@QT}@rA_@f@S`@Yd@QZEH_B`DsAlCy@bBeAxBkCpFKNoBxDUb@GJ_@p@KLY`@_@j@WTSRIH_@ZURSNu@d@ULi@ZA?g@T}@XKBUH[Hk@HG@YBM@q@FG@c@Bm@?i@Aa@CA?c@GmC[c@EiBU}Da@{@KuL_BiBUc@GwDg@yBUwACSAO@oAH}@RkBb@_@Lq@ZkAt@SJiA~@oBtB]j@Yd@s@hAk@|@GLm@lAwB|DKT}BvECDy@xA_@l@qAjBU\\kBvBi@j@qA~@kA~@uAfAg@^_@VkAz@q@d@_Ap@g@Zw@l@_@V_@VYTc@`@]\\A@s@x@CBw@~@[^y@hAe@r@s@rA_CrEWf@GJyBbEOZYf@Wf@Wd@Wf@_AlBeAlCCHMb@IVGVa@nBG`@U|AKx@ALOdBEnAGrCEfBAt@Ct@EhBAt@Cr@At@C`AY|KAt@EpASlKAr@C|AE`AAt@Ct@A`@APIrAIv@KdACTEZc@vCAJMb@U`AKZQl@Md@o@|AGNoA~B}@rA[`@g@n@mAfA?@wFpFcIzHyAvA]Z]\\]\\oFhF{AvA]\\WV_@f@]^GJm@x@CDw@pAQVk@bAQZWf@gAtBWf@y@`BeCzEWf@eBfDqG~Lc@x@gAtBWf@Wf@yEbJYf@Wd@a@x@e@|@oClFiAtBoFlKWf@aEzHOZ_@r@gDtGgAvBo@nA[j@Sb@o@nAuBhEy@`BMTEJO\\GPMXEJaClGuAjE}@bC}@bCw@xBmCdIcE~LmC`Ik@bBYx@Yz@w@vBSj@g@xAk@`BSj@Sj@O^o@bBQd@ABO\\KVS`@QTGFQXg@f@[TA@q@b@SL[NGBYJ]J_@H]Dm@Dc@?WAO?E?YE]Gw@Sw@]g@ScCiA]QuAo@eMyFa@QcAe@cBu@?Aa@QwDgBqI}DiFeCEAiBaA}@g@SOm@g@e@e@o@q@CEkAsA}@gAg@o@}@kAg@i@]_@w@q@i@a@y@i@cAg@EAWK_@Mo@Qw@QGA[EGAe@Ca@CE?]AY?I?c@Ac@Aa@AsC@a@Ac@?Y?m@AcBAm@CcAEc@GUCm@IC?iB[UGwEy@oB_@iAUm@M_BYa@IC?_@Ic@GaAQCAc@IeB]C?gAUa@MICWIGCu@W}@[g@SGCaAa@c@ScAc@_@SqB}@qAq@ECcBw@a@Sw@]m@WUIKEe@O_@Ia@MWGqAWc@Gc@Gg@GiAI_A?c@?A?sA?U@c@@C?_@Dc@Bc@DQ@yAJaAHg@BwBNoAFO?g@@eACmAE_AIE?kAOw@K]GgBSGAiBSC?_@EgAMc@Ec@GeAMc@Ec@Gq@IUCa@EgAMaAKi@Gc@EeAMMAUEc@GiBUE?]Gc@GeAOICYEc@Gu@Ks@KgAOKCWCu@Ii@Eo@Ag@?]@s@@w@DM@k@F}ATYDc@Hw@LyBZa@FG?[Fc@FcALC@a@DG@g@Du@BE?]@E?c@?A?a@?A?a@Cc@Ce@Ea@EC?_@GE?g@K{@QC?]KUEo@Sq@Qu@Uc@KICWIc@Km@QWGsDcA[IeA[mDaAA?a@KqBi@_Ba@a@Ki@M[KuAc@QGUKaAc@KGa@SMGQMOIQMMIUQYUYSEEe@_@]]o@q@a@c@[a@a@i@Ya@a@m@?Am@aAg@u@c@y@i@{@q@oAqBgDu@oA_BsC[k@wAeC_AwAAC[a@o@}@}@iAi@m@OQ[[_@a@CCYUGEWUEEo@e@IE_@UWOk@[{@]g@Og@O]K]Ii@ISCOC]E}@GM?YAI?c@AE?]@Q@u@DUBa@Ds@Fg@FaALgALC?eBVO@eC\\[Dc@D{@HK@eANM@UBgANC@uAPO@{@Hq@Ha@B]@E?Y?I?m@Ac@C_@Ee@Ee@Ie@KWI_@K?A]Ms@[QKSKMIOIOK[SCCcBkA[UwAaAUQ_Aq@g@_@gD_CSMgAs@m@]KE_@QAAs@YOGa@OMEw@WUIKCa@Me@O_Bc@uA]iFyAg@O]Ka@Mc@Ke@O}@UsAa@[Kc@O[M_@Os@[QKg@YYOSOKGg@_@WQCCYWECYWEEWUQQKK[_@OOi@m@s@}@i@y@OUYe@ACYi@S_@i@eAo@yAWk@Um@Ui@kBoEWo@uAiDe@kAkAqC_@{@_CyFWo@Ui@Uk@k@sAUi@k@uAM[GMUi@aA_C[u@O]Uk@_A_CUi@CE{@sBCCeAeCQc@Ui@ISy@oBSe@Sk@g@mACGSk@[u@O_@Si@Qc@k@sAq@mBO]Yy@]aAi@{AUs@[aAIWSm@Yy@M_@Qm@Uu@Oc@y@iCWw@Ma@Qm@cA_DGUg@yAUo@q@uBW{@M_@CMWaAWkAOq@Kq@M{@Kw@AOGg@KqAEw@Cm@Ao@Am@?E@gA@aA@u@@eA@M?}AAyB?yB@kA?A?s@@cAAgA@}ABkC?aD?eA?e@@{CDiF?e@@{A?O@u@?y@Ao@Cu@Ao@?EGiBAII_BGs@C_@CUGs@AGGi@Ei@AIOgAG]Km@?CMq@CQI_@Mq@CQc@iBYaACMM_@Og@Us@_@aAISWm@]w@_@u@[o@e@w@MUMUKO]k@i@q@GKOQKM]_@AA[]KMOQUSGG][_@[IG]Yo@c@o@]_@U[QYMu@_@OGc@OAAa@MUGk@OCAYGIAg@K]Gc@EA?_AIg@Eg@As@?M?wBDgA@aBDW?Q?YAk@Cc@Eg@Is@Oe@QMEe@Qo@]MKQKMKYUi@i@UW]a@Ya@SWGI[c@a@i@eBeC[c@s@eA[c@iBmCsBuCeAyA_AsAaB_COSIMuAqBoAeBs@cAIM_AuAwAoBIO_AoAa@k@m@y@e@i@q@q@II[[AAi@e@c@]OMYS[UUMSMQKy@c@_Aa@YMq@Ui@QMEMCKCeAUo@IKAkAMkBOIA_BM{CUKAoCU{@Gg@Ai@?m@@]Ba@De@Dm@LG@]Fm@PUHEBc@PYNu@`@o@`@m@h@a@^MJm@l@k@h@[\\cA~@aA`A}B|BcBbBk@j@qCrCg@f@aA`Ag@d@_@\\o@f@]TID]RA@c@Ri@RWHWHm@Lg@Ju@Ls@Fc@@G@i@@cAAo@Aq@EwAK}Hm@gBIgAGWCIAkBQqBOaAIqBM_AIc@CiE[qCSm@EsAKeBMy@Is@I_@G_@Km@Oe@OYM_@Og@Y[QYS[Sc@_@SQGGSQo@s@Y]s@{@sAcBe@m@uBkC}AmBoBeCOS_AmAy@eA}AoB}AoBaAkAW[CE[a@[a@a@g@UY[a@OSKM[_@m@u@g@m@[a@OQg@m@]a@y@}@MMa@a@KKUSGG]Wu@m@KG_@USMKGUMi@YAAcAc@a@QeBu@a@Q[OmDyAEC_DmAkCgAw@]SKyAo@sAs@q@_@m@a@MIm@c@c@a@o@m@c@c@sA_Bq@w@kAuAmAwAUWyBgCs@y@}BmCkB{Bo@s@}BkCk@q@wAaBeCuCgBsBwCiDqCeDeBuBEAUMIKu@u@e@c@a@]g@]c@Ym@]WM_A_@i@SKC]Ic@K[EWEWCC?k@Cc@Aq@?W@M?Q@C?a@Dm@Jo@J[Hc@Nu@Xg@RYNE@YPA?[Ra@ZA?WRGDWV_@^C@OPYZUZSVY`@OTKNMRS\\S^Q`@MV]z@_A~Bk@tAmBpEiAnC}@vBaAzBoAxCeDbIyBbFWn@s@|A_AtBi@pAmApC{@pB_@z@_AzBi@nAw@hBWl@Uh@e@hAu@fBe@fAO\\yBhFADSb@M\\s@`BABi@pAO`@Wh@c@dA[n@Yn@CHQ`@o@xAA@uAdDABUh@CDg@nAEJO\\}@vBg@lAc@fAgAjCs@fBcAdCi@lAABi@lAo@zAi@hAm@tAQb@Yp@g@lAm@rAYn@[r@yAhDSd@ABs@fBi@jAg@hA?@_@t@MVQ\\[h@_@h@ADW\\QVIHe@n@k@n@[ZCD_@ZMLONCBYTKJa@Zk@`@i@\\a@Vk@XOHQHm@Xe@PQFQDcA\\C@_@JiCv@kCt@iCv@uDfAC@]JeAZ]Jg@NaBf@uAb@qA`@yAb@aCt@sA`@wAb@IBaAX[Hc@LaAV_AXG@s@ReAZ}Ad@iA\\_AX_AXo@Tu@V_@JKDWDe@FSD}@Ja@DYBa@Bg@Bi@@a@?]?KAWAg@Ae@C[Ce@G]Eg@I]Ei@KiB]cASA?uEy@gASA?iB]cB[cAQyCi@}Ck@qAUcCc@eCe@YEa@IA?g@Ii@IWCKAWCWC_@Ak@CG?_@?g@?C?o@Bm@BsAJgAPkAVcAZgA^kAd@MFa@TQHeAt@aAr@iA`A_A~@qDrDST]^a@d@}EdFe@d@]^]\\y@z@]^uBxBSPIJqDvD}A~AuAvAm@n@qArAkAnA]\\wAzAaDfDmDrDkAdA]V[V]R_@Rq@X[Jo@R}@TG@[DUDs@F{@Dg@?C?a@Aq@C}@Ka@IGA_Bc@sA]w@S_EcA{Bi@kCo@cCo@gA[[KEAo@Ug@Sa@S]O[SSOk@i@m@m@}@_A]c@i@y@a@o@IOMWMSYk@O]]_AUu@g@{Ag@_BOg@}AeFSm@Qm@c@uAeBqFu@}By@gCm@kBeCcIcAaDQm@AEy@eCYq@a@cA_@y@q@qA_A}Au@iAk@u@s@y@uA{AYWi@c@}@s@kBiAm@[e@UyAk@}Ae@]Ig@I_BQcCOE?wEYSAOAE?]E]Em@Mg@KWGGC[KWIw@Wo@W{@c@_@Se@Y]Uk@a@i@a@k@g@]Yc@c@o@s@yA{AsGeHSS{CgDOQKMmCwCeBgB}@cAs@m@_Au@[SGEaAm@y@a@s@]k@W_A[OCeDg@yD[c@CeAKyOqA}Gk@aIq@c@Eu@GwAMoCUc@EsJu@wEe@mCUc@EoAK[CwE_@eAIgAKc@Ew@GMAc@EgAKeAIA?gEa@q@Ew@E{@?[@S@g@Be@FG@m@LWFc@Jc@PuAj@o@Xc@R_@PcAb@k@VyAp@WJcEjBQFa@ReChA_Br@sD~AgF~BGDWJ}BdAmAh@cBv@gAf@aA`@aAb@cAb@a@PGDeDzA[LeBt@a@NOFQFa@L_ARmATc@Do@FaADgAB_A?q@Cq@E{@KwAQiAYcA[SGq@UoAc@}By@_@Me@OcA_@eA_@YIkAc@{@YICa@MeBi@yA_@s@OaAQEAeAQa@IgAMgBMCAgAEc@CC?cEO{BIc@A]Ci@Ac@CiBIy@CmH[c@AeCKoCMk@C{AGiAGe@Ac@?e@?I?]@]BcALOBa@F_@FkARw@RKDc@NE@y@\\sD~AYLa@Ra@Pg@NiGnCcDvAoItDGBcBx@{@`@i@Ty@\\k@Pg@PcBb@UD}@Nw@Js@Ds@DsAD{AEyBSk@Kc@KYGGAc@Ma@Kc@Kc@KcAWc@Ka@Mc@Ka@Kw@S}DeAa@Ka@KaD{@yCy@cA[c@KuBm@uMeDEAc@Ka@Kc@KgBe@c@Ka@K}Cw@wA[}Bk@iBc@mEeAwFyAmD_AgAUoDw@GAuB[qCKyCNmBXoCt@]LeDpAc@ZaAl@k@^gDhDmFfIoCbEiErGaFrHaAzAmFhIkKdPk@|@uAzBgBrCiC`EQT[^oBfC[`@[^GHsCzB_@Z_@X_@PqCpA{Al@a@P_EdBuAh@}@^aA^c@Pa@PqCfA_C~@IBWJyD|AuAj@iAd@uBz@qChA_Br@cAl@aBhAeAx@qAtAy@dAgDnEkCtD[b@U\\cDpECDgDzEkAdBYb@{AxBOR[`@qAhBYb@y@hAsDlFa@j@kBjC[`@A@kBhC{@nA}AhByAzA{BnBm@`@s@b@qAl@a@PqBn@kB`@y@LsAPc@Fg@FcYfDsHx@[DqBXyBRiCVkBRiBVu@BK@W@gAFA?uACoAGsAQ}Bc@oEy@yAWc@Gw@MwBKA?iABa@@gAB_@@aEz@_GpAKBa@JeAVg@JuBh@wA`@eBr@QFOJ}@f@oAx@}@r@s@l@URwAtAyAtA]\\o@l@iAfA]\\]ZgAfA{B|B}AvAIHeBfBaDxCe@d@oBjBmBfBe@h@y@z@i@f@]\\{DpDsBpB{@x@uCrC]\\yAvA}@x@{@z@yAvAUTGFoArAoBjBo@l@iAjAOLkBfBKJsBpBgCfCgCdCeB`Bo@l@iAfA_A~@oDlDQRgAbAmCfC_C`CyBtBe@d@mCjCs@r@sApAk@j@qBnBiC`CeDhD{CvCaDzCQNsDpDSPyGpGiDbDwIpIkHhH]ZkLfLmAlAc@^IFi@b@w@f@kAn@cAd@s@X{Ad@mBb@m@Hs@F]DaADS@[?g@@_@A]AiAIaCQ{@MyBWkBSaCY}AQiC]_BQYCgAMmC]m@GiD_@uEk@UCwBWc@Ey@KyEk@k@I_AM_BQaCU_@Ck@EmACkA?{@B{AL]D_@F{@NsAZUD{D`AOBSDoDv@c@J]F}EpAaB^gB`@c@JQDs@PmFlAk@Na@JiBb@a@JiBb@OBQFyG|AyA\\ODa@JuInBk@NeAVgFjAq@Pa@LqAZkAZuD|@qEdAqEbAc@Ja@J_JrB}A^eAVa@JMDk@Lo@Tm@Xs@\\g@Xg@\\QP_@Zs@r@k@r@QV_@f@U`@Q\\Yl@QZGPEJ[x@[|@Sp@Oj@s@lCCFIh@Mn@Kt@Kl@QlB?BUxDCj@StECr@YjGARC`@_@pEGt@ARe@xDIr@OjAiA~J}BrROnAY~BgAhJ_@zCi@lE[nCu@nGIp@g@nEIr@UfBIt@]vCaAxHWxCQfBQhBc@xHKdDEjBAf@AbAAt@EnDM~LEpC?t@CjBAt@U|TQfSAx@Cl@GjDClAEfAE~@CTMfCK|AGbAGt@OfB?@SpB_@|CgAtHkBtLe@vC_@fCi@hDcAtG}@|Fe@vCKp@uAbJe@vCq@lEYpBS|AOzAGd@Eh@EjAAHC`AAhAAbA@|@?F@l@@VDhAD~@Fr@@BJbAR~ATxAZhBt@`EJp@v@fElBnKLn@zB`MfBzJ`@~BV|APlALjA@DFl@DVHz@HbABn@FfAFjABrA@x@@|A?x@?v@CzAEvAC|@IdAEz@CVIdAUvBGn@[hCK|@MjAMdAK`AM`AK`AIn@M~@CPG\\Kl@Mr@Mj@Qp@Qn@Qj@IVGRSj@Yp@IPoAdCQVYb@KNe@p@{@~@{@v@c@^{ArA{BnBeA~@{@x@m@p@i@n@SVW^W`@Wb@S\\Q`@S`@MZQd@EJKZUp@Sn@Oj@On@Mj@UjAUhAyBhMcAtFcBrJ_@vB[vA_@zA]nAEJQl@M^k@~ACD[v@i@fAy@zAm@hAm@z@[b@[`@CDm@r@c@d@A@[ZIJc@\\]Zk@b@g@^[RGDg@Xc@TOH]Pm@Tg@Ni@Nm@Po@LiCb@aC`@g@JiAPyB`@aAPmAPiB\\q@Lw@NG@c@Hc@H{@Ny@Lw@LA@oCb@a@Fo@LUFiB`@IBeBp@y@\\e@Ts@b@k@^]Vc@\\k@d@]ZYXUTYZORSVOPSTOROTQTMTMRMREHm@bAo@jAGNS^c@~@s@|Aa@v@}@hBqBjEqCbGw@`BUh@s@vAaAtBUf@sArCkCxFw@`BmAhCkB~DWh@Sb@gClF_BjDYn@oC`GqFjL}AdD}AbDkBbEqBjEeAzBeAzBiB|D{JdTiBzD_C~E}EjK_E~IeAzBkC~FmHnO_AtBeBlDABoAjCoBfEUf@o@tAu@vAy@tA_CpC}@dAyAhAg@^WNkDzB{ApAgAnAkAlBmB|DsAvCUh@oDbIaArB_@|@Uj@[r@_C~EQ^}@|Au@jA[d@[f@q@dAs@hAwBdDyA`CoAnBYb@iAhB_@d@aBrBQNyBlBCB}A`AEB_Bl@aA^oDhAgBh@_TtG}@V]L_@NaBv@aAh@k@^w@l@_At@{@p@k@f@SRo@p@y@dAGH[`@gA~AUZgBtCKRQXWh@]t@aA`CIPIVqBhFiCfHCH}AnEaAfCiAzC[v@cAnC_A`CkAlCgApBILOV[f@o@|@a@f@W\\}@`AKJq@l@]ZCBaAr@k@^MH[RaAf@E@a@Rc@RgCx@WHoAT]FmAHUByBFS@OAiACaAKC?}@MG?gAScAYGCkAa@SKa@Q_@Sa@Sa@Uc@U]UmAw@qCoB{CwBCCiAm@wB{A_GeE_@W_Aq@_Ao@_D{B_@W_D{B_FkDEEgCgBQKiAu@eB_Am@UIEa@OCAcAWm@KoAGs@?k@@oCPeBb@qChAsDnBoH|DcB|@aAh@a@RaAh@kHxD_@ReB~@_@PeClAcAd@_@R{At@mAr@_Aj@}@l@OJm@h@_@Xq@d@MJ}@x@]\\yAxAe@f@kE`EmAjAkA~@{BjB_@Xs@l@i@`@_@X{BhB_@XcBrAYT}@r@_Ar@}C`C_@XGFu@l@}AnA_@XQNKHmIhHu@h@y@h@g@^OHYNo@\\k@RQHYJgAZg@J_@He@Hy@N{@HcAFs@@k@Am@?cAGc@CoAG[AqDSoCMc@C]Ci@EgAGc@EqDUc@CeBKEAgAC_@AC?q@?m@@u@DyALm@FYDgARk@La@Ja@Hs@TqA\\cA`@iBx@u@\\oAr@o@b@oA|@o@l@y@v@wA|AOPcAjAk@z@[b@eAhBy@tAABiAlBi@~@y@xAm@fAw@pAgBtCk@bAWf@Yd@Wf@q@jAYf@KPiCvEEHQZkAtBwAvBo@v@ILaAbAk@f@[XuAfAiAr@A@u@^cAh@wAh@{A^q@Nu@LkCVI?}@BcAAs@C}@ImAMk@IiDq@eB]mAWmCg@mBe@yA[EAm@Ki@EQA[?gACG?o@B{AJg@DS@_@Dm@L}@Tk@P_AZc@Pk@VIDUJgCnA_@POHsAr@a@RaAf@mGzCcBx@gB|@_Ad@y@`@aD|A{C|AeBx@y@b@UJKDaAf@[Lw@\\u@Va@La@NsGtBc@NcA\\oA`@cGnB{OpFaBj@cA^cA^c@LuCdA_DbAa@LgBj@c@NeBj@c@LwDlA{Aj@}@Z{Ap@aAd@g@ZID]T_@Z_@Z_@Za@^c@b@q@p@]`@e@l@[`@c@p@o@`AUd@c@x@y@fBa@~@Yx@o@pBCHQl@g@bB_BnGc@fB_AzDcBfHa@bBQn@e@bB[hAUp@CHIRKT_@~@Wl@w@zAq@lAEFW`@]d@Y`@ORKN[^_@b@m@t@mAhAm@h@GD_@VEDYRKFSL[Rk@Z[NOHsAn@MFSJa@Pa@Pa@RkAh@yFbC}@`@wB`AqAl@a@Pa@Po@Zu@Za@PyAn@mAj@cAb@a@PiBx@sCnAc@PuDbBu@\\iDzAaAd@mF`C_F|BkAh@A@a@PYLcAb@w@Xm@Tk@PyAd@w@PeCb@A@sBX}@LkAJuAJgDVaBNoCVYBI@c@DmCVsBPqFb@}BPu@FwGd@cALmARaAR{@XODa@NA@{@^cAj@uAz@mBzAYTCBcBtAYT_@X{CbCCBiEtDi@`@_@XuB`ByApA}@p@y@h@m@^iAh@u@Xm@Te@Ns@P]JiARC@y@Hw@F}@DQ@q@@eCBqDA{B?{AB_@@{@BoAHk@F_@FK@UFOBs@PA?y@Tm@VODQHSHMFWLIDa@Ra@RKFSLa@V]TOJQJ_BfA_BhAa@VmChBQL_An@_An@w@h@o@d@sDfCmA|@YTy@p@_CrBiBhBeAlA_@b@ORKL[`@kA`Ba@j@Yb@ILcAdBWb@Yd@MTcAnBg@bAa@x@sA~CkAvCc@jAq@rBYx@Y`AENSx@]rAa@~AAD_AzDs@~CaA`E]xAgCvKoApFOn@aB`HOp@qApFq@nCOp@WfAuGfYSx@qApFWbAg@|B_@`BaAfEm@jC_BzGm@|Bo@~Bo@pBc@nAgAnCiBhEO\\yAhDcA~BUh@cA|B}ChHUh@qBrEoBrEADeExJ{CjHUh@IT}KrWkG|NWh@wAhDyAhDk@tAWh@_FjLoGvNqF~Ls@bBu@hBs@tBk@nB_@zAG^Mp@Ov@UrAAJKp@Gb@a@zDEd@Gt@uAnOGr@It@W|CGr@Y|CQhBGt@uBbVOfBGt@QhBGr@cAdLs@lIEb@It@eBvRIt@a@pEGt@k@fGc@~EWnCGt@c@tEWzBOfASnAUnAMp@EPI\\c@|AMf@e@xACHk@`B_AvBGLk@lASZYd@a@p@QVWb@A@uCtDQT[`@gErFW\\sAdBsAdBo@t@e@n@sAdBY`@mA~AiF|GW\\sAfBCBgBrBGD]\\[Vw@r@oBrAsAp@s@Xa@PSH_AZ_AT{@Nc@FWBu@Hy@DiABi@@_@?kA?I?Y?cFCiF?yAAeAAmBAw@?oCAyDA{DAA?c@AoBAkIC{@?aA@}@Di@Hw@Nw@Te@Ri@Xo@d@m@f@STUTGFQTY^U^[h@IRUf@[r@g@tAQl@IRUbAg@dCSfAaAdFw@fEMp@s@hDg@hCYpAwA`G{BjJ}FjV[lAw@dDeB|GOn@On@Qn@Kb@_BnHSdAM`AQrAW|B[pDWnDGlACn@Cr@ElBARAlC?@?nA@jABbBLlD?BBt@XjGFtARpEJjBRvEHhB\\fGZpGBf@@JHjBDt@HjBDt@LnCZ|GDt@RlEF|@Dt@P~CJjBn@pLHtAD~BBv@?V@pA?@A~@Al@Ab@API~AI~@C`@WnBOfASfAc@nB]jA[`AIRKVYl@Sb@Yf@Yh@W`@[b@QVa@h@_@`@i@j@eAz@KHg@^WLa@RgAj@uBbAKBaAd@g@T}@`@cAb@C@]NcBv@A?oHfDIDWJeChAa@Pa@ReBt@yDdBa@PcAd@iDzAoHdDmF~BiElBcAd@eBt@a@RcBt@gChAmBz@sD`BmAr@A@cAn@[Xo@j@i@f@A@c@b@e@j@_AnAy@jAs@dAw@jAoDnFcEpGuB`DYd@gA`B{@tAoAlBu@hA}C|EYb@s@hAoAnBu@hAaCvDA?yD~FcCvDmKdPqAlBwAtBQTA@[^i@j@k@l@eAbA_@\\i@f@c@`@]Z_@^a@d@YXAB]^AB[b@Ub@Wf@Sb@Sf@Sl@Qn@Mh@Kj@Kn@Kx@Gl@EdAAJCl@An@?b@?v@D~AJxF@HFzD@n@?DFpCLlGBhA@t@B~@@j@?TDtA?LB`B@r@PbIFdCD~CHxCBbAR~HBbBNnG@n@DpB?L@f@@h@@~A?hAAfAGvCM|EAn@KxEAt@UzJWpLOvGA`@ARAt@Ct@A~@CbB?RA`@?^?T?^@v@B`A@d@BV@ZFz@Dl@BXFt@?@P~A?Fl@dGz@fILpAJvADt@DnA@Z@v@?F@vAA`AA\\AVAh@EhAKpAIdAANGb@EZKv@ERUnAERMp@ADMj@[zAOv@Mp@On@Mp@Op@Mp@On@ETWlAOp@Mn@_@`BI^EP_@~AMf@e@fBOn@Qn@a@~Aa@zA?B_@~AIZERGXGVAFId@Kn@Ih@K|@AFI|@Gv@Cj@Cd@AJA`@C|@Al@Az@?dACtGAfAAp@AvAClACh@C`@ItAMlAAHIh@CPIh@SlAOx@ADOl@?@Qn@Qp@k@`BOb@Sj@Uj@g@xASl@Sj@uFxOeB~EABe@tAY|@q@zBM^CLc@`Bo@lCCJKd@Or@_@bBc@dC[pBAFIj@Ih@U|ACPIr@Kr@?@Ip@Ir@CZEVGt@CNWbDMnBK`BKxAEr@AROlCEt@Er@Gt@?FKdBOfB?BMlAETAHGh@M|@c@dCMx@ERSpAEPM`AIv@CNGx@QbBGr@Gx@QdBOtAAP[dDIl@Mz@Q|@UhAU~@YdASr@_@~@]z@IP_@r@OZYf@OVIJ[b@MNMN_@`@y@x@IJSNYV_Al@aAf@a@RQFUHA?_@Le@JGBc@HYDI@e@Do@BsAHA?wETgBHg@DW@e@HI@]Hk@L]LWHi@Ri@Va@Te@Zi@^IHi@d@_@\\m@r@ON_ApAk@bAIN[p@g@jACD]`AGPK\\ENe@dB_@vAOn@?@qAnFYhAWfAOn@g@rBs@~Co@nCQn@_@zAc@`BA@Sr@e@rAA@Uf@MXa@z@a@r@]h@c@l@w@`Aa@`@]^A?QNKJGD]Xi@^i@XEBa@PeAb@cA\\SF}EzAkAd@qAj@IH[RE@WRs@l@QNe@d@STKLaAnA_AxAkEdHcCxDmChEMTmAnBcCzDYb@s@jAcDhFwA|Bc@p@s@jAsD`GmFrIYd@}LzRYb@aCzD{LzRYb@qEjHuM`TkFnIKPuBhDsAtBU^Yb@Yd@m@bAaC~DOT{EzHyBlDa@p@s@jAYd@EDaA`Bm@dAqCjFKRWf@Yj@k@nAWh@GH}@pBUh@sA`DEHw@lB]|@Sf@ABe@nAWt@M\\ENk@~Am@hBIV[bAm@pBA@Sn@m@rBwBnHK^ENu@jC}@~Cw@jCc@|AoAfE_@nAIZs@dCm@vBUx@c@|AU|@Or@Or@Or@ObAMr@ERG\\Kp@e@tCYhBm@tDw@bFMr@WdBMp@qBhMe@xCYdBKr@kCnPc@rCMv@wAxIu@tEGb@CNkElXq@jEYdBwCbR_A~FMp@AFiChPo@bEmAvHu@pEu@nEc@lCe@zCMr@Kp@Kr@i@fDGb@a@`CYzAS`AYnAYfAUt@]dAKZ]|@c@fAQ\\Wh@EJs@rAi@z@y@rAaCfDqAjByEhH_F~GkBlCkBnCABW`@s@hAINg@`Au@~Ak@tA_@jACH_@rAc@|AOf@w@rCIXEVOn@EPI^Mn@?@UnAERIh@AHKr@E\\S~AE\\Gn@?BKhAC^Gr@Cv@Et@ADCn@IjBEt@IjBCt@A@Cp@s@jOKnBAJGz@Gl@C^KdAMv@Kp@A@Q|@If@Qp@Oh@?BQh@Kb@]bAMb@y@fCSn@i@fBM`@K\\EP[pAS|@?@UdASpAWfBQxAIv@?@E^Ep@IjAEnACh@EvBAhA?hBB`BBj@@f@@RDl@Dr@Dh@@RHz@DXFh@@HFh@PjAHb@Hd@RbALj@DRH\\Nn@^`B@BNj@Nn@Pn@`@|ANn@h@rBrD|NNn@Pn@Nn@`@~A`@~APn@`@~AbA~DNn@dA`EVdAFXLl@@@ThAThA@@Jp@DXPpADn@@JDdADvA?|AA|@Ct@ALCf@C`@I`AKx@?DKl@ALIb@I`@Qv@CHOn@CFYbAmAlEQn@u@lC{ApFw@rCQn@CHwDdNWhASx@WnAUvAOhAEXEXGj@IjAG~A?JAh@AVClA?nAB|BD|D?l@?t@?p@CzACTCn@ABKdAM`AQ`AADMn@]nAK`@MZEJa@~@a@t@_@n@o@x@o@p@GFe@b@k@b@KF]VWNa@T_@PqBt@a@NoAd@yAl@sAn@QJa@PA@i@XUNYTs@h@c@^oAjAiApA}AnBu@~@{@bAuAbB_CpCw@bAe@r@Ud@[j@]|@]|@CJQn@ADOh@On@Mp@CLMhAOxAEx@EhACpACxCCrJAlAGnSE`LA|BIfKAfA?l@?t@A`EAzB@zB?pG?H?j@AjBAlEC|G?F?l@@t@BxA?RBt@?RB`@HfBDx@HlAPjBX`C@HPpAN|@DXFVZzANx@HZFRVbATx@DNRl@JXFPj@vARj@Vn@Rf@Tj@~@`CTh@bCbGJVt@hBlBtEnDxITh@pDxI|@zBBBnAhDp@hB^rA^xA@DLp@DXRjA@BHn@@FFj@Fd@J`AFh@Bd@JrBJ|BBt@RvEDt@N`DL`DDt@Bt@B\\HtED|BAdCAf@?t@AFE`CGnAAb@APGt@IvAa@`EG`@Iv@Kn@Kr@ABSfAEVMl@?BWfAa@fBk@nBAFOf@Sl@IX]~@]dAIRSl@g@xASj@i@xAg@zASj@{@fCUt@Mf@M`@S|@?@Mp@Kl@Mz@Kv@OdBIlAGrACvA?dA?@?r@?ZBnA?HBj@@z@HfBBt@TlGJ`DBt@HlBTlGXbIFjBr@hSBt@j@|OFlBHlAJnA?BHn@Fr@?@PfALv@ZtAZpAf@xATl@Rj@JTHV|@bCRl@Tj@Rj@t@tBFNTj@f@xA|@dCTj@Rj@Rl@rApDjGbQzAfEr@tBh@~APn@Pp@Lh@h@hCRbAJj@XvBLlA@BFr@Fh@Dd@Fz@Dz@@b@Bl@@f@@H@j@@x@@t@AfCA|AAf@A\\AVGjBAXAZIdCK~DCt@Aj@KjDCt@u@vVCt@K`DCt@GlBCt@At@OvEm@hSKbD]pLK`Da@fNCt@OvECt@ElBQjFIlCGvBGtBG`CCxBCt@AzAANEpDGxEAt@OrLEbDE`D?NE`CCbBAv@AlACn@Cl@EdAAFQzCc@nGUvCs@tJQ`CY|DGr@]tEO|B}A`TGt@u@lKQfCW~CMhBQbCQfCEt@OlBG|AG`BChAA|@?n@?h@?J@jA@n@@^?F@Z@`@Bx@D|@HlAVhDFp@?@dAfMb@fFVxCbCdYNhBFt@jBpTFr@\\zDj@`HPhBV|CBXBZNhBFt@Hr@Ft@V|CFt@^rEFt@NhB@HN~AFr@NjBNhBFr@PhBV~CFr@V~CHr@Ft@Ft@Fr@pApOFt@`@tEV|CFr@PhBFt@bBzRNhBFt@Fr@Ft@Fp@fB|Sb@hFp@|HhA|M|@bKJpADb@Fh@NvA@BHr@Hl@BJJr@RdADPJj@VbARz@X~@ZdAJZRl@jB~FX`Af@|Ab@pAn@pBx@hCPl@x@hCf@|A`@pATv@Vz@Nf@Lh@@FZnAFXF^@DP|@PfAF\\D^Jt@PxAPzAp@dG@BHr@RjBh@rEHl@`@jDJ|@ZlC?BRfB\\|CHr@f@rEx@tHZfCV~BJt@Hl@@JFf@DXN~@Jl@Hb@H\\Ln@HZJ`@J`@J^VbAd@`B^rAb@zA`BxFtA`FBF^tAPn@~@dDXdAb@|AHVFVd@|APl@Pn@`AjDx@rCBHt@jCPn@jA~Dt@jCx@rCV|@jAbE\\hAt@lC^vAHXNf@Rt@Pn@|@bDZfAb@|AVz@^pAPl@Pn@t@jCxAfFb@|AhA~DPl@XbAxB|HHRNl@\\pARr@Pn@Pv@Px@FXHb@Jh@Hj@Lt@?DHh@Hp@Jt@Fr@Fr@Dj@Dl@@BBh@@JDp@?BDhABhABtA?p@?t@CbG?bACtFCdF?v@At@?pAC|DCxECnHAbCAt@G`PElJ?LAt@AxECxGAdD?j@Ar@?p@AbBEtBQ|CQvBMzAa@fEQhBOnCEt@GjBEhA?`@?v@At@?|@@zC?t@?t@?x@@hB@t@?v@@vBDzH?t@?t@BfELjF?NBd@Dr@d@dK^xFVzEFt@VzEDn@VdEDfA@t@FzADlEAdDG`BI~BEdAEt@IjB[jGEx@Cp@I`CA^CxA?RAfBBx@@v@Bt@@PBb@TjENzBJjC?NFxB@f@@jAA`@ApBI`DI|CKpFEnB?T?rC?t@?t@@lB@t@HhH@pADxG@l@@t@BlB@jABtABt@@v@Dr@Ft@Dt@r@jL?@Dr@JjBDt@FjABrB?bC?p@?z@?t@?lB?t@AbD?F?l@At@At@ApC?fA?v@@zAH|CBRBt@Dt@B\\\\zETxBZ|CX|CPhBFr@T`CBd@Ft@HjA?^Bt@Bt@DhBCdDAPCb@Et@I~AAHShBSfBQhBw@pHAHy@fJI|@MnBIrAK~AYxGKjBIjBi@lLM`DEt@ANEd@Gr@UdCOjA[bCWzBOfCGvB?RC`B@HDjB@f@?NBt@B`A\\hDh@tDDXf@rDLx@ThCJbC`@fLJdCZ|IXfIFnBVvI?bBC|AIrCEp@WtC?DW~AKr@Kl@?BaAtDWv@Qj@g@zASl@g@zAeAhDy@~Cm@dCAFe@|CYrC?DY~CEd@GbAi@`I?@IhBEt@EnD?zD?NHrCJxBFtA\\pDb@pC^jBRdAx@nDn@pCn@pCPp@zAvGzDrPn@|CxAlIn@bFFb@r@bH`@pF\\vGrBz`@f@nJ~A`[fAhTlA|Ut@~Nh@pKDt@Dt@d@bJ~@lPHnARzD|@xPVjFj@hLVzEDt@x@bOj@lKHrCHvD?dBAdAG|BGjAK~AUxCObBsB|QeAdKGh@g@~EMpFAtCC|FBtCHlBPpCB\\PhBDh@@HbBzRvCx\\ZjDTpCFr@`E`e@`B~QjAvN`B`RD`@b@hHP~EJ~JAxRAr@?bDAt@CrL?t@GtWCtQAxEAt@?z@?dN?jAGvL?xK?t@?d@CvJCzJCtHGrQAvDEfI?t@?t@CfM?pH?t@?bDAhFO`KAt@?d@SrGOjCQ`C[~CAFa@zDCTm@`FaAvH]fCIr@}El_@eClRIp@eClRkAjJcDhWKr@Ir@uAtKe@lDo@|EIr@a@zCwBzPIr@CNs@pFIr@Kr@UfBIr@UfBKr@Ir@Mz@o@bEo@pCMp@ABe@fBy@dCoAbDe@z@_A`Bq@lAKPg@x@Wf@kArBYd@q@lAYd@q@lAYd@cChEk@dAyBfEGH}@rBMZ_A`C{BtGc@rA{F|QSn@eInWQl@_BdFSl@Ql@}Jz[eFhPe@zAy@hCSl@Qn@m@nBKXqBrGSn@u@`Ci@jBU|@IXWpAQrAK|@a@rF_@rE_@rEY~CGr@W~CGr@I`AS`DItC?LAf@CxBCnJAt@ApE?FAlBEzJAlBAnAEbJEjMEfI?t@EnG?t@?v@At@?t@At@?v@At@?t@AlC@z@?x@?bB?tBCnGAh@E`D?LEfAEl@A\\CVGhAGn@SvBKhAe@rEIt@Gr@QlBMvAATCZGjACpACbAAfA?`A?rB@JBjBFjBLdD^pGXdG@VB\\Bt@HpA@XBt@@RDfABvABlA?J?v@?F?l@A^?TCn@?DCt@?HEj@Et@?@KfAOlAU~AO~@Kp@[pBIf@YdBKp@Mv@iAbHmBxLi@jDSrAaAdGuBnN[lBu@xEMr@Kp@Kr@G`@ENMp@WvAQ|@GRSv@W|@CFSj@O`@e@nAa@x@]p@Yd@e@r@e@n@EHk@n@g@b@C@YV_@\\k@^y@d@e@Vu@Zq@RsA\\C@aAReARQDQBoATs@N}HxAc@Ha@Jc@HeARc@Hc@Ha@HgARa@HwAXgB\\oATa@HiBZ[H]F{Dr@y@Pc@Hc@HcB^yAXa@H}AXKBiCd@iCp@c@JUFKBkA^aBl@iBv@]LcA`@?@a@Na@Ra@PcAb@a@PC@yFbCs@Xa@PEByAl@g@Ra@P}@^kBt@[J{E~AgCx@aA^wBt@oBf@iBb@oAZiBb@kCn@YHGBkCn@c@La@JoD~@w@TqA^c@LsDdAiCx@A@}@^e@V_@R[RYPUPWR[XWV]\\UV]^uAbBuA`BGHGF}AlB{AbB[d@oBjCeCdDC@[`@oDrEaG|HcArAuBlCqCjD_AjAeBxBwAjBaCxCcBvB{GvIsAdBuAdBa@h@q@z@Yf@e@~@k@hAc@fAQh@KXSz@Sp@WnA[rAsAnG[zAOp@CHKf@g@~Bk@hCGZOp@a@hB[zAMn@c@nBi@dCc@tBgAbFMp@a@jBKf@Op@m@rCYnASbAQt@Mj@On@K`@g@lBCHa@pAM^ELg@xAABUd@Uh@EJ_AjB_CdEGJOXYf@Wd@Wh@q@lAq@lACBUb@sBrDINo@lAYf@q@nAWd@q@nACFS^Yd@q@nAk@bA]p@Wf@GJaAvBc@pASn@Oh@Mn@Kl@Mz@?@Kr@Gd@a@jDALGd@OvAMdAAJIf@Gh@Mt@Oz@Ib@K^GXK\\Up@[v@a@z@[p@]p@Yj@Wh@}@nB]v@EJM`@Of@Op@ABUbAG^AFGh@Gb@APCREp@C^?DAVCh@?j@Ab@@X?t@@l@Bf@Dp@Fv@LjAJfAN|AX|CDd@Fr@BPFxAB\\BlA?t@?@?t@A\\CrAGbAMxAKn@CPSjAAFMp@Kr@AFKh@Gb@CNSlA[dBET[`B[fBKp@Mr@O|@MbAYlBCNk@`DIf@If@O|@c@hCCLKr@Mr@If@AHGXKd@Ml@]tAQv@Uz@Oh@K^Qn@Ql@?@Qn@On@Mb@g@jBOl@ENi@jBEPQn@Op@Mh@c@~A_@xAQr@Uz@Ot@[tASdA]nBOnAKz@ANGp@Gv@CZKvAEr@GlACl@El@ANE\\MrAQxAIp@E`@G`@I^GZETGVCJIZK`@Mb@Qj@e@|AENo@zBGP[lASt@[pAi@pB_@rAa@xA?DQn@Kd@Ux@Ql@EJM`@Sj@ENe@pAe@pA[t@e@lAWf@IRa@v@ADWb@ABWb@SZ[b@GHWZQVg@j@_@b@OPKLi@h@_@f@i@n@UVc@h@w@~@]^y@~@]^]^OPi@l@QRg@l@c@h@SVA?WXCBQPQNUPYPKFGDWLC@[Nc@To@Zy@`@{BfAwAt@oAp@u@ZaAd@a@Ra@Pa@Rm@XUJ_@RcAd@EB[NcBx@a@Ra@R]NC@aAh@aAf@KDUJa@Ra@PC@yBdA_Ab@a@TKFOH_@X]X]\\[X]\\A@[`@SVSVMRCDU^?@Wd@OX_@t@_@x@Yp@Uj@Sl@Ob@GTCFETIXIb@Kj@EXKr@Ef@AFCTC^AHC`@Cb@A\\Ax@?f@?F?V?P@J?X@f@Bb@?F@RBX@FB^BR@THj@Fd@F`@TtAZvBBPJp@BR^dCBHFh@Hh@@HFh@@HDd@BNDn@@BDt@D^@TBj@?HBT@^?FDr@BjA?`A@N?^@zA@pD?lA@rA@nA@r@?B@t@@R@`@?HBf@?B@RBZ?DD\\BV?BFd@@HD\\BTHh@@HJt@F^Jf@FXDRHZHZVbAFPHZTv@f@bB\\nALb@ZdAZfADNNn@Nl@Jf@Jn@Jp@Fr@B^BT@R@`@@R@`@?@@t@?J@zC?~@?p@?j@B~@Bp@@HBd@@BB`@DRDXDVLr@@HLd@Rv@d@`B^pAl@nBfAnDdAnDTt@bAfDBJPl@Rn@BLl@`CBNH`@PdA^`C@BHr@Hr@@F^rCDRZfCRfBHp@Jv@Hr@Hr@@RD^Hx@JfBHfAD`@Dt@Dt@f@`IPtCLhBJvB?@DbA@d@@x@?h@?JAf@GjACl@AJGr@Kz@G`@EZUbA?BSr@Qh@ENMZSl@e@pACFi@vASj@]t@O^MZGLa@fAGNSl@]`AIVQ`@[p@Q^EHU^]h@EFUXGHo@x@OP_@j@e@p@e@x@GNWf@Yn@g@pAGL_@jAMZEPMd@CH[fAa@jB_@pAYnAi@bCQz@AHIh@EVOdAI|@ABEp@Et@CdA?d@?P?v@?b@?@D`ABf@Dt@@@PfBLp@DZLn@FVHXFTTv@N`@N`@DHZr@PZ@@\\h@V^HJX\\TR\\Z^ZbAn@dAd@~@ZRHn@VlEdBz@\\h@T`@PVJb@RDDXNn@b@VRB@^ZXVd@b@VRHFpA|@b@V\\RBBTJJDVJHDZJlAX~@Vf@Jb@Lx@RrBh@RDNDdAV`@HfAV`@J`ATf@L`@JrAZTFb@JdAVrAZpA^p@T`@NZLNHp@ZVNHBz@d@lB`Ax@^jAb@VJlAd@PHNF`@Nb@P`Ab@`@PFBXJbA`@RHlBr@FBbA`@B@~@^dBr@@?dBp@`@N`@NLDt@Z@?`@T^R@@d@^TPDDZ\\RTX^DHJLd@v@n@dAr@lADF|AjCjAnBh@v@l@v@bBrB`@b@`@d@t@x@Z^zAbB|BjCv@z@|@fAJNBBRX^h@^l@h@bAZt@N\\Vl@?@Z`Ab@xA`@|At@`Dt@~CPn@^`BJ^BN`@`BLh@@Dp@nCPp@`A~D^`Bt@~CZpA\\xARv@Pn@p@pC@DLh@j@|BDPNp@DVFXHf@J~@BNFl@Bj@?HDx@@f@@z@Ap@?h@AJEl@Gz@C\\EVKv@YtAQx@On@Op@Op@Mn@GXGVOn@Qn@Op@CJi@dCQr@]bBU|@Sx@[|@?BWf@AD[j@SZe@r@QP[^]^o@r@IL[`@[^IJk@z@Yf@o@hAYj@_@v@a@hAGNKZOb@g@hB?@s@fC?B_@`BMp@Sz@k@fCm@bC}AzGeBxHABOl@uAdGYnAu@bDI\\Op@m@rCy@~Dq@lDg@nCCJ[bBMp@ADoAxHIb@YdBMp@[fBg@rCMr@If@Oz@o@~D]pBMp@Mp@AJIf@YdBKr@Kl@?BKr@WdBKr@Kr@G^EPgAvHWbBKr@OfAo@pF[dDc@hEADIl@O~@Q~@GTOj@ABSj@IRKVUh@A@Wd@ILOTY`@A@g@j@QPURIF]Zq@h@KJ_@Z}@t@]\\EBWXEDS\\QTGNYf@CHQ^MZGNSl@CHSt@Sz@SfAIp@ADEn@Ef@IjBMfFKvCAl@OvEADMnDIdBGvAMpBCR_@xEGh@Gh@CVCVOrAStAa@~BsBnK[zAAFYlAERQn@On@K^m@tBu@`CQl@g@zACFQb@Sj@CHOb@Uj@M\\ELk@tAUj@aA`CMZuBfFADSb@g@dAa@p@QZGHYb@SVe@j@[^[`@CBu@z@]^u@|@_@b@y@`AORKLe@p@g@v@Yh@Ud@ABUj@ELK^Of@AFOn@ETG\\Kp@Ov@OdAEZKp@Kr@a@zCKr@Ij@ADq@zEQ~AM|A?HG`BAHAlA?\\?t@?R@b@BhB?@?rBAn@Af@ALEx@Gp@EXEVOn@?@Mb@CHIVKTWn@Q`@A@QXa@p@ORi@l@EDWV]\\w@v@CB{@x@]\\}@x@]Z{AvAyBrB{@x@]\\_@Z]\\{@x@_@Z]\\SRg@d@]\\}@x@]\\]Z{AvA]\\OLeD~C_@Z]Z]\\}@x@YVCBu@n@GD_@XKHSJYPGBa@REBYN_@PA?a@NQFQFa@NeAZUHKF_@Pa@V_@V_@XABUTCD]^W^[j@ABSd@GJO\\Wr@Od@KVETGRG\\AHQ`AEXE\\ATGt@APGjA?LAr@?@@v@@`@@R@j@F~@Fr@PrAR`ABJJd@ZvABH`@~AbB`HPr@Nl@Nn@Nn@p@pC`@~ANn@pArFPn@^~APp@Nn@Nn@`@~ANp@Nn@Pn@`A`ENn@?BNl@Pn@Nn@Nn@Pn@Nn@Pp@Jb@BJNn@Nn@Pn@p@pCLj@Pt@Pn@H\\T`ANp@Nn@Nj@l@hCBJNp@FVFVFXDVBLJ`A@XBX@Z?Z@X?bA?h@?VA\\Ah@I`AALGd@CVMv@]~AY`AWl@Yf@GLOXIJQVKPONIJSPMLOJ_@XSLc@Rg@Ry@PyC^qBRc@Dc@Fc@DeAJc@FG?_ANgAN[D[Fq@To@Xo@`@A?_@ZWTi@p@SXW\\AD[h@Wj@[z@IVSj@KXk@rBEJg@hBq@`Ca@lAADw@bC_@dAYt@EHMZ_@x@Wd@_@v@OVOVILw@lAW^[`@EDq@|@WZCD[b@[`@[`@QTe@n@[`@[`@SXGH[`@[`@[`@W\\CBYb@[`@i@r@MP[`@[`@c@j@_BtBGH[`@[`@[`@SVyAlBkA|Ag@v@c@v@_@v@Un@CDa@rAQz@ShACPIt@KbASnC?@Gr@Iv@QzAOz@AHMd@GXGTOj@ABUj@ABQ`@ABUb@ABYb@?@a@l@i@n@y@v@}@`A_@f@[b@ABU`@CD_@v@Yv@Ut@Or@S~@If@UjBABi@zE[bCAHyAvMg@pE_@fDIr@]|CUbBObBCJCf@IfACb@O`DAPAb@Ab@CxB?D@hC?X@t@?t@@h@@xB@v@@t@?HBxC?PBpC?t@@r@?@@lBBjB@jA@`@?t@BlB@jB@v@@jB@v@@jB@nAHzK?t@DpG@HBnEJjN@PDdCF`BBR@\\JlARhBJl@Lt@@FLh@FZDTHZRv@Rr@Xv@Rd@HTb@|@?@dAxBn@pATb@Vn@@@Rh@Nb@Nh@DLNf@Lf@DNH^Np@Hf@Lr@RjAJr@VzA\\lBZbBZdBLp@BNJ`@Ln@Nl@Nd@DHPl@f@zAx@hCFP^fATl@f@xAdB~ERl@Rj@|@fCPh@f@rAr@hBd@jAr@fBfD`IdA`C`FhLVh@Th@~@vBXp@Vh@Tj@nBrEvAbDdAdCj@tATj@LXZt@@D`@`Al@lB@BNp@Jf@@FNp@Hd@N~@XdBXdBHf@@Hl@vDh@nDJp@F^BRRhAXzAJ`@Ld@^vAVl@DJTd@@BVf@FJPXDFTZFFn@z@JJNTx@`A`AtAXf@JTHLLXLVZx@BBRj@Pf@Tr@L`@BLNp@^zA?BJp@Ln@L`ATzA@JHf@Ff@VhBLfAXrCPbBVfCBZX|CH|@^dFFdB?b@@`@BjABjBBlA?^@t@@t@?xAE`BEz@CVAJIf@ALIb@Kt@YlAEPM`@EJYz@[p@Yf@KN_@j@_@f@QTs@`A_@b@qBfC[^[`@kAxAIJw@bAsAdB[b@WZ{@hAaBtB_AvAk@jAe@tAGNK\\Sx@AFQ~@QrAMzAEfA?@At@A`@D|ABb@JjBDf@@JFt@V~CDt@NhBDb@@PNhBlArOFt@NhBB^X|BJr@Hr@Jx@Hl@Lr@Jp@DXRjALp@\\bBLp@@@Ll@h@~BbC`Ll@lCNp@lCvLNp@DN`BnHFTbAtEd@pBx@tDNn@|@bEFRl@rCLp@Jd@BH^xARt@xBlIhBvGvBxHNn@t@lCPl@t@lC\\nAlAlEPl@V~@J^b@|APn@Pl@@HNd@Pn@Nj@@@Pn@Nn@Pl@Pn@Pn@Nd@@F`@`BDPH\\VrABNT|A@HFr@Ft@@HH`BB`@?RDbB?tBEjDAv@Af@?LCjBAv@At@At@ClCQ~NC~ACxBEzEEbCCpCCdBAtB?X@~ADrA@HDx@D|@Hz@Fh@Hj@Hn@Lj@Px@Jd@Lb@Rl@Nh@L`@J\\LZJVLXTj@`@z@`@t@V`@f@v@vAnBt@bAZ`@FHxAnBdAxAtAjBTZDF`@d@VZb@b@d@d@f@d@JJRNRNf@^f@\\~@h@\\P`@TLFRJ`Ah@TNXPPJPLRP`@`@RRXZRVR\\NTBDT^@BRd@P`@Pd@DNL^DLLf@Px@@@Jd@@HFd@Jv@Ff@Bb@F|@D~@?TBnAH|D?@@t@BdAFrC@t@?BHnD@d@@t@D`BHxDF|B?XBt@@^?VDlAB`BD~ABjB@N@d@@t@H~CFdCDbABn@Bj@B`@@HDj@?BDl@Jv@BRF`@Fd@Nx@Jh@Jb@Jb@^rAb@|A`@tA@FV`AH\\J^Jf@Lr@Lt@L`ATjBZbDHr@Fr@@LHt@Fd@Hv@Jt@F`@@JDTJj@H`@Ll@@BLj@FRHZ@BL^BLTn@Nb@Rf@P^Tf@JRn@nA?@Vf@`@v@d@`Ap@nABHP^Vh@FNVj@JXRf@?BN`@BJHVHTFTRz@T`ALn@Jh@@FZbBNp@BPVpALp@Lp@Lp@DRTnABHP`ARlAJp@DTDZJv@J`ANvA?DFn@Fr@HvA@RDt@?DBn@Bf@?NBt@BnA@|A@`BBlA?\\@v@@bB?FBlB@nA@Z@d@@n@@V@VB\\B^N~BBd@@NLhBHlARpCDj@JjBBVPfCFdARnCDt@LdB?DBb@Dl@Dv@BbA?j@?h@?h@?TAHAd@A`@C\\Cf@KxAInAGt@Gt@En@?BGt@MjBGv@Cf@AHA\\AV?BAZA^?X?^@^?H@VBn@Bb@@R@TBTD^Hf@Jp@\\dBf@rB@Bl@dC@FNn@Nn@Np@Rv@Lf@Nn@`@bBVnAJh@FXDVBR@DBTDb@Dd@?HB\\@V@R@^?@?`@?h@?`@?LAf@?@Ch@Cn@ANEl@[bECXEr@Gt@]tEAF[nEg@zGARKhAALGx@Gn@CPE`@ADGd@Ij@Kl@Ml@Op@Ol@GVIVSt@O`@Sj@Sh@Yn@]r@EFYf@ABYd@{C`FkAlBYd@S\\oB~Cq@hAi@|@c@p@KNc@t@]h@CDU^QXa@p@EFQVOXGNABS^CFKTO^O`@Sl@?@{@dCQh@A@oAtDy@hCCFc@pASl@o@fBM^M`@EHSj@[t@MVMXQ\\OXW`@U^SXGHSVMPMNOP]^WTWTs@j@_BjAeAx@_@XOJ_BlAMJ_@Vu@j@iBtAqBxAoA~@uB~AcBnAMJqBzAsCtBiCnB_Ap@_Ar@]V_Ar@mDjCwDrCuHxF}C~BgCjB_BjA}@r@sA`AiIhGeCjBuHxF_BlAkAz@c@^YVSNQR_@^c@d@]b@aAhASXsA`BwAdBq@x@EF[`@]^IJc@f@KJUVGFo@p@kBdBu@p@A@_@XCBm@d@kA|@WNiAr@cBbAOJOH_@TaAh@aAj@GDcFrCi@XsAr@a@PC@]P_@LE@[J_@LUFUFA?a@He@Hc@Ha@De@Du@Fk@@c@@uCBc@@gA@C?kB@cBBiA?qA@aB@A?a@?c@?Q?yA@gA?]?qB@}A?gA@gA?{FBm@@aB?gA@gA@a@?c@?c@?W@o@?wFBgABI?mABm@BC?]BE@c@Bc@DkAJcBPe@DmCVA@a@D_@Bg@Fk@F[BiDZcDZWBG?c@DW@[@]?]?[A[CUAWCUCWEWEYG_@I[Ka@Ma@MYK_@M]M]MGCYKGCq@WICYKIC[Mc@Oo@Uk@SOEa@KA?a@Ic@KQEOAc@IQCQAc@CYAm@CWAs@C_@?c@?C?c@?cA?I?Y?O@S@Q?[BW@I?e@Dq@Dm@Fm@F]BMBM@s@J]FMBUD[Fq@NwA\\c@NKBWHSFg@Nm@Ts@Ve@RIB]Nq@Xu@^_@Ru@`@m@Zo@^SLUNiAx@s@h@SLOJw@n@UREBc@`@k@f@c@d@SRu@v@WXIJe@h@Y\\_@d@c@j@[`@QTY^]h@e@p@k@|@c@t@ILc@v@]n@Wd@CDeApBINo@nA{@dB[j@S`@g@dAc@~@]x@Ul@Wr@Mb@Mf@Md@?@Mn@ELQ`AO|@In@ALGn@Eb@CTCRCl@Er@Cj@Cj@C~@A`@IrBC`ACv@Ct@ADEtAANCt@AXCZA^Er@I`AGx@Iv@E^Il@G\\ALIb@CHGXKh@Mf@I\\GRIZK\\EN]bA_@bAENm@zAi@rA]z@Yt@y@bCW|@CHMb@Op@Mr@CNO|@OjAIz@I|@Ef@Cx@Cj@?BAj@?H?l@?H?v@@p@Bv@?HB`@Dt@Fp@@LBXBXD\\Jx@Jv@F`@Ll@H`@H^J^Nj@JX@FL`@Pd@Vr@DHLZfArCTj@Tj@Th@Rh@Vp@Rf@@DPf@LXL^Rp@Pn@Lf@Nj@Jh@FZDTJh@V|AJr@Jx@BJHp@r@rFXvBPjADZf@zDb@bD@JJr@Hr@Hr@BLXnCXnCTzBFl@BJHbABXJ`ANhBDf@PtBFh@Fr@BXL|APhBR~BLpADh@Dl@@FV~C?@TjC@PRzBDb@Fr@BZJhA?BLvAXrCL`BDd@JdAPxBBTJhAbAtLZnETbCFr@@R`@tED^PhB@L`@hFBPDt@Fp@F~ADjA?~AA~A?TO~GEzAAv@Ad@ANIzD?\\GhDCn@At@A^GbC?TM`HIdCC`ACj@Eh@A^CTCVI~@M`A?BKn@?BKj@Ox@Qv@a@hBi@`C?@m@dCCJi@~Bs@dDS|@Gb@ETEZGd@ARE^El@Ev@Cz@C~@?b@Af@@hB@~@D`ADl@Fr@JlA@HHn@?BFb@Ln@RbA~@bELh@@F|@|D\\hB^jBVlABJNn@Pt@^zAb@vAd@tAXp@Vh@b@x@Zf@LPT\\DDZ`@LNLPX\\j@j@RNb@`@j@b@|@l@n@b@|AdAB@fCdBx@h@p@d@l@`@vE`DHF^Vt@h@HDfAt@VTh@b@TTXXj@n@^d@JNZb@PZR\\P\\P\\DJTj@Rh@Rl@L`@J\\V`AJ`@H\\Hb@Hd@@JJf@@HFd@DZDj@Hx@Dx@Bf@Bh@B~@?n@?|@?b@Aj@A\\A\\AXA\\Cp@IdAYvEG~@APCx@Cv@Ap@Al@?j@?H?`ABzABp@@TDt@Ft@H~@JdAJt@F\\Lr@RdALl@Lb@Rp@Lb@Nd@^hAfCbIPl@f@zArBrGd@zARl@Rl@x@hCv@dCz@nCPl@lAvDRl@Pl@fFhPzAxEpAbEFTHVvApE`AxDf@`B`@jAHVDJN^Tj@P^Rf@Vb@Vd@PZT\\`@l@b@f@\\`@PPHHVVXTl@d@VPXNVNJFr@^b@TJDn@\\FBr@^LFXNd@Tf@Tb@TZNLF`@Rj@XFD\\PB@j@Xb@Rb@Tl@XD@v@`@HFTLd@XDDRL^X\\Zb@^b@b@RTVZt@|@b@h@t@z@l@r@d@f@v@x@TTHFRRXXb@^^XXVBBj@b@RPNLj@`@B@^V@@j@^d@Xl@\\l@\\l@\\h@VDBj@VPF`@Pr@Xp@V@?~@\\p@T@?`@LRFLDXHFBTDd@Jt@Nv@L~@LfANp@FRBr@FL@r@Df@B@?x@B`A@z@?l@?t@AbAGDAz@GzAG~@Ej@CxAKF?b@C`AGrAIpAGRApAI|AKbBKpAGPAPAzAIvAKb@Cb@CVA~AI`BIjAGzAEnAAV?|@@T@\\@`ABjAHjAJf@FPBN@b@Fr@Jn@Lz@Pn@LB@b@JJDn@N|@Xr@Tx@Zz@\\z@^l@XrAp@|@h@HDdAn@t@f@h@^`BlAvAfA@@tAfApAbAtAdAz@r@NL^VZVrAfAnA`Ap@h@JHx@n@~@r@tAdA`ExC`D`CZV^X|@t@rBbBvAhAdAv@bBrAlA~@~@r@zD|C\\V`@Z~AnAv@l@|BfBjCtBLHj@`@XVDBxBdBp@h@VTRPNLLJLNNR\\^Z`@BDRZPXPZVb@JTP\\JTLZPj@Lb@Lf@Lh@Nn@FXF^@JDVFh@?BDb@@DFn@D~@@VBz@@`A?l@?\\AZA`@Cj@Ct@E|@Gz@A\\CXCTCXIn@E`@GZ?@G^Mt@Op@Qx@Of@q@zBaAjDY`AQl@g@jBuA|E}@`DA@a@zAQn@Qn@qB`Hk@pBg@bBc@~A{@vCCJK`@CHMd@I^CRCNG`@CLGf@Gf@AHC\\Cj@A`@Ad@A^?Z@\\?R?DBn@@r@Bd@?RFnBJtDDvALxEBt@HbD@x@FxBNrF@H@t@@p@@jA@zA@V?^?b@A`B?Z?l@A~@Ah@AbACt@Ad@?NCv@GhBALCf@Cx@KfB?FEl@CZMhBSfCItAQ|BAJQjCG|@APQ`CI`ACVQdCSnCGfAGt@MhBGt@K`BOrBGr@?DW|CEp@U~CWhDWpDUdDIhAGt@MlBU|CI`AEf@[tEALEf@Gt@Er@]tEEt@OjBWpD}@lMGt@C^ATCZGz@IfAEv@Cf@E|@Cl@GnACl@Cz@MdGCt@?FCr@An@A`@IlCGdDGrCAJC~ACt@?LGrC?@Ct@ElBKpDC|AEjACtACt@A\\EfBA\\EpBCn@?LKvDAd@IhECdACt@ErAKfFMzFI`ECj@?HOjGIdDCt@IhEIrDAVCrAElB?@MfEEzBCt@Cv@Ar@GdDGdCItDShKG~BCt@MnGCt@q@z[[rNKnECt@g@bUa@tQIlDElBKvEIbDAt@[hNKxEIxDWpLIbDG`CCx@Ad@AVCp@Ep@Cf@Eb@I~@?BEd@Kt@OhAGf@Kh@Kn@Mj@GZIZMj@W~@[dAWv@Qb@O`@Q`@Wh@Uh@Ub@]n@S\\W^U\\]d@EDOR]^SRYZYXWRSPQNUNaB`AMHwAz@aAl@_@TaAl@_@TMHYP_@Va@ZWT{@x@QPYXOPABQRGHEHSXEFS\\Yb@?@Yd@EHKREHINMXEJO\\Qb@Uh@CHCHK\\CBK^ENGPOr@On@Mr@GXCJGf@?@Kp@ADIl@Kt@KbAEf@Gh@C\\A\\AFC^Ad@Cd@Al@?DAn@?PAb@?R?b@?t@@x@@r@Br@@b@@R?BBT@R?FD^Fl@NtAn@~FHt@Hn@Z~Bp@bGD^R~AZhCBLHr@Hr@^rCTnB|@xHHr@Hr@RdB@BHr@r@bGn@fFb@zDFh@R|Al@`FPxAD\\Dd@BZ@ZBl@?d@?^?X?R?TATA^CTAVCVEZIn@Kn@Qp@IXMb@GNMZQ\\Yh@KRMPCBORMPKLYXQPEDOJSNSJSJSHUHI@YH_@F_@Bm@BM?a@@sABE?sADu@DU@UB]FODG@YHYJi@TA@[NC@{BpAe@Va@PYJSHWFSFUDSBa@DeAHu@FUBUDQDUFSHSHSH]P{Ax@YP[NOFMD[J[J[FYFSBwBTg@HMBOBMDQFKD[LSJSLOJMLOLUT_@b@OPeBxBc@f@CDW\\CBOTS\\[j@OXO^Un@Qf@Wp@aA|CWv@cAfDgAdDsBvGcBhFSl@e@xASl@g@zAe@zASl@K\\GNsAdEOj@KZEPCJGZI\\Kd@G\\Oz@Ih@Mp@CTm@tDMr@Mt@Y`BAFKh@[bBGb@ENYbBMr@Mp@Ox@W|AYdBA@e@tCO|@Mv@E^?BG^ATC`@CVA`@AX?R?V@x@@`@@R@NBRDh@Fh@DXF\\BNBLDPDNDLBHNf@HVTn@jAvC~A`EVt@LZ@FLb@Jb@H^FXFd@Hl@Dd@B\\Bb@@f@?b@?T?^A\\Af@CZ?FCb@AHEd@EVE^I^Kh@YxA{@zDqAvFEPOp@A@Qx@[tAo@`D[rAUjAKh@Ib@Mt@ObAIj@E\\Gf@E\\Kv@?@K`A[zCQbB]dDGr@It@CZy@lIIz@Y~CIr@Ef@m@pF{@zI_@xDUrCEd@Ej@IzAAB[`GKlBG`AIfAIx@CTG`@APMz@W|AGb@a@zBMv@Y~A[bBMr@W|Ai@|CeA|FKp@ENUrA[dBMp@i@tCI\\oClPSfAeAjGc@hCMp@i@zCq@fEMr@Kn@?@Kt@Ip@ADE\\APCVGt@CVEx@AJCh@IjBKjBMjCEjACt@M`DCv@?H[xHM`DAPCb@Ch@Ep@Cf@C\\ALKhAGt@Ip@ARUfB?FM~@OhAi@bDs@jEKp@Kr@YdBYdBmApHAJGf@Gt@Gf@G`AE`@ARG|AEjA?l@?b@?tAHpBBb@B`@@RFt@Dp@`@~CLp@H`@DNVnAFNPl@Rl@f@zAPl@Rl@`BdFx@hCRl@Rl@d@zARl@x@fCRl@hApDz@dCLh@Lb@BJNl@Pp@BLHb@Jf@@JNdAB`@Fr@?@HxA@PDt@HjBDt@HjBBd@@NFjBJbDH`DBt@FlB@T@^DdCBrA@t@@X?Z?ZAjA?DCt@An@ADCt@ALM`BIdAG^Ir@ABOhAWlA]vAi@lBO^Ul@Uj@Uh@Uh@Uj@m@rAa@`AGNoBtEi@|A]bAe@zA_@rAYlAS~@Oz@Mv@W|BGn@S|BC\\KjBClAE`ACbBCr@KxEGfEC`BAlC?DAt@A|@C|AA|@A^ATCt@ADGhAMbBIr@G`@CJO|@Kf@a@zA[z@Wt@Wj@CHS^CFOTOVU\\UVy@|@e@d@WTSN_@Vk@Xe@TEBa@P{MxF{Q~HeCdAgChAiCjA_Ah@o@d@k@b@s@r@QT]b@i@v@_@p@Ub@Yt@Wp@Ux@Qp@Ol@CNOt@OjAKz@Iz@G|@C|@CdA?bA@zAHfAH`B\\fELhAHr@PvA`@pB?BRl@Tx@N`@h@vAJVHRl@rAb@hAl@~AVv@Rx@Nx@FZF`@J|@Fz@@@Dt@?D@b@@f@?r@?d@Aj@Cd@E`AIn@Gn@Il@ERMp@U~@Wv@Wt@[v@Sj@Qf@m@|ASj@k@bBWz@U~@Sv@Q|@O|@MdAAJK|@Gj@AVC\\Gt@E|@ChA?XAp@?DAbC?tA?tC?bA?lB?xE?P?pC?t@@pB?`C?lAB|ABbABl@Bh@HhA@FJhANjALx@n@rCt@fD`@nBHd@Hj@@FP|A?HFt@@NFjABdA?l@?H?l@A|@GtDI|EClBAb@AfAAv@EbDGxEShNAt@SjNClBAt@EbDCjAMfJWvQEfCMjKCbAOhMWjOAvAATQrLAt@?@E`DK`IEfDKpGAt@CtCExBAv@KdGOvJKlF?TAtAAt@Ad@?|@?v@BtBFjB@LPjEDdA@d@Dt@Bt@@FLvCLjCJtCFzAJrBJjBDj@Fl@RlBNlAVfBb@~Bb@rB|@bEd@|B?@X`BPnAVpBJz@HfAPbC\\dFLjBZnE~@lNLdBDt@`@rGZnEHjAj@`IB\\XtERbDFr@n@tJF~AFrA@f@Bh@@z@@bA?|@Az@EpAATGzAANOzAKv@OfASlAm@pCMn@a@fBWjAm@rCETOp@[|A}@hEOp@ETIZ_AbEWhAi@tBQn@y@`CeAhCu@zAiArBcAzA_AhAA@Y\\oAxA]Zg@`@kAz@}@d@_Ad@y@\\q@X_EvA{KbEoA^g@HQDk@DI@a@@i@Bq@@{AGgBGK?}AGkAIuAM{A[oA_@_Ae@{@i@{@o@_@W}@o@aBmAUQIEa@Wa@GKAg@WOGc@MME}@W[Gc@Ka@Kc@K_AUi@Ma@KWGiBc@yA[s@I]C]Aw@DI@]BE@a@FYF_@LMD]Pe@V]XSNKHc@d@m@v@CDwAfC{@dBWf@Sb@ADiDzGWf@KRq@lAi@r@ORKLm@n@o@l@[T_@X?@}C`C_@X]XKHsAbA_@XMHoA|@_@\\YT}@t@g@h@WXQRc@n@[f@ILaBzCuAdCwAjCi@bAs@nAqCbFgAnB_@p@g@z@sAbCs@rAQZiAtBGHU`@[b@Y^k@p@o@j@a@XUNq@^s@Zu@Xs@Pk@FC?g@@y@Am@GeAO{AQgBUaBKYAS?w@@]Be@Bs@Lk@NGB_@JA@i@T[Nm@\\c@XOHWR]Za@`@k@r@k@t@ABw@tAYj@Yr@Wn@Wt@St@WhAUdASpA]bCa@zCKr@a@zCy@`G_BjLABs@pFM`AIt@Ir@CNQvBMbCEn@GrCAzCBhCDzBFrCLdHPvILbGBxAPzJZ|OTrL@t@Bv@`@bUBt@DrCF|BLnGLhG^lS@v@JhEBdA@t@Bv@DjB@JBh@R`D?@Fp@LtABRb@rE@Hj@|FHp@Hr@Z|CHt@?BFn@Hr@RhBNlAVlCXfDJ|BDzBAhBEpBObDi@pECTi@|BQz@aAzCo@~AoA~B}AxBeEpF{B|C_BxBgBhCOXyAfC}@`Bo@nAIPiBbEwB~FwAlEgA|Dy@fDyCvPw@hE_B`JMp@[dBo@jD{@fFMp@g@xCMp@Kh@[lBMp@i@vCKr@i@vCKp@i@xCMn@Kr@u@hEMr@CRWnA[bBm@`DWxAMp@q@tDaAbD}@~BKXINy@xASV_ArAo@r@]\\}AnAUPIDeBx@a@ReCjAy@`@eBxAQNKJy@`Aa@f@U\\Yd@e@t@y@jBiA|Cm@xBKj@SbAaAvFqApHg@pCeA~FMt@e@pCg@xC_AxFABKr@Kr@Kr@Ir@Ir@CRKtAGt@AVSvEGtAIjBC^MfB[nBc@lBg@zAGRu@tAgAxA{@|@{CnBOJq@^eCpA_@T[NcAx@UPIFeA`AiB`CwAhC]|@Uj@EJ{@tCk@hCc@tCEh@It@C\\ATS`D?FCdB?j@?`A?rALhCTxCX~B\\`BH\\P~@f@fBnA`DR^Vh@Zl@lAbB`CbDFH\\`@vBlCjBxB\\^tAbBDDTXx@`Ax@`AZ^TXDFnA`BBDXd@r@jAR\\DFTh@Tj@Vh@BFb@pARl@DLZpANn@FR^bC@FR`BD`@@PP`D@t@Bv@BbB?FIpCMhCYvCi@~C[vAk@hCu@xCCNK^Op@o@nC?@Qn@_@`BQn@?@aA~DELK`@c@nBq@zDELQvAKn@Gx@Ir@QhB?@KjBIhCCdCAr@?@?|C@XF~C?BDt@J|BJxAF~@jAnQ`@hGb@pIFlE@`AC~CEfCGpAI|AIbA?BCXCV?DY~B_@hCId@CPUpAMf@Sx@Qn@wBtIeAxDyBlIeA~DeA~DMf@W`A]nAoAzEGXK`@CLQr@Mn@EXEVMt@QlAETMz@[tCIr@Ir@CLaBhOiBhP{AfNcAdJi@zEIn@?B}@jIWtBOjAGb@CLWzAAHMr@Kl@ABYnAc@hB}A`FOb@m@jBs@xBSl@wBzGaAzCGRSn@sKh]gIpWQl@Ob@CHy@dCABQl@Y~@K\\c@|AWtACNKp@G^OfAIl@?DGt@CVC\\IvAGhAALIrCE|AIpD?@Ct@At@ElBMxEAb@?PIhEMhCKpBKfBWxCiBlRGt@Gr@}@rJAHu@fHQvA[jBO|@Op@Md@GT_@lA_@~@_@~@q@vAyCrGsBpEcCnF]r@c@|@cBrD}C|Gw@~Ag@bA_AxBeA`CYp@c@hAi@dBGPQn@CHYjAYrAUjACN]tBe@nDMdAG`@e@jD[jDCVEt@GlAAbBAzABnB?LJrCBf@Z|GDt@P`DPnDX~FHpBJrABPHz@PxATxARdAPz@XxANp@Hd@n@~ChAxFLp@fB|I@Dh@nC\\bBdB|INp@vAjHLn@hAxFJh@BFLp@\\bBj@tCLp@vBnKLp@\\`B\\bBx@fENp@j@tCLp@z@fELp@l@tCb@fCp@jEBP^|C@HRhBDh@Dt@@TJjBJhB@`@Bt@BtA@lA?t@@jDCdBKdE?RCt@K`FAn@GbDCx@KjFGdDE~BCdAEp@ATIz@ObBGf@Gb@Mv@SjAQ|@ELMf@Sr@Yv@[`AIN[v@y@`BS\\S^[f@_@d@w@~@mDvDyDlEk@n@iH`IkCzC]`@uA~Au@z@kD|Dy@|@c@h@MPMP}@pAc@x@]t@Qb@Wl@Yx@Sn@e@~A]tAKn@Y~AW`CMlBMtC[jIGzACt@KlDQfEYtGMfBUrCOpAMz@_@|B[|Am@~C{A~EqArECHQn@eA|Dk@zBoApEs@nCCFYbAW~@gA~DiAfEg@bB]jAgBvF}@pCu@bCSl@_BdFy@jCcAbDuAjE_J|XK^yAvEeAbDkAtD{@bD]zAQfAUnBCb@Iv@GtAAPCp@ADChAAjB@l@@x@FbBBp@B`@LtAFf@Ff@@JVdBLr@Lp@h@vCH`@BNfAxFz@fEtAjHx@hETfApAtGhAvFTlAp@jD`A~EjDhQn@bDvAjHr@rDhA|Fp@dDJl@h@dD\\dCVhCTdDHjC@^D|BApB?FAn@A~@ExAEz@?BEt@Cl@MhBQlBU`CE`@c@rEc@rEMvAkAlME`@u@|Hu@|HAHGj@UvB[tBc@jCg@xBCFOn@GT_@pAa@rA{@hCSl@cEhMo@lBi@zAc@bAg@`As@nAcA~Ak@~@kAhBiBrCoAdBc@f@EFWT_@^s@j@GDeAt@{AbA}@j@ABuChBkA`AEDoArAu@bAw@rAm@pACJ{@tBO^EJyAtDQd@wCpHoA~CgAjCkAlCm@nAoBdEu@xA_AlBaC|EqB`EaElIS`@CDkA`Ck@hAWh@[n@cApBA@yBnEq@tAi@fAu@zAeAvBq@tAYl@]t@i@nA[v@Qf@GPOd@Ob@Md@Oh@ELQn@Kd@_@dBOx@EVGZKj@ObAIp@In@Gp@W~CIr@W~CEf@e@rE?@Kz@Mz@I^G\\On@Sr@Oj@IPO^[p@Yp@ILQ\\a@r@[d@c@j@k@p@{@~@gAbAcBvAiC~B]Z]ZaB|AwDjD_@Z]\\]ZQNMJ}@x@]Ze@b@s@r@[ZA@]`@W\\CBc@r@OTOVYf@Wh@GNs@hBIXSn@Ql@IZGRS|@UvAETE\\Ij@?FIt@Ir@?@Er@Gt@I|A?LCt@Ab@EhACt@Ct@AFCl@KxBEf@MvACPKr@QpA]dBe@`Bo@fBCJcAxBo@bAQV_AlAA@}@x@]ZA@}@p@_@X}@r@_@X_Ar@qDrCYTy@l@gA~@a@\\[Z]\\URe@l@u@bAA@Wb@o@fAYn@Wh@CFg@pAQh@Sl@EN_@rAw@nCu@nCW`A]jAQn@oApEkB|GaBfGABOh@c@~A{@bDeAzDu@nCOn@s@hCAB]bAKT[p@m@jAyAlC_@r@Yd@q@nAYd@c@v@iC|EuDbHaAfBWf@cB|CYf@wFjKYd@Wf@iAtBu@nAqCjFWd@Yf@Yd@e@z@g@r@[b@SXGF{@z@]\\UTID_@VgAr@wBv@uBd@a@FmCL_@@C?gADsDH}BFQ@c@@kDLG?c@BsCPwCP{@Dk@Bk@@QAgA?c@Cc@AEA}@MiAQa@KGA[I[Ii@Qw@WKGa@OSIo@]WMiAs@_Ao@?A_@Y][CCu@q@CC]_@[[AAeAqAOQ[a@[a@Y]]e@uAiBYa@[a@{@kAU[[a@oBiCSWGIaAoASUg@q@OQSS_@a@g@a@IISQIGc@USK_@QWKKESIOCECWGq@KYCWAKAI?UAC?Q?Q?G@Y@W@w@JgAZ_@Na@PA@c@R[TGD[Vc@`@SRGFUT?@WZCBQVSXOVEFQ^OVGNUj@Yl@?B_@|@eE~KuAnDi@vAaBhEiAvCUj@i@vAYp@Qd@i@vA}@dCQb@qAjDwAxDYn@Yr@u@~Ag@v@s@fAg@j@q@p@IFk@f@m@b@cAt@{@n@}C~BaBvA_@ZaA~@u@x@Y`@MPe@x@KRc@bA_@bAGPOh@YbAUdACLIj@Mx@KbAI`AAXCj@AHAn@Ax@?z@?~DFpU@tOBfJ@lF@dN?vEAfAAt@?|@GjCIzB?@Ct@Ch@IlBMrBm@`Kc@zHAFw@rM[fFaA~OWbEMdCG~AAx@?H?j@?b@@`BDzADjAHdAJfAFj@J|@^zBd@hBZjAHZLd@d@lAh@fAp@rANVb@n@z@hAn@r@dA|@`@Z`@Xj@VdAh@f@NVJHBbARhAPb@DdAJXB|AFfCP^Bt@DrBPtBNrAHlCP`CPD?z@FxAJp@DH@b@BF@`BJtBLrAHx@Dd@Dx@Nd@FXBl@Pd@N~@XnA`@fDnAlDnA`@Nv@Zl@VjAh@VPNHXR\\Vp@j@b@`@LLdAvAh@r@R\\RZ\\n@P^f@fAVp@@FRj@@BNh@Ld@Px@\\bB?BNp@Jn@p@tDDVh@vCZ`BLr@Lp@Jl@`@pBVzAJt@Fb@@NLbAJvA@@Bv@Bz@Bn@?L@Z?J?V@b@?l@AlAAp@Cr@GbAIpAIt@EZKv@CRKf@Mn@u@`DOj@Qn@Y`A[lAQl@c@~AI\\c@~AENs@nC_@xAq@hCi@lB[fAeA~DSp@yAtF_BxFGVQn@e@dBa@xAGRGZa@|AUx@Mf@Ot@Or@Id@M~@SnAGb@SdBKfAQpB?JO`CAR?JAd@ElAAbBC|CCjD?NAr@Ar@@l@?l@@b@?TFnADlADd@BZPpBb@rC`A~Dl@rBv@nBh@pAnB`FJVRj@`AbC^`Ar@lBBF\\|@r@hBd@jAZv@Th@Tl@`@bA\\|@Tj@N`@Pf@X|@Pj@@@Jh@Rv@@DRhAJp@Hx@Ht@Bx@@N?@Db@?N@R?f@?pAAt@Ap@CbAALCZC`@Il@ATG`@QlAERMl@Qv@K^Qj@[x@CJQ\\]t@mA~BqAbCCHkAtBCFYn@Wl@KZOb@[dAS|@GTMh@AF]dBKt@OtAMjAGfAEh@A`@?DEjAAfB@`CDtD?h@NjILtH?Z@v@BhA@bA@bA@jA?b@Ah@?\\AP?BARC\\CZEr@Gp@Ih@UvAg@`Ce@bCMd@EV}@fEmBjJmCfMaF`V_AlEyAhHOp@On@uDrQOp@qEjTm@tCsAtGq@dDELMp@YrAYxASlAMp@GZStAKt@SxAQlAQzAk@fEg@jDOpAS~AYnBIt@Kr@M~@OlAALOjAMrACf@En@Ad@Ab@Af@?j@AT?T?P@T?d@Bh@@Z@h@Dj@PbCVxCNjB?FPzBT~CVlDHdANrBXvDT~CXvD?@VlDLzALbBVnDVbDP`CLbCHhBB|@@x@@j@?J@f@?@@b@?j@CzBCdAAb@IxBGv@ATCZKhAGp@Gh@OjAg@nDy@vFWfBWdBYfBYpBM`AIj@Ih@YhBQrAW`BW`BYjBO|@U`BIl@YjBWdB[rBObAQhAEZ]zBWfB_@jCYjBa@nCAFKt@_@dCCHObAYnBEXG`@CPO~@Gf@Gb@CNKv@Q~AABGt@MpACVQhBGt@E^GjAQ`DIzAGdAMjBAP[`FGnAKjBEt@AJCh@IpA]pFEt@Ev@Er@GdACd@IxAGfAGt@?FWfFYxFGhAEl@?FCl@Et@?FQ`COjCEn@YfDQfB[~CMrACTYtCMbBMhBUbDCn@Cx@CzAEjDCnD?fIDnAH~AFnAP|BN`B?DTbDHdALjBRdCFt@Df@@LFt@Fr@NjBDd@BPB^@NLhALjBFr@B`@Fz@Ft@Bh@D`ADt@JtBBxCBrAD|D@v@BpBDlBB|ABbB@hA?D@p@?`@BrA?l@@t@?@@t@@x@@p@?p@@D?t@@f@?LBv@?T@^?v@@t@?TBpA?D@t@@v@DjB@v@@t@@t@FbD@v@@t@FbD@v@FpEFfI@v@?@?jB?d@ANGbDEt@M`CWdD[hCUfBCNGd@M|@qBfOu@xF_AbHU|AYpBSvAIl@Il@Il@G`@Gb@Il@CTYzBCVMfAI~@MzAItAKjBKfBSlDe@pHuAxUSnDEl@Ev@Cd@?TAf@?rA?nABx@Bv@JhBNhBBVBZBPHf@NbAZzA\\zAVz@Vv@DNTl@@DVn@Zp@z@~AdBdDxBfEXf@fC~EjEzIlAbCnDhHnCtFrAnC`CzElA|BtApCLTHRhHfOBPDJHR`A|Bf@jAl@|ARd@Xn@bAtBf@hAl@bAzA`C|@nAp@x@zA|ArBdBdAr@t@d@lAp@dAd@d@N~@\\bAZlBl@NDnDdApEtApBn@hA\\fD`A`Cv@ND`@LbBh@xBn@vBp@b@L`@N|@XpAh@`Ab@|@b@RHr@^^RnAr@ZRRL^Tb@X|AhA\\Vx@n@DB?@^Xr@n@f@d@\\Z|ArAhB`Bl@h@\\ZbCxBpCbCnA~@NH`@V\\V`@TTLJD`@RDB|@Z|@\\fAZB@dAT@?tATv@HL@x@FH@tBJrCHjKZbADhFNb@BbIT`@Bb@@b@@nCHxBHvWx@jBFrDL`@@b@BdCHH?fAD`ENnCHvENb@@fADb@@`@Bb@@b@@@?hBH|CJx@Hb@BZBj@F`AJ|@JfBVf@JdB\\d@JfATrA^`AZ`@LVHHBb@PfA`@\\N^P@?`Ab@b@R^RnAl@j@ZZPLHrBtA~AjAh@`@|@l@LJbAz@VT`@^x@t@\\\\^\\dAfAlArAv@~@\\`@NPf@p@Z`@V\\^f@n@|@`@j@h@x@dBlCNThAlBlAtBfAhBh@`A~@`BxAbCT\\r@tA|@`Bd@|@FLNXLXVj@\\x@j@vAr@fB`ApCbAdDtA`FrAbFj@vBhBtGpApE~@hD@BvAdFzAnFZ|@^dAXr@rArC^v@DHR\\N\\Zh@h@t@f@n@^h@f@n@b@f@d@f@|@|@h@d@^^`@\\l@f@j@\\^T`@Th@T`@Rz@`@t@Xt@ZhATfARJ@b@Dr@JfAJhAF~@@|ABvBBbC?zFCxKCbEA|L?x@@jA@r@CVA`@IpM?b@?rD?jB?b@?bI?fJ?vNArD?bD?n@?~FFb@@hAHrARp@Nj@Nl@Tp@Tp@Xp@\\p@^`An@|BxAdCbBdKzG^VdO|JxDpCt@p@JJRRHJRT`@h@Zf@DDd@|@Zl@Tj@JZVr@DNVz@Tx@n@pCNp@XlANp@Nn@Pn@Nn@Np@Pn@Nl@?@Np@Nn@^`BNp@Nn@BLJb@ThAt@tDF^xBxLLp@dA|Fh@tCv@hElBrKt@~Dj@`DvCbPLp@h@tCv@hE`B`Jv@hELp@TlAvEhW^rBnBzKn@`DXvAVdATz@vExNvBnGRl@xCxIn@hBRl@pArDd@vA@@f@zARj@Tl@Rj@Rl@Tn@b@nAbAvC`@fADHj@tAHPJV^v@NXXd@?@r@fAZb@BF|@lAzC~DrAdBtAdB?@v@`AhAxA|ArBd@l@j@z@@@\\n@b@~@d@fAHTRj@Rp@f@fBZvAZxBb@jDB\\Ht@ZnDn@xHL~AHbArAbP`@zEXnDFt@N`B`AnLPjBFt@z@dKx@tJVpCn@xHHfAFt@h@hGJjAl@fHFt@BVr@lIHhAFz@Bt@Bl@@`A@t@@zA?@Av@?bD?jB?hAAjH?fI?jAAdI?fEA\\?bH?D?t@?lB?zE?f@?fK?dBB`A?BBbAFvAFrAJvAPnBTlBXtBLt@Jf@DVR`AZrARt@DNLb@Vx@^fATl@Tj@Vl@\\t@Vj@zAtC~BhEbExHvAlCfCvEp@lAXj@n@jAp@lAVf@b@x@NVhBhDNXdCtEzAnCzBdEVf@hAtBlEfIvExIXf@bEzHvFlKXf@|FvKR`@n@lAbAhBzBdEfEzHrBvDx@|AdB`DT`@Vf@jAvBpBtDdCrEv@tA|AtC`BxCfE~HtD~GlDpGtBzD@@Td@n@fAt@tAt@|A~@dBn@jAl@`An@|@j@r@\\b@^^z@v@hAbAnA|@x@l@j@\\B@j@Xh@Tj@Rr@Tz@Vz@PPB`@FB@^D`@DZDb@@lADjA?J?jD?~C@rF@`F@tB?d@?b@?r@?nB@dAAj@@f@@d@D\\Bl@J\\FZHZHXHZLZLl@Vj@XNHzAp@tAn@dBv@zFhCbObH~JrErD|AtJbEdBr@`@PrEjB|DrBfBdArBlA`Al@`Al@`CxAbCxA^T`Al@^T`Al@`Al@^R`@T`B`AbAl@`Aj@bB`AbDlB`Aj@^TFBbDnBBBZPdCtAr@`@nAp@`DhB~GdEv@h@~HzEl@\\p@Zj@T\\NZJ^JTHVFVF\\Hj@J`@Fb@F`@Df@Dd@@`@@p@?~@AfAEhDK`BIv@CjCELAjEE`@?n@?fA@b@@D?dBDfA@dA@@?tBB`CD@?b@@tADx@@b@@hABlDH`ELtBDdABn@BD?~@F`ALz@Lf@L^Jv@Tr@V\\LXL~@d@^Rf@Z^VVPlDtCbEvDlE|DdIrHpAhA\\\\xNxM|FlFb@^pFbF@@zBrB\\Z|DpDnE`ExClClGzF~BvBvCnCzAtA\\\\dB~AjFvEbAdAz@x@l@l@TRTT\\Zb@Zx@n@n@b@^TXPXNXNz@b@RJtCpA~FlC`@R`@PdAr@tAfAd@b@VT~AdBnC`DBD|BfCbBjBNP\\^rB`C`ClCzDhE~AxA\\Z|DrDrBlB`A|@dDvCp@j@XR`@Xb@Zf@X^Rt@Zz@\\`A^bA^LD`@LNFf@RJFTHJFJDTL`@V^T^VFFd@\\n@f@x@t@BBbBzA|@z@\\\\l@j@DBb@d@n@p@BDX\\^b@p@~@`@j@\\h@l@bAl@fA\\l@P\\DHr@rAr@hAd@l@`@f@X\\TTTVTPRP@@NLRLZTXPr@`@|@\\n@Tv@P@?d@Jl@Hf@D^BV@|AEH?p@GZAVAhDYRAb@CrDUfAGb@CdAGjBKzA?l@Bl@Hx@NFBlA\\VHfBp@r@V`@PHBzAj@JDVHlAd@|Ah@HBdBl@dBn@dE~AXJlBv@l@V@@dAd@ZRj@^v@f@z@p@bA`AnAnAbAbArBtBrDvDdCfCjBjBr@t@nAnAfIrIzA~AvIvIZZ~@`A~A~ARRdBdBhAnA@@bApAnAbB|A~BhAtBjA`CHLdAfCdAzC@BfAtD^pADHb@|Al@rB^fBd@zBX|ALx@`@hCTlBFl@Hj@LvAPxBLrBNlDTbFXpGTrF@V@\\H~AJhBRzBPtALfANbAN~@P`ATbAV`ATv@f@nBh@zAZv@HVPb@bArBv@tAZh@p@lA@?Xd@PVb@n@Xb@JLl@r@HJPRXXBB^XPJnAx@"
                     },
                     "start_location" : {
                        "lat" : 46.9316981,
                        "lng" : -84.51848079999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "64.4 km",
                        "value" : 64445
                     },
                     "duration" : {
                        "text" : "40 mins",
                        "value" : 2413
                     },
                     "end_location" : {
                        "lat" : 48.40555149999999,
                        "lng" : -89.28787200000001
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eTrans-Canada Hwy W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-11 W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-17 W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "u{ihHvy{{Ox@f@t@b@JF|F|C`@RlJbF`Af@`@TbCpANHPJnC~AtEbCf@X`B~@nAp@t@`@`Af@`@RDBz@b@`@RbAd@xAl@pA`@D@rDhAxBb@D?fAP|B\\p@N^FlBb@`@JhB`@F@ZHdGtAt@NdCh@D?j@LzA\\fB`@b@HTFrAXfB`@fB`@jBb@`@J@@`@J|A^|EdAb@HHBv@T`FjA`B^`Dn@hBb@nAX`@J\\HjAXb@J^JfAVJB|A\\b@H`@JVFJB`@JLBlDv@VFb@H`@JJBxA^d@Nr@TrAp@DBXR^VHDp@f@d@b@^^v@t@jG~FfBdBn@l@tCpCBBnGjGXVxBtB\\\\nBjBrAnA~@p@n@`@b@VHDVHx@ZHBlA\\ZH`@L^JdBl@dBp@dAj@DBzAjAbA`AbAlAvAlBx@jAVZpAjBl@|@d@z@p@nAl@jATf@pAlCj@lA`AxB^x@x@dBjBdELXbBrDtBlEpBlEFLtAvCHPtBpEJRfCrFj@lAnApCrArCVj@jB`ETb@Zr@tBtEdE~IdAzBTh@Vf@jCxFl@rAVf@Rd@@BfAzBVf@Zn@x@~A`@~@l@nA\\x@p@tA\\r@jAtCz@vBZdAf@jBBJNn@HXXlAVfAz@bDt@fCpArDHT|AdEnAdDn@bBLZDNp@jBf@tAr@tBb@nADJTp@XhATdAVhAd@fCHb@x@hEt@tDbAfFj@rCl@tCd@zBhArF^jBJp@Fh@NlAFdABTFfAFrB@tAAtACbBCt@CfAKzAQrBS~BY|CIlA?LIjAKbCIxBAr@ElDEtC?f@?LAh@?`DFlCDhAFt@Bd@BNLfAJx@PpALl@Lp@P|@h@fCf@~BhBxIDP|AfHBLz@rD\\xAx@lDf@bC^lBV|A\\~BT~B^jEb@tE@XRrBNxBNzBBVJhCHbCFhC?@LfG@z@DbCFzFJfEFjBHnANhBXlCVjBX~AXzABJ^`BZlADN`@pAl@bBDL~@dClAbDrAlD\\|@t@nBdAjCN`@xAvDx@pBXp@Rd@hA|Bj@dAbAxAl@r@fArAnDrDjAlAj@j@`LhLrKxKnBxBPTf@j@xAfBnBbC`AlAxAjB`ApAtBhCdB|Bl@r@t@bAxAfBr@`AjBbC\\j@tAzBdCjE`@v@`AbBdAhBfAnBzBzDpBlD@BhB|C|BbEbB|C`@r@jAxBlAtBjArBnApBxApBDDZ^DFrArA\\^jAlAJJxBvBxAvAl@l@rBtBzDzD|DzDfAhAPPlBrBBJFJtBjBvAxAhAfA`A`AXVnCbClA`ABBXV|@v@DBvAhA^ZtAdAjC~Bt@p@\\Z@BvBnB\\ZnBhBdAbA|AzAnBnBjDvDf@d@fBfBlBlBf@d@`C~BxAvA\\\\x@x@f@d@zC|CXXzBxBdBbBrDpDtJnJ|@`Ax@x@j@j@l@l@v@v@jBlBtAlAbA~@hA`AlAnAr@r@d@d@\\\\XXvDvDtCtCtCtC~B~BTTvAzA@?x@|@\\\\HFnArA\\^z@x@n@l@bCbCrCpCfBbBvBxBz@z@\\\\JL`F`FvA~A\\^PRl@v@\\b@V\\JPd@p@b@p@p@lAHN`@v@Vh@Vf@P^FLR`@`@|@Vh@Pb@Pb@\\z@Z|@f@tARp@L\\ZhAXdABF~@pDn@~Bj@xBPn@z@dDLh@`CrId@hB^nAFT~A|Fh@hBfA~DfDxLRv@r@dCTt@dA|Dl@vBfBtGBHp@`Cn@|BDLfAvDt@lCj@nBn@~BDN\\rA`@vAPr@J\\z@xCNf@vAhFZfAj@tB^pAXfAX|@`AlDNl@d@`Bh@nBHXJ^^tARx@R|@d@rBPz@Jh@Jp@Nz@DTNdAZzBJz@NzANdBL`B@JDt@JxAFbA?@JzBBd@Dr@HxBF~ABt@Dt@H|BB`@Bt@Dt@Bt@J`C@^HjBHjBDt@?LBf@Bt@Bb@JxBDv@FtALlCFpAHnBH|AFdADx@Fz@HhAF|@Fj@Fn@H|@Fl@Fp@P|AJz@Ht@Hh@RzAN|@N|@\\vBP|@DVLp@DPXvAh@jCTfAt@nDP~@t@pDNv@F\\b@xBZ~Ah@pCNt@r@tDj@xC|@vEf@jCp@hD~@vEXxAZ|Aj@rCfAtFDRHZvAjH\\~APv@XvAXxAP~@h@lCjAdGZ|Ab@xBtAhHFZNp@j@rCJh@Nx@t@tDz@lEXxA|@pExCxNt@lDRdATbA`CxLr@hDTlALj@XxARbAf@hCPz@h@pCt@rDp@hDb@vBd@|Bz@jELl@FRFZNp@DPPt@Ld@XdALh@FNPn@J`@DJb@zA`@nAVt@@BRl@Rj@FNp@jBvA|DzBdGVv@j@|Ax@tBf@vAr@pB|AbE@FxBbGp@lBnAhD`BnERj@bAlCv@zBt@rBl@fB@DRj@J\\l@pBj@pB^zAd@nBn@tCfAjF~B|KFZtDtQzAfH~@rEbAzE\\bBrBxJl@xClA~FbDtO@FXpARdANz@P|@P|@DNLj@?DPt@b@lBl@pCNp@FXz@hEr@dDLl@@BLn@~@nElBbJ`AzEh@hCR~@Np@Lp@Jd@fCxLJh@hAnF@DNp@`@lB|DjRb@zBvAxGNt@hAlFxAlHNt@jAtFz@dEjAtFNn@jAtFLp@DPn@tCFZNp@Ld@\\tA^vA\\rATv@Tt@J\\Vx@b@nAdAdDj@fBrBrGFRnA~Dx@|Bd@fBl@vBVdA`@hBXtA^hBb@~Br@xEdApI`AvHl@|EnAzJzAtLHp@j@nEHr@j@nE~ApM^zCJr@jFrb@l@vEHr@j@lEn@fF~@tHn@nFHr@r@bGjBdNfBtNnAtJFf@~@tHvBvPn@tDb@rB?Bn@`Cv@fCnCrIv@bCPl@rBrG~Mxb@~AdFfFfPrNfd@jD|KdDfKX`AdBrFp@|Bb@zAp@rCb@hCn@|Ez@hI^fHFnEBp@BnC@bBPzJPxJLlGZdQDvE@jCBtA@pADz@H`DBnAHlGJxGZpLNbFBhADhBDnBBr@HjBL|CFxAD~@HzAHxAJ`CJvAJdBNvBL~ALdBJdBJ~ARjCL~ATvCb@~FPfCJjAPtBPrCJjAFhAJrBHvABrB@xBApBCbBKrCMfBUrB]vCM|@M|@a@~Cg@tDg@tDsAxJUbBMdAK~@]fCOjAQnAMfAQdBI|@SfBOxAq@rFwAxKa@hDUzBq@pFSvBMvAEj@M~AGxACrAAtDB`B@x@BnBFlCVjD@H\\jC^dCPhARbANr@Jj@Lf@Nn@Nf@Rr@^fAZz@h@tAN`@Xt@`A`Cj@xARf@z@vBp@~A|DjKRj@h@vAxAzD@@n@lB|@dCHTr@fB`@dARf@@Bj@tAj@tARf@@@x@pBv@jBBFz@pBpA`DhBnEJ\\n@fB@?Rj@Zv@r@jBPf@t@lBn@bBbClGBDPd@|@~BZp@bCpGJVTj@rAlDzC`IjAvC|@`CrBdFf@rAh@tA@DPf@z@dCBDNf@lApDfBlFn@tBzBxHbB|Fv@xB`ApCHTpAfElA`EjBlGRl@^nAf@dBjAvDRl@f@`Bj@rBx@jDh@rCZnB^jCRlBN~AF|@BZBXHdBFdBD|BDdE?`@?R@nG?T@^@`G?L@t@?bE?R@t@@xE?t@@pE?|@D`J@fH?`B@~@H|CBn@HpBTfDLxA@JLnAJ`A@B`@xCJr@^nBTpA`@bBt@lCvApEbAhC@B^x@hBzDXh@fAvB\\n@j@fAbCvElBvDVf@PZhEjIVf@Vf@j@fADFlBrDz@bBv@zANZ|@bBtAhCVf@pCnFfAxBTb@@BTb@hAzBdC~ErDbH@Bn@hAlCjFdC|EjAxBpCpFfArBvGnM@@vBdE@Bd@|@dCtEfGrL?@BDJNx@`B|AbD^|@v@vBlArD~@bDr@lCx@rCnAnElB|GfBdGdAxDjBxGnAjEfBlGn@`CNf@ZdA\\dAt@`Cd@xAJVz@fCL^^fAZv@dApCxAnDzAhDpApClBzDlBvD|@bBVf@rAnChCdFnB`E`ArBl@xA`DzHt@hB`BvDJ\\bBfFRb@n@fBLNTT\\|@xAzDdCzGlA`DnBvF`C~Gj@xAJTAPFPdAvCrDfJTf@jAtB^h@LPPXbB`CvAbBfBxBzAjBtA`BnA~ATZNPB@LDxHtJbBvBzBtCzCvDrFdHhGzHjExFrBfCVZrEzFrE|FbC|C|@dAh@l@v@r@j@f@b@\\XRb@X|@h@t@`@n@Xj@Tt@Vt@TtA\\vEp@z@JfHbAdANTDbF|@vF`Av@J~Fl@RBpE`A^BxIz@`@DdK|AtEr@`BVfIjAr@JzK|At@Lr@Jn@NZJF@^LTTTHhBp@lE|B"
                     },
                     "start_location" : {
                        "lat" : 48.716271,
                        "lng" : -88.6212393
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.1 km",
                        "value" : 2126
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 171
                     },
                     "end_location" : {
                        "lat" : 48.4064409,
                        "lng" : -89.25958609999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eHarbour Expy\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "uemfHd`~_PTNFm@h@aDXyBFg@Fq@ReCBa@@a@Bq@@}@?}@IsCEgBCy@M}EWaL_@kLIaDKqDKsCAg@KmDMcCU_FKaDAs@C{@MwE_@{OcAcb@KkDEqB"
                     },
                     "start_location" : {
                        "lat" : 48.40555149999999,
                        "lng" : -89.28787200000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.9 km",
                        "value" : 1919
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 157
                     },
                     "end_location" : {
                        "lat" : 48.3897103,
                        "lng" : -89.2582146
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBalmoral St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gkmfHlox_PFq@?CDk@Dg@H[FQLQHIPOb@[|@B|B?Z?jHIz@I`N?nB?tCC`DA|@?T?L?VAb@?\\At@?xMBjN@zIE|BA`AF"
                     },
                     "start_location" : {
                        "lat" : 48.4064409,
                        "lng" : -89.25958609999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 541
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 57
                     },
                     "end_location" : {
                        "lat" : 48.3891894,
                        "lng" : -89.2510997
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCameron St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ubjfHxfx_Pj@gBNi@l@aC?a@AwC?kB?iE@mAAeCAoC@_C?eD"
                     },
                     "start_location" : {
                        "lat" : 48.3897103,
                        "lng" : -89.2582146
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 926
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 101
                     },
                     "end_location" : {
                        "lat" : 48.3808628,
                        "lng" : -89.2511157
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eVickers St N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "m_jfHjzv_PxD@nCBt@?pIA~GB|FChAAnDCvCD"
                     },
                     "start_location" : {
                        "lat" : 48.3891894,
                        "lng" : -89.2510997
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 254
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 42
                     },
                     "end_location" : {
                        "lat" : 48.3808589,
                        "lng" : -89.24768189999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eArthur St E\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kkhfHnzv_P?}EA_F@cF?M"
                     },
                     "start_location" : {
                        "lat" : 48.3808628,
                        "lng" : -89.2511157
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "702 km",
                  "value" : 702243
               },
               "duration" : {
                  "text" : "7 hours 38 mins",
                  "value" : 27452
               },
               "end_address" : "Winnipeg, MB, Canada",
               "end_location" : {
                  "lat" : 49.8951374,
                  "lng" : -97.13836839999999
               },
               "start_address" : "Thunder Bay, ON, Canada",
               "start_location" : {
                  "lat" : 48.3808589,
                  "lng" : -89.24768189999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "3.8 km",
                        "value" : 3793
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 423
                     },
                     "end_location" : {
                        "lat" : 48.380889,
                        "lng" : -89.29901
                     },
                     "html_instructions" : "Head \u003cb\u003ewest\u003c/b\u003e on \u003cb\u003eArthur St E\u003c/b\u003e toward \u003cb\u003eSyndicate Ave S\u003c/b\u003e",
                     "polyline" : {
                        "points" : "kkhfH~dv_P?LAbF@~E?|EAtGA|G@fG@xB@zC?fCArGArB?^?bE?hA?bA?`E@|C@v@BrC?rA?|AAxC?bB?tBCfD?xG?vG?fN?dR@|FE~@ArB?DAlB?bB@fC?PHh@@lD?`B?pL?bB?f@?pAArD?`HAhI?bD?fF?lA@pQ?bE?hE@pL?xACVCVABAR"
                     },
                     "start_location" : {
                        "lat" : 48.3808589,
                        "lng" : -89.24768189999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "8.7 km",
                        "value" : 8672
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 484
                     },
                     "end_location" : {
                        "lat" : 48.3808302,
                        "lng" : -89.4158815
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e to continue on \u003cb\u003eArthur St W\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "qkhfHxe``PAfB?D?t@?vD?tD?X?nK?tCDbB@zDDTAzB?b@?v@?~A?xB?zEA~BC~AD~EGjB?V@vE?pEB~U?xE?hRAt[BtD?rD?`D?tHAlFDvF?xG?vEEv[AlH@rQ?vR?T?^?TA^At@Ez@AVWhCo@|DStAg@~CQvAObBALAp@Cv@@lB?^HjD\\dH?@Ft@Dp@JnBBn@@RRlDXdFLpBf@xHHxB?tC@d@?|X@dFCxEEf|@?nL?~CB|BFnBLpCDl@R`DJpBTlDF`AF~@`@`FFdABxA?xA?v@CfAEfAGbAIjAa@zD[|CSbCGz@OpCCjAClB?`CCvY@jXD~g@?bD@zP"
                     },
                     "start_location" : {
                        "lat" : 48.380889,
                        "lng" : -89.29901
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.0 km",
                        "value" : 2018
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 100
                     },
                     "end_location" : {
                        "lat" : 48.382133,
                        "lng" : -89.44233469999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eON-130 N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ekhfHf`w`PAhT?xE?t@?vX@pLDpNDpb@FrPB|B?hA@dBIvBKx@[lAIXKVCBeDtEk@r@"
                     },
                     "start_location" : {
                        "lat" : 48.3808302,
                        "lng" : -89.4158815
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "337 km",
                        "value" : 336664
                     },
                     "duration" : {
                        "text" : "3 hours 32 mins",
                        "value" : 12728
                     },
                     "end_location" : {
                        "lat" : 49.7862263,
                        "lng" : -92.83346539999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-11 W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-17 W\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Trans-Canada Hwy/\u003cwbr/\u003eON-17 W\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ishfHpe|`PXfAVbAPt@Lj@Jh@TjAPx@^vB?DH`@PpALfAP~AJlA@JHlADj@LbCLtD@jA@`A@lA?~B?~D@fN?t@?xL?zG?bD?bN?rM?xD?|S?rA?tB@jJ?fG?hE?dU?|T?jGAdO?L?nH?|BAjM@rCArB?lD?xIAbDAnDB|CBv@?HB`AFdABVB^@TDn@PfBHx@JrAT|BHbAH`ADh@?@Bp@Bn@@j@@l@?X?\\?V?LA\\Ab@AZAl@Ep@AJATCb@Gf@Ef@KbAMlAMfAG|@A@IbAGlAIpAEdAChACv@?JAtA?~@?r@AtB?l@?`DAxE?nCApD?tC?`A?xE?nG?jG?h@?dF@xK?bC?lGAlG?r@ArL?lH?vE?t@?tD?fJ@pM?bI@hS?|O?|J@r@?vEBtV@nG@`E@~FB~G@jE?nG@dH@vB@nG@~D?lABlG?T@bE?vF?T?t@C|FAzDA|ACzFClD?xD?jDAzV?`_@?vBA`I?nBA~E?dF?^?tH?|GArC?r@?j@Ab@Cb@Ad@Cl@Eh@Eb@?DEb@Mx@Kp@CHKj@ADQv@Mf@?@Ob@Ob@GNO^a@|@Q^W`@Yb@e@j@UXMNOLQPe@`@e@ZKFSLWNy@^SHyCfAoQvGGBa@NoAd@_Cx@}Bz@kA`@_Cx@}Bz@qE~AwAf@iC~@UHy@VoC`AoAb@y@ZwAf@a@NMFIDWJKFm@Zc@VEBYPEBe@\\m@b@WRCB_@\\MJo@l@SRqAlAq@n@i@f@QPi@d@s@l@eAjAe@d@cAdAOPQRMPU^KNKPGLABMXQ^Sf@Qf@K^ADMf@Op@Kh@Mp@Kp@ObBGz@Eh@G|AEpAEzAExAAZKvCA\\Cd@UhHUfHKhDIdCM|DO`FGjBGrAA\\El@AHCZEf@Eb@G`@E^Gf@Kj@Mp@Mv@Mh@GXENGVIXIVOb@M^Qd@KZOXSf@kAbCeAxB[l@Sf@[t@O\\Sf@K\\M\\Of@K`@K^GVGTGXEVEVKj@Id@Il@Gj@Gh@Gr@Et@GdAC^C~@KfCAf@KpCGhAGv@EZAPERE^?@GZ[nBMh@Sv@KZGPIRQf@Wf@CB_@r@KRKNS\\Y^UXQRYZSRA@kAx@SLULSJUJC@OFQFSFq@RqIbCiBh@k@Na@Na@LODwA`@g@NUFk@LQD[FUD[D_@Fe@DWB_@B[BM?i@BuB?e@AYAWASAUCe@G_AMsCo@UGUI[Kc@QUKQGOGMG]OUMQK_@SwEkCaAi@kLsG_@SYOWMGEGCSKEAMGSIQGQE?AOEOEA?OEKCQEQCMCQCUCSCC?KAOAG?KAQAU?M?Q@M?[@U@S@K@E@WBWDWDSDQDIBWFwCz@o@Ra@LQFg@NoAb@i@PcCt@iA^aBj@uGtB_AZiA^[J]HYHQDSBQDMBUBC@a@Dk@B[@]?c@?{A@oBAwG?uB?Q?oCAqA?eC?{ME_OE{DBgC@{D@kB?Q?}B?sD?aF?oC?oB?wA?{A?iB@u@?u@?_H?gC?mFCy@BsDFuDAyC?sDAkB?c@AiA?eAAcIGc@?s@Aw@?c@?kB?c@?iBAI?Y@O?{A@uA?sDDeDDsB@kBBK?mE@aFBkG?A?kB?oCAmDAgAAyAA}BCwEC[Ak@?]@U?S@C?Y@_@@UBWBY@c@B_@Ba@Fc@DE@WDc@Fu@Lq@N_@HwA\\WHGBuDhAiCx@oBl@kDhAgBj@gA^UFI@OD_@JUDa@J}@JI@QBWB]BQ@]@]@a@@g@@_@?YAUAcAE}ASOAuAWa@Ke@Ka@KQGICi@Qa@O]MUK{@]kAe@OGuCgAy@Y_Bw@sGmCkEiBk@YSIg@S_@MICSGCAQGWGSCICMASCQCUCUCI?GAY?A?c@AC?[?S@W?O@c@BUDUBUFOBUDQFC@WHSFSJSHUJUJC@MHSJSNSLQNEBOLQLQNQNSRONOPA@STEFKLa@f@c@n@OX[l@OXMVINMXMVO^MZITO`@Yv@Wr@a@hA]t@Sd@c@|@q@nAYf@U\\W^U\\W^WZWZ{@fAC@{@jAi@r@a@f@CD}DjF_AjAoClDiAxAwAhBeDfEY\\qBhCu@bAaApAk@t@qAdB_CzCi@n@STOPURMNMJYVIFA?]X[RYR[P_@Pc@RoCnAaEjB{CpAuCtAuAn@s@\\iBx@UJiAh@cAb@y@\\s@Vm@N_@HYF_@F_@FYB_@BQ@S@_@?m@@a@Ac@Ai@E]Ei@Gi@Kg@Ke@Mg@Qm@Sm@Y_Ac@s@g@KIUQUSQMOMSSQQQQsB{B}JuKyA_BeAkAOQeBiBOO[[YW[YWSQOA?QOSMSMg@WKGICIECAIEICMGKCKEOEQEEAOCQEWEYESAOCO?MAM?KAU?O?Q?M@K?mAJI@K@MBGBK@QDSDA?SFYHqBf@mBf@G@a@JoFrAE@iB`@sAVs@Po@Jq@NuAXmB`@[H]Hy@TSHUJMDMF[PYNYPSNMJCBOLMLQLMLMLMLQTWZKLOREHEFORKPIPINKRILGNOXKVQ`@KXIRIT?@ITIVKZGRCNGPGXGZAFGTGXGb@Ib@E\\Gb@Gf@Ir@Ef@OzAGp@OzAKlAO`BQdBKbAIbAGf@Gp@Gj@Gl@EZE^EVE`@If@Kr@UpAYrAc@dB[nAEJUt@k@dBo@bBGJqAdDoC|GmAxCKViEnKo@~A[t@oB~EKXQh@]dAK`@Sr@Mh@Q|@Kn@Mt@Kx@Ip@KnAIlACj@Ad@?LClAAxA@b@?h@BhADbAHvALnAHt@L~@@FFf@Nt@Nr@Px@X`AZdAl@fBhA`D`ApCrAtDp@pBXbA^tARbAJh@?BJx@R`BJvADt@Bj@BhBBbDFxGBzC@zAAhAEfA?@GhAKtAMdAQhAOt@Qv@W|@Yz@Uj@a@|@S^KP]f@[b@eApAiBzBwBjCiCzCqA~A_AlA_@j@]h@a@v@GLa@~@_@|@[z@Y~@Sv@Oj@Mn@Ml@Mx@Mz@Kx@M~AGhAMlCIlBItBMzCc@|JMzCG|@Eb@Gj@Gp@ObAOz@UfAWdAe@dBiBbGABa@vA]rAEPI\\Ot@WrAQbAQrAUlBCXKnAGt@CXEj@KtCATMnEIrBQ|FMnCGl@I`AObAKr@O~@[xAU~@[bAg@vAYt@u@zAADWf@e@~@uApCu@dB_@|@M\\a@jA[dASt@IV[tA[rA?@SfAYbBEXMx@YfCGp@Ep@MdBG`ACbAAPAxACt@?L?~A?L@|ABt@BdAN|DHdC@n@@pAA~BA|@EzA?DCp@GrAIjAQrBGt@OnAM|@Mx@ADUlAQ`AENYpAa@|AQn@ADwAdFiAxDgAzDu@jCUt@Qt@_@pAELeBjGg@bBo@xBsAzEIX_@nAW`AaAhDk@pBw@jC_@pAq@|BUn@IRc@dAw@bBmCrFGLwApCCBSb@o@pAWf@q@vAg@fA]~@[x@{@vC_@xAWbAYzAUnAADKr@Gd@UjBOjAUbCWrBSfBMlAE\\Il@O~@Kl@SfAKj@Ot@GTOn@Qt@_@xAQn@a@~ACJKb@Qn@Qn@On@YdA{@fDQn@wBlIQn@i@tBaCfJi@rBmAxEOn@On@Qt@aAzDOn@kAzEi@rBOp@e@lBmA`FOn@Mf@YdA[pAOj@Sr@g@~By@jEs@dE}AbNe@jHOlDQhJClCA`AArAEtCMrIA`@ItD?VErACt@ALCf@Cd@IjAIt@Ir@Kr@Kp@Kl@Ml@ADOp@Oj@Qj@AFOd@CDQh@Sf@MXINQ`@Ud@S\\_@p@]j@A@o@~@gAbBaAzAMP{@xAu@pAEJmAbCmAlCq@zAk@xA]~@{@bCuB`HADsApEgApDGRIZ[`AIZCJKb@CJMl@UlAALKl@?BKr@Ir@Ef@Ix@El@E~@A`@Cx@CjAA^CzB?DClBCvAGrCCv@ARAXAZAXKhBKxAIdACZEf@U`CQ|A[|BM|@G^Kl@c@fC_@xBOv@Mt@ObAG^OnAOzAEh@Ej@Gt@En@?FQvCYtEGp@Gx@Gl@Gd@Gb@Id@Kl@Kf@Mh@Mh@Od@M`@K\\O^Qd@OZEJQZCFWf@m@fAQ\\Yn@KVKVc@hAQh@Mb@K\\Ol@GXKb@Kh@Id@If@Kj@Ir@Gp@Eb@E^C\\AZEx@Cp@Af@?JAX?\\Ab@?`@?xA?tE@rG@fD@xB?~A?z@?v@?dAAp@Aj@Az@Cr@Ch@Cn@Ab@C\\Eh@Ej@Iz@Gj@CTE^ARCNG`@Il@Ih@Kl@Ox@Mr@Ml@YpAWnAQv@Kh@IZSdAI^Kl@Kj@Gb@Kp@Gf@Gd@E^Gp@Gj@Ej@Cb@C^Ch@InAMrBMrCSfEMhCKjBSfEQhDADUtEIpAMbCIvAGhAWtECl@SvDQ|CUxE?@c@dIQ`DM|BMfCMbCQvC[hGAFMfCIlAANIpAI|@?DI|@KfAKfAKbAKv@Kx@OfAOjAO`AIj@I`@CNMp@G^Mt@CNOn@[|AADYnAg@~Bq@~CKb@]zAk@jCc@nBs@bDADc@jBa@nBWjAe@vBc@pBa@hBMf@Oh@Oh@Ut@EHSj@Yp@MVMVMVA@U`@Wb@MRORA@OTKJCDOPQRQPQPQPQLOL{@n@IDIFSJQHUJSJSFSHUFKDA?ODQBE@]Fm@FOBgAFI?U@g@@s@@]@M?M@cCBM?gABi@BcBDsHPc@@W?K@eB@wBFiBDoEJE?c@B_CFO@oCFc@BO?uCHwBFiBDmBF_DHS?oFNo@BoCH_ABsBFmABiBHyFPA?eBFiBDc@BkBDgAB{JXO?c@@k@@c@@_@?_@?G?qACg@Ec@Cg@E_@Ec@EEA]E[Gm@Kw@MiB]iB[c@Iq@MsB]_AQu@Ma@IqDm@c@IsB]oB]aBY[GmASgAQA?gBY{JcByCi@_Ca@gASeDi@aCc@wHqAeCc@YGw@MyB_@a@Ic@I}AYm@Km@Kc@Ga@EWEE?MA_@CWAQ?QAQ?]?Y?k@?aCAg@?cBA}AAkFCw@?c@AcA?wAAsFAo@?qBAaDAeGCqFAoBAo@?sDCoA?s@?c@Ac@?c@?c@AkB?c@Ak@?uCAuBAm@AmCAA?c@?kB?M?U?kB?wB?gD@c@?gC?i@?oC?e@?eGEW?kBCgA?gBCC?gHI}@Ac@?kBCA?a@AgAAoACo@IuCKgCC}A?eB?{BA_EEsB@yAAQ?G?cCAC?c@?W?yF?}C?c@?{@?kD?e@@_BBw@AiBCu@CwBCwAB_AAwCDsBDkBDsDAwCAkB?Q?}BA{@?K?gC@}C?]?wB?qA?gD?C?_@?kBAs@?w@?uB?}@?c@?q@?eAAs@Aw@Ek@AsBO}@Iu@Ia@IQCu@Ma@Gg@Mq@O}@WkA]c@Ka@MiA]aAYWIqBm@i@QuBo@kBk@_@MiDcACAa@MuAc@uBo@gA]aAWc@Mu@Qa@Ii@Io@Ig@EGA}AM{C]IAgBQ[Ec@E}AQMAkDa@qBSaAMsC[iBSc@Ec@GcAKe@Gc@GeBQcAKw@Ic@G_@EkAO_BQeD_@UEWC}@KUCsAOWCWC_BQUCgAMgD_@}AQUCc@EMCc@E}AQEAE?c@GkBSc@EiBSc@Gc@Ec@GiBSc@EyFo@kBSuEi@a@EoC[c@Ec@G_I{@kLqAiKkAiBSkFm@aBQmLsAiAOaAQm@Ky@Wq@Qu@UgA[kC{@aEqAi@Qe@KiAWc@KYEGAYEi@Eg@EIA{@ESAOAeDIMAcACwDMgAEq@AUA_HUKAWAiBIc@Ac@CeAEA?}@Ee@Es@E_AIA?a@Ec@EaBSaGq@iBS}Gw@mC]kBSc@GmC[mC[IAYCeJgAc@EeAMmC]C?yH}@CAeBSc@GuC]mC[kBSiBSgAMc@EeAMgAMc@Ec@GMA{AQc@EmBUqBMiAGW?Q?]@{@Dq@JUD_@Fe@NUFi@RC@s@ZOHa@R_@RmFpCgCnAA@a@RaAh@a@Ry@b@kBbAi@XWNeCpA_@RcAh@yBjAk@XuC|AsH`E}C`BkIlEmCvAa@RiFnCcB|@_@TkHvDgDfBcCpAa@RcB|@a@RiHxDcB|@a@RcB|@a@RgEzBaDbBkE|BeCnAcB|@iFnCeDdBeCpAeDdBeCpAeDfBeAh@_Af@gFnCcBz@sFvC{A|@[R]Tw@j@YVYXe@b@_@`@m@r@g@l@GJIJ]b@OTY`@[d@oAlBg@v@}A~BYb@eCtDYd@uCjEINwAzBo@fAmA`Ce@`Ao@tASb@Wj@i@tAA@Sh@EJ_@dAUt@Sl@CLa@pAm@rBITo@rBY|@CDYx@eAlCIR[r@k@lAcAvBeAzBg@hAu@xAsC|FaAnBEHi@z@cAzA{@dAiAjAaA~@[Xc@^i@^qBnAyDxBwAv@eCrAa@TaB|@cB~@cB|@sDpBwC`BMFaAj@qBnAe@`@WTe@b@ML]\\IHSV[^MPMN[`@UX}@rAiBlC[b@aIpLoC~DeJzMiDnF[b@GLgA~AYb@o@`AoA`BY\\[Zo@p@m@h@KJs@j@[Tc@Zk@^}@f@yBlAMHgE|Ba@RaAh@KF{DvBaB|@i@Z{Ax@aB|@eCrAiHzDa@Ti@Xy@d@o@^g@ZQLOJQN_Av@aAz@cAbA_AfAQRqA`BwJpMkK|MwFhHuBnC[`@{DbFaAlA{KtNwJbM[^sDxEaJnL[`@mFbHeHdJmUbZqE`GuJdMkHnJ_BtBaFpGoGjIqE~Fq@~@s@~@y@jAy@jA}@rAcA~Ay@pAgAfB?@sA`CeB~CgBfDa@v@oJbRcApB{EfJ}O|ZkDvG_CpEQ^mBvDaAtBmAzC?@Sl@}@dCSn@M\\KX}ChJITgC`GGLc@x@[l@kDhGsBxCiDrEwBhCQRIL}CrEyB|DGNyAnC}LfVcGfLoMzVWf@cE`IWf@wBfEA?mAfCcClFm@nAi@tAO`@Uv@e@pAw@fCo@`CeArEmAlFs@`DSz@k@hC}AdHOn@wF~VuBhJo@rCEPq@xCeC~KADmAnFsBbJ{C|MKh@}A`Hc@lB_@~AsBdJsAbGe@vBOp@UbAeCvK{BbKgFfU}B`KmBvI_AdEOn@Op@}AbHmFbV_CfK}Jxc@_AfE_L|f@{Kvf@Mn@Ol@qEnSKb@Op@_@`BoArFOp@e@tBYlAOp@}AdHOp@Md@qB`Jm@lCoB|I_@`Bk@dC{CfNENeCvKI`@sBhJ}BdKqBzIERiClLaAvE_@rBOz@O|@WzA]zBw@jFSpAi@lDId@wAtJSpAi@nDOhA_@vC]hDCVY|CMhAUhCYrC_AfKk@~FQhBIt@c@rEm@rGo@bHy@lIu@zHq@zGc@pEEb@It@e@hEwAfNc@nEGj@QpBSvBOzAIt@gAfLWjCiAxLkB|RGr@c@rE}@rJmAlMm@vGu@xHoA|MQhB?DGn@iDn^k@hGoAzMs@xHWjCWnC[fDc@rEMvA_@dEUvBY~CAFa@jEIt@U`Co@dHWnCSxBc@rEMlA_@|Di@~FQnBe@zE_@~DSvBGr@c@xEQdC[fF_@tGw@jMATEt@e@rHWlEWrE]rFYnEe@|HOjCk@tJwAdV_AzOYrEWnEyDro@_AzOmCnd@e@zHIpAWrEMjBIpAEd@CTEl@QnB?@mAhMUvBYzCeAxKeBjQaAjKqArMi@bGGr@StCKvBWbHC`@g@zMOfFQtFK`CYjGQzCYhDY~Co@jGCZuAjNu@lHW~CCZGlAKlBKhBWbEOnCCf@WlEU`E[hFSlDG|@El@StDe@nHGnAQfCWtEOzBU`EEz@MjBK~AG`AKlBa@tESdB[lCa@|Ca@bCI`@i@tCS~@YtA]bBQt@mBpI_@`BOn@i@zBwBnJe@pBi@`CEP_C`Ks@dDEPc@lBg@xBo@dC]rAo@bCOj@A@{CxK_FhQQl@uDxMcB`Gs@hCq@dCu@lCg@fBqDnMEPaFpQABiFfRc@~A{@|CiGtTiDxLyEzPo@~BwCfKSv@gBlGe@dBu@lCc@|AQn@kBzGgEhOQn@cApDqCdKiBrGeDnLOf@Qn@_@tAe@fBOp@Op@CLg@fCc@rBsDzRKh@m@~C[bBeApFQz@}CfPOp@AJKd@_A|E]fBYxAYrAOp@On@ADMj@ELUz@Uv@O`@Sl@Wr@MZKXMXO^KRQ^Sb@k@dAcAjBADmC`F}ApCeCtE]l@q@nAq@lA{@`B{DhHWf@{BdEq@nAy@|Ay@xA{ArCe@|@u@rA_@t@GLc@|@aAzBq@~Ay@nByBbFcA`CUj@m@rAc@dA_@x@Uj@uCvGkApCeC|FyBdFOZyC~Gq@|AIRy@jBUj@w@jBKRmCnGqBvEg@hAeAfCq@bBs@hBUn@}AbEw@tBQd@}@fCSh@Uj@Sj@Ul@eBzEg@rAgAxCiA~CoBpFaBnEeAtCK\\o@bBWn@[`AsCtHsApDa@dAi@xAITITQd@aAjCy@xBiA~C_@dAw@rBo@hBaBpEmDlJk@zAEHi@pAo@tA]t@m@nAS^m@fAsA|BUb@ILo@`Am@|@y@hAu@dAeAxAoAhBy@tAa@r@c@t@Yh@[j@]p@Wh@[r@Uf@Yn@O\\Q`@c@fAO`@c@nAQb@Wv@Up@Yz@gAhDmAvDoAxDkAvDM\\q@tBc@nAENe@pAg@jAUl@Sd@Wl@g@hAc@|@_@v@m@hAaAfBkApBAD{AjCy@tAm@dAeCfEOV{AlCkCpE{B~DuA`CwAdCqCzEWb@S\\W`@q@~@ILWZc@f@WZe@d@i@h@MJURGF]VUPg@\\c@XIDe@Xg@Xm@XA@_@NUJqBx@cCdAaCbAg@R}B~@q@X[NiAd@}@`@WJsD~ASHaAb@g@RcBt@yCpAu@\\aA`@sAh@a@N[JSFMDYFWHg@JWD_@FM@I@QBSBYBQBM@W@S?W@W@YAU?SAI?c@A{@Ae@C]Am@A_@AG?c@AQ@O?Q@S@WBWBO@OBQDOBSFWHIDIBSHSHOH[RUNa@Xg@d@WVMLIHQRQVSXMRMTOVUh@Sj@Wl@Wv@Sr@K`@I^Kb@Id@Mt@Gb@G`@CRGt@GdACr@Av@A`@?nA?hA?bD?v@?tH?`O@bD?v@?lN?xE?hU?~H@zE?lB?t@?dD?zE?`A?`Z?v@?zA?\\?h@?J?nE?J?lB?tL?zE?zE?bD?vF?zE@dL?zEAbD?lB?t@?v@?fE?pA?rG?t@?|D?nA?|@?v@?H?vA?`A?t@?v@?v@?hH?rA?xD@rH?v@?~I?^?t@?pB?`D?~@?pE?t@?dP?bD?v@?t@?lB?hF?vB?jC?N?d@@hD?~C?\\?tB?hB?tB?fA?hE?fF?Z?vA?n@?fC?`B?~A@v@?xE?rG?zI?rG@pG?zE@xQ?rG?pG?t@?tE@vH?dC?n@@hD?h@?|D?jE?JA~D?Z@bD?dC@tA?p@?B?|B?|AAlBAn@?FEpBAn@Cl@AHKfBOjBIv@K`AWfCAHMhAKbAOdBABEt@AXM|BErAAhAAbB?zA@~@@b@?^DnAH~A?HHvAJdBZjFLpBDt@XvEDt@R`DDt@x@dNDt@LjBDt@lBr[?@Dt@Dx@Dp@H|ANxBB^NtCLtBTlD?JFt@JjBHnAHbAFbADn@NfCJdBDh@Dt@RbDFlAFbAVnDHx@Fn@B^BRFh@JfANpAXvBHh@XpBBNNz@PjALr@FZhB`KHh@@@Jn@BNRdABNLp@FZNz@N|@ZhBLv@XvBJjAJtAHrAJbC@b@DxA@zDCrCAZCt@IxBSrCGt@Ej@]lDaA`KUjCABEp@W|CEt@GdAC`@IlBCbAEhAAZA\\?VAh@AJApAArAA`@?RAf@?v@?bAArA?lBAfCAPApCA~@?dBCpE?FAvCA`D?dAAdA?`A?x@AtAAzBApC?RAfBCzG?\\?v@?TAdEAfCAhCAhACjAG|AGbAItAIx@In@Ij@Q`AYxA_@xAIZ[dAYr@a@`AQ`@Ud@sAlCsErJCBm@pAw@|Aq@xAaDpGq@lAq@nAo@bAYd@gAhBsAxBYd@_@l@}@zAw@pAy@vAo@hAYh@]j@i@hAq@vAy@fBm@`B[t@i@zAo@lBa@pAe@`Bo@`CMb@o@`Cq@fC]nAQt@q@hCAFOf@s@nCQn@wApFu@jC?BOj@y@xCcA~DYfA[dAe@lB_@rAg@xAk@`Bg@lAi@fAkAxBg@|@k@z@W^UV_@`@QRIJe@f@SP_@^KHs@l@q@f@e@Zs@^w@`@m@XgAb@s@X{@XwAd@{@VYJk@PA?g@NoBn@o@T}@Xw@X{@V{@XiBl@i@PiCx@GB[J}Af@IBa@LA@kBl@eCx@_Bh@}Af@wAd@oA`@w@Xs@TyBr@_Bh@oC~@{E`BaCz@_Bt@SHMFu@^k@Z}A~@GDwA|@mBxAu@n@u@n@g@f@iAfA}BfC_AhAmGlIaHfJ[b@aBvBkBhCoFbJCBoBfD{A`CU^CBsBdC_@d@qAzAGFWTyAvAiCbCMLoAhA]\\{@x@_@\\sFfFg@f@aBvAcB~A{AjAmDxBIF_HfDoBt@IBiDz@_Cf@_D`@q@JsHd@qF\\_F\\sDVc@Bc@Bc@DiBJgAH{F^cFt@_Dv@w@R}C~@aCjAa@RoAl@kDrBiFfE[Z]ZiBhBc@f@eEnFEFuEdHcA~AmFnJaAhBcDtFSZ_G`KsIbOmEvH{F|JiApBAB{A|C}AjDWl@Uj@i@pAk@|A_AfCmAdE_@pAk@tB_@pA_@tAs@nCwAtFm@nCYtAi@jBi@jBwC`LCFaCzJYhAWfAWdAo@tDYdBaA`GYlBqCbRUfBADKl@Kr@Mp@kAlHqAtJeBbLsBhNi@hDKr@wDvVCLyAnJo@dE_AnGcAzHmAvHoCvQwDtVe@vCgBlLKr@iAtHKr@oBnMKr@ADa@tCYdB{@bGYhBoApIERKr@aBxKKv@WfBqArIiIpi@}@`GEZ]|B_BnKM`AMr@c@xCc@zCSvAu@|EMp@Kr@q@nEa@lCAJk@rDQlAObAm@|DCRq@nEm@pDgArFcApEaA~Ds@nCQr@e@nB[pAk@|Bk@zBk@hCeB~GADiBpH[pAQn@eAfEo@jCQn@On@c@fBcBzGc@fBaAzDAFqBbIe@hBo@bC_A|DELQl@Sl@aAxCSb@s@rAq@hA{@hAo@r@s@r@cAv@eBdAC@]LeA^GBmATgAPkABM?yAAQAc@Co@C_BGc@AU?aBGSAg@AqCIc@Ae@AeHW}@C}BIyAGc@Cs@Ca@AuCIiBGq@AsCKc@A_ACk@Cc@As@CqAEsBEuAEc@?CAoA@w@Fi@JI@c@Le@JeA^mAl@yAdAaBzAGHgArA}@xAoArBYf@_@j@iBzCQZYd@}@xAcA~AuCxE{BxDgAbBi@~@kAjB_BjCi@|@}@jBGL]r@y@xBQh@a@lAaAvDYjAOp@aA`E[pAe@pBq@pCQp@Qx@Mf@q@pCOp@IZERu@pCQj@Sr@]`AIRiB`EmAxBqFzI[h@aCzDMRaE|GCDeBnCYd@cAbBy@rAkDbFkBxByA~A{@|@k@h@o@j@cA|@_A`A}@bAQL_@X{BbBA@_Ar@}BdB_BjAaAl@[Pe@\\_@XiAx@UJa@Rq@\\iAf@mBv@gA`@sG~Ba@NA?}FzByBx@i@TcBl@oDdBeCtAuAt@aAh@a@TA@{CdBg@Xa@TwBlAKF_@RcB`Aa@REB{@f@_@RYNi@ZaAj@}BpAgAn@_@Ra@TkAr@UL_Aj@gAv@iA|@OJ]X_@Z{@r@}DbD}BjB_At@aF`EaCnBiB`B}A~A]^QRq@v@s@|@W\\g@n@_@h@q@`AeA`B_AzAu@rA_@v@]p@cArBeBxDmH`PoAlCiBxDk@vAABWn@Sj@Y~@]jA[rAYjAYvAKn@EV[rBQtAIr@MvAMjB?@Er@?@Ct@Ch@?h@Ah@A~@ApAArAEdP?bBCfO?zDBvCBrA@b@B|@F`BHrAJ~AZfF^nFjAxPx@tLFt@RpCnB`WFr@t@xJFt@n@`In@nInAxOHdAjAfOh@jHhAzNFt@b@`G`CnZjAnORhCJzAJ|ABj@@`@@|@?b@?b@?j@AhAAr@Cl@Cl@Ch@Ev@Iz@In@Gf@QnASdAOv@Qr@M`@Qj@ENUr@a@dAu@lBoArCSh@]t@a@|@k@hAKN[f@i@t@o@v@e@f@[XURq@f@a@X_@TWLOFc@PcA^s@Pc@Hm@Je@DA@i@DuAJo@DeCP}ALUB[Bk@HI@SDE@WH]JODMDWLa@R]R]V]VYVYXe@h@[b@S\\GFMTIPILQ\\O\\Sd@Ul@GRMb@Mf@K`@Mj@Kn@Kp@UzAi@xEcA~IIr@ADoA~Kg@rEIr@}AfNeA~I?DIr@_A`IaEd^aBvN}BpSIt@]tCs@nGeDjYUrBkAjKSdBIr@CPk@dFANkAdKOtA_@|CEZq@dGaBtNgApJGp@AB}AjNQvAi@xE}B~RiDrZKt@eBnOIr@WxBmBxPeAbJUnBSjBK|@UxBGl@Gl@Ed@SxCInAMxAOzBEj@Et@WnDW|DEl@WfDOxBi@`Ik@tIYfEcAbOi@pHo@vJy@nLGt@iAnPE`@Et@G~@E|@I|BExBAlA?~@BvAFpBLfBNzA@JJh@@HT~AZxAh@nBf@zARj@h@jArAhCzBhEzDfHDHbB|C|BdEp@nAnA|B`B|CXf@BF~BjEx@xAf@fAZp@LZVp@JXL\\d@vAJ`@@FZjAH^\\bBHf@RrAHt@BPLlAJvALbCB\\BfA@hA@`BA`ACfAAd@ARAh@GbACd@AJCZQdBQ|AWfBMj@UlA_@xAMh@Qb@w@pBm@bBmBnF{@`CeDxIOd@kHvRoFxNMZSl@_FxMGNwB|FqAnD_@z@g@pAiC~Gw@tBKXGRo@hBaAtCi@pBY`AI\\m@~Ba@lBa@hBCJk@|Cw@dFAHIr@g@hEgAfK}@nHUhBo@pFsA~Ku@lHa@|DKt@YhBGZI\\c@pB[pAWfAmB|H}@xDuEzROp@eDhNgGfWOp@eDfNsBtIQp@uDxOa@~Am@jCeApE]|AMp@ADKj@o@~Dc@fEWbEGvBEhC?J?lDFlCL`DDz@b@bEb@rDRfBd@nDFd@f@rDhAvIj@nEn@jFDZn@nE?HvEl^ZhCHr@dAhIt@tFPpA`@fDRdB`AxIPfCZ|ED~@Ft@n@dLd@jI?DP`D`@tH@NPbDHjBBl@HzABhA@`@@lA@~@AzBA~@WlHCv@a@rLiAr[KpBWnFSpFm@hOEnASpGAZQ|DIrB]tIQ~EUhEMhBi@dE?Bu@jEMr@w@jD{@jDOl@q@rC?BMl@]hBMl@i@jCi@jDIl@Ir@A@e@`Eq@pIM~B]zEUpD[lFCd@WhEC\\k@vJEx@_@dI?D[hGEv@MhCc@|Ik@~KQrDMzC_@xHM|Ce@rICf@IlBIjBEv@IdBK~BYnGI`BEt@MpCc@jIMvBIzAANGt@IfAIdA_@lDABa@tD_@dCKp@Kr@Mr@[nBq@zDu@tEs@jEMr@AFW|A_@zBu@xEKp@s@lEoAnHQr@Mn@A@YfAk@nBUr@g@pA]z@wA|CIPMVGLsB`DwAdBEFmBjBo@l@uAz@EB_@VKHqOnI{BpAiBhAa@Tk@\\gBvAo@j@sA`BcAtA}@pAk@`A}@fBo@|Au@zBSh@yApF{@~CmChKiAnEyCrL_@vAi@~BWhASr@g@lBkAvEw@|CQr@sAjFc@bBa@`BOn@Qn@Or@yArFMh@K^ENs@dCUr@_AtCOd@Sj@a@hA]z@A?m@vAUf@Uh@m@rAq@pAMVqA`CCBYd@Yd@c@t@gMnQ]f@y@hAUZYb@IJiA~AORs@`AkBjCORu@fAgDzEU`@[j@s@nAeApBWh@o@pAWf@MVkAtCMZy@vBMZ_@hAmDbKq@zBoAtDUl@{@fCg@zAcDhJeBbFeA|C_@dAyLl^oB~FM^mAjECLKZADMn@Qx@CPOr@Ox@Kp@If@UvBE`@Ed@CVI|@IfBAXy@vQq@lOMzCEt@a@zJ]dIEx@GnAGrASzECh@MnDm@vNI~AOlDGbBSdEWnGUpFOpDQ~DOlDAVGrAMtCKnBMvCQdCGl@Gr@K|@QpAgArGcC~KOn@}AhHcFtUyIba@_CjK_AfE}AfH]`BOp@_@bB_@bBiEdSCHgEzROn@}@fEcArEiAhFmAvF}AhHiAjFs@`DOp@On@]bBk@dCCLq@nCMl@Sj@k@`BGLYl@INKRi@bAGNMRABYd@EFGFMPKHQRyA|A]^]\\]\\qAjAe@j@[^?@OPKNONQVSXMTMTEJILUd@Ud@Wn@Yt@Wv@Up@Mb@ELGVENMp@CFId@SnAEZWdBQlBGr@y@vIMrAmApMsAhNk@hGMlAsAjNk@pGaBjQGt@CL_BzPGt@cAtKsClZOxASxBm@jGY~CIt@yCj[_AvK}@jJYfCOpAm@fE]tBa@rBeCdMqAvGiCzMyAxHKd@oBhKcDtPm@bDcGf[qBfKk@tC]bBOp@e@`CuBhL?@Op@i@nCAFq@|CMd@[lAm@nBA@y@vBCH}@rBGJmAxB}BdDc@l@qAhBqAhBKJgBjC{AvCaAhCo@|Be@~BSxAKr@Gb@IdAKjAGvAEt@E`Aq@nQ[fIUzF[~JCv@SpFQ`DIvAC\\SnBYdCe@jDg@vDy@zFMz@UfBoBlNEZKr@kBnNaA`HIr@Kr@{@bGKr@WjB_CzPgBtMo@nEm@pEKr@y@dGo@xDSdAMl@Mp@Sx@s@dCw@~BYp@{@rB_AdCi@xAgAtC}GvP{AtD_C|FkAvCa@`AaDfHk@vAo@|Ag@nAyArDg@tAEJe@zAm@dCIVEVa@rBYtAMr@kAxFMp@m@lDs@dDS|@Qp@ADs@xBcCtGSj@Q`@cEzK_AdCsCvHcExKmGrPwAtDgBzEqBlFoCbHiAxCoEhL_AjCY~@Y~@Md@k@bCc@hCq@dF_@vDIt@KfA_ApJkAxKWhBQjAOr@g@tBw@xCi@hBy@vBSb@[t@aAnBUb@CBgAxBWf@{BjEgAxBWf@{EjJe@~@oJ`RyBhEWf@oMbWqCrFWf@kDzGaEbIWh@cEbIq@pAiBpDiC`FWf@w@zAsEfJaB~CYd@c@t@_AtAgAtAiAlA_BvA}CvBe@\\_@Xo@f@mA~@_@XC@WRk@j@a@b@MPSTIJKNo@bA}@`BiBhDiAxBCDS`@Wf@q@nAWf@wDjHeCxE[l@wAjCc@z@iAvBoCnFA@gAtBk@dAiBlDWb@Yd@CF[n@iBvDYv@Yx@K^[`AKZQn@CHKd@Mh@[`BOv@sA|IQdAWfBMr@WjBKn@Kr@Kr@c@zCADW`BKr@c@zCMr@CRSrAKr@Kr@Kr@YfBo@nEKr@Kr@Kr@}AhKIj@e@xCWfBMr@Kr@AFIj@{@vG}@dEkAfEo@hBg@hAa@dAyBdEeN|UeAdBsFpJkGrKkIxN{AhCa@x@Wh@Wf@IPcAhDK^CNk@|CUzAAXG|@]hG_@~KStJGzAC~@AREnAOxDUpG]bLgA~UUnFcAtTOlCQlBUhBS~@Ot@[tAs@lBMT]t@a@r@e@n@m@|@wAhAk@^k@^gBv@wI`DQFOF}KbEgBl@]L_C~@{@`@u@\\ULgAn@aBhAq@j@sBbBw@n@yBdBqDrCo@h@{@t@A@e@d@iApASVEDq@|@{@pA{@tACBINIRUd@q@~Ao@zA]fA[bA_@lAKb@Mh@CHCLQ~@g@jCMp@EXEVYzBCb@EZKnAANMzACZMlAGt@y@xJGt@?Bc@nF[xDAJQzBEb@Ej@Er@KzACn@GjAIbBW~GQzEA\\a@xKw@jREt@}Ap_@c@zJa@`KIlBCt@OpDIvCClB?@BnCD`BB^Dl@?FFt@JnAPtAX`BDVj@|BjBpGxBbHt@dCf@|AjAzD`@pAjAvD|@vCNr@Jd@b@tBTzAP~AN|AH`AF`BBjA?H?tDC|AG`BGjAK|AY|BIb@QrAe@tBAFOh@U`Ay@`Ck@tAo@nAe@x@a@r@GHa@l@e@n@Y\\UTc@`@gCnB_@X}GjF_ErCcHjF}M~Jo`@rZ_@X}AnA}EtD_BlAq@~@y@pAs@lACDc@x@Wj@]v@Qj@Y|@EJSl@AD[fAg@pBQn@a@|AQr@s@pCq@lCu@rCc@zBSxAS`BAFKbBAVKjCAbA?zBB`B@h@FvCJpEPrFXnN@v@FbDBv@FdDBt@@`ABj@@v@FlC@VBfB?|@@vBCvBE~ACp@Ct@ABGvAKfA?JGh@OjBANmApMQhBw@`IyAvOgC`Xu@`IIt@i@vFKpAq@dHKz@Gl@}Cj\\SbC?@Gp@Ev@ADEbAEx@Ev@Al@Cz@Ah@?|@Af@?d@@fC@p@?v@@lB@fB@zFLpO@nD@~ABjFBrF@dE@nD?l@BhH?r@BhDBnD?j@@t@@fBB~@BzBBh@?RB`@?HBb@HhABj@Df@N`BBTLhAT|ARjARbARbA|@`ElAbF@BNp@XjATfANl@VvABNJl@Hj@LfAHp@BPDb@B\\Hv@JtAHxA?FBj@?J@l@Bl@@lA?`@@b@AhA?x@Az@CnAGpAE`AEv@Gt@Cl@AFI`AQ|AGt@It@e@tEIr@?Be@pEQhBWhCKbAw@rHIp@It@It@ShBEd@KbAeArJE`@MhAq@lG]`Dm@|FAHIt@c@dE{@lI?@[~C_@lDg@zEGt@I|@IlAGr@?@IlAInAGfAGvAEjAChAAVEhBInGI|G?DAp@IvHQtKG~BCn@AZGrAOnCMbBGz@En@_@dFg@vGeAxMw@lKQtBOpBKfAKbAGd@Ip@QpAQfAUlAS~@UfAQp@Mf@K\\c@vAw@xBe@nASh@[~@a@pAQp@Md@Qv@WlAKl@Mv@CTCTE^Gh@Cd@ItAGjAA\\?LCt@?h@Aj@?dA@p@@nC@V@lB@h@?LFjI?\\?XBrCAlA?p@?JAj@A`@ChAEbACj@AVC\\Gx@G|@KhAYpCOvAIt@QjBGl@Kz@It@_AhJgA~JWhCeBhPa@dEQvAQ|AUzASlAo@bEIh@aCfOY`B{@jFaD~Re@zCKr@e@zCY`BkAzHMr@AFc@pCMr@_A`GQjAuApIYfBq@hEaAlGW~AW|A_@|Bs@nEIb@WlAQx@CLK^[nAM^GPKZCJe@tAa@bA[v@A@Uh@?@[n@S`@MTKPs@nAgAjBi@|@_@n@_@p@]r@_@z@]z@_BhEmEfMSj@wDxKeAzCoD~JiAxCSj@Q`@O\\CFWf@IP]n@u@rAEFc@r@iC~DGHeA|A[f@mApBoAnBwA|B}@`B[n@]t@]|@GNYv@a@lAQp@ITi@|BOn@I^Qz@AFMr@WxAAJGf@Kv@Ed@Gj@KhAKnAEh@C`@AT[|HShIQjIIdDIbDS~IShISjHAv@I|E?tABzAJrC?BFt@Bj@h@zFDh@F`AJvAFdA?B@XH|B?JBv@?N?l@A~@IpDKbDAZOlBu@vJo@bIGt@}@pLW`DGt@QhBGt@_@vEo@bIGt@UfCAXc@rHqAzP]xEM|AUxC_@bEEd@Il@OlAIl@E\\CNIb@CJKj@Or@S~@q@rCq@vBSn@gBjFuBhGSl@_DfJUr@qAtD_DjJwFjPQf@{@hCsA~DmAlDoAvD}@hCSl@kC~H}@hCCJ_BrEe@xASt@Wz@St@Mh@WlAk@zCk@~CsCxOiAvGMp@w@lEg@vC[fB[dBiC~NMp@k@bDaAtFcA~FeCfNs@pEaAfGcB|KeB|K]hBMn@Kj@_@zAc@~A_@lAKXSl@KXs@bBcAxB]p@MVkB`DoKbRwAlCKPiB~C{@~A_@p@k@bAKRMRq@jA?@Wf@KRWj@Wf@q@bBo@hBQh@Sl@CFw@rCa@nASl@CJoApEu@zBy@nBo@tAm@nAc@t@y@pAiA|A{ArBmC|CQVgBzBIJgBzBcAlA{@dAoBnCw@dAc@z@Wr@kA`CiAnCQ\\oApCoBxEm@|Aw@dB?@q@hBg@hBg@tBMr@UpAUlBIrAGtAGfAEdDAhD?bB?lD@vA?N?vAItBSzCOfAK`Aa@fCAD_@bBGRYlAK`@[|@[lAi@vAGNQn@]fAGTQn@Mb@c@lBQp@?DkAvEEVm@pCABo@pCQp@AD[|AADk@dCw@nDI^]|ASt@On@Mj@ADSz@WnACHWfAWfA_@xACHOp@IXETa@bBENK^q@fCg@fBQl@Sp@Ql@Ql@GR_@fAUl@IXIRSl@{@hCCJc@nAaAxCM\\wAbEO^qArDSl@gB`FCF{BzGiBdF_@fA[z@aAvCEPSl@g@zAGR_@dA]~@KZi@xACJc@nAg@zASl@Ob@Wx@]hAu@jCEVi@xCABUrAO|AMjAIx@?BGr@Ez@GhBE`BANAfACpA@bA?`ADj@@\\FnAHxBTzEDf@NjBDn@NnBRtCVxDXfDJpBJvAHpAZtERtDvCb_@Dn@HjA`@bGRzDFrBH`CB|@@zAAfAEbCMhDMtB]vDAFU`BE`@ObAShAYtAWfAGRQp@Qn@e@zAg@xA[z@eA~BaAhBcC|D_B`CSZ{@rAY^y@lAa@l@u@hASXEJm@~@s@nAc@z@Yp@_@~@g@`B_@pAUlAWlAQrA[lC}ApO?BIt@o@rGWzBOnAGd@YzAWfACNK`@Md@Ux@EJM`@Sf@ABe@jAu@|Ae@`Aw@dBSb@CDy@fBe@dA[x@_@hA]nAQt@_@fBQfAM|@CPOpASfBMrAGp@Gt@CNEd@O`BK|@It@KfAKx@Ot@Kl@Mj@M`@GVITOd@CF]z@_@z@EHg@~@g@t@{B`De@n@sAhBsAjBy@pAi@bAc@z@_@~@a@`AUp@o@pB?@Ql@w@lCSl@Qn@Ut@a@vAe@|AQn@e@|Aa@tACHk@pB]hASn@e@|Ac@zAM`@W|@Sn@e@|AQn@Ql@Sn@Qn@Sl@Qn@Sl@Qn@Sn@Ql@K\\sAlEy@jCIXGTQl@mAfEOd@aArDiAnEQn@]tAmBzHwA~Fm@jCK`@Ol@a@jBEPWvAQhAKt@Kv@IdAIx@KnAOnBGjAMhCe@jHALIrAKjAQzAOjASlAUpAGVOx@c@bB[vAc@tAw@~Bu@fBEJg@fAk@fAEHYd@S\\qBnC{@hAy@`A[`@]b@u@bA[`@uCvDuAjBaAdBEHQ^m@pAA@Uj@_@`A_@bA]`AIXm@rBc@lBU`A_@vB]vBYhCKfAOvBKhCC`AC`AAf@A|@?dA@|@?bA@|FAxG@nF?d@AfAC|BCtBEvAMrCSzBK~@Ir@Gb@CP_@fCCR[bBa@bBGRIZOn@ELUz@a@nAO`@}@fCkAtCgBpEq@`BUj@k@tAUj@cAbCyBjFmC~GmCzGqC|GyAlD]x@aDrH[n@k@z@m@r@CB]\\IJa@Ze@^y@b@m@ZcA^uBl@yBf@}D`AiBb@a@JmCn@qEfAc@JaDv@}EnAE@cCv@s@Zq@\\y@f@}AdAqAjAcBfBe@j@YZCDu@dAu@lAiA`Cq@rAs@lBaAxCo@`Cc@nBa@bCe@xDEZYdCMbCO|CAb@AnAAjB?pANdJB`BLxFDrCLdHJ~FTxNZ`OL~B^bFBTFt@BLR~ARfARpAT`AlCdLPp@fFnTp@rC@F\\xAPp@hAzE~@nEBRr@nD\\bC?BJt@LvAl@zGX`DVjDTxDDj@Bz@@Z@\\A~DCjIA~C?D@fD?t@@zL?|E@tG?zL@v@?rG@xH?~L?tBAnCAb@AdAExAIbAAZIhAAFOzACLy@~HCVc@xD[`DGfACx@Cx@CjC?r@@x@?DBv@?LFdAFtAd@hG`BhVBTHjBFjBBjC?bBKnFKjBKxAS~BYrCyAjNIt@yA~McAtJIt@e@nEiAnK_@dDs@|GcAtJIr@e@tEg@tEIt@y@~Ho@hGq@lGyA~M[~C}CtYmBhQcAtJqEpb@_CtTK~@m@dGGp@q@dG]bDYbCWdC{@jIQ~AYfCMlAIr@Iz@KrAInACn@Ez@EjACjAGdFEdDObKClBEzBAj@ClBAv@?HKfBI~A]dEQlASzAKp@Q`AOr@On@_@bBOh@Sl@aA|Cy@rBABWh@o@vAcBxCABo@fAgBzCyCfFs@jAYf@s@jAsDnGoItNYd@Yf@mArByCfFYd@mArBYd@Yf@yGfLYf@sGzK_@j@mA~BaAzBO`@M^Wz@e@bBo@|Bg@pB_@~AQn@sAtFQn@_@`Bs@rCOp@eBdHcAbE]vASx@a@~ASn@Sl@CLQ\\Yr@i@jASd@cAbBiBxBmBfBCDuAp@sAf@a@NmAb@oFzAwBRQ?kBFgAB{AK[C}C_@OAoAUmAUOCcEo@CAqCa@yF_A]GeIqAa@IyBe@QIa@OIEmAk@MG_@Ui@[_GoD}CqBCAw@e@m@Y_@KoA]}@Sa@GYEIAWAo@Aw@?{@BgAFmAFuADaCJcFTC?_@@c@Bc@Bi@@y@BwEPk@DyBRSD}BZYFOF_AFO@w@Lc@FcC\\mFx@w@Nc@H_@FqAZYJa@NIBgAh@q@f@URIFg@d@o@l@AB]`@EF_ApAKNYf@ILe@|@Wn@M\\GLa@jA{@`DQl@q@rCQn@IZWdAeBdHa@`B?BOl@y@fDeAjEg@tBQn@a@bBKb@_ApDYlACJENWjAUlACRADMp@OtAANIx@IrAE~@AREhBAvBBxBFdBLpCTzEHbBPvDBl@Dv@?BBz@@l@@f@?N@t@AlAA`@Av@A\\GfAIhAGx@QrA?Dq@|DCN]pAOj@GPSn@A@a@jASf@GLWh@e@|@KPs@jAYd@oGfKk@`AAByBpDaAxAiAzAa@f@[\\{@z@}ArAWRgAt@_@VCB[R]RCBoAbAcEnCeCbB_@X[RkCfBwDhCOHyNxJSLGDwCpB_@Zg@`@wAfA]\\GFUTq@z@i@v@QXc@n@SV}@rA}@lAs@bAm@|@}@nAU\\_@j@m@z@GJIJc@l@e@n@qAjBKNi@v@wArBUZ{@nAUZo@|@GHYb@A@oAhBw@bAm@v@c@b@s@t@y@f@k@b@w@b@}@\\C@s@T_@Hc@He@Hu@F{ABs@@}@@mC?sFAi@?wE@sD?c@?Q?eE@gA?gA?oA@_A?c@?cIAkA?kC?c@?Q?yA?wE@kA@wABo@Bm@F_@Fe@Ji@Ni@N]Nk@T{@d@s@f@k@d@GD{@z@g@l@k@r@U^_@j@S`@Yh@e@bA_@x@KVaAzBKT}@pBGNkAjCk@|A]hAK\\Ol@I\\Qx@Kj@Mp@ObAK`AKfAGj@GhAEdAA\\Cd@ArA?rABrAP~CFv@B\\TnBr@bF`@rCZvBb@jCRrAPpANpAN|AJtAHxABfB@zAChCIhD[dP?@Ah@GhDAFGvC?@?LIdDElBCdBCv@ElBEnB?JE`BIdDAX?HEpACn@C^Gz@Gv@ANALOtAQlAG^Ox@Ov@Md@St@U|@ELCJo@tBCJM^ELSn@Ql@ENGP[`AW`AS|@UbAG^Kp@CNETE\\Ed@It@CNCXIpAEr@Ah@?PAd@CfAAh@?L?v@@d@?N?^FnA@d@@NBf@?N@PBb@F|A@N@XBtA@v@@d@?N@~@AtA?@CdA?REhAGfAIlB?FC\\K|BCf@IjACp@Cd@MdCOfCW~EKvBOfCOtCQ|CKnBKjBIjAKpBCb@ARIrAATIvACp@ABKfBMxBEl@Ix@UpBCLGZUtAc@tBYdAGXMd@q@hCsAjFIVGVg@nB{AbGy@bDGT_@`BShAQdAKx@MjAIv@G`AARAHAXG~@Cl@IlA?DI~AOrCMxBI|ACd@APOdBQpBk@nDk@~BK`@qArD{@lBk@fAWf@kFpKyF`LWh@Wf@aBbDcEhIUf@o@zAITcBtEcA~CCBg@bBy@fCg@bBa@nAWv@c@lAABSj@o@`Bk@hAS\\o@nA{@tAu@fAEDWZuAbBGHST{@~@kF|FuAzAmFbGiBrBiFzFuC`D]\\iBnBcGvGGFyA~AcCnCMLqAxA_AjAm@`A[h@Wd@INa@~@Yv@[`AUt@K`@Qp@Kb@CJQp@Mh@Qv@m@lCERe@nBW`AITO^KZMV_@r@w@dAuA`Bo@r@_BfBqC~CiBtBY\\iAnAoAlAmAz@wAn@{@d@[PoAj@a@RoHfDa@Ra@Pa@RqCnAw@\\KFiDzAoGtCa@PSJm@ZC?m@b@OH]VYTyAxAw@|@GF{@bA]^kAtAeAlAQR]^cAlAQRKJQRy@`AyDlEQTwA`BaIbJuB`CEFUVaAnAm@z@EFm@dA{@fBm@vAkAvCk@vAUj@aAfCmAtCO^qCfHyF|NmBzEUj@cEnKaAbCaAbCuApDk@vAUj@cElKaAdCwAnDSj@uDlJmB`FkB~EaAbCkDbJUj@oAbDUj@wCtH}@vB[t@O^EJa@|@e@|@]p@S\\S\\a@j@k@v@g@p@u@fA[^?@w@dA[b@[b@OPmBjCg@t@[b@}@jAEHi@v@{@nAa@p@cAfBk@pAKVq@bBM`@a@hAW`AA@Ol@Oh@a@jBCJ]jBERG^O|@_@~CSbCU`DIjAMnBYxEc@jHg@bJ_@vGSdDKjBYzEYjEQpBK`ACZEXOtA]zBe@lCYlAc@fB{@lCk@`Be@nAGRe@jAs@nBkAzCk@|As@lBgBzEs@hByChIuArDsApDqAlDcApCu@jBIPm@~As@zAaAjBe@v@g@t@o@~@_@d@o@v@q@t@qAjA{BbB]XEBeCdBu@h@_D~B_@VuB|AeJvG?@_@V_IzFaCdBqJdH_D|B}FbE{CzBw@p@k@f@{@|@i@n@u@jACFk@bAi@fAWj@Yv@KV]lAa@fB]dBUxASdBO~AC^GdAG`BCbBCxBMjPEtGEtGAdAApBCzDClEA|E?|E?hC?nL?j@?dD@jE?dK?fE?fC?t@?fDAlI?nB?v@?|E?v@?v@?dD?v@?vE?fD?v@?dK?dD@nI?dK?v@?lI?t@?fH?lI?pE?rD?vG?~I?dC?v@@tG?fE?x@@lC?fD?v@?vD?hBAtG?v@?zS?v@?v@?tG?v@?rG@~G?hA?vG@xP?rC?pM?hAArJ?bB?H?bA@nC?J?|L?t@?l@?fB?`C?zC?H?v@?j@?x@?H?bB?J?lI@bB?xB?v@?l@?t@?pBAzF?vJ@fF?dD?fD@fIA|B?|L?hB?D?v@Av@?t@CtACfCC|A?PChAAr@I|DAb@Ad@CfACt@C~A?PAt@EzBAj@ClAE`CAp@CtAMfHElBIhFErCAf@?NAhDAzE?lB@|MAh@AlCAl@?f@?tB?tA?~AB|J?pA?`BAjDAjC?pI?dBChE?dA?zCAtB?zBCfG"
                     },
                     "start_location" : {
                        "lat" : 48.382133,
                        "lng" : -89.44233469999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1126
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 99
                     },
                     "end_location" : {
                        "lat" : 49.7887792,
                        "lng" : -92.8472896
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eGovernment St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "}zznHdpruP?^?xD?|AAxEIrBATI|@Gh@K~@Kx@i@tECpAAfA?Z?v@AfD@pE?~EAfCAt@C|@C|@Mz@UbAi@hBUn@EN_@v@Yf@e@h@QNOHC@QHYJUFSBi@BY?"
                     },
                     "start_location" : {
                        "lat" : 49.7862263,
                        "lng" : -92.83346539999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "119 km",
                        "value" : 119365
                     },
                     "duration" : {
                        "text" : "1 hour 16 mins",
                        "value" : 4530
                     },
                     "end_location" : {
                        "lat" : 49.7331602,
                        "lng" : -94.3021581
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-17 W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "{j{nHpfuuPkB?kA?iB?c@?c@?mAAaDBeA?qA?qC?a@?mA@wBA}@@aABi@?qFDkA@_H?kB@oC?oC?cA?o@?aB?eE@OAA?uE?A?eJCA?}GAkB@mB@yBAgB?GAeD@mAAi@?cBAsA@a@?C?m@B_@@g@HYDSDWFq@XMHUJoAx@gAdAg@t@s@fA]x@KXEJO\\[x@UbAEPYxAMp@Ip@Ej@Cd@Ep@C`@Av@Av@AfA?T?nC?zC?J@|E?L?h@?lI?L?h@@pD?nBAnB?tG?fD?t@?~E?v@?~B@xA?pE?xEArB@jI?vB?hD?rK?fJ?nB?nBAdD?H@dB?|E?nB?H?|C?nB?t@?fD?v@?fH?fD?nB?dD?`A?|I?tAAtG?T@hE?bC?lE@nB?nB@tN?v@?|E?v@?nB@lI@pN?`K@`G?zD?zS?v@?jB?B@dD@v@@pD@rE@fD?b@BpF@vG@l@HlR?v@?BAjB?v@AnA?\\?v@AtG?^AVEtNAv@ArC?j@CtF?bAAnCAvGAvGGlV?lP?vG?t@?fD?v@?|E?v@?dK?v@?~E?dDA~E?fD?dD?dK?nB?nB?v@?bR?v@?fD?nB?tG?v@?dD?v@?fD?v@?dD?v@?~E?v@?v@?bR?|L?fD?rN?xIAdD?fD?bD?zDBpG@dDAv@?R?b@?fD?lBAnB?jB?xG@vG?jP?nB?v@?v@?fD?D@nG?v@?lI?nB?v@?lB@tN?nB?zA?~C@jI?fE?xF?|C?~@?|C?v@?|L?H?tEAtI?hY?dD?v@?v@?fDAlI?~E?tG?v@?dK?v@?nB?t@?~E?v@AtN@tH?v@?lB?nB?~E?|E?fD?dD@~E?|L?|L@rX?fD@|E@hL@xD?|A?v@?|E?v@@dR?v@@zZ?t@?~E?v@@xX@xB?P@bG@|@@vEBdK@v@?v@?nB@nB?JA`I?|EAfD?v@?rE?nG?|F?dK?pb@?v@?fD?nD@tH?lI?v@?v@?lB?v@?lI?v@?|S?dD?v@?nB?fD?v@?^CjO?v@?v@?nBAlI?fD?v@AtG?v@AdK?v@?tC?dD?fDAnBAbY?lIAlI?v@?dG?fD?|EAfD?nB?v@?dD?v@AnMAzL?hI@f@ApE?~E?nB?v@AlB?dK?fDAtN?v@AdD?v@?v@?v@?v@?fDAjP?~EAdD?v@?nI?t@AfD?fG?~E?jE?v@?`H?fG?|S?nB@|E?nB?v@?nB?dD?~E?jP@|SA~E?fD?jKB`I?nF?`E?lB@lP@lI?fM?xU?v@?|@@~C?z@?jB?bA?tCA~A@vA@pA@~B?v@?@DdEJ|CLxCRfEd@pIx@lNLxBJlB^pGDv@LrBJdBZpFTdEP|C?HRxCTbDLtBd@hI\\pG\\rGPbDVzEXjFXjEb@dIRdDDt@PlDPjG@X@\\@v@FlBLtGHdDBv@@v@DlBHfDDlBR~HBbABj@?f@DrA?pABjC?`@AlAGrCK~BA^Gz@[~CY|BUtAg@dC{@hEm@vCMr@yAnHm@tC]dBOp@YrA{ChOGTuAvGMr@_@fB{@fEm@tCOp@Kf@AHg@~Bc@zBm@vC]dBI^EPe@~Bo@zC]xAaBjIa@lBq@nDs@hDMp@Or@_AtEYxAeAbF{AlHqAtGOn@q@dDe@xBCPOp@w@xDq@fDi@jCQx@a@pBqAlGs@lD}AtHgAhFo@bDm@tCQz@c@xBqAlGo@bDaAvEe@|BKf@gAdFMd@Mf@K\\O`@CJSl@i@xAUl@Yt@qC|HcIbUeDhJyF`Pi@zASj@eDjJoGnQ}CzIiAbD]`AKVm@bBgAzCq@jBSj@}@hCUl@cCzGgCdHwA~DSj@iA|C{AlEUl@u@xBY~@Qn@KXc@fBYxAABoBpKMp@G`@SdAu@lEMp@Mr@w@lEMr@u@hEy@nEMr@w@lEMp@]hBMn@u@lEI`@CPaCjMaAnFMp@Id@cBxFSn@Ql@y@nCQl@Sn@w@lCSn@}AjFQn@e@|AM`@ELy@lCQl@g@~AQl@Sn@wCxJ_EvMeFtPy@lCGRqCbLOj@u@tCgA`EQp@kB`HeA`Em@zBiAtE}BlI]vAeA|DMh@sAvFUhAe@tBQdAKn@SvAOnAaA|Ia@lDWpCYhCKjA_@jD]bDEXAFEb@?HO|AMtACVCd@Eb@ObAI`@EX?DOt@Kp@Q|@UfAOn@?BgDjN?|@uAvFERiAzESx@mApFGX{@hDWbAAB_@~AKl@E`@MhAOdBM`CExBB`B?fADfB@l@Bv@FnBBt@JfDFlB@\\ZtMBv@?RBb@DlB@P@d@Bv@Bt@Bv@Bb@@RBt@Dv@HpBn@`HD^^`DHp@Ht@Fb@TzBHt@RjBXhC\\lDb@jDh@rEHr@Ft@x@lIR~AJr@Jt@?Fl@~ERtA^bCLz@Hl@H^d@fC`@rBd@lBH^Np@T|@^rAPn@DJj@dBHX^hAp@lBRj@@Bl@dB`@lARl@BJb@nATp@p@jBz@lCd@nAN^Tj@LVh@dAPZXf@BDT^`@r@|@lAr@`AhAhA`@^^ZxE`E|@v@pAhA~BrBd@d@pAvAl@p@JLvA`BZ`@hL~Mt@`A|@bAZ^xA~AZ^NNLNZ`@\\`@Z^nCdDx@`A\\`@RVb@j@JLPR@@d@r@\\l@FLVf@T`@z@pBv@tBj@hBl@~B@BJn@TrADPJr@F\\LjALbADf@F`ABj@Dv@@b@@P?v@@v@@`A?tAA`BCvAAr@Ch@ErDClAEvBAv@KnFElAGpE?VDpF?P@d@N|EDxAHjAFt@HlAVhCD^VvBb@pCR~@VrAb@tB^zARt@Pn@Pn@HXnBpHxAzFp@dCf@jBPn@b@~APn@Pp@@Dp@hCPp@J\\fAhEx@zCfA`Ef@fB^vAl@zBDHL`@p@~BDLTj@v@pBd@|@|BhEVf@`AhBvDdHjAvBXf@p@nAp@nAJPnBvDTd@@@jAlCN\\Tj@h@rAl@|AhB~E^bA\\bARl@Tl@Rl@Rl@Vx@Jd@Np@@FVrARnAFb@Hp@@@VxBVhCH|@Fj@@HTxBNzAHt@Ht@RjBBVDZTfC\\bDd@|EZxCTvBXvCZtCv@rHXpCFr@Fh@NvALz@Jp@FVHf@T`ATv@V|@HRPf@\\v@d@`Af@x@Xb@^h@d@h@x@x@r@h@x@f@~@`@@@hAb@\\Lp@TPFb@LB@r@VJDx@Xt@\\ZPVN`@Td@`@PNXXLNFFd@p@h@t@f@|@\\t@FP\\z@^rAFVT|@ZxAh@vChA|FDZFTtAnHl@zCLp@BPf@dC?Dx@dER`Aj@zCh@tC^nBr@xD\\pBPlA?HLhAJzADnA@Z@v@Bz@AzAAfAAvAIxAAXQpBKz@M`ASjA[`B]pAe@|A?@g@tAWn@c@z@[l@IL_@j@m@|@[`@eAnAm@v@{@hAu@dAe@r@MVYd@[j@qBjDKPkAtBs@lAS\\u@zAiAtBu@nAYd@u@nAW`@eBzCsBlDMTmBfDQXcBvC[j@Yd@INwA`Cs@lAk@hAU`@[t@c@dA]|@e@vAK\\Ur@]tAa@fB?@a@pBU`BUbB?@]~C?HO`BIt@Ef@ALGt@SdCOhBOxAQ~A?DSlAWlAYfAAB[lAY|@EJSf@Uj@k@hAUb@s@tAOZIJuCrFuD`HaAjBYf@q@pAMTuAhCWf@q@nAuAjCmBpD{@dBOZ_@z@y@vBg@~Aa@tAe@pB]bBKd@UzAYrBQzAc@zDGh@OrAa@pDWhCGl@G|@C`A?TA`@AR?lA?xA?JDdCJrBFfABb@B|@N~B@\\HlBBf@FdADv@HlBPdDDfAThEDjAB`@JfBNnB?BPfBJv@Hh@@JJr@Fb@BNLr@PnARjAJr@DTD\\XhBJr@DVh@fD`@hCh@jDh@pD~@fGVjA^bBDRPj@?B\\dAVp@v@hB\\r@PX|@~Ab@r@|@|Af@bAl@vAp@vB^rAJd@Np@Lj@N|@R~AP|AH`A?FHbB@JDbB?H?v@?N?dAApA?t@?RCvC?j@CrBCrDCtCAtAAvEA^Av@AlA?`@AtAA~A?fB?`E@fEBhG@jA@zABvC?N@fD?t@BnB?`@FbJ@b@@bCHjP?v@@nB?@BzE@nB@nBBfDB|E?v@@j@@xBDpG?D@dD?bA@bB@v@@nB?L@nBBdC?vA@v@?L@fA?dBCxAE`AMlCQrCcA`MATWbDSfCCZOjBUnCS~BI~@_@xDMfAUpBIl@CRE`@UzA[hCUbBi@dDEZe@pCo@xD]tBa@tBk@tCm@xCKd@Q~@}@pEKj@wBtKYrACP]bB]dBi@rCaA`FI^m@vCMp@q@tCWlAg@nBw@nCAFoAxD_@lAyAbEyA~Do@zBEJKb@c@nB_@tBg@~CERKr@CTUrBQjCOxCOnCOzCKfC?FCrAAdB?`ABfAD`AHfA^fEBR|AvRrArPNlB`@vEBb@BRFt@|@nJ`AfIh@tEJt@`A|Hv@fGJ|@Dl@PjBDv@Bn@FtB@R@xA?v@?PCtCAlAKzG?Z?v@AhBFjD@VFtABv@@FVbEhApPDt@`@dGp@pIFt@TnCFhABj@P~CNvD@lB@x@EzEm@hGc@`Dm@pEe@|CKr@q@nEKt@SnASjAKr@cAhG[rBY~BM|AO~B?HEfC?rA?@DlBFnBBx@h@vIdAjNLxAh@dHx@|KDt@PlCDpAD`G?dV?v@A|L?v@?vG?|TAlA?v@?t@AnB?|A@jBBbBFvADt@VfFVnEFdALtCLbC?jDIxCMbCU~BKhAG`@kBxNIt@[hCQnCMjBM|AEdACv@EtAGnAMzBKvCUbDGjAKvAMlB?Fc@nEANGd@ShBIt@Gh@_@jDIt@]vCUpBqAjLIt@?@}CzYs@jGUpBm@zFa@`FANGhAEzA?HCl@EjBAvA@fDB`CTrLf@tWBdAJdGDvF?nC@`AIxJg@lf@A|ECdFEnDAlBG~EAv@?t@CnBCnCAVAt@I`D?DGt@G`AO`BOxAKdAIr@u@pEiB|Ku@lEMr@gBrK]|B[~BCRMfAGr@Et@IxBA~BAp@DjCZrF@P@PTvAHf@p@`En@rDLr@d@nCV|ATxBHz@DZJdCDpB@fBCnCKfCInAE^MnA]bC?Da@fCU~@K^U`AIXq@nBGNiAbCe@x@GJoAhByA`BWXUTg@`@aCvAcAn@_B|@aDjBqFbDwBrAKJ]Z_@\\]Z[^{A|BOXWf@Wd@Un@{@jCKXERQp@ABYvA[tBGp@Ir@Eb@I`ACv@Ax@ABAv@?B?r@?Z?z@@`ADx@FfADt@Fn@BVNnAL~@j@|C|@hDz@zC`CnIZfAv@pCv@lCTt@r@hCt@pCb@~A~@pD\\nA~@lDVlATnAD`@Jr@?@Fj@Dx@@DHxB@^?nBEdBGjAMbCGlAIlAK~AGt@Gv@KvAMbCIlBAb@E`CAz@@hCFrCD~ALnBFv@RlCNfAJt@Fb@PbAV~A@FNp@\\|AbA|DBHb@~At@pCPn@b@~AHVl@vBPn@fA`EPn@BFr@lCt@tCZzADRD^Jp@R~ANfBHxABdA@TBjA@zA?dK?h@CzAGvACXO|Be@hDE\\a@pCyAlJKr@e@|CKr@e@zCMt@UfBM`A_@|CEh@QjBQjBQlBAHK`BEv@CZKvBStFSrIABSlIElBAv@Cv@K|EIdDAv@Cv@EnBWzLInDAbB@jABfAJnCBt@PzANzA?@d@|Cf@xBr@fCd@hATl@@B|@fBzA|BpBbClCfDLNNPzFbHbBvBz@vAx@`Bp@dBd@|ApAtFnAnHfAjGb@pC`@pCvAxJ\\~BPxAL~@\\lCFz@RtCBdABp@?zAAnA?n@Q|GGlC?tCDnBNxBJdAX~B\\bBb@`BBLRl@`@jA\\z@jB~EBDPd@|BdGfB`FhAzC|BlGTl@Tj@|@fC~BlGh@xAj@xA|@fCTj@Xv@rBnFbBvEBFNd@Rn@FPb@`Bd@rBt@rDTzARdB?BHp@Hv@Dr@HhALvBFtBD`CH|E@v@@v@@v@@v@@p@BjDL|LHxHD~EF~DFbGDnB@v@BxA?T@t@LhMHrDNjD\\tD?BJr@Fh@d@lCXfANn@@Dt@jCTj@Rj@Tl@HTJRVj@Th@Vh@p@nAzBlEVh@hAxBVf@Xj@lClFtD|H|@dBb@~@b@x@`AhB`@v@HLr@jAZd@dBxB^^`@b@v@v@HHnApAvA|Af@h@p@t@\\\\vA~A\\^`@d@r@z@|@pAlAlBPZz@`Bf@|@p@nAbCnEtHvNx@zAVf@p@nAbB~C\\n@dAnBXf@Xd@Vf@r@nAjAtBfApBVf@r@lAXh@Xh@zBhEf@`AFNTj@j@vA@@fAlDBHRn@Pn@@Bp@lCDLHb@^rBTxALr@BLR`B\\fDTtDNnCf@dLRdFDt@Dv@Bv@Dt@HlB?FBn@LdDRzEHnBBt@B`@@\\BZBPHt@JdAFb@Jr@@HJh@P`AJb@Nn@Nj@Tr@DJL^Rh@@B\\z@h@hAT`@Xd@b@r@|A`CnAdBvBvCrAhBZb@dB`CpAfBdAjA^b@x@v@\\\\\\\\|@x@\\\\\\\\@?zBrBrEjEzAvA\\\\n@l@rJfJz@bABDl@~@x@zAFJb@hATj@BFn@tBDNNp@^fBd@vC@@Jp@XfBf@xCnAtHf@zCl@rDvBnMp@~Df@~CdAjG?@Lr@X~ANx@BLJb@DTPt@Nj@h@`Bd@nAj@nAn@hAn@dA@@Zb@T\\DDZ`@TVl@v@h@r@BBx@bAHJPRx@bADFr@|@t@`A`@f@|@hAfBzBt@bAh@t@LTZd@Vf@LRJPLVHPN^Zv@BBPf@FR\\hAHTTx@X|@d@bBHTn@vBnB|GPl@@@fA|Db@~APn@Rn@Pn@Lb@x@zCd@~APn@b@~APn@Pn@Vz@Jb@t@pCh@nBJ^bAjDx@zBLZL^j@nAHP`@x@h@|@PZZd@r@bAd@l@\\d@X\\\\`@HJz@z@RPPPLHx@p@BB^V\\Tb@V`@T`BbA^Vl@^v@d@f@\\j@d@f@b@LLv@x@RTFH\\d@f@v@\\n@^v@Pd@BF\\bAv@lCFNv@jCx@lC`C~HRn@HXV`ATlAP`ALbAJhAFr@@b@Dj@?J@h@@v@?jA?|AC|EAdD?v@AbBAdD?nBClI?L?h@?v@At@?rBAr@?p@@|@?JB`B?PBd@Bl@?HFt@@JDh@Fn@@DFf@Jr@BJLp@DRH^DNNh@Vz@HVNd@BFP`@BHn@rAzAfDx@hBv@dBTl@Vr@Tt@J`@BJJd@DNLp@Lx@LbA@NFj@@HDj@Bp@D`A@v@?z@Ap@C`AIlBObDQbDObDKzBCd@A^A|@Ah@@j@?l@?JBh@?NDn@Bn@Ft@@BNpABRN~@Hd@@BR~@\\nADJL`@JXZr@BHLX^r@Zh@JNNRV^BBRVVVd@b@FF^XBBXPb@V^R`@RHDlB|@xBbA`Bn@NFtAj@`@PHBrClAr@\\ZPB@ZRh@^\\VZZ^d@d@l@Zd@\\n@^x@NZFLTj@h@xAJRJVTj@@BRf@JV\\~@FN`@dAfAzCLZTp@`@hAXz@JXFR^fAb@hAN`@Tj@~@dCLXFPd@jADLPl@L\\DPRr@VhANz@Nz@?DPpAFp@H`AFlA@n@Bb@?R?h@@dA?DAn@?FEtAE`AGfAMhACTGb@CPIf@Qx@Ml@Or@ADOd@AHY|@Qf@Q`@KXKPUd@_@r@m@`Ac@h@W\\[ZSRIHWRGD[Xc@Xa@X_DrB_Aj@e@XkBjA}@n@s@j@]^s@v@c@n@m@~@U`@Yl@Yn@i@xAOb@EPK\\CHQt@Kd@Ml@GVEZKh@K~@CPC`@E`@KjAEt@ARAb@Cl@?~@?H?pA?R@f@?NBx@Br@@JFbALrADd@BLFj@BHRlADVJf@t@|CDNx@`D|@jDb@zAXhAVdALv@Nz@NrAL~ADr@DxA@v@@|@AdA?JCbACt@I`BOpAIx@OfAKr@EV]dC[vBu@dF_@lCCLKt@Mr@Il@a@jCCTIf@ALMfAC`@AFGdACnAAz@?B@nA?f@Bj@?@Bn@?FFt@Ft@Dl@@FFj@Jp@P|@f@rBRl@L\\Nd@Tj@BFR^BFXf@JTJPR^lBbDXh@v@tAfApBT`@lE~Hr@nA^p@PZXf@h@~@HLVf@R^r@nAR`@Zt@d@nANh@FRH\\XdAXnARdAF`@l@dD?Bt@lEnArHJj@l@~CLr@j@vCJl@x@pEv@lEJj@@DP`ANbABTHh@JhADl@Dh@DbA@Z@|@?TAvAClAEt@?BQ`DIdBMtBc@nH?FEv@K|AEdAC`@Ax@A`AAjA@|ABz@@XFtABZ@XFt@LlBV`DNjBVbDzArQFt@PjBFt@V`DD`@@RPlBFt@x@vJ?@^fE\\jC\\dBPx@\\pAx@fCZr@Th@r@rAr@fAPV~@nAn@p@LJf@^~@l@l@\\|@`@~@\\pAZn@Lb@JzAZLB`@Jr@Nt@Nb@HJBx@Pb@Hl@LVFb@H`@JPBrBh@tA\\lBl@xBz@d@RbCfAXLFBxBbAn@XfAd@hBv@|ErB~DjBZND@bBv@bAd@ZNDBdClA`@RnExB~Av@xAr@HD`@R\\PB@f@ZVPB@r@l@FFXXBBj@p@p@bAf@`Ab@|@Zz@Z`A^rA@Bn@nCNp@VfAzApGNp@Np@Nn@Pp@Nn@ZpADP`@`BNn@Pp@p@pCPp@Rv@~@|DNn@r@rCJb@BLp@pCnD~NXlAPp@^bBp@rCb@pBXvAXtALdAL~@BXPlBFz@D`AD~A@f@?lAChBC`@Cj@AJK`AAVK|@AHOdASlAQv@WbA[fASh@Sl@KTIVSj@}@hCK\\M\\EJSl@GLM^a@jAc@vAYbAOp@?@Mh@AFKf@O`AMt@K~@OxAADIdAE|@CXARCx@EvAAZGhCCd@?PGlBAPAd@Av@Ct@CnAEvACn@?DEnA]hJGlBC\\AXa@vKQ|FCx@GxASnFEfAAd@KzCAHEt@?DIfAEt@E^Eb@KdAIt@AFIl@Gh@UpA_@pBg@`CcCvJABMr@WfASlA?@Mr@Mt@SfBIt@E`@MfBAVEv@Gt@ANG|BEzG?PAv@C|ECnBCnD?l@IlIGtGItG[f^EhCGdDO~H"
                     },
                     "start_location" : {
                        "lat" : 49.7887792,
                        "lng" : -92.8472896
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "33.6 km",
                        "value" : 33594
                     },
                     "duration" : {
                        "text" : "24 mins",
                        "value" : 1464
                     },
                     "end_location" : {
                        "lat" : 49.7461752,
                        "lng" : -94.6458172
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eON-17A W\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "gopnHnkq~PUrKUfMQfGArAE`CIpDE|AMjB?FQvBGz@Ij@Kx@QtAMn@?DI^ShAQp@_@|AW`Ao@lBc@hAKZ]v@e@dAEH_@t@MV[h@CDU`@GJSVKPc@l@EFEFUXa@d@k@p@g@d@?@u@n@g@^?@a@V_@V[Re@VKFw@\\UJ_Bd@w@Na@Jc@Hc@HWDqAVoEv@g@La@JuFrAG@[HkCn@mDz@oC\\UDy@Jk@DgA@iLJW@cIPaCNC?o@Fo@Ho@Jc@FuAPSBg@F_@Fw@JcFn@c@FSBoC\\_H|@qC`@w@Jg@Hu@N]FuAVmBd@s@Ru@Va@LsBn@qAf@IDqBbAqEfCiBhAcAl@_Al@sBpAMHgF|C_E`CaHvDMHcCvAiAr@YNwFfDoAt@eDpBi@ZyAx@mCzAaF`CC?w@Z_AVGBQDa@Lo@Ng@LYFcARK@UFK@kBZE?{AVI@SDy@LaANaAPoCb@c@H}@Nk@La@Fy@RMBi@Li@L{A`@sAZSF{@Tk@NoA\\]H}A`@sBh@_@J{Bj@{JjCqBj@g@L_@Le@Pi@R_@LMFcAf@u@^g@Xs@d@EDm@^k@d@o@h@o@j@CB]\\IFy@|@mAvAe@n@SVQVIJYb@IJQX[f@m@bAo@hAEJS`@a@x@Q^Qb@a@`AWn@O^Qb@Wp@Wv@Qh@[dA[fACHMd@ENSz@GTG^Ml@Q`AY`BCPG`@Mr@?BKn@G`@CRIr@QzA?BYtCCVEl@KzAGrAEl@Cv@ATCjACdAAt@?VA^?Z?Z?V?^AP@fB?bB?v@?l@@tA?b@@`A@jC@~B@t@?v@@fA@~A@rD@fB?D@v@?fB@lD@pA@nD@bE?rA@NAf@?r@AzACnACjAGtAGpAE~@IbAGr@Gl@Kz@MhAIh@CRIf@Il@Mr@If@Ml@Ml@Mn@Mh@Mf@Mj@Mf@Of@Ux@[~@Wv@GRO^EJSf@aAhCUl@wApDUj@IVu@lBUj@]|@a@dA}A~DoAbDSh@c@fA]`AKZUn@_@nAUt@ADY`AQr@K`@Mj@Kd@Mp@Qx@?BMr@AHKh@Gj@Mx@?BIt@Kz@Gl@C`@CRIjAEp@Ed@?@Ct@?@Cp@ABAr@CbAAl@C|@?p@?\\?V?h@?L?v@BjBBdBFbABj@Bv@Dd@Bj@Dl@Df@@DFt@@HJlABRPfBHx@Ht@Db@@PHr@B\\PdBHdA@NBVDr@DpA@D@j@?J@\\@x@?V?P?b@?XAb@Aj@?HCx@Ad@Cf@ABAd@GbAGx@Ef@OzBMdBG|@WjDWnDw@fLq@bJKdBa@nF[tECZGt@SlCKjAGt@Eh@?Je@pGCZCXMjBEh@O|BIhBAHCl@AZA`BAz@?jABfA?BBr@@l@JjBB^LvAJfANpALx@Ht@NbAFb@Jt@TfB@DHn@Jr@`@bDZdCBVFh@@JFt@Fj@Ft@?HFp@?BF`ADj@Bp@?DDt@B`@Br@@t@@X@`@?T@t@Bx@?v@?B?hB?^EpCAl@CbAG`B?HEhACXEt@Ev@Gr@?@YhEANOtBEl@MlBMhB?Bk@dIEv@MbB?FUbDGv@GjASlCCZOfCEf@]fFEb@ARMjBGv@a@nGGv@c@nGq@|JYpEu@tKIlAeA|N]dFc@pGO`CIjAGt@]|Ea@lGGv@UfDKlBI|AEdAEvAAhACl@?v@AnB@bB?R@~ADzABdA@j@Dz@H|AJhBLrAJpADd@Fl@VpBNdAFf@Jl@@DTtAVtATfAVlAz@tDNp@x@lDVhA^`BjAbFTfAv@fDH\\Np@d@nBZtAPr@XnAJb@Nv@VlARdAF\\Ln@TxA\\|BDRZ~B\\rCP~AD\\l@pFLjAl@|FNdBf@xE\\vCr@hGd@xEFp@`@zDRjBHr@l@pFnAlLt@bHJt@N|AVvBHt@J`Ax@rHD`@BRZ~C@Df@lENpATfBRtALx@PfAVzAXxA\\dBLf@VhAzBrJfBnH`AbE`A|D@DbB`HNn@p@rCFTHZp@rCp@rC@BRz@J`@DRH\\Lh@F\\FZBHTtA@FHb@PfAHn@DRD^DZLdALhAJbAJpAFt@?BHfAB`@@TFnA@FBv@@\\@V@\\FbB?d@@x@@hBAnDAfBArCAjD?|BAv@ArF?xA@r@B|DBbBB`BFdBFlBDrAPnEDt@Bf@NrDB`@@TBv@XfHHjBJzBBv@RzEBj@?JJzBDdADdA@HHfBJ~BPzD@TBv@F~A@LBt@NdDBv@Dn@B|@JzBBh@HrA@XFt@@PHrAT~CHx@H|@Fr@@@Hr@BNNtAPlAF^Hl@ZrBHl@FZDVBLHd@BJj@zCR|@ZnAXpA`@`BTv@HZFRNh@Pl@BFRl@BJXz@HRh@zABFNb@Zz@f@lARf@Rf@@@Vj@j@rAp@tAz@`Bt@tAHNRZDHb@r@~@zADFZb@Xb@\\d@X^r@`A^f@Zb@x@hA^f@d@n@d@r@V^j@dAXj@FHJVHPJTHTPb@BFPd@Pl@ZbARx@T|@P|@Lp@?DPlAJt@BX@FLlAF|@@NDt@@NBz@DzA@lA@vACvAAbAE~@Ad@CRCj@AJCZGr@Iz@KdAADKr@AJMv@UpAQv@?@U~@Sv@Wz@Wx@ABmAjDWr@Sj@{@~BCFUl@M^EJq@hBqAlDe@zA[`Aa@tAYnAWfAWxAShACPG\\Id@UvBIt@AFM|AK`BKpBOtHAlA?J?zA?hA@fA?X@\\BjBD|A@r@@T@XB\\@j@HvAB`@Dt@?BDp@B`@BTFt@Fz@Fn@Hn@?DHt@Hn@?BVvBHf@TxA@LHh@BHRnAThABJJd@FZFTNx@Lh@FRH\\DRZjA@@Rt@Nf@Pn@@Bb@vA?@Rl@BH\\~@\\|@@BRf@JXr@bB@Dn@rAFNZp@HPR`@Zp@JTJRTj@LVHP\\x@L\\HTDNBFHRHXPd@@FNb@BJNn@BHLf@Lf@Nz@@?PdAF^DVNhA@FJ`AHv@Dd@@RFv@B`@@\\BX@V@\\@^@VBv@@n@JjCDvAJdDHlBBv@FlBBv@L~CB|@Bt@Bv@Bv@Br@HjBFvADbAJhBLjBHlAHdAFn@Df@JdANvAHx@Ff@TvBHh@XtBVdBDXPhA?DLr@BPH^PdAVrAJf@b@tBLj@ZrAd@nB?@ZhAb@~AZdAV~@d@xAVx@Tp@Z`APh@@B\\`AfAvCXp@^|@b@bAP`@b@`Ah@hAjA~BR\\p@nAHNh@|@Xd@FJPVh@v@LN`ArAj@p@BBZ^\\^LLz@z@dA~@FFjA`A`Ap@jAv@nAr@p@\\n@Xp@Xd@Rn@Rz@V\\Jl@N`AR^HF@p@J~ARn@DJ@b@BZ@F?X@hA@j@?R?NA`ACD?bAGt@Iv@IJAz@Mt@MtDq@bDk@z@Ob@Iv@Mv@M|@Of@GPCPAx@It@G\\CZAF?b@CR?NAb@AF?l@Aj@?j@@f@@^@b@@X@^Bn@Db@Bl@F^D\\B@@b@Df@H`@Fj@Lz@Nb@Ld@Jd@LJBTH@?^LF@`@L|@Zn@Vp@Vl@VZPTLHDb@Rv@b@f@Vf@\\ZPDDXPJHRLPJNJ@@\\VPLLJ\\X@?n@h@LJ\\ZLJPP\\ZLLNN\\\\\\\\XXDB\\\\\\^z@x@\\\\rApAvAxA`A~@nAnAzC|C"
                     },
                     "start_location" : {
                        "lat" : 49.7331602,
                        "lng" : -94.3021581
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "186 km",
                        "value" : 186376
                     },
                     "duration" : {
                        "text" : "1 hour 51 mins",
                        "value" : 6659
                     },
                     "end_location" : {
                        "lat" : 49.85605409999999,
                        "lng" : -97.0487613
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-17 W\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Trans-Canada Hwy\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Manitoba\u003c/div\u003e",
                     "polyline" : {
                        "points" : "s`snHjot`Q`@^r@r@j@j@v@v@r@p@h@h@f@f@d@f@d@d@ZZRTHHHHTXVX^b@Z^NPp@|@r@`Av@fAt@hA?@d@r@h@|@Vb@PZDJ\\l@Xh@\\r@LTRd@j@lAh@nA^|@DJ^`AN`@Xv@Xx@Vt@@@Vx@\\hA@DPn@HVPn@HVNn@b@~A`@|A\\tA`@zA`@xA`@zABFv@nCPl@pBzGXbAZbAbAhDZfARn@FP`@vA`@rAPn@Nd@X~@Pp@Z`ADPLb@ZbA\\hA`@tAX`ARp@HXZbAPn@FTX`ATt@DLJ`@Tv@ZpAZlALj@R|@ThATfATlA@HJh@Jn@XdBTvARvAt@lFvA|Jb@tCTvATbBl@|D^fCVxAFXjAvH`@tCRtALr@BNN`AHf@Lj@Lr@Jd@DTHZPx@Pp@T~@FXNl@XjAVdAT|@VbAVbAVdAZlA@FXhA\\pA|@pD@F`A~DjAbFv@bDrArF`@|ARt@?@Nl@Tz@^tAh@vBPr@d@jBBLd@jBn@fCBH\\vARx@Lf@Nl@r@jCBFPn@^pAh@jBZbAHXd@~Ad@|ADR^jAb@|ARp@bBzFvAzEFVZfAd@|AhA|DZfAzBrHFRHZv@lCHRHXh@hB`@rAPn@J\\pAnERr@^nARr@Rt@FNVhARfANx@Lz@LdAFl@Dp@Ft@@TDt@DvA?x@@j@?^Ax@C|AI`BIpAAHU|BMdA_@jDWxBW`CSlBQdBOrAK`AG|@IdAG`AE|@Cx@At@Av@?rA?zAB`ADfAFlAPrC^tF?B^hFf@tHNnBNzBL`BNxBF~@Dh@Dp@NpBDt@B\\XhEPbCP~BPdCNfCLjBJxAJjAN`CTlCTtCh@fIRxC?HThDPhDBRFdADrADzAFxB?RFlD?ZDbCDhDJvGDjC?@@r@@|AHdGBbBDpD@j@@n@DfCFjCBtAF~CHdFF~C?DDdD@v@@^JdI@\\?r@?B?n@?v@Av@?|@AB?h@Cj@Cr@Cv@CVCf@ALEv@Gp@KfAS~BWnCs@pHe@lFGl@Gt@ADIpAATAPCb@AJCj@Cr@?@E~ACfA?z@?p@?J?j@?\\@h@DdB@n@PbFHzBBn@HpCFpAP|EDt@LrDBb@PzEHbBBn@VrGVdFBh@FhBDnAF`BHpBHlB@b@DjA@HD|@F|@HhAHt@JbALfAHh@N|@Jn@Lt@Jb@Pz@Nn@FTLb@d@lB?@Nl@Lp@Nx@Lt@NbAJz@HhAH`ABn@B`@@ZB|@@~@?n@?|@AZAj@Ar@Cp@C\\Cb@G~@Gl@Gp@SfBWjCAFIt@APOvAADW`CKbAQzASjBiAlKE\\g@tEIr@[zCADY`DGt@?Bc@pEIt@QhBUjBIt@{@~HIt@[rCo@vGMpAO|BE`@Ad@GdBC~B?\\?~@@|@@j@?b@Bl@Br@Dv@DhAJ~AX`DVbDFt@Ft@Ht@@JDh@Ft@Fd@@NNnA\\~B?@Np@TfAh@lBr@pBv@|AJRRd@B@PXb@l@v@dAZb@`BnBl@v@DDx@dAfA~Ab@r@b@`Ad@rA`@hAb@`BLh@Jp@Lr@Fb@D\\Hp@H`ADl@Dt@Bv@@`@@H@v@?BBjB?t@@v@F|EDhFDdD@v@@fAJfIDdF@~@?|AAnAAZA`@?RANE|@Ep@Gt@KfAIj@EZE\\ETKn@?BOp@?BOr@K\\I\\Oh@Md@kAbDu@pBq@pBEPm@pBYlAQz@a@vBEVKh@AFi@vDQ~AYpCOhBU|CC\\CVIfAEb@CRC`@Gn@Iv@Kv@Gf@CLc@zCCLq@zDMr@Q`AUvAw@jEY`B_@xBoBpLE^GZMz@KdA_@~C[hCIr@WzBOvAKt@If@Mv@Q|@On@Ol@YdAOf@]bA[v@GRKVmDbJoAbDm@~A[v@aBlEy@xB{@bC]jAQj@YbAk@xBOj@Qn@CHKd@Qx@[`BU~AIn@IbAGfAEt@Ab@Av@?HAdB?D@n@@x@B~@Bd@?DDn@L|AThBBTPbAXrAd@nBZtA~@|DHVT~@ZtAV~A@HL|@J|@L|AJ|A?JFbB@nA@r@?^A\\C|AGdCMpFIpDIxCIxDCt@Ah@Q|GAz@ChAEzAEnAA^GzCIvBCh@ShF_@dIIpBIpAGpAGxAKbCCf@K|CEpBAl@?dA?lB?N?vA@lA?`@B|C@^@lABfEBbE@dDBhF@rE@v@?t@BhC?v@HdKDpI?fEChAA~@G|A?FEt@CZQtBc@zDsA~KUfBIr@_A~HOhA[nCCVa@`EGp@QpBc@nFaAfLMxAoAtOm@dHm@jGk@pHCPY|Ca@vEIn@Kv@M|@AFa@~Bq@rDm@~CMr@[zAQz@Mp@]`B?@Or@{@hES`AQ~@Kd@UtAENKr@SrAQ~AE^ABGp@?HKlAIlAGjAItCAtAAhA@lB?Z@ZBpAXvLTjJBv@@v@@b@JvD@v@LvEDxBBp@FdCL`FH`EFzBFnCDvBLnF@t@FxC?LBtBHjC?PBpA@|A?nA?`B?b@Al@C~@?FAn@Cp@?DGnAC\\C^ATGv@Gz@CXOxAMfAOfAOjAWnBWrBCJYfCOlA[~Bi@|De@rDQpAOhAYjCGr@It@Gt@Gt@Gv@]dEe@`Gk@lHGv@CXa@rFIz@Ep@Q`Ca@bF_@nFE`@IvACh@Gt@GnAIbBAf@MjCG`CE`BEhBAnAAn@CpA?b@?v@?vA?hA?vA@nCDdDDfBFvBLhE?L\\zKF`CLlE@XL|EBf@?NJpDFxCBv@?TDvABv@?LH`CHpC@h@@XDnADp@Dx@HxAJvADl@PvBRvCPdCB\\Dt@LpBDp@Ft@?@H~A?LBj@@H@\\B~@@v@?\\?h@?X?p@?Z?F?r@GlCKvGE`CIjDGnCS~IOdGGpBCpAK~CGpCGlBCx@EvAIpAIzAQzBYnDCb@Gt@Ix@UrCYpDOhBQ~Bc@zFOlBaCh\\QzBWpDc@rF_@|EKjAKtAGl@OpAOfAOfAQdAKd@Q`Am@hCwAhGa@bBOp@cBtHw@lD[rAu@bDo@tCqC|Li@|B{AvGkBbIa@jB[tAeBvHg@zBGVOp@o@tCMl@AB_@~AA@Op@?BQx@Qz@WzAKh@WxAeBpJOv@Kl@Ib@CNw@jEaBfJKn@{AhIwA`I_@vBCPI`@e@lCCJMr@W~Aa@jCYzBIr@SfBAHGt@CNEd@CZOfBKrA?DEp@Gt@Cf@GdAEt@AHCl@C^ATATA`@ANAd@ARCzA?FAn@?b@AR?l@?FAfA?~A?V?tA?v@?@?bC@r@?d@?J@h@@p@FpCFzABp@D~@DdAJxAF|@LxALrALnAN~AThB`@nDNhAZlCLfAJr@Ht@`@hDFh@bAnJ@DRjBJr@Fl@d@|DP`BFf@NnAJdAJpALxADv@Dn@F|@Dj@L`CJhCFhB@dA?F@t@@\\DxCB|CPjN?T@`@DfD?XJlGFzDJpHJlIHbFDnF@v@?R@f@FvFFpFL|IJtFLhFF`CNlELdCBb@P|DPrD^fHLhCAt@?ZDtA@j@BjATtI?XFhCFfDHlDZfOHrDDfBN`H?LHhCBjA@j@HdEF`C?BBv@FvDF|ARrGRfGn@hSD`BBv@PfG?LBh@@JDt@@nB?tG@v@?v@?v@?n@?F@lB@fB@v@@v@BtEBvB?v@B|E@pA?\\@t@DdKBhE?jAB~E@|E?R@b@?tG?v@?xA?R@nB?tA@nA@rABjCBdD@v@@nABlCB~AHdH@bAB`BB~B?d@FpE?\\@nA@v@BdD?N@vC?lBF|G?b@BpE@fA?D?vA?vCBdD?v@@v@@dDB~EBxFBdD@nB@v@JrN?v@H|KBfCLfDRpDXtC|@lHd@fCdCrLlCjMjApFlAxFbEjRh@`CzDbQbAxE~@fEDT@@F\\hAlF`@pB|@fEhAjFBNPp@f@zBf@tBz@lCn@|AtAxCHPp@fA`AzArAdBvAxArAlApA|@jJtFFDdOzIzD|Bj@\\pF~CxBjA`@T`@R~A|@lHfEbEdCbDpB`Al@dEbCdEbC`@Tz@h@lFxC|CdBf@\\n@`@NNjB|Al@p@HJPR`@f@r@`Ab@r@v@pAb@x@Zr@Xr@Tj@HRv@~Bn@`Cl@dC`@tB^pCV~Bf@nGBb@VlDRtC|AbTj@zHFt@@JXtCPhBLlAt@fGF\\Lr@Lp@Lr@RnA|A|IH^t@lEbAvFv@tE~@nFn@hD\\hBLn@XdBh@xCZdBv@lELr@dA~FLp@ZhBh@vCZdBdBxJ`DrQpE~Vv@lEXdBLr@vG`_@Lp@zBlMdA~Fh@xCLr@hKdl@zDrTLp@ZfBH^h@dDbAlFh@zCh@xCBNBNb@fCt@bElFhZZdBLn@Lr@|BnMtDtSv@lE@Hf@nC\\nBhCtNLr@fAhGXzAh@xC@HJf@@JrApHbArFtApHNnAj@bD`@|Bv@lEf@lCbF|Xn@jDl@pCbB`Hn@dCx@vCtBxGpAjDpAdDl@vAl@pA~A`D~@fBdAhBjAtBXb@jBrCXd@hC|DtEhHnAnBbCzDxSd\\fMvRXd@dHvKXd@dF|HbFtIhCxFhAvCt@nBdApDRn@X|@j@|BzDzQJd@`@pBlHn^fCdM~FxY`GxYtBhKlBfJxBjKNv@`AfFd@zB|@fElBfJp@dDxGn\\zAlHLp@|EfVfBpIvE~TLp@h@hC|AzH\\hBf@tCb@dC\\pCv@hHz@dMJzAz@bOTbEp@rLnBx]Ft@nChf@Dv@hAnS~@`P\\pGvA|VvA|VDt@nChf@RpCZtFHpADv@zHltAhD|l@xAhWDh@|Bna@dArRXlF@VNhDHxCDrC@|gA@lc@BveA?t]?P?bR?hLA~IC|_@?~C?xF?~NA|D?bB@~P?`D@zAAnKArD?nC?t@?fE?zC?|E@tG?xb@?|E?~[?dH?fA?hGAtH?vK?fG?jD?nE?rE?jD?^@~K?~C?xCAvF@hF?tG?zF?hEAlP?`C@fD?T?`G?xE?vG?v@?t@?l@?H?fG@jCAdD?zDA`G@~DAbF?vB?t@?`A?rL?xD?lD?rA?hB?B@dD?N?rE?nD?`E?L@lB?h@Crg@?`W?v@?t@ApU?t@?lP?v@?|F?jH?X?\\?v@?vI@lGApG?v@AlI@|C?tA?fE?tGAdAChDE|AEpAGtAGhAMnAMtA[`Ca@nCi@jCk@|Bc@vA]fA_@`ASj@sAtCm@hAuBtDmFfJ}D~G}B~DiBbDy@tAiF`JeEjHoItN}BbEYf@Yd@ABWb@MTi@fAm@zAKZSh@]hAYfAGTw@jDk@|CIr@S~AWfCQtBQrDGvCAxAA~A?rB?f@@bG?zA?t@A|JAn\\?v@?nB?`Y?vZAn\\?zS?t@?v@?dD?lI?pU?v@?tG?nB?xSArU?~HAlK?vSA|f@?dMB|]?v@?v@?~PAjG?DCjEw@`u@q@hp@g@bf@m@fm@Av@KbKS`RSxSOzLA`K@~VHpwABvZ?nB?t@@~EBta@?nB@pNDdp@@tS?jB?jBHzr@Hhc@Fn\\Ch^BrJ@dIBnQNbmAFjj@?v@@dD@tGBzSFzm@H`p@J`f@BjPF`YBjI?v@BdKIpLAt@?FOpHEhAKzBo@rIm@tG{@hGmAzHaDbSiBjKkFvZs@fEs@pFo@`Gw@tJq@rMgAzTEbAa@hIEt@oAhXqAhXMlB_@tEYbD[hCa@vCkBtMeAzHcC~Pc@|C{@jGW`BkAjIc@bEWhCKjA[vEa@lIGjBk@vSGlBcDxkAe@~PqA~g@WnI[nL{@xZm@vUo@dUMlE]hNQhDOpC]dEOlBIz@Q~Am@zEy@tG}@hHcA|HIr@k@rEyAdL}AbMuBxPo@~E_@pCi@fE_@pDI|@UrC[lFUzEIlEIbJDdHFhC@X@ZVnHh@tHj@~F?@Hr@ZdCj@tDRxA|AbIlGd[Lr@lXdtAv@zDvChOjAvF`DnOpBxJXxAj@dDP`A`A|Gd@bFFt@@HXpDTnDFlAJjCFdCFzBBfD@jC?fD@tB?|@?|FAjI?`C?fH?|F@~D?|D?tA?v@?|NChDGfHE|DCrAG`E?PM`HQzKK|GObIKtGKrGEnBMpIChBCt@Y`RAv@G|EUpNOdKGdDI|EAt@QzLI|EAv@Ab@MpICdAUxN?RQzKOrIClBKpHAXAtACbBi@v\\GdDEbDAx@I|EAv@EjCApACv@GfDCvCCz@?fACxD?z@?b@@~@@`@?R@hA@p@HbCR~FFjAB\\JtBX`GxAjZtBzb@PrDLfC?PL|BJxBFdAJrBNtCR~DNvCDdANrE@PHdE@|A@vB?bA@jE?z^?t@?|L?rDGbHUlHw@hPYdGa@nImAnW_@nHGnAGtAInAYrGEt@{@bQc@fJU~DcCj`@aAjOCl@g@nIGt@ARmAxRwAfUkBxYq@jKoA~RkFj{@a@rHMfDGvBG`IE`k@?tI?vHAl[?jP?nQ?nO?`E?nC?|DA~F?`F?pB?`E@vMClu@?xPCl~@A~Z?hM?bG?h@ChnA?nM?v@?|b@?|IAd[?dE?dJ?lNApO?h_@?lR?|g@Al@?rW?rN?tA?bR?bW?xMAvN?tD?vL?jC?hFAhM?\\@rL?zNA|P?pL?~C?v@@fE?dHA`M?lV?vA?zE?rJ?hL?`M?F?zJ?lN@rKAnL?rB?nJ?bK?bM?bJ?zLA~E@fJAfI?fLAtKA~K?`A@hIArP?xQA`E@|T@bQ?|I?nB?hQ@hJ?vQ?D?v@@rI?~C@nGAtFAxAEpAGhBCl@Ep@I|@MxAEd@OrAIn@Kl@QfAOz@Qz@S|@ADOp@ADg@fBq@~Bg@`BgDdLCFqD|LgD|KsGpT_Lh_@e@zAkA~DaE`NgApDe@|AiAvDyC|Jw@lCY|@iFdQk@nBoBrG}EhPcBxFeCpIeInXqIjYw@lCSn@{DvMSn@uFdRw@lCQn@oHrVQn@_Ln_@Sn@aFvPwI|YmSbr@[`AgCrI{Kh_@cAvC_Ntd@e@zACJ}CrKENu@nCyJb\\aBxFuFdR_Lp_@gDbLqJ|[eCjIiDhL{Qjn@eJ`[gDbLQl@uFfRsVdz@cR|n@ic@dzAyMbd@yFtRiZpcAgBdGuAnEq@bCqP`k@uX`|@mb@hsAa_@lkAiCdIuXh|@eZt_AiEdNa@lA{@nCqAdEgAfDqAdEkBbGeAfDy@hCeBnFi@fB[bA{]phAcXzz@oCxIo@rBQh@}CxJoAzDgH`UcCzHsE|N}DbMqVjw@aSbo@cBlFmb@vsAcJtYgR`m@{EnOSl@_CrHaWrx@u[zcAu@|BsBvGoB`HwAlFs@tC_ArDa@zA[hA{@lCK\\qCdJ_@lAgAfDk@dB}BnHo@vBiE~Mi@xAe@jAk@rAy@dBe@z@c@r@c@x@g@t@}@nAi@l@mAzA{AxAeD|CqCjC_Az@a@`@_@b@iArAw@bAy@lAy@tAw@xA_AjBeAfCc@hAe@tAe@~AAB[rAe@dBk@xBoA`F[nAaCbJg@lBg@lBs@jCgAdESt@Sr@cDjLaDbKq@vBq@~BYtAUnAQjAQhAKpAI|@KdBGdBEtB?dC@jC?lBAhCAtAAJGdBKbBO`BSbBETKr@ERG^S~@eArDw@fCm@pBo@pB{@lCAB_@pAo@pBo@rB_AxCeE~MsC~IiBzFkD|K?@Y|@g@pAc@dAa@`AmAxBmGnKgCjEqT~^aA`BoBbDaA~A_A~A}BzD{JrPwBpDm@dAs@lACFi@dA_@v@Wj@ADYt@]|@Ur@Wx@Wx@Sx@Sz@S|@Kf@Q~@Ot@AHMr@S`BOlAKhAIbAItAG~AE`BE`D?jA?dA@bA?\\BfAD~@TxERfEVzERzDH|AH|AX|FL|BJbCBfAD`B@xCCzBGtCIdBAXIfAc@bFiAxMO~BKdCE~B?xBAtM?H?RAnI@|O?~N?H?bCCdE?rA?dC?lG?tD"
                     },
                     "start_location" : {
                        "lat" : 49.7461752,
                        "lng" : -94.6458172
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.6 km",
                        "value" : 3612
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 217
                     },
                     "end_location" : {
                        "lat" : 49.881932,
                        "lng" : -97.07209899999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eProvincial Trunk Hwy 59 N\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRte 20 N\u003c/b\u003e (signs for \u003cb\u003eRoute 20 N\u003c/b\u003e)",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "iohoHvyioQI`@EREPGPCDEHEFGFGF[Ra@?]?S@U@[B[F[Fg@NQH[NOFQL[RGFQNi@f@QRU\\QVYd@Wb@Yn@Sh@Ob@M`@K\\I^CHENMn@?@EZGZE`@EV?FE`@MrAG`AC^OfBCb@CVGd@Eb@O`AKn@I\\GVI\\I\\Ut@M^Q`@]v@S`@MROXmCvEoC|EmCzE_@p@{@vAg@x@_@l@y@lAy@jAsAjB}@hAqJvMwDjFsHdKm@x@s@dAi@p@UX[\\WVONc@ZUN_@P[HUHKBOBWBYB]@}@AmAAu@Aq@Ai@CWAsAA_AAu@A_@@_@?[@E@e@B[B[DM@OBi@Ho@JgBZo@JsAPs@HeALcABW?a@@{@?_A?cA@s@?g@@yABS@y@@uA@qB@"
                     },
                     "start_location" : {
                        "lat" : 49.85605409999999,
                        "lng" : -97.0487613
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.9 km",
                        "value" : 1876
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 167
                     },
                     "end_location" : {
                        "lat" : 49.8819242,
                        "lng" : -97.098277
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMarion St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRte 115 W\u003c/b\u003e (signs for \u003cb\u003eRoute 115 W\u003c/b\u003e)",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "aqmoHrknoQ?b@?~B@tI?~B?xH?L?bH?hR?~C@nF?dD?|I@vG?zR?vF?lEAlV?jC?`@?dBAr@"
                     },
                     "start_location" : {
                        "lat" : 49.881932,
                        "lng" : -97.07209899999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.7 km",
                        "value" : 1725
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 140
                     },
                     "end_location" : {
                        "lat" : 49.89617399999999,
                        "lng" : -97.105581
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eArchibald St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRte 30 N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_qmoHfosoQMn@CFCJCDEHSXkB|@o@R[ZcCdA{CnA_DpAgAb@IDC@KFMHKHKJKJiEpFmB`Co@v@QNQLQHQDO@QAMAOCMC_@QMGYI}Aw@OCGAGAGAG?E?G?M@O@OBgDb@k@Hk@LQDWHi@RuCjAy@^e@PeKfEwAj@cBl@WHm@R"
                     },
                     "start_location" : {
                        "lat" : 49.8819242,
                        "lng" : -97.098277
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.5 km",
                        "value" : 1513
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 146
                     },
                     "end_location" : {
                        "lat" : 49.8914876,
                        "lng" : -97.12503959999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eProvencher Blvd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRte 57 W\u003c/b\u003e (signs for \u003cb\u003eMB-57 W\u003c/b\u003e)",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ajpoHz|toQg@RPlALx@fAfHZdBLr@ZdBP`AHd@RlATzAPpAPtATzAh@xCNv@Hd@LbARhAfCzOJr@t@pEnAvHhA~GpAtIdCbO"
                     },
                     "start_location" : {
                        "lat" : 49.89617399999999,
                        "lng" : -97.105581
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 550
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 51
                     },
                     "end_location" : {
                        "lat" : 49.8922374,
                        "lng" : -97.1321142
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eProvencher Blvd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eProvencher Bridge\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRte 57 W\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Provencher Blvd/\u003cwbr/\u003eRte 57 W\u003c/div\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "ylooHnvxoQPhAVxABLF`@Jv@L~ADtABd@@`BAn@CfA?@GlA_@tC[pAW`AKXGP{B|G"
                     },
                     "start_location" : {
                        "lat" : 49.8914876,
                        "lng" : -97.12503959999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 572
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 63
                     },
                     "end_location" : {
                        "lat" : 49.8969816,
                        "lng" : -97.1334556
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWaterfront Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "oqooHtbzoQqCuAOEUCa@EUAG@E@KD[BK@ODQFKFWL[Za@d@k@t@CDQTWTQNa@Va@Xk@Vo@\\q@Xk@RODsAFO?EGEAEACEII"
                     },
                     "start_location" : {
                        "lat" : 49.8922374,
                        "lng" : -97.1321142
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 457
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 110
                     },
                     "end_location" : {
                        "lat" : 49.8979302,
                        "lng" : -97.1389714
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e2nd\u003c/b\u003e exit onto \u003cb\u003eBannatyne Ave\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "copoHbkzoQACAA?CAAAAAAAAAAAAA?AAA?A?A?C?A?A?A?A@A?A@A@A@A@A@A@AB?BA@AB?@?BAB?@?B?B?B?B?@?B@B?@@B?@@B@@?B@@@@@@@@B@DHBHBHBH@H@N?ZAPANCZ]zBQjAq@tE}@nG?FCHAN?N@jC"
                     },
                     "start_location" : {
                        "lat" : 49.8969816,
                        "lng" : -97.1334556
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 330
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 71
                     },
                     "end_location" : {
                        "lat" : 49.8951374,
                        "lng" : -97.13836839999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMain St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRte 52 S\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "aupoHpm{oQBj@hDc@nEy@|@O^GRKDAh@WLG"
                     },
                     "start_location" : {
                        "lat" : 49.8979302,
                        "lng" : -97.1389714
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "e`miGhmocNr_CtdHhbBd~RmaJhwGsbGifJcqw@deLi{g@lkMkb[`fEgoCfoBixDqdDamDehCguNzjMo`Fzk@mgCm_FenPwqKcbM`rG_dFv\\ssDxnGmkP|oCuwSl{CmuS|UmvT|iEauMnlG_nDd`OcoHrsNqdGztFecGxaOmiUf~a@osMpgM{p`@dj[o|R`yDu`Slp@_`c@dsa@crLp}GkdQ~gCqbLh_PcO`hWjrBzh_@luExaZxoHloj@ttJppz@zzGp|VhkC|jg@`Dtnr@aX``e@zkCvqn@qgC|yY_}EdeU{lHhjVqNvxV~hCjeXcvDpum@io@nuLgpEh{NaQfd]ooXyoA_eGnr@q~CldM_g@`_RvjD~xIsmK}h@m}NvjHwvTdoGkvGlkDmfDohEs{BgzAueFjmEodDpdKbBheOabGz`m@mpEjmAaqFg^etMc~NutG}Ve`MeuGbT}tH_uHmnEgoMlzMi]dlGctEzkBivNniSk{O`z@e|Lzy@yqRFasJbsNwwJgwBecGecHygHwdDuxDysCswCfeFwcF|vAawFowDipRjpCu}TnxJ}hDvwUmiHvmKozFxxAy~MtuHelGdtBmhFj|Mq{IxqRqqCzxQo|IrpQ{}BjqRx}Bpwq@na@rmY}gBplr@wkApyG_dG|oEygCndLkj@bpH|_DjaIgyFvfX|_Bxz`@rlAppJw_ItoIulDfgE~|AhhNfdJbuGow@fqTm}En`ZcmAtrNfX||NwtD~|Be|F|kWs~BpbX}_A|c[ouH~dQiuCoJ{d@tnJzdAp`MgrA~xU~hBvbKzxGbbBlbI|pErxCboNbkE`}KbkIdxBrcNjqNrtGjsC`mCx{JvbN|zVzfGtoZf}Gtqe@r}DjbN~`D|mFjjCodAvzCq~BGboIaC~kZpD~hSazB|aJ_~G``Es{LdxBocDhwFudElrTmwBv`P}iQq@kiSuDqzUbt]wzJ`cv@quLzuYex@jnXdEdjIw`F~aGibQdk\\ieGn~Gyr@r{Mm}Edqb@yOjrSakEjbKqlIbog@_oNt{^cuCzr[uqDxtWaiMrdp@wcDplIaNf_RgrEleOijDz`CijF~mDoo@|}FyiJtgTwrEtwJ}EjjSodDt|FsPzhQfB|ds@uyGn`b@hoE|}Rah@lkQgx@vty@xbMhcj@lu@|pJ`yEn{Okn@l|JclG~hC}tCjbKvbBxbf@fmEbqGjsEfcOon@rfl@qXdhx@`wGzoSntHf|m@}uCnatAqVprrAiiHnuh@qlW|sy@q}GlvSsqAb_K"
         },
         "summary" : "Trans-Canada Hwy/ON-17 N",
         "warnings" : [],
         "waypoint_order" : [ 0 ]
      }
   ],
   "status" : "OK"
}
```
