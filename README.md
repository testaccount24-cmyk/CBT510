# CBT510
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 510 is from Ricardo Paranhos and contains the IEBLIST     *   FILE 510
//*           program the SPACE program, and the VARYDASD program.  *   FILE 510
//*                                                                 *   FILE 510
//*           The IEBLIST program has much flexibility in listing   *   FILE 510
//*           datasets by DSN (maskable), VOL(partial or complete)  *   FILE 510
//*           SG (storage group name), ADD(unit address range),     *   FILE 510
//*           and CATALOG (search by dataset on catalog).  You can  *   FILE 510
//*           also list datasets last referenced on or before       *   FILE 510
//*           a certain date:  REF(yyyyddd) .                       *   FILE 510
//*                                                                 *   FILE 510
//*           Using IEBLIST, you can get allocated space and used   *   FILE 510
//*           space, and totals of these, even for VSAM datasets,   *   FILE 510
//*           because this program reads the VVDS.                  *   FILE 510
//*                                                                 *   FILE 510
//*           IEBLIST was updated by Alexander I. Vasilenko, to     *   FILE 510
//*           filter on dataset Create Date, and Block Size.        *   FILE 510
//*                                                                 *   FILE 510
//*           Fixed by Sam Golob to get the ADD(mmmm-nnnn)          *   FILE 510
//*           command to work.                                      *   FILE 510
//*                                                                 *   FILE 510
//*              email:  Ali_vas@mail.ru                            *   FILE 510
//*                                                                 *   FILE 510
//*           The SPACE program is another utility that Ricardo     *   FILE 510
//*           developed and which is helpful to search volumes by   *   FILE 510
//*           volume names, storage group names, unit address and   *   FILE 510
//*           mount status.  The list that the SPACE program shows  *   FILE 510
//*           is a search result, and a specific volume can be      *   FILE 510
//*           selected to view a list of data sets inside, and      *   FILE 510
//*           space used in VSAM data sets too.                     *   FILE 510
//*                                                                 *   FILE 510
//*           The VARYDASD program will vary DASD volumes OFFLINE   *   FILE 510
//*           by checking to see if the volser matches a list       *   FILE 510
//*           supplied by the SYSIN DD card. If no match, the       *   FILE 510
//*           program uses IEEVARYD to vary the devices offline.    *   FILE 510
//*                                                                 *   FILE 510
//*     "Ricardo J Paranhos" <ricardoparanhos@easi.com.br>          *   FILE 510
//*                                                                 *   FILE 510
```
