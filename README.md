# RecombinationSpots
----dev env
MATLAB R2018a
----runtime env
libsvm-3.22
This package of codesprivate	.		
----usage 
1. Set up the MATLAB to a correct JDK environment on the windows system. 
2. Open the MATLAB command window.
3. Go to the dir where you place all the binaries.
4. Note that "Predictor.m" is used to predict hotspots and coldspots.
5. Type "run" to open the txt file, where you saved the DNA sequences in FASTA format.
6. Read the output in command window.
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
PS：
（1）Select the ‘’PREDITOR’’ file in the MATLAB environment, than choose the file that need to be tested(The sequence is saved in the vents TXT file, the sequence is in form of FASTA);
（2）Select the ‘’TestSamples.txt’’, the MATLABwork page will display the following results:

>YBL076C  #11 - #154 
GTAACGCACACTTCTCATTTCCAAAGGAGGAAGAAAAAGTTCTATCTCTTTGGATGAAATAGATGCCTTTCATACTTCATTAGAATTAACAAAAGACAAACCGGAGTTTTCCTCTTCGATGGGCCTCCATT Coldspot
>YBL076C  #11 - #154 
TAACGCACACTTCTCATTTCCAAAGGAGGAAGAAAAAGTTCTATCTCTTTGGATGAAATAGATGCCTTTCATACTTCATTAGAATTAACAAAAGACAAACCGGAGTTTTCCTCTTCGATGGGCCTCCATTT Hotspot
>YBL076C  #11 - #154 
AACGCACACTTCTCATTTCCAAAGGAGGAAGAAAAAGTTCTATCTCTTTGGATGAAATAGATGCCTTTCATACTTCATTAGAATTAACAAAAGACAAACCGGAGTTTTCCTCTTCGATGGGCCTCCATTTG Coldspot
>YBL076C  #11 - #154 
ACGCACACTTCTCATTTCCAAAGGAGGAAGAAAAAGTTCTATCTCTTTGGATGAAATAGATGCCTTTCATACTTCATTAGAATTAACAAAAGACAAACCGGAGTTTTCCTCTTCGATGGGCCTCCATTTGC Coldspot
>YBL076C  #11 - #154 
CGCACACTTCTCATTTCCAAAGGAGGAAGAAAAAGTTCTATCTCTTTGGATGAAATAGATGCCTTTCATACTTCATTAGAATTAACAAAAGACAAACCGGAGTTTTCCTCTTCGATGGGCCTCCATTTGCC Hotspot
>YBL076C  #11 - #154 
GCACACTTCTCATTTCCAAAGGAGGAAGAAAAAGTTCTATCTCTTTGGATGAAATAGATGCCTTTCATACTTCATTAGAATTAACAAAAGACAAACCGGAGTTTTCCTCTTCGATGGGCCTCCATTTGCCA Coldspot
>YBL076C  #11 - #154 
CACACTTCTCATTTCCAAAGGAGGAAGAAAAAGTTCTATCTCTTTGGATGAAATAGATGCCTTTCATACTTCATTAGAATTAACAAAAGACAAACCGGAGTTTTCCTCTTCGATGGGCCTCCATTTGCCAC Coldspot
>YBL076C  #11 - #154 
ACACTTCTCATTTCCAAAGGAGGAAGAAAAAGTTCTATCTCTTTGGATGAAATAGATGCCTTTCATACTTCATTAGAATTAACAAAAGACAAACCGGAGTTTTCCTCTTCGATGGGCCTCCATTTGCCACC Coldspot
>YBL076C  #11 - #154 
CACTTCTCATTTCCAAAGGAGGAAGAAAAAGTTCTATCTCTTTGGATGAAATAGATGCCTTTCATACTTCATTAGAATTAACAAAAGACAAACCGGAGTTTTCCTCTTCGATGGGCCTCCATTTGCCACCG Coldspot
>YBL076C  #11 - #154 
ACTTCTCATTTCCAAAGGAGGAAGAAAAAGTTCTATCTCTTTGGATGAAATAGATGCCTTTCATACTTCATTAGAATTAACAAAAGACAAACCGGAGTTTTCCTCTTCGATGGGCCTCCATTTGCCACCGG Hotspot
>YBL076C  #11 - #154 
CTTCTCATTTCCAAAGGAGGAAGAAAAAGTTCTATCTCTTTGGATGAAATAGATGCCTTTCATACTTCATTAGAATTAACAAAAGACAAACCGGAGTTTTCCTCTTCGATGGGCCTCCATTTGCCACCGGT Hotspot
>YBL076C  #11 - #154 
TTCTCATTTCCAAAGGAGGAAGAAAAAGTTCTATCTCTTTGGATGAAATAGATGCCTTTCATACTTCATTAGAATTAACAAAAGACAAACCGGAGTTTTCCTCTTCGATGGGCCTCCATTTGCCACCGGTA Coldspot
>YBL076C  #11 - #154 
TCTCATTTCCAAAGGAGGAAGAAAAAGTTCTATCTCTTTGGATGAAATAGATGCCTTTCATACTTCATTAGAATTAACAAAAGACAAACCGGAGTTTTCCTCTTCGATGGGCCTCCATTTGCCACCGGTAC Coldspot
>YBL076C  #11 - #154  
CTCATTTCCAAAGGAGGAAGAAAAAGTTCTATCTCTTTGGATGAAATAGATGCCTTTCATACTTCATTAGAATTAACAAAAGACAAACCGGAGTTTTCCTCTTCGATGGGCCTCCATTTGCCACCGGTACT Hotspot 
>YOR353C  #21 - #154 
GAGGACGTTGGATCCGAAGGAGGAACATTTGCCTGCTGACAAACATCCACTAATTCAAGCAACACTATAATATCTGAGTTGGCAACACAAGAGAAATCCAGCCTAGTGGTACTACACTAAAATTAATAGCT Coldspot
>YOR353C  #21 - #154  
AGGACGTTGGATCCGAAGGAGGAACATTTGCCTGCTGACAAACATCCACTAATTCAAGCAACACTATAATATCTGAGTTGGCAACACAAGAGAAATCCAGCCTAGTGGTACTACACTAAAATTAATAGCTC Coldspot
>YOR353C  #21 - #154 
GGACGTTGGATCCGAAGGAGGAACATTTGCCTGCTGACAAACATCCACTAATTCAAGCAACACTATAATATCTGAGTTGGCAACACAAGAGAAATCCAGCCTAGTGGTACTACACTAAAATTAATAGCTCT Hotspot
>YOR353C  #21 - #154 
GACGTTGGATCCGAAGGAGGAACATTTGCCTGCTGACAAACATCCACTAATTCAAGCAACACTATAATATCTGAGTTGGCAACACAAGAGAAATCCAGCCTAGTGGTACTACACTAAAATTAATAGCTCTT Coldspot
>YOR353C  #21 - #154 
ACGTTGGATCCGAAGGAGGAACATTTGCCTGCTGACAAACATCCACTAATTCAAGCAACACTATAATATCTGAGTTGGCAACACAAGAGAAATCCAGCCTAGTGGTACTACACTAAAATTAATAGCTCTTA Coldspot
>YOR353C  #21 - #154 
CGTTGGATCCGAAGGAGGAACATTTGCCTGCTGACAAACATCCACTAATTCAAGCAACACTATAATATCTGAGTTGGCAACACAAGAGAAATCCAGCCTAGTGGTACTACACTAAAATTAATAGCTCTTAA Coldspot
>YOR353C  #21 - #154 
GTTGGATCCGAAGGAGGAACATTTGCCTGCTGACAAACATCCACTAATTCAAGCAACACTATAATATCTGAGTTGGCAACACAAGAGAAATCCAGCCTAGTGGTACTACACTAAAATTAATAGCTCTTAAT Coldspot
>YOR353C  #21 - #154 
TTGGATCCGAAGGAGGAACATTTGCCTGCTGACAAACATCCACTAATTCAAGCAACACTATAATATCTGAGTTGGCAACACAAGAGAAATCCAGCCTAGTGGTACTACACTAAAATTAATAGCTCTTAATA Hotspot
>YOR353C  #21 - #154 
TGGATCCGAAGGAGGAACATTTGCCTGCTGACAAACATCCACTAATTCAAGCAACACTATAATATCTGAGTTGGCAACACAAGAGAAATCCAGCCTAGTGGTACTACACTAAAATTAATAGCTCTTAATAT Coldspot
>YOR353C  #21 - #154 
GGATCCGAAGGAGGAACATTTGCCTGCTGACAAACATCCACTAATTCAAGCAACACTATAATATCTGAGTTGGCAACACAAGAGAAATCCAGCCTAGTGGTACTACACTAAAATTAATAGCTCTTAATATC Hotspot
>YOR353C  #21 - #154 
GATCCGAAGGAGGAACATTTGCCTGCTGACAAACATCCACTAATTCAAGCAACACTATAATATCTGAGTTGGCAACACAAGAGAAATCCAGCCTAGTGGTACTACACTAAAATTAATAGCTCTTAATATCA Coldspot
>YOR353C  #21 - #154 
ATCCGAAGGAGGAACATTTGCCTGCTGACAAACATCCACTAATTCAAGCAACACTATAATATCTGAGTTGGCAACACAAGAGAAATCCAGCCTAGTGGTACTACACTAAAATTAATAGCTCTTAATATCAA Hotspot
>YOR353C  #21 - #154 
TCCGAAGGAGGAACATTTGCCTGCTGACAAACATCCACTAATTCAAGCAACACTATAATATCTGAGTTGGCAACACAAGAGAAATCCAGCCTAGTGGTACTACACTAAAATTAATAGCTCTTAATATCAAG Coldspot

