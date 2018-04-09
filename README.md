# EstMalt
Estonian DT and UD models for MaltParser.

Documentation for UD annotation  is available at EstUD repository.

----------------------------

MaltParseri mudelid, mis on treenitud sõltuvuspuude ja EstUD puudepankadel. UD sisendi formaadi ja märgendite kirjeldus on saadaval EstUD repositooriumis.


## Maltparser for UD v2.2 (aprill18-et-ud.mco)
Trained on 288.000 tokens (see https://github.com/UniversalDependencies/UD_Estonian-EDT/tree/master), tested on 41,000 tokens, used maltparser 1.8.1 (see http://www.maltparser.org/)
```
Performance:
accuracy / Metric:LAS   accuracy / Metric:LA   accuracy / Metric:UAS   Token
--------------------------------------------------------------------------------
0.79                    0.891                  0.823                   Row mean
41273                   41273                  41273                   Row count
--------------------------------------------------------------------------------
```


## MaltParser UD-puudepangal v1.4 (dets16kogu.mco)

   Treeninghulk:   256642 tokens (ilu ja aja)
   Testhulk:        32320 tokens (kvm kaasaarvatud)
   Morf analüüs:    puudepangast käsitsi märgendatud teisendatud automaatselt UDsse

```
accuracy / Metric:LA   accuracy / Metric:LAS   accuracy / Metric:UAS   Token
--------------------------------------------------------------------------------
0.912                  0.797                   0.822                   Row mean
32320                  32320                   32320                   Row count
--------------------------------------------------------------------------------
```
