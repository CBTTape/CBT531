# CBT531
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 531 is from David Stern and contains routines that will   *   FILE 531
//*           detect various OS/390 details.                        *   FILE 531
//*                                                                 *   FILE 531
//*           The exec uses :                                       *   FILE 531
//*                                                                 *   FILE 531
//*           EZASOKET to retrieve details of TCP/IP stack(s).      *   FILE 531
//*            The TCP/IP VRM(s) and operational status(es) are     *   FILE 531
//*            displayed                                            *   FILE 531
//*           TSO LINK against imbedded OBJ text that retrieves     *   FILE 531
//*            the level of Language Environment and output of      *   FILE 531
//*            the CSRSI service (CUOD information). The BAL        *   FILE 531
//*            source is also in this file (OBJSRC)                 *   FILE 531
//*           ISPF/PDF LMDxxxx services to find DSN info based      *   FILE 531
//*            upon a LLQ match (SMP/E 'style')                     *   FILE 531
//*           Rexx STORAGE functions to search the SVC table        *   FILE 531
//*                                                                 *   FILE 531
//*           Some of the internal routines have been used to       *   FILE 531
//*           create separate execs in this file.                   *   FILE 531
//*                                                                 *   FILE 531
//*           Member IGGCSIRX uses the DFSMSdfp Catalog Search      *   FILE 531
//*           Interface to retrieve ICF catalog entries.  The       *   FILE 531
//*           exec is from the IBM sample and catalog diagnostic    *   FILE 531
//*           information is displayed along with the BCS type.     *   FILE 531
//*                                                                 *   FILE 531
//*           The main REXX exec called OSANALZ is in TSO XMIT      *   FILE 531
//*           format, because its actual DCB requirements are       *   FILE 531
//*           LRECL=132,RECFM=FB .  You have to issue a TSO         *   FILE 531
//*           RECEIVE command on this member to get it into its     *   FILE 531
//*           proper format:                                        *   FILE 531
//*                                                                 *   FILE 531
//*             RECEIVE INDS(yourid.FILE531.PDS(OSANALZ))           *   FILE 531
//*                                                                 *   FILE 531
//*           I have also taken the liberty of disassembling        *   FILE 531
//*           David's object deck, which is imbedded in the         *   FILE 531
//*           OSANALZ exec.  David has provided the source, too.    *   FILE 531
//*           So member OBJSRC is David's source, and OBJSRCD is    *   FILE 531
//*           my disassembly of the (supplied) object deck.         *   FILE 531
//*           (S.Golob)                                             *   FILE 531
//*                                                                 *   FILE 531
//*       David Stern                                               *   FILE 531
//*       IONA Technologies plc                                     *   FILE 531
//*       Shelbourne Road                                           *   FILE 531
//*       Dublin 4, Ireland                                         *   FILE 531
//*                                                                 *   FILE 531
//*         mailto:David.Stern@iona.com                             *   FILE 531
//*       Tel (IE): +353 1 6625255 X2519                            *   FILE 531
//*           (US): +1 800 orbix4u                                  *   FILE 531
//*            WWW: http://www.iona.com                             *   FILE 531
//*                                                                 *   FILE 531
```
