# HarmonyParsers_TriadicProgressions

The XO chord transcription data set observes the nomenclature of Sears, D. R. W., and David Forrest. (2021). Triadic Harmony Analysis Tool. https://doi.org/10.17605/OSF.IO/KDZM3.

Each CSV file contains on column of data. The files correspond to the following tracks:
SA.csv - 1. "Sweet Adeline"
TT.csv - 2. "Tomorrow Tomorrow"
W2.csv - 3. "Waltz #2 (XO)"
BB.csv - 4. "Baby Britain"
PZ.csv - 5. "Pitseleh"
ID.csv - 6. "Independence Day"
BW.csv - 7. "Bled White"
W1.csv - 8. "Waltz #1"
Am.csv - 9. "Amity"
OK.csv - 10. "Oh Well, Okay"
BX.csv - 11. "Bottle Up and Explode!"
QM.csv - 12. "A Question Mark"
CU.csv - 13. "Everybody Cares, Everybody Understands"
DU.csv - 14. "I Didn't Understand"

The first cell in the CSV file for each track provides the referential pitch center for the track. Subsequent cells provide each successive chord parsed according to Sears and Forrest (2021), the README file data of which is reproduced below.

Harmony Parsers for the Relative Root Encoding Scheme

      PARSE -- Relative Root Representation 

         Encoding:    <RN><Quality><Inversion><Extensions>
   
            RN         -- Roman numeral encoded in relation to the key. Case
                          denotes quality of the triad (major or minor).
                          Named chords (+6, Ct, etc.) are converted to RN roots,
                          with the names included in the quality slot (e.g., 
                          #ivGer). Applied dominants (e.g., V/ii) receive 
                          diatonic equivalents. Chords may also be preceded by a
                          chromatic accidental relative to the major scale 
                          (e.g., viio/V --> #ivo):
                              --  double flat
                               -  flat 
                               #  sharp
                              ##  double sharp
   
           Quality    -- Chord quality: 
                               M  major seventh 
                                  minor seventh (no symbol)
                               d  major RN with minor seventh 
                               h  half-diminished seventh
                               o  diminished triad or seventh
                               +  augmented
                               p  power (i.e., no 3rd) 
                             Ger  German augmented sixth
                              Fr  French augmented sixth 
                              It  Italian augmented sixth
                              Ct  Common-tone diminished seventh
   
          Inversion  -- Chord inversion:
                                  root position (no symbol)
                               6  first inversion triad
                              64  second inversion triad
                               7  root position seventh
                              65  first inversion seventh
                              43  second inversion seventh
                              42  third inversion seventh 
   
          Extensions -- Suspensions or added tones appear in parentheses, with
                        added tones preceded by '+'.

          Example:     V(64) (i.e., a cadential six-four)
